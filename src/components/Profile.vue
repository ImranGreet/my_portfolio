<template>
    <section id="profile">
        <div class="section__pic-container">
          <img src="../assets/project-1.png" alt="John Doe profile picture" />
        </div>
        <div class="section__text">
          <p class="section__text__p1">Hello, I'm</p>
          <h1 class="title">Imran Hossain</h1>
          <p class="section__text__p2">Frontend Developer</p>
          <div class="btn-container">
            <button
              class="btn btn-color-2"
              onclick="window.open('../assets/resume-example.pdf')"
            >
              Download CV
            </button>
            <button class="btn btn-color-1" onclick="location.href='./#contact'">
              Contact Info
            </button>
          </div>
          <div id="socials-container">
            <img
              src="../assets/linkedin.png"
              alt="My LinkedIn profile"
              class="icon"
              onclick="location.href='https://www.linkedin.com/in/imran-hossain-9210042a7/'"
            />
            <img
              src="../assets/github.png"
              alt="My Github profile"
              class="icon"
              onclick="location.href='https://github.com/ImranGreet'"
            />
          </div>
        </div>
      </section>
</template>

<script>
export default {

}
</script>

<style>

</style>