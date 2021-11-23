<template>
    <div id="jumbotron">
      <div>
        <h2>Jumbotron</h2>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Tempore necessitatibus officia animi, libero ratione dolor consequatur hic, fugiat voluptate, fugit ex! Dolorem ipsam esse commodi earum? Blanditiis voluptatibus sit distinctio.</p>
      </div>
    </div>
</template>

<script>
export default {
  name: 'Hero',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
#jumbotron{
  position: relative;
  background-image: url('https://source.unsplash.com/user/erondu/1200x500');
  // background-position: center;
  background-size: contain;
  max-width: 1200px;
  height: 500px;
}
#jumbotron>div{
  position: absolute;
  width: 50%;
  left: 10px;
  bottom: 10px;
  color: #fff;
  text-align: left;
}

</style>