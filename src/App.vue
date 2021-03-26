<template>
  <div id="app">
    <header class="cover">
      <div class="container">
        <nav
          class="navbar is-transparent"
          role="navigation"
          aria-label="main navigation"
        >
          <div class="navbar-brand">
            <a class="navbar-item" href="/">
              <img src="./assets/logo.svg" width="112" height="28" />
            </a>
            <a
              role="button"
              class="navbar-burger"
              aria-label="menu"
              aria-expanded="false"
              data-target="navbarBasicExample"
            >
              <span aria-hidden="true"></span>
              <span aria-hidden="true"></span>
              <span aria-hidden="true"></span>
            </a>
          </div>
          <div id="navbarBasicExample" class="navbar-menu">
            <div class="navbar-end">
              <a class="navbar-item"> Seccion 1 </a>
              <a class="navbar-item"> Seccion 2 </a>
              <a class="navbar-item"> Seccion 3 </a>
            </div>
          </div>
        </nav>
      </div>
      <div class="container">
        <div class="mt-6 content-header">
          <h1 class="is-size-1 px-3 title-podcast">PODCAST</h1>
          <p class="mt-5 px-3 is-size-3 intro-color">
            Unde quia minima aspernatur quam fugit in est. Autem et ipsam
            molestias ad autem ut aut. Et alias eveniet occaecati et.
          </p>
          <button class="mx-3 my-6 px-6 button is-rounded btn">
            Capítulos
          </button>
        </div>
      </div>
    </header>
    <main>
      <section class="intro-episodio">
        <div class="container">
          <div class="columns pt-6">
            <div class="column">
              <img src="./assets/CardPodcast.svg" alt="podcast">
            </div>
            <div class="column">
              <h2 class="is-size-1">Nihil cupiditate illo</h2>
              <p class="is-size-4 mt-3">
                Tempore qui mollitia consequatur quia. Eaque ut et autem facere.
                Debitis quis et ut quisquam praesentium dolorum aut.
              </p>
              <div>
                <button class="mx-3 my-6 px-6 button is-rounded btn2">Escucha ahora</button>
                <button class="mx-3 my-6 px-6 button is-rounded btn2">Lista de Capitulos</button>
              </div>
            </div>
          </div>
        </div>
      </section>
      <section class="section-medium">
        <div class="container">
          <div class="columns">
            <div class="column pt-6">
              <div class="bg-medium">
                <h1 class="is-size-1">Natus asperiores illo</h1>
                <p class="is-size-4 mt-3">Asperiores consequatur sint quam omnis sint. Molestias quibusdam quaerat et vel quas. Magnam qui velit blanditiis. Incidunt dolorem veritatis aut consequatur nihil nemo ab. Sunt at omnis non eum similique voluptas qui.</p>
              </div>
            </div>
            <div class="column is-flex is-justify-content-center">
              <img src="./assets/Podcast-color.svg" alt="svg" class="imagen">
            </div>
          </div>
        </div>
      </section>
    </main>
  </div>
</template>

<script>
export default {
  name: "App",
};
</script>

<style>
body {
  background-color: #f2f2f2;
}

.cover {
  width: 100vw;
  height: 100vh;
  background-image: url("assets/podcastlanding.svg");
  background-repeat: no-repeat;
  background-size: cover;
  background-clip: border-box;
  background-position: -0.5rem;
}

.intro-color {
  font-size: 6rem;
  font-weight: bold;
  color: #000;
}

.navbar {
  background-color: transparent;
}

.navbar-item {
  color: #9f0052;
}

.navbar-item:hover {
  color: #ffbe00  !important;
}

.title-podcast {
  font-size: 6rem;
  font-weight: bold;
  color: #ffbe00;
}

.btn, .btn2 {
  background-color: #9f0052 ;
  color: #fff;
  border: none;
}

.btn:hover {
  background-color: #ffbe00 ;
  color: #fff;
}

.btn2:hover {
  background-color: #ffbe00  ;
  color: #fff;
}

.content-header {
  width: 50%;
}

.intro-episodio {
  height: 32rem;
  color: #fff;
  background-image: url('assets/fondo2.svg');
  background-repeat: no-repeat;
  background-size: cover;
  background-clip: border-box;
}

.section-medium {
  height: 32rem;
  color: #000;
  overflow: hidden;
}

.imagen {
  width: 35rem;
}

.bg-medium {
  margin-top: 5rem;
  /* background-image: url('assets/fondo3.svg');
  background-repeat: no-repeat; */
}

</style>