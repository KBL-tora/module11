<template>
  <div id="app">
    <nav>
      <router-link to="/about">About</router-link>
      <router-link to="/quotes">Random Quotes</router-link>
      <router-link to="/contact">Contact</router-link>
    </nav>

    <router-view />
  </div>
</template>

<style>
nav {
  display: flex;
  gap: 20px;
  padding: 20px;
}

nav a {
  text-decoration: none;
  font-weight: bold;
}
</style>
