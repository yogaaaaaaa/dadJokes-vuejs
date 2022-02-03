<template>
  <header class="header">
    <h1 class="title">Dad Jokes</h1>
    <ul>
      <li>
        <nux-link to="/">Home</nux-link>
      </li>
      <li>
        <nux-link to="/jokes">Jokes</nux-link>
      </li>
      <li>
        <nux-link to="/about">About</nux-link>
      </li>
    </ul>
  </header>
</template>

<script>
export default {
  name: 'AppHeader',
}
</script>

<style>
.header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 1rem;
  padding-bottom: 1rem;
  border-bottom: 1px dotted #ccc;
}

.header .title {
  font-size: 3rem;
  color: #526488;
}

.header ul {
  display: flex;
}

.header a {
  display: inline-block;
  background: #333;
  color: #fff;
  padding-bottom: 0.3rem 1rem;
  margin-right: 0.5rem;
}
</style>
