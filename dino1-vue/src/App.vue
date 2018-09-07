<template>
  <html>
    <div id="app">
      <body>
        <Header />
        <main>
          <Job_List />
          <Job_Form />
        </main>
        <Footer />
      </body>
    </div>
  </html>
</template>

<script>
import Header from './components/Header.vue'
import Job_List from './components/Job_List.vue'
import Job_Form from './components/Job_Form.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'app',
  components: {
    Footer,
    Job_Form,
    Job_List,
    Header
  }
}
</script>

<style src="../styles/listings.css">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
