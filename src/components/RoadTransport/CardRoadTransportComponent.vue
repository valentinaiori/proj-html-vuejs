<template>
    <div class="card">
      <div class="arrow">
        <i class="fa-solid fa-arrow-right"></i>
      </div>
      <div class="content">
        <i :class=iconCard></i>
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
    width: 350px;
    height: 220px;
    border: 1px solid #19191f;
    background-color: #19191f;
    border-radius: 10px;
    margin-right: 20px;

    .content{
      width: 190px;

      .title{
      font-size: 1.2rem;
      padding-top: 20px;
      padding-bottom: 20px;
      
    }

    .text{
      font-size: 0.8rem;
    }
    }

    
  }

  .arrow{
    display: flex;
    padding-bottom: 10px;
    padding-top: 20px;
    margin-left: 180px;

  }
</style>