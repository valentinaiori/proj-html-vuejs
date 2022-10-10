<template>
  <div class="card">
    <div class="arrow">
      <i class="fa-solid fa-arrow-right"></i>
    </div>
    <div class="content">
      <i :class=iconCard id="icon"></i>
      <h1 class="title">{{titleCard}}</h1>
      <p class="text">{{textCard}}</p>
    </div>

  </div>

</template>

<script>
export default {
  name: 'CardRoadTransportComponent',
  props: {
    iconCard: String,
    titleCard: String,
    textCard: String
  }

}
</script>

<style lang="scss" scoped>
.card {
  color: white;
  margin-top: 50px;
  width: 260px;
  height: 220px;
  border: 1px solid #19191f;
  background-color: #19191f;
  border-radius: 10px;

  .content {
    width: 190px;

    .title {
      font-size: 1.2rem;
      padding-top: 20px;
      padding-bottom: 20px;

    }

    .text {
      font-size: 0.8rem;
    }

    #icon {
      background-color: #16282e;
      color: #058283;
      border: 1px solid #16282e;
      border-radius: 50%;
      height: 21px;
      width: 38px;
      padding-top: 8px;
      padding-bottom: 8px;
    }

  }
}

.arrow {
  display: flex;
  padding-bottom: 10px;
  padding-top: 20px;
  margin-left: 220px;
  color: #038384;

}
</style>