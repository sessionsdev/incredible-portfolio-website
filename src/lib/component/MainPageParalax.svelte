<script>
    import TypewriterCodeBox from './TypewriterCodeBox.svelte'
</script>

    <!-- <section class="hero is-small has-background-primary">
      <div class="hero-body">
        <div class="container">
          <h1 class="title is-1 ">Jon Sessions</h1>
          <h2 class="subtitle">Developing in public.</h2>
          <a href="/" class="button is-info is-medium is-inverted">Hire Me!<i class="fad fa-chevron-right"></i></a>
        </div>
      </div>
    </section> -->

    <!-- paralax section 1 -->
    <section id="parallax-1" class="hero is-fullheight">
      <div class="hero-body p-2">
        <div class="container">
          <div class="columns mb-6 pb-6">
            <div class="column is-5 is-offset-7 is-hidden-mobile">
                <TypewriterCodeBox />
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- paralax section 2 -->
    <section id="parallax-2" class="hero is-large ">
      <div class="hero-body">
        <div class="container">
          <div class="columns">
            <div class="column is-6">
              <h1 class="title is-1 ">Dolor Sit</h1>
              <hr class="content-divider">
              <h2 class="subtitle">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Doloremque veritatis sequi natus minima distinctio ullam deleniti quasi quisquam autem deserunt.</h2>
              <a href="/" class="button is-white is-inverted">Next&ensp;<i class="fad fa-chevron-right"></i></a>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- paralax section 3 -->
    <section id="parallax-3" class="hero is-large ">
      <div class="hero-body">
        <div class="container">
          <div class="columns">
            <div class="column is-6 is-offset-6">
              <h1 class="title is-1 ">Amet Consectetur</h1>
              <hr class="content-divider">
              <h2 class="subtitle">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Iure minus nam necessitatibus neque in perferendis eveniet dolorum assumenda dolores accusamus.</h2>
              <a href="/" class="button is-white is-inverted">Next&ensp;<i class="fad fa-chevron-right"></i></a>
            </div>
          </div>
        </div>
      </div>
    </section>

<style>


.title {
  color: white;
  font-weight: 800;
  font-size: 4rem;
  font-family: 'Nunito Sans', sans-serif;
  text-shadow: 1px 1px 1px #000, 3px 3px 5px rgb(0, 0, 3);
}

.subtitle {
  color: white;
  font-size: 1.2rem;
  text-shadow: 1px 1px 1px #000, 3px 3px 5px rgb(0, 0, 3);
}

hr.content-divider {
  max-width: 75px;
  height: 5px;
}

#parallax-1 {
  background: url('/img/main-background.png');
  background-attachment: fixed;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  border-top: 10px solid coral;
}

#parallax-2 {
  background: url(https://source.unsplash.com/featured/?computers);
  background-attachment: fixed;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  border-top: 10px solid yellow;
}

#parallax-2 hr {
  background: yellow;
}

#parallax-3 {
  background: url('/img/main-background.png');
  background-attachment: fixed;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  border-top: 10px solid hotpink;
}

#parallax-3 hr {
  background: hotpink;
}
</style>