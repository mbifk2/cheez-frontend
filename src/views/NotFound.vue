<template>
  <div class="not-found">
    <div class="not-found-container">
      <img
        src="@/assets/404.png"
        alt="404 Not Found"
        class="not-found-image"
      />
      <h1>404</h1>
      <p>Oops! It seems you've wandered too far.</p>
      <router-link to="/" class="home-button">
        Return to Home
      </router-link>
    </div>
  </div>
</template>
<script>
export default {
  name: 'NotFound'

}
</script>

<style scoped>
.not-found {
  min-height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
  padding: 20px;
}

.not-found-container {
  max-width: 500px;
}

.not-found-image {
  max-width: 300px;
  margin-bottom: 2rem;
}

h1 {
  font-size: 2.5rem;
  color: #2c3e50;
  margin-bottom: 1rem;
}

p {
  font-size: 1.2rem;
  color: #666;
  margin-bottom: 2rem;
}

.home-button {
  display: inline-block;
  padding: 12px 24px;
  background-color: #42b983;
  color: white;
  text-decoration: none;
  border-radius: 4px;
  transition: background-color 0.3s;
}

.home-button:hover {
  background-color: #3aa876;
}
</style>
