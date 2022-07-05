<template>
  <div class="contact">
    <h1>Let's Get in Touch</h1>
    <p>
    We can have a nice chat at:
    <br/>
    <i>elena_tapean@yahoo.com</i>
    </p>
    <h3>Newsletter</h3>
    <label for="newsletter"></label>
    <input type="text" name="newsletter" placeholder="Your email here">
    <button class="subscribe">Subscribe</button>
  </div>
</template>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="css">
p {
    font-family: Helvetica, sans-serif;
    font-size: 21px;
    line-height: 30px;
    text-align: center;
}
input {
    width: 30%;
    height: 25px;
}
.subscribe {
    margin: 10px;
    padding: 5px 10px;
    border-radius: 10px;
    border-style: none;
    background-color: darkgreen;
    color: white;
    font-size: 16px;
    font-style: normal;
}
</style>
