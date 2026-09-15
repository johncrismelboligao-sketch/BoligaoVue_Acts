<template>
  <div>
    <nav>
      <RouterLink to="/">Home</RouterLink>
      |
      <RouterLink to="/about">About</RouterLink>
      |
      <RouterLink :to="{ name: 'Contact' }">Contact</RouterLink>
     </nav>
    <br>
    <RouterView/>
  </div>
</template>