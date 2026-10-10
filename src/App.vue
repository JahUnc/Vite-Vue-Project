<script setup lang="ts">
/**
 * App.vue
 * Root component of the Vite-Vue project.
 * Displays the page heading, a welcome paragraph, and a warning button.
 */
</script>

<template>
  <main>
    <h1>Steven Gutierrez Vite-Vue Project</h1>
    <p>
      Hello, and welcome to my first Vite-Vue project. This webpage is showcasing my
      ability to create projects using vite and vue. This was created for my dynamic web applications
      course.
    </p>
    <button type="button" class="warning-button">Don't press the button</button>
  </main>
</template>

<style scoped>
/* Red warning button shown below the welcome paragraph */
.warning-button {
  background-color: red;
  color: white;
  padding: 20px 40px;
  border: none;
  border-radius: 6px;
  cursor: pointer;
}
</style>
