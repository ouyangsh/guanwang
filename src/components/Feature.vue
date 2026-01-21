<script setup>
</script>

<template>
  <section class="feature">
    <div class="container">
      <div class="feature-text">
        <h2>欢迎回家</h2>
        <p>记载每一个相爱的时刻</p>
      </div>
      <div class="app-showcase">
        <div class="phone-frame">
             <img src="@/assets/app-screenshot.png" alt="App Interface" class="app-screen">
        </div>
      </div>
      <div class="feature-details">
         <div class="detail-item">
             <h3>安全登录</h3>
             <p>隐私保护，专属空间</p>
         </div>
         <div class="detail-item">
             <h3>爱的记录</h3>
             <p>每一天都值得纪念</p>
         </div>
      </div>
    </div>
  </section>
</template>

<style scoped>
.feature {
  background-color: #fff;
  text-align: center;
  padding: 80px 0;
}

.feature-text h2 {
  font-size: 2.5rem;
  margin-bottom: 20px;
  color: var(--text-dark);
}

.feature-text p {
  font-size: 1.2rem;
  color: var(--text-light);
  margin-bottom: 50px;
}

.app-showcase {
    display: flex;
    justify-content: center;
    margin-bottom: 60px;
}

.phone-frame {
    width: 300px; /* Adjust based on your screenshot aspect ratio */
    border-radius: 30px;
    box-shadow: 0 20px 60px rgba(0,0,0,0.15);
    overflow: hidden;
    border: 8px solid #f0f0f0;
}

.app-screen {
    width: 100%;
    display: block;
}

.feature-details {
    display: flex;
    justify-content: center;
    gap: 50px;
}

.detail-item h3 {
    font-size: 1.5rem;
    margin-bottom: 10px;
    color: var(--primary-color);
}

.detail-item p {
    color: var(--text-light);
}
</style>
