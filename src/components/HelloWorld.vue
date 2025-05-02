<script setup lang="ts">
// script
</script>

<template>
   <main class="webgen">
    <h1>Webgen + Vue + TS</h1>

    <img class="logo" src="../assets/vue.svg" alt="React Logo" />

    <a class="react-link" href="https://vuejs.org/" target="_blank" rel="noreferrer">
      Learn Vue
    </a>

    <p class="description">
      Thank you for using <strong>Webgen</strong> — a fun little starter for your projects.<br />
      More updates will come. Don’t forget to check my GitHub!
    </p>

    <a class="github-button" href="https://github.com/zen-Hikari" target="_blank" rel="noreferrer">
      Visit My GitHub
    </a>
  </main>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
  
.webgen {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  min-height: 90vh;
  padding: 40px 20px;
  background: radial-gradient(circle at top, #1e1e3f60, #111);
  color: white;
  font-family: 'Inter', sans-serif;
  text-align: center;
  animation: fadeIn 0.6s ease-in;
}

h1 {
  font-size: 3rem;
  font-weight: 700;
  margin-bottom: 30px;
  background: linear-gradient(90deg, #61fba1c7, #61fba1d5);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}

.react-link {
  font-size: 1.25rem;
  color: #61fba1;
  font-weight: 600;
  margin-bottom: 30px;
  text-decoration: none;
  transition: color 0.3s ease;
}
.react-link:hover {
  color: #61fba198;
}

.description {
  font-size: 1rem;
  color: #ccc;
  max-width: 500px;
  line-height: 1.6;
  margin-bottom: 40px;
}

.github-button {
  background-color: #fff;
  color: #111;
  padding: 12px 24px;
  border-radius: 50px;
  font-weight: 600;
  text-decoration: none;
  transition: all 0.3s ease;
}
.github-button:hover {
  background-color: #61dafb;
  color: #000;
}

@keyframes spin {
  from {
    transform: rotate(0deg);
  }
  to {
    transform: rotate(360deg);
  }
}

@keyframes fadeIn {
  from {
    opacity: 0;
    transform: translateY(20px);
  }
  to {
    opacity: 1;
    transform: translateY(0);
  }
}
</style>
