<template>

  <div class="blog">

    <router-view />

    <router-link to="/" tag="a" class="back">&laquo; Back</router-link>

  </div>
  
</template>

<style lang="scss" scoped>
.blog {
  max-width: 50vw;
  margin: 10rem auto;

  section {
    h1 {
      color: #171717 !important;
      font-weight: 500 !important;
    }
    
  }
    h4 {
      margin-bottom: 3rem;
      color: #35495e;
    }
    pre {
      overflow-x: auto;
      background-color: #35495e;
      color: white;
      border-radius: 0.3rem;
      padding: 1rem;
    }
    img {
      max-width: 100%;
    }


  .back {
    background-color: #42b883;
    color: white;
    margin-top: 5rem;
    text-decoration: none;
    padding: 10px 15px;
    border: 1px solid currentColor;
    border-radius: 0.5rem;
    display: inline-block;
    transition: all 0.3s ease;
    &:hover {
      background-color: transparent;
      color: #42b883;
    }
  }
}
</style>

