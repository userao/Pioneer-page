<template>
  <header>
    <div class="navbar-container">
      <div class="brand">
        <img src="../assets/images/pioneer-logo.png" alt="pioneer logo">
      </div>
      <nav class="navbar">
        <a link="#" class="w600 navbar-item">О нас</a>
        <a link="#" class="w600 navbar-item">Продукция</a>
        <a link="#" class="w600 navbar-item">География поставок</a>
        <a link="#" class="w600 navbar-item">Контакты</a>
      </nav>
    </div>
    <div class="header-body">
      <h1 class="header-title w700">Российский завод<br>силовых машин</h1>
    </div>
  </header>
</template>

<script>

</script>

<style scoped>
  header {
    position: relative;
    height: 950px;
    background: gray;
    background-image: url('../assets/images/header-background.png');
  }
  .navbar-container {
    display: flex;
    justify-content: space-between;
    align-items: flex-end;
    height: 127px;

  }
  .brand {
    position: absolute;
    left: 165px;
    top: 60px;
  }
  .navbar {
    position: absolute;
    top: 82px;
    right: 165px;
    display: flex;
    width: 635px;
    justify-content: space-between;
  }
  .navbar-item {
    font-size: 18px;
    color: white;
  }
  .header-title {
    position: absolute;
    top: 287px;
    left: 165px;
    font-size: 70px;
    color: white;
  }
</style>
