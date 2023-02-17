<script>
export default {
  props: {
    myName: String,
  },
  dev: {
    useEslint: false,
  },
};
</script>
<template>
  <div
    class="home__container container-sm mx-auto columns-1 px-10 w-4/5 column-2"
  >
    <section>
      <h1 class="text-6xl font-medium leading-loose">Hello.</h1>
      <p class="text-3xl font-medium leading-loose">Me chamo {{ myName }}.</p>
      <p class="w-4/5 text-xl font-light">
        Sou um desenvolvedor front-end apaixonado por tecnologia, especializado
        em criar interfaces e experiências do usuário para sites e aplicativos
        usando HTML, CSS e JavaScript. Além disso, estou estudando ativamente
        sobre desenvolvimento de software backend para expandir minhas
        habilidades e oferecer soluções mais robustas e escaláveis aos meus
        clientes.
      </p>
      <p class="mt-6">
        Minha paixão por tecnologia me inspira a estar sempre atualizado com as
        últimas tendências do mercado e a buscar inovações para criar soluções
        eficientes e inovadoras para meus clientes.
      </p>
    </section>

    <section class="mt-7">
      <a
        href="https://github.com/Msamuelsons"
        target="_blank"
        class="ml-5 text-center inline-flex items-center justify-center p-2 bg-grey-200 rounded-md shadow-lg"
        >Github</a
      >
    </section>
  </div>
</template>
<style scoped>
.home__container + section {
  width: 100vw;
  height: 100vh;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: space-around;
  flex-wrap: wrap-reverse;
  color: #121314;
  z-index: 1;
}
.home__container p + p {
  font-size: 1.6em;
  font-weight: 300;
  line-height: 1.4;
  max-width: 28em;
}
</style>
