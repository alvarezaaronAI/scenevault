<template>
    <div>
        <nav class="navbar"> 
            <h1>
                {{title}}
            </h1>
            <ul>
                <li><a href="netflix.com"> <b> Netflix </b> </a></li>
                <li><a href="starbucks.com"> <b> Starbucks </b> </a></li>
            </ul>
        </nav>
    </div>
</template>

<script setup>
defineProps(['title'])
</script>

<style lang="scss" scoped>
.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 1rem;
  background-color: #f3f3f3;

  h1 {
    font-size: 1.2rem;
  }

  ul {
    list-style: none;
    display: flex;
    gap: 1rem;
    
    li a {
      text-decoration: none;
      color: #333;
    }
  }
}
</style>