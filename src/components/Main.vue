<template>
  <div class="intro-container">
    <div class="intro">
        <h2>Victor Cui</h2>
        <h3>Software engineer</h3>
    </div>
    <div class="about">
      <h2>About Me</h2>
      <p>I'm a 22 year old software engineer living in Seattle. I currently work at Amazon on the AWS Revenue Reporting Team. My hobbies include playing basketball, cooking, and skiing. </p>
    </div>
    <div class="work-experience">
      <div class="amazon">
        <h4> AWS </h4>
        <h5 class="title"> Software Engineer 1, <i>Since March 2019</i></h5>
        <p> My team works on hosting game servers in the cloud for game developers like Ubisoft</p>
      </div>
      <div class="amazon">
        <h4>Fintech for AWS</h4>
        <h5 class="title"> Software Engineer 1, <i>August 2018 - Feb. 2019</i></h5>
        <p> My team worked on reporting revenue for AWS on a fine-grained level, by service, time period, and region.</p>
      </div>
      
    </div>
  </div>
</template>

<script>
export default {
  name: 'Main',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.intro {
  background-image: url("../assets/ocean.jpeg");
  background-size: contain;
  height: 500px;
  width: 100%;
  h2, h3 {
    color: white;
  }
}
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
