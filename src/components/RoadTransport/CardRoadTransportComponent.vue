<template>
    <div class="card">
      <div>
        <i class="fa-solid fa-arrow-right"></i>
      </div>
    <i :class=iconCard></i>
    <h1>{{titleCard}}</h1>
    <p>{{textCard}}</p>
    </div>
</template>

<script>
export default {
    name:'CardRoadTransportComponent',
    props: {
      iconCard: String,
      titleCard: String,
      textCard: String
    }

}
</script>

<style lang="scss" scoped>

  .card{
    color: white;
  }

</style>