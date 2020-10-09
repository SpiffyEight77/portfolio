<template>
  <div class="container">
    <div id="name-container">
      <img id="avatar" src="./../assets/images/avatar.png" alt="avatar" />
      <h1>SpiffyEight77</h1>
      <h3>👋🏻 Hi there, I'm a web developer</h3>
    </div>
    <div class="title-desc-container">
      <a href="https://github.com/SpiffyEight77" target="_blank">
        <i class="ri-github-line"></i>
      </a>
      <a href="https://blog.spiffyeight77.com/" target="_blank">
        <i class="ri-article-line"></i>
      </a>
      <a href="https://twitter.com/SpiffyEight77" target="_blank">
        <i class="ri-twitter-line"></i>
      </a>
      <a href="https://www.instagram.com/spiffyeight77/" target="_blank">
        <i class="ri-instagram-line"></i>
      </a>
      <a href="">
        <i class="ri-telegram-line"></i>
      </a>
      <a href="http://psnine.com/psnid/spiffyeight77" target="_blank">
        <i class="ri-playstation-line"></i>
      </a>
    </div>
  </div>
</template>

<style lang="css" scoped>
.container {
  background: #ffffff;
  -webkit-box-shadow: 0 10px 20px 0 rgba(236, 236, 236, 0.86);
  box-shadow: 0 10px 20px 0 rgba(236, 236, 236, 0.86);
  width: 800px;
  height: 420px;
  margin: auto;
  padding: auto;
  border-radius: 16px;
  transition: 0.3s ease-in-out;
  position: absolute;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
}

.container:hover {
  box-shadow: 3px 18px 32px 2px rgba(0, 0, 0, 0.15);
  transition: 0.4s ease-in-out;
}

.title-desc-container {
  margin-top: 10px;
  font-size: 24px;
}

.title-desc-container i {
  margin-left: 5px;
}

@media screen and (min-width: 1600px) {
  .container {
    width: 1000px;
  }
}

@media screen and (max-width: 900px) {
  .container {
    width: 95%;
  }
}

#name-container {
  display: flex;
  flex-direction: column;
  justify-content: flex-start;
  align-items: center;
}

#avatar {
  width: 150px;
  height: 150px;
  border-radius: 40%;
  padding-top: 50px;
}

h1 {
  font-size: 28px;
}
</style>
