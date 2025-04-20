<template>
  <nav>
    <h1><NuxtLink to="/">LOGO</NuxtLink></h1>
    <ul class="menu">
      <li><NuxtLink to="/">Home</NuxtLink></li>
      <li>
        <NuxtLink to="/customer-projects">Customer projects</NuxtLink>
      </li>
      <li>
        <NuxtLink to="/personal-projects">Personal projects</NuxtLink>
      </li>
    </ul>
  </nav>
</template>

<style scoped>
nav {
  padding: 20px;
}
.menu {
  display: flex;
  flex-direction: column;
}
.menu a {
  display: block;
  color: black;
  text-decoration: none;
  padding: 10px;

  &:hover {
    background-color: rgba(0, 0, 0, 0.2);
  }
  &.router-link-exact-active {
    background-color: rgba(0, 0, 0, 0.4);
  }
}
h1 {
  font-size: x-large;
  margin-bottom: 30px;
  padding: 10px;
}
</style>
