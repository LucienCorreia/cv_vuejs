<script setup lang="ts">

</script>

<template>
  <div id="resume">
    <h1>Apresentação</h1>
    <div class="divider small transparent"></div>
    <div class="resume-paragraph">
      <p>Trabalho com desenvolvimento de software há seis anos, atuando em maior parte com Laravel e Flutter. Participei de projetos em âmbito nacional e internacional de diversos tamanhos. Com propósito de expandir as frentes estou começando com DevOps.</p>
      <p>Das tecnologias que domino se destacam Laravel e Flutter, mas incluem também PHP, Dart, Angular, JavaScript, MySQL, Postgres e Docker. Valendo destaque também para algumas poucos utilizadas em projetos como Java, VueJS e Kotlin.</p>
      <p>Os maiores projetos foram dos setores de Ecommerce, Financeiro e setor público, também atuando em projetos de sistemas internos de empresas, ERP, CRM e força de vendas. Com isso abrande grande experiência com integrações como Gateways de pagamentos, cotação de frete, sistemas financeiros e demais sistemas de terceiros.</p>
      <p>Planejamento e desenvolvimento de soluções para larga escala e disponibilidade, utilizando estratégias de arquitetura e engenharia de software para tais finalidades, visando também a manutenção dessa aplicações ao decorrer do tempo.</p>
    </div>
    <div class="divider transparent"></div>
    <h1>Experiências</h1>
    <div class="divider small transparent"></div>
    <div class="experience">
      <div class="title">
        <div class="company">
          Doutor-IE
        </div>
      </div>
      <h3 class="role">
        Fullstack Developer
        <div class="date">
          (maio 2023 - novembro/2023)
        </div>
      </h3>
      <div class="description">
        <p>
          Atuei como desenvolvedor fullstack utilizando de Flutter e Laravel para desenvolver o aplicativo, sistemas internos e a APIs.
        </p>
      </div>
    </div>
    <div class="divider small transparent"></div>
    <div class="experience">
      <div class="title">
        <div class="company">
          Guide Investimentos
        </div>
      </div>
      <h3 class="role">
        Mobile Developer
        <div class="date">
          (outubro/2021 - março/2023)
        </div>
      </h3>
      <div class="description">
        <p>
          Entrei pra ajudar o time de mobile a migrar o projeto atual desenvolvido nativamente para Flutter e a evangelizar o Flutter na empresa. Ajudei também a capacitar demais desenvolvedores para atuarem com Flutter. Esse projeto utilizava a arquitetura de micro apps juntamente com clean architecture. Por algumas vezes também atuei com Angular.
        </p>
      </div>
    </div>
    <div class="divider small transparent"></div>
    <div class="experience">
      <div class="title">
        <div class="company">
          Ioasys
        </div>
      </div>
      <h3 class="role">
        Flutter Developer
        <div class="date">
          (julho/2021 - outubro/2021)
        </div>
      </h3>
      <div class="description">
        <p>
          Alocado na CVC atuei ajudando no planejamento e reescrita do projeto atualmente em Flutter porém iniciado por desenvolvedores de outras Stacks e reescrito utilizando melhores padrões pro Flutter. O aplicativo era white-label, era possível fazer build dele como CVC, Almundo ou Submarino, três produtos da CVC Corp.
        </p>
      </div>
    </div>
    <div class="divider small transparent"></div>
    <div class="experience">
      <div class="title">
        <div class="company">
          Multiplier
        </div>
      </div>
      <h3 class="role">
        Fullstack Developer
        <div class="date">
          (julho/2017 - julho/2021)
        </div>
      </h3>
      <div class="description">
        <p>
          Iniciando como Wadvice e depois mudando o nome para Multiplier, indo de uma fábrica de software para uma startup com um ecosistema de produtos próprios atuei em muitas frentes. Inicialmente como Fullstack Web utiliando de PHP vanilla e Laravel. Desenvolvendo sites pequenos e grandes, para empresas regionais e nacionais. Um tempo depois aprendi desenvolvimento mobile utilizando ionic e atuei em alguns projetos para empresas da região. Na transição da empresa me tornei líder do time de mobile onde começei a atuar com Flutter e ainda atuando com o backend Laravel criando as APIs do aplicativo.
        </p>
      </div>
    </div>
  </div>
</template>

<style>
  @import "../assets/base.css";

  #resume {
    padding: 3rem;
    width: 100%;
    min-height: 100vh;
    height: 100%;
  }

  #resume h1 {
    font-size: 2rem;
    color: var(--color-tertiary);
  }

  #resume p {
    font-size: 1.2rem;
    color: var(--color-tertiary);
    text-align: justify;
  }

  #resume .resume-paragraph p {
    margin-top: 1rem;
    text-indent: 2rem;
  }

  #resume .experience .company {
    font-size: 1.5rem;
    color: var(--color-tertiary);
    margin-right: 1rem;
  }

  #resume .experience .title {
    display: flex;
    align-items: end;
    flex-direction: row;
    text-align: start;
    align-self: start;
  }

  #resume .experience .role {
    font-size: 1.2rem;
    color: var(--color-tertiary);
    display: flex;
    align-items: end;
    flex-direction: row;
    text-align: start;
    align-self: start;
  }

  #resume .experience h3 {
    font-size: 1.2rem;
    color: var(--color-tertiary);
  }

  #resume .experience .date {
    font-size: 1rem;
    color: gray;
    margin-left: 1rem;
  }

  #resume .experience .description {
    margin-top: 1rem;
    font-size: 1rem;
  }
</style>