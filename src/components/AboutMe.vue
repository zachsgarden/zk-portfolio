<template>
    <section class="flexed container-sm" id="about">
        <div class="row">
            <div class="col-7 d-flex flex-column justify-content-center">
                <h2>Let's cut to the chase</h2>
                <p>I am a front-end software developer who has experience building full-stack vue and react
                    applications. I
                    have
                    worked with many clients from ecommerce to the medical industry.</p>
                <p>Software is how the world operates and I believe it should be created in an ethical manner in order
                    to
                    maximize
                    human freedom.</p>
            </div>
            <div class="col-5 medicine-man">
                Chase
            </div>
        </div>
    </section>
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
    section {
        background: var(--light);
        color: var(--dark);
        /* margin-top: -12em; */
    }

    .medicine-man {
        content: url("../assets/medicine.svg");
    }
</style>