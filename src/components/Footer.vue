<template>
  <div class="footer">
    <div class="powered_by">
      <p>
        <a href="https://github.com/spiffyeight77">
          Designed by SpiffyEight77,
        </a>
        <a href="https://vuejs.org/">Proudly published with Vue.js</a>
      </p>
    </div>
    <div class="powered_by">
      <a>
        <p id="busuanzi_container_site_pv">
          Viewed by you guys for a total of
          <span id="busuanzi_value_site_pv"></span> times ♥
        </p>
      </a>
    </div>
    <br />
    <div class="powered_by">
      <a>©2016 - {{ getYear() }}</a>
    </div>
  </div>
</template>

<script>
export default {
  methods: {
    getYear() {
      return new Date().getFullYear();
    }
  }
};
</script>

<style lang="css" scoped>
.footer {
  position: absolute;
  top: 550px;
  bottom: 0;
  left: 0;
  right: 0;
  clear: both;
  width: 780px;
  height: 100px;
  text-align: center;
  font-size: 12px;
  padding: auto;
  margin: auto;
}

.footer a {
  color: #a6a6a6;
  margin: 0 12px;
}

.footer a:hover {
  color: #1f1f1f;
}

.footer .powered_by {
  margin: 0;
  font-size: 11px;
}

.footer .powered_by a {
  color: #cccccc;
  margin: 0 2px;
}

.footer .powered_by a:hover {
  color: #1f1f1f;
}

@media screen and (min-width: 1600px) {
  .footer {
    width: 1000px;
  }
}

@media screen and (max-width: 900px) {
  .footer {
    width: 95%;
  }
  .footer a {
    margin: 0 6px;
  }
}

/* Pixel 2 XL */
@media screen and (min-width: 823px) and (max-width: 823px) and (orientation: landscape) {
  .footer {
    width: 90%;
    top: 480px;
  }
  .footer a {
    margin: 0 6px;
  }
}

/* iPhone X */
@media screen and (min-width: 800px) and (max-width: 812px) and (orientation: landscape) {
  .footer {
    width: 90%;
    top: 480px;
  }
  .footer a {
    margin: 0 6px;
  }
}

/* iPhone 6/7/8 Plus */
@media screen and (min-width: 736px) and (max-width: 736px) and (orientation: landscape) {
  .footer {
    width: 90%;
    top: 480px;
  }
  .footer a {
    margin: 0 6px;
  }
}

/* Pixel 2 */
@media screen and (min-width: 731px) and (max-width: 731px) and (orientation: landscape) {
  .footer {
    width: 90%;
    top: 480px;
  }
  .footer a {
    margin: 0 6px;
  }
}

/* iPhone 6/7/8 */
@media screen and (min-width: 667px) and (max-width: 667px) and (orientation: landscape) {
  .footer {
    width: 90%;
    top: 480px;
  }
  .footer a {
    margin: 0 6px;
  }
}

/* Galaxy S5 / Moto G4 */
@media screen and (min-width: 640px) and (max-width: 640px) and (orientation: landscape) {
  .footer {
    width: 90%;
    top: 450px;
  }
  .footer a {
    margin: 0 6px;
  }
}

/* iPhone 5/SE */
@media screen and (min-width: 568px) and (max-width: 568px) and (orientation: landscape) {
  .footer {
    width: 90%;
    top: 400px;
  }
  .footer a {
    margin: 0 6px;
  }
}
</style>
