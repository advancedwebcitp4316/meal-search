<template>
  <nav>
    <RouterLink :to="{name: 'Home'}">Home</RouterLink>
    <RouterLink :to="{name: 'MealsByName'}">Search By Name</RouterLink>
    <RouterLink :to="{name: 'MealsByLetter'}">Search By Letter</RouterLink>
    <RouterLink :to="{name: 'Ingredients'}">Search By Ingredient</RouterLink>
  </nav>
</template>

<style lang="postcss" scoped>
nav {
  @apply flex justify-center space-x-4;

  & .router-link-active {
    @apply underline underline-offset-4;
  }
}
</style>
