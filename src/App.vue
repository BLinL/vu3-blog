<script setup lang="ts">
</script>

<template>
<div class="flex pa-0 bg-gray h-[4rem]">
  <nav>
    <ol>
      <li>posts</li>
      <li>achive</li>
      <li>about</li>
    </ol>
  </nav>
</div>
</template>

<style scoped>
  nav ol {
    list-style-type: none;
    padding-left: 0;
    display: flex;
    justify-content: center;
  }
  ol > li {
    list-style: none;
    margin-left: 20px;
  }
  ol > li:hover {
    list-style: none;
    margin-left: 20px;
    list-style: none;
    border-bottom: 2px solid blue;
    color: blue;
    cursor: pointer;
  }
</style>
