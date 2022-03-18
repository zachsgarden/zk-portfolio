<template>
    <section class="flexed">
        <div class="container-sm">
            <h2>Here are some of muh jobs</h2>
            <p>Work work work work work work work.....</p>
        </div>
    </section>
</template>

<script>
    export default {
        name: 'ProfessionalHistory',
        props: {
            msg: String
        }
    }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    section {
        background: var(--accent-red);
        color: var(--light);
    }
</style>