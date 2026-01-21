<script setup>
</script>

<template>
  <footer class="footer">
    <div class="container footer-content">
      <div class="footer-logo">Haven</div>
      <p class="copyright">© 2026 Haven. All rights reserved.</p>
      <div class="social-links">
        <a href="#">Privacy</a>
        <a href="#">Terms</a>
      </div>
    </div>
  </footer>
</template>

<style scoped>
.footer {
  background-color: var(--bg-color);
  padding: 40px 0;
  border-top: 1px solid #eee;
}

.footer-content {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.footer-logo {
   font-family: var(--font-serif);
   font-weight: bold;
   font-size: 1.2rem;
}

.copyright {
    color: var(--text-light);
    font-size: 0.9rem;
}

.social-links {
    display: flex;
    gap: 20px;
}

.social-links a {
    color: var(--text-light);
    font-size: 0.9rem;
}
</style>
