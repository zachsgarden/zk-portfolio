<template>
  <div>
    <section>
      <div class="row">
        <div class="col-sm">
          <h1 class="heading-left">
            I
          </h1>
        </div>
        <div class="col-sm">
          <h1 class="heading-left">
            go
          </h1>
        </div>
        <div class="col-sm">
          <h1 class="heading-left">
            by
          </h1>
        </div>
        <div class="col-sm">
          <h1 class="heading-left">
            Zach
          </h1>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
  export default {
    name: 'Hero',
    props: {
      msg: String
    }
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  h3 {
    margin: 40px 0 0;
  }

  ul {
    list-style-type: none;
    padding: 0;
  }

  li {
    display: inline-block;
    margin: 0 10px;
  }

  a {
    color: #42b983;
  }

  .heading-left {
    font-size: 5rem;
  }

  .heading-left:hover {
    background-color: #2c3e50;
    color: #ededed;
  }

  @media (max-width: 575px) {
    .heading-left {
      font-size: 3.5rem;
    }
  }
</style>