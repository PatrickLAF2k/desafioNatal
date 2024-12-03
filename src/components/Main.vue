<script setup>
import caixas from "../assets/caixasDePresente.png";
</script>

<template>
  <section>
    <h2>Tempo limitado</h2>
    <p>
      Nessas festas de fim de ano mande um presente para a pessoa amada e
      compartilhe a alegria do Natal.
    </p>
    <h2 class="timer">10d -24h - 01m - 52s</h2>
    <img :src="caixas" alt="" />
  </section>
</template>
<style scoped lang="scss">
section {
  margin-top: 3rem;
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 2rem;

  h2 {
    font-size: 2.5rem;
  }

  p {
    font-size: 1.25rem;
    width: 25%;
    text-align: center;
  }

  .timer{
    font-size: 4rem;
    color: #CD3C32;
  }
}
</style>
