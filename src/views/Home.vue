<template>
  <div>
    <banner />
  </div>
  <div class="main-container">
    <h1>Monte seu Burger!</h1>
    <BurgerForm />
  </div>
</template>

<script>
import banner from "../components/banner.vue";
import BurgerForm from "../components/BurgerForm.vue";

export default {
  name: "Home",
  components: {
    banner,
    BurgerForm,
  },
};
</script>

