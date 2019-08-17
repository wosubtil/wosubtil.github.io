<template>
  <AppProfile />
</template>

<script>
import AppProfile from './profile'

export default {
  components: {
    AppProfile
  }
}
</script>

<style>
body {
  background-image: linear-gradient(120deg, #fdfbfb 0%, #ebedee 100%);
}
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: BlinkMacSystemFont, -apple-system, 'Segoe UI', 'Roboto', 'Oxygen',
    'Ubuntu', 'Cantarell', 'Fira Sans', 'Droid Sans', 'Helvetica Neue',
    'Helvetica', 'Arial', sans-serif;
  display: block;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
  padding: 30px 30px 0px 30px;
  font-weight: 700;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
}

.links {
  padding-top: 15px;
}

.footer {
  font-size: 18px;
}
</style>
