<template>
  <div class="container">
  
  <div id="hero-page-a"></div>
  <div id="hero-page-b">     <h1 class="title">
       Punyasloka
      </h1></div>
   
  </div>
</template>

<script>
export default {}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family:
  'Rockwell',
    'Quicksand',    
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    Arial,
    sans-serif;
  display: block;
  font-weight: 300;
  font-size: 3em;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
#hero-page-a {
  width: 100%;
height: 30vh;
background: #F9F9F8;
}
#hero-page-b {
  width: 100%;
  height: 70vh;
}
</style>
