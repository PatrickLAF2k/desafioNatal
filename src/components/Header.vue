<script setup>
import noel from "../assets/rostoNoel.png";
import loja from "../assets/lojaNatal.png";
</script>

<template>
  <section>
    <div class="textos">
      <div>
        <img :src="noel" alt="Rosto do papai noel" />
        <h2>Feliz Natal</h2>
      </div>
      <h2>Uma <span>plataforma de doação</span> para espalhar alegria</h2>
      <p>
        Nessas festas de fim de ano mande um presente para a pessoa amada e
        compartilhe a alegria do Natal.
      </p>
      <button>Fazer uma docação</button>
    </div>

    <img :src="loja" alt="Criança olhando para dentro de uma loja" />
  </section>
</template>

<style scoped lang="scss">
section {
  background-color: #ffe9e8;
  justify-content: center;
  align-items: center;
  display: flex;
  justify-content: space-evenly;
  width: 100vw;
  height: 40vh;

  .textos {
    width: 30%;
    display: flex;
    flex-direction: column;
    align-items: baseline;
    gap: 2rem;

    div {
      display: flex;
      align-items: center;
      gap: 1rem;

      h2 {
        font-size: 1.5rem;
      }
    }

    h2 {
      font-size: 2.5rem;

      span {
        color: #cd3c32;
      }
    }

    p {
      font-size: 1.5rem;
    }

    button {
      background-color: #cd3c32;
      color: white;
      border: none;
      padding: 1rem 1.5rem;
      border-radius: 10px;
      font-size: 1.12rem;
      font-weight: bold;
      cursor: pointer;
    }
  }
}
</style>
