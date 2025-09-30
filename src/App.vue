<script setup lang="ts"></script>

<template>
  <div name="main">
    <h1>You did it!</h1>
    <span is-="badge">badge</span>


    <!-- Shear off the top edge's padding -->
    <div box-="square" shear-="top">
      <div class="header">
          <span>Left</span>
      </div><header>
      <h2># Chakradhar Gorthi</h2>
      <nav id="nav-links">
        <button variant-="maroon">Sick</button>
        <button variant-="rosewater">Button</button>
        <button variant-="sky">Variants</button>
      </nav></header>
    </div>

  </div>
</template>

<style scoped>

div[name="main"] {
  padding: 5ch;
  box-sizing: border-box;
  position: fixed;
  height: 100%;
  width: 100%;
}


span {
  background-color: var(--background0);
  padding: 0 1ch;
}

header {
  display: flex;
  justify-content: space-between;
}

nav#nav-links {
  display: flex;
  gap: 1ch;
  margin-top: 1ch;
}
h2 {
  box-sizing: content-box;
}
</style>
