<template>
  <div>
    <h2>About</h2>
    <p>
      Loremipsum dolor, sit amet consectetur adipisicing elit. Dolorum ipsa sunt
      veritatis quod, quo ullam molestias enim officia illo minus!
    </p>
    <p>
      Lorem ipsum dolor, sit amet consectetur adipisicing elit. Dolorum ipsa
      sunt veritatis quod, quo ullam molestias enim officia illo minus!
    </p>
    <div>{{ data }}</div>
  </div>
</template>

<script setup>
const { data } = await useFetch("/api/currency/GBP");
// ?name=mario", {
//   method: "post",
//   body: { age: 30 },
// });
</script>

<style scoped>
h2 {
  margin-bottom: 20px;
  font-size: 36px;
}
p {
  margin: 20px 0;
}
</style>
