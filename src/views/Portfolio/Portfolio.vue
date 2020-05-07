<template>
  <div class="portfolio">
    <nav id="colorlib-main-menu" role="navigation" class="navbar" style="">
      <div id="navbar" class="collapse" aria-expanded="false">
        <ul>
          <li class="active">
            <a href="#" data-nav-section="home">Home</a>
          </li>
          <li class>
            <a href="#" data-nav-section="about">About</a>
          </li>
          <li class>
            <a href="#" data-nav-section="services">Services</a>
          </li>
          <li class>
            <a href="#" data-nav-section="skills">Skills</a>
          </li>
          <li class>
            <a href="#" data-nav-section="education">Education</a>
          </li>
          <li class>
            <a href="#" data-nav-section="experience">Experience</a>
          </li>
          <li class>
            <a href="#" data-nav-section="work">Work</a>
          </li>
          <li class>
            <a href="#" data-nav-section="blog">Blog</a>
          </li>
          <li class>
            <a href="#" data-nav-section="contact">Contact</a>
          </li>
        </ul>
      </div>
      <div class="description-section">
        <p>Welcome to FRS-HSR</p>
      </div>
    </nav>
   <!---------- <div class="contact-section"></div>
    <div class="icon-section">
      <div class="home-icon"><i class="fas fa-home"></i></div>
      <div class="phone-icon"><i class="fas fa-phone"></i></div>
    </div>------->
  </div>
</template>

<style scoped>
ul {
  padding-top: 3em;
  padding-bottom: 40px;
  float: left;
  width: 300px;
  position: fixed;
  overflow-y: scroll;
  z-index: 1001;
  background: #ecedf1;
  -webkit-transition: 0.5s;
  -o-transition: 0.5s;
  transition: 0.5s;
  height: 564px;
}
li {
  color: rgba(0, 0, 0, 0.7);
  text-decoration: none;
  position: relative;
  padding: 10px 0;
  font-family: quicksand, Arial, sans-serif;
  -webkit-transition: 0.3s;
  -o-transition: 0.3s;
  transition: 0.3s;
}
.navbar {
  display: inline block;
}
.description-section {
    padding: 15px 350px 17px;;
    font-size: 35px
}
.icon-section {
    float: right;
}
</style>

    