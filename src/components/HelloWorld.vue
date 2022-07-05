<template>
  <div class="hello">
    <div class="row">
      <div class="column" style="background-color:#FFFFFF;">
        <h1>{{ msg }}</h1>
          <p>
            Designing user interfaces using HTML, CSS, JavaScript code and frameworks such as Vue and React. I also create icons with Figma and Git.
          </p>
          <h3>Projects</h3>
            <ul>
              <li><a href="#">My Portfolio</a></li>
              <li><a href="https://elenatapeanpoetry.wordpress.com/">https://elenatapeanpoetry.wordpress.com/</a></li>
              <li><a href="https://elenatapeanphotos.wordpress.com/">https://elenatapeanphotos.wordpress.com/</a></li>
              <li><a href="#">Cooks and Books. Delicious Recipes Everyday</a></li>
              <li><a href="#">Vue a Literary Blog</a></li>
              <li><a href="#">React to an Interface</a></li>
              <li><a href="#">The Webpage Game</a></li>
            </ul>
          <button>Hire Me</button>
          <h3>Contact</h3>
            <p>elena_tapean@yahoo.com</p>
      </div>
      <div class="column" style="background-color:#FFFFFF;">
        <div class="clearfix">
          <img alt="Vue logo" src="../assets/img1.jpg">
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="css">
* {
  box-sizing: border-box;
}
.column {
  float: left; 
  width: 50%; 
  padding: 10px 80px;
}
.row::after {
  content: ""; 
  display: flex; 
  color: #000000;
}
.clearfix {
  overflow: auto;
}
img {
  margin: 0;
  padding: 0;
  float: center;
  width: 450px;
  height: 600px;
  border-style: none;
  display: inline-block;
}
h3 {
  font-family: Helvetica, sans-serif;
  margin: 10px;
  padding: 10px;
  text-align: left;
  text-indent: 30px;
}
p {
  margin: 10px;
  font-family: Helvetica, sans-serif;
  font-size: 20px;
  display: flex;
  line-height: 30px;
  text-indent: 30px;
  text-align: justify;
}
ul {
  list-style-type: none;
  padding: 0;
  margin: 0;
}
li {
  display: block;
  margin: 0;
  padding: 0;
  line-height: 30px;
  text-align: left;
  text-indent: 60px;
}
a {
  line-height: 25px;
  color: green;
  opacity: 0.8;
  font-size: 18px;
}
button {
  border-style: none;
  background-color: orange;
  opacity: 0.9;
  color: white;
  font-size: 16px;
  font-weight: bold;
  display: block;
  margin: 30px 50px;
  padding: 20px 20px;
  border-radius: 15px;
}
</style>
