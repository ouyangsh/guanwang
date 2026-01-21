<script setup>
</script>

<template>
  <header class="header">
    <div class="container header-content">
      <div class="logo">Haven</div>
      <nav>
        <ul>
          <li><a href="#">Home</a></li>
          <li><a href="#">App</a></li>
        </ul>
      </nav>
      <div class="header-action">
          <a href="#" class="btn-download">Download App</a>
      </div>
    </div>
  </header>
</template>

<style scoped>
.header {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  padding: 20px 0;
  z-index: 10;
}

.header-content {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.logo {
  font-family: var(--font-serif);
  font-size: 24px;
  font-weight: bold;
  color: #fff;
}

nav ul {
  display: flex;
  gap: 30px;
}

nav a {
  color: #fff;
  font-weight: 500;
  opacity: 0.9;
  transition: opacity 0.3s;
}

nav a:hover {
  opacity: 1;
}

.btn-download {
  background-color: var(--white);
  color: var(--text-dark);
  padding: 10px 20px;
  border-radius: 20px;
  font-weight: 600;
  font-size: 14px;
}
</style>
