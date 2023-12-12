<script setup lang="ts">

</script>

<template>
  <div id="aside-right">
    <aside>
      <ul>
        <li class="title">
          <h1>Links e Contato</h1>
          <p>Tem algum projeto que precisa sair do papel ou alguma demanda em projetos que já estão rodando? Entre em contato e vamos conversar sobre!</p>
        </li>
        <li class="item">
          <a href="https://www.linkedin.com/in/lucien-correia" target="_blank">Linkedin</a>
        </li>
        <li class="item">
          <a href="https://www.github.com/LucienCorreia" target="_blank">Github</a>
        </li>
        <li class="item">
          <a href="https://api.whatsapp.com/send?phone=05548991373581" target="_blank">
            WhatsApp
          </a>
        </li>
        <li class="item">
          <a href="mailto:lucienrc@outlook.com.br" target="_blank">
            E-mail
          </a>
        </li>
      </ul>
    </aside>
  </div>
</template>

<style scoped>
@import "../assets/base.css";

#aside-right {
  align-self: stretch;
}

aside {
  background-color: var(--color-quaternary);
  min-height: 100vh;
  height: 100%;
  width: 20vw;
  padding: 2rem;
}

aside ul {
  list-style: none;
}

aside ul li {
  margin-bottom: 1rem;
}

aside ul li.title h1 {
  color: var(--color-tertiary);
  font-size: 2rem;
  font-weight: 700;
  margin-top: 1rem;
  text-align: left;
  align-self: flex-start;
}

aside ul li.item a {
  color: var(--color-tertiary);
  font-size: 1.5rem;
  font-weight: 400;
  text-decoration: none;
}
</style>