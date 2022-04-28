<template>
  <div id="main-banner">
    <h1>Make Your Burguer!</h1>
  </div>
</template>
<script>
export default {
  name: "Banner",
};
</script>

<style scoped>
#main-banner {
  background-image: url('/public/img/burger.jpg');
  background-position: 0 -450px;
  background-size: cover;
  width: 100%;
  height:30vw;
  display:flex;
  align-items: center;
  justify-content: flex-start;
}

#main-banner h1 {
    color: #FFF;
    text-align: center;
    font-size: 3.5vw;
    background: rgba(34, 34, 34, 0.473);
    padding: 20px 40px;
}
</style>
