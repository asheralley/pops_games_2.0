<template>
  <header>
        <div class="mobile-nav">
            <div class="mobile-nav-icons">
                <a href="index.html"><img id="home-icon" class="menu-icon" src="Home-icon.svg.png" alt="home icon"></a>
                <a href="javascript:void(0);" onclick="myFunction();"><img id="hamburger-icon" class="menu-icon" src="images/Hamburger_icon.svg.png" alt=""></a>
            </div>
            <ul id="menu-items" class="mobile-nav-menu">
                <li><a href="games.html">Games</a></li>
                <li><a href="puzzles.html">Events</a></li>
                <li><a href="gallery.html">Gallery</a></li>
                <li><a href="hireage.html">Hireage</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </div>
        <div class="logo-div">
            <img class="main-logo" src="src/assets/pops-logo.png" alt="pops games logo">
        </div>
        <div class="full-width">
          <nav class="wrapper flex" id="desktop-nav">
            <ul class="nav-main">
              <li><a class="main-nav-item show" href="index.html">Home</a></li>
              <li><a class="main-nav-item" href="games.html">Games</a></li>
              <li><a class="main-nav-item" href="puzzles.html">Puzzles</a></li>
              <li><a class="main-nav-item" href="gallery.html">Gallery</a></li>
              <li><a class="main-nav-item" href="hireage.html">Hireage</a></li>
              <li><a class="main-nav-item" href="contact.html">Contact</a></li>
            </ul> 
          </nav>
        </div>
    </header>
</template>

<script>
export default {
  name: 'MainNav',
  data () {
    return {
      msg: ''
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
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
