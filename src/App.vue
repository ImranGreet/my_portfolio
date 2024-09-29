<script setup lang="ts">
import Navbar from "./components/Navbar.vue";
import Profile from "./components/Profile.vue";
import About from "./components/About.vue";
import Exp from "./components/Exp.vue";
import Projects from "./components/Projects.vue";
import Contact from "./components/Contact.vue";




</script>

<template>
  
  <section>
    <Navbar />
    <Profile />
    <About />
    <Exp />
    <Projects />
    <Contact />
    <footer>
      <nav>
        <div class="nav-links-container">
          <ul class="nav-links">
            <li><a href="#about">About</a></li>
            <li><a href="#experience">Experience</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#contact">Contact</a></li>
          </ul>
        </div>
      </nav>
      <p>Copyright &#169; 2023 John Doe. All Rights Reserved.</p>
    </footer>
  </section>
</template>


