<template>
  <div class="about">
    <h1>This is an Details page</h1>
    <br />
    <button>Click me</button>
  </div>
</template>

<style scoped>
@media (min-width: 1024px) {
  .about {
    display: flex;
    flex-direction: column; /* Stack children vertically */
    align-items: center; /* Center align children horizontally */
    justify-content: center; /* Center align children vertically if needed */
    height: 100vh; /* Full height container */
  }
}

h1 {
  color: hsla(118, 100%, 30%, 0.4);
}
</style>

<style>
/* @import '../Detail/DetailView.css'; */
@import '../../assets/glassmorphismbutton.css';
</style>
