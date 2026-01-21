<script setup>
</script>

<template>
  <section class="hero">
    <div class="hero-bg">
        <img src="@/assets/hero-bg.png" alt="Welcome to Haven">
    </div>
    <div class="container hero-content">
      <h1 class="hero-title">Welcome<br>to Haven.</h1>
      <p class="hero-subtitle">Family & Love</p>
    </div>
  </section>
</template>

<style scoped>
.hero {
  position: relative;
  height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
  color: #fff;
  overflow: hidden;
  padding: 0;
}

.hero-bg {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    width: 300px;
    height: 400px;
    border-radius: 20px;
    overflow: hidden;
    z-index: 1;
    box-shadow: 0 20px 40px rgba(0,0,0,0.1);
}

.hero-bg img {
    width: 100%;
    height: 100%;
    object-fit: cover;
}

.hero-content {
    position: relative;
    z-index: 2;
    margin-top: -60px; /* Adjust based on image position */
}

.hero-title {
  font-family: var(--font-main);
  font-size: 3rem;
  font-weight: 400;
  line-height: 1.2;
  margin-bottom: 20px;
  text-shadow: 0 2px 4px rgba(0,0,0,0.1);
}

.hero-subtitle {
    font-size: 1rem;
    font-weight: 600;
    text-transform: uppercase;
    letter-spacing: 1px;
    opacity: 0.9;
}
</style>
