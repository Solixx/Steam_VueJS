<script setup lang="ts"></script>

<template>
  <div class="steam-page">
    <div class="container profile-shell">
      <div class="panel profile-shell__panel">
        <h1 class="profile-shell__title">Steam Profile (WIP)</h1>
        <p class="profile-shell__subtitle">
          Theme tokens + base styles are wired. Next: header, recent activity, showcases, comments.
        </p>
      </div>
    </div>
  </div>
</template>

<style scoped>
.profile-shell {
  padding: var(--space-7) 0;
}

.profile-shell__panel {
  border-radius: var(--radius-2);
  padding: var(--space-5);
}

.profile-shell__title {
  margin: 0;
  color: var(--text-strong);
  font-size: 28px;
  font-weight: 600;
  letter-spacing: 0.2px;
}

.profile-shell__subtitle {
  margin: var(--space-3) 0 0;
  color: var(--text-muted);
  line-height: 1.45;
}
</style>
