<template>
  <footer>
    <div class="logo-container">
      <div class="footer-logo">
        <img src="../assets/images/pioneer-footer-logo.png" alt="footer logo">
      </div>
      <p class="schedule">ПН-ПТ - 9:00-17:00</p>
    </div>
    <div class="company-info">
      <h6>КОМПАНИЯ</h6>
      <ul>
        <li>О нас</li>
        <li>Продукция</li>
        <li>Скачать каталог</li>
        <li>Сотрудничество</li>
        <li class="info-last-item">География поставок</li>
      </ul>
      <p>1994-2021 ООО "ПИОНЕР"</p>
    </div>
    <div class="contacts">
      <h6>КОНТАКТЫ</h6>
      <ul>
        <li>+7 800 120-52-50</li>
        <li>+7 495 456-24-21</li>
        <li class="contacts-last-item">pionerrr@sila.ru</li>
      </ul>
      <div class="social">
        <button class="social-link">
          <img src="../assets/images/facebook-logo.png" alt="facebook button">
        </button>
        <button class="social-link">
          <img src="../assets/images/youtube-logo.png" alt="youtube button">
        </button>
        <button class="social-link">
          <img src="../assets/images/twitter-logo.png" alt="twitter button">
        </button>
        <button class="social-link">
          <img src="../assets/images/instagram-logo.png" alt="instagram button">
        </button>
      </div>
    </div>
  </footer>
</template>

<script>

</script>

<style scoped>
  footer {
    border-top: solid #1AA0FF 5px;
    background: white;
    display: flex;
    justify-content: center;
  }
  footer > div {
    margin-top: 60px;
    margin-bottom: 60px;
  }
  li {
    list-style: none;
    font-size: 20px;
    line-height: 24px;
    padding-top: 15px;
  }
  .info-last-item {
    margin-bottom: 60px;
  }
  .contacts-last-item {
    margin-bottom: 130px;
  }
  h6 {
    font-size: 20px;
    color: #1AA0FF;
  }
  p {
    font-size: 20px;
  }
  .logo-container {
    margin-right: 125px;
  }
  .company-info {
    margin-right: 100px;
  }
  .company-info li:hover {
    cursor: pointer;
    text-decoration: underline solid #1AA0FF 2px;
  }
  .social {
    display: flex;
    justify-content: space-between;
  }
  .social-link {
    cursor: pointer;
    background: none;
    border: none;
  }
</style>
