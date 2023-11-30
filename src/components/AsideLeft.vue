<script setup lang="ts">
const frameworks = [
  'Flutter',
  'Laravel',
  'VueJS',
  'Angular',
];

const knowledges = {
  'Conteinerização': ['Docker', 'WSL', 'Kubernetes'],
  'Integração e Entrega Contínua': ['Fastlane', 'GitHub', 'Actions', 'Jenkins', 'CircleCI'],
  'Versionamento de Código': ['Git', 'GitFlow', 'Conventional Commits', 'Git Hooks', 'Semantic Versioning'],
  'Bando de Dados': ['MySQL', 'PostgreSQL', 'MongoDB', 'SQLite', 'MariaDB'],
  'Metodologias Ágeis': ['Scrum', 'Kanban'],
};
</script>

<template>
  <div id="aside-left">
    <aside>
      <header>
        <img src="../assets/profile_photo.jpg" alt="">
        <h1>Lucien Risso Correia (#OpenToWork)</h1>
      </header>
      <section>
        <ul>
          <li class="title">
            Frameworks
          </li>
          <li v-for="framework in frameworks" class="item">
            {{ framework }}
          </li>
        </ul>
      </section>
      <section>
        <ul>
          <li class="title">
            Demais Conhecimentos
          </li>
          <li v-for="(value, key) in knowledges" class="item">
            {{ key }}
            <ul>
              <li v-for="item in value" class="item">
                {{ item }}
              </li>
            </ul>
          </li>
        </ul>
      </section>
    </aside>
  </div>
</template>

<style scoped>
  @import "../assets/base.css";

  #aside-left {
    align-self: stretch;
  }

  aside {
    background-color: var(--color-quaternary);
    min-height: 100vh;
    width: 20vw;
    padding: 2rem;
  }

  aside header {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
  }

  aside header img {
    border-radius: 50%;
    height: 10vw;
    width: 10vw;
  }

  aside header h1 {
    color: var(--color-tertiary);
    font-size: 2rem;
    font-weight: 700;
    margin-top: 1rem;
    text-align: left;
    align-self: flex-start;
  }

  aside section {
    margin-top: 2rem;
  }

  aside section ul {
    list-style: none;
    padding: 0;
  }

  aside section ul li {
    color: var(--color-tertiary);
    font-size: 1.5rem;
    font-weight: 700;
    margin-top: 1rem;
    text-align: left;
    align-self: flex-start;
  }

  aside section ul li.item {
    color: var(--color-tertiary);
    font-size: 1rem;
    font-weight: 400;
    margin-top: 0.5rem;
    margin-left: 1rem;
    list-style: circle;
  }
</style>
