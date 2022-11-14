<script setup>
import Header from "./components/Header.vue";
// import TheWelcome from './components/TheWelcome.vue'
</script>
<template>
    <div class="container">
      <Header nama="Anton" role="front end developer"/>
      <div class="about">
        <div class="row-about">
          <h1 class="second-title">About Me</h1>
          <p class="second-paragraf">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolore
            dolorem consequuntur, odit ipsam suscipit harum amet eveniet
            voluptatum, officiis repellat sed numquam veniam maxime. Non nemo
            placeat ut quos accusamus?
          </p>
        </div>
        <div class="row-about">
          <p>Age :</p>
          <p>Email :</p>
          <p>Phone :</p>
          <p>Address :</p>
        </div>
        <div class="row-about">
          <p>21</p>
          <p>antonrobian@gmail.com</p>
          <p>+6285234932112</p>
          <p>kotaanyar, Probolinggo</p>
        </div>
      </div>
      <div class="contact">
        <div class="col-contact">
          <h1 class="third-title">Contact</h1>
          <form>
            <div class="form-input">
              <input
                class="form-control"
                type="text"
                name="name"
                placeholder="Your Name"
              />
              <input
                class="form-control"
                type="email"
                name="email"
                placeholder="Your Email"
              />
            </div>
            <textarea
              name="text"
              cols="61"
              rows="10"
              placeholder="Your Message"
            ></textarea>
            <button type="submit">Send</button>
          </form>
        </div>
        <div class="col-contact">
          <h3 class="fix">Address</h3>
          <p class="fix">kotaanyar, Probolinggo</p>
          <h3 class="fix">Phone</h3>
          <p class="fix">004124115</p>
          <h3 class="fix">Email</h3>
          <p class="fix">antonrobian2@gmail.com</p>
        </div>
      </div>
    </div>
    <div class="copyright">
      Di buat oleh <a href="https://github.com/Antonrobian">Muhammad</a>Anton Robian
    </div>
</template>

<style scoped>
header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>
