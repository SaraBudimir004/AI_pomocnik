<template>
  <div>
    <header>
      <nav>
        <ul>
          <li><a href="#home">Home</a></li>
          <li><a href="#about">About Us</a></li>
          <li><a href="#contact">Contact</a></li>
          <li><a href="#signin">Sign In</a></li>
        </ul>
      </nav>
    </header>
  </div>
</template>
<style>
header {
  color: #624F82;
  padding: 1rem;
  text-align: right;
}

/*omogucuje horizontalno postavljanje navigacijskie trake*/
header nav ul li {
  display: inline;
  margin: 0 15px;
}

header nav ul li a {
  color: #624F82;
  text-decoration: none; /*da nije podcrtan tekst*/
}
</style>
<script setup lang="ts">
</script>