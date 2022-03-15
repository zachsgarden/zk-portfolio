<template>
    <div>
        <section>
            <div class="row">
                <p>Let's cut to the quick...</p>
                <p>I am a front-end software developer who has experience building full-stack vue and react
                    applications. I
                    have
                    worked with many clients from ecommerce to the medical industry.</p>
                <p>Software is how the world operates and I believe it should be created in an ethical manner in order
                    to
                    maximize
                    human freedom.</p>
            </div>
        </section>
    </div>
</template>

<script>
    export default {
        name: 'AboutMe',
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

    /* section {
      height: 100vh;
    } */

    @media (max-width: 575px) {
        .heading-left {
            font-size: 3.5rem;
        }
    }
</style>