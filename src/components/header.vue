<script>

</script>


<template>
    <div box-="square" shear-="top">
      <div class="header">
          <span>Navbar</span>
      </div>
      <header>
      <h2># Chakradhar Gorthi</h2>
      <nav id="nav-links">
        <button variant-="maroon">Home</button>
        <button variant-="rosewater">Blog</button>
        <button variant-="sky">About</button>
      </nav>
    </header>
    </div>
</template>

<style scoped>
span {
  background-color: var(--background0);
  padding: 0 1ch;
}

header {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

nav#nav-links {
  display: flex;
  gap: 1ch;
  margin-top: 1ch;
}
h2 {
  box-sizing: content-box;
  font-size: 2lh;
}
</style>