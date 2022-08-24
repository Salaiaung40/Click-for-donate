<template>
  <div class="body">
    <div class="header">
      <h1>{{ msg }}</h1>
      <h2>Essential Links</h2>
    </div>
    <div class="but-grup">
      <Buttons-Compo
        onclick="window.location.href = 'https://salai.be/';"
        target="'_blank';"
      >
      </Buttons-Compo>

      <Buttons-Compo></Buttons-Compo>
      <Buttons-Compo></Buttons-Compo>
      <Buttons-Compo onclick="window.open('https://salai.be/','_blank')">
      </Buttons-Compo>
    </div>
  </div>
</template>

<script>
import ButtonsCompo from "@/components/ButtonsCompo.vue";
export default {
  name: "Home",
  components: {
    "Buttons-Compo": ButtonsCompo
  },
  data() {
    return {
      msg: "Welcome to  Click for TuuMee"
    };
  }
};
</script>

<style scoped>
/* template {
  background-color: rgba(187, 179, 159, 0.925);
} */
.header {
  padding-top: 2vh;
}
.but-grup {
  display: flex;
  flex-wrap: wrap;
  margin: auto;
  width: 80%;
  /* border: 3px solid green; */
  padding: 10px;
}
</style>
