<template>
  <section class="myclass hero is-info is-fullheight">
        <vue-typed-js :strings="['เข้ามาทำอะไรกัน 😤','ยังจะดู👀ต่ออีก ออกไป ❗️️❗️ ','คนไล่🐒แล้วยังจะดูต่อ ผมว่ามันไม่ใช่ล่ะ ❓❓❓ ','ถ้าอยากรู้จัก มา จะแนะนำ🎤ตัวสั้นๆ🗿 🗽 🗼' ,'🎬My name is Teerapat.', 'I am a senior 👩🏻‍💻engineer student at TU🏫.', '🙏🙏🙏Thank you']">
          <h3 class="title"> <span class="typing"></span></h3>
        </vue-typed-js>
    </section>
</template>
<script>
import FlipCountdown from 'vue2-flip-countdown'
export default {
  name: 'home',
  components: { FlipCountdown },
  data () {
    return {
      isComponentModalActive: false,
      isComponentModalActive2: false,
      isComponentModalActive3: false
    }
  },
  mounted () {
    this.$anime(/* ... animate something ... */)
  },
  methods: {
    onCancel () {
      this.isComponentModalActive = false
      this.isComponentModalActive2 = false
      this.isComponentModalActive3 = false
    }
  }
}
</script>

<style scoped>
.myclass {
  /* background-image: url('../assets/body-background.'); */
  height: 100vh;
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
  display: flex;
  flex-direction: column;
  align-content: center;
  justify-content: center;
  text-align: center;
}
h1.title {
    font-size: 4em;
    font-family: 'Gamja Flower', cursive;
    color: chartreuse;
}
.my-box {
  margin-top: 30px !important;
}
p.modal-card-title {
  font-family: 'Gamja Flower', cursive;
}
p.modal-card-title2 {
  font-family: 'Gamja Flower', cursive;
  font-size: 15px;
  color:  black !important;
}
p.content {
  color:  black !important;
  font-size: 10px;
  font-family: 'Itim', cursive;
}
ีul.recap-des {
  flex-wrap: wrap;
  align-items: flex-start;
}
div.recap {
  margin-top: 15px;
}
.recap-container {
  display: block;
}
.message-body2 {
  font-size: 12px !important;
  color: black;
}
</style>
