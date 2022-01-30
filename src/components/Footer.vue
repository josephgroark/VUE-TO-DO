<template>
    <footer>
        <p>Copyright &copy; {{year}}</p>
        <router-link to="/about">About</router-link>
    </footer>
</template>

<script>
export default {
    name: 'Footer',
    props: {
        year: Number
    }
}
</script>


<style scoped>
a {
    color: #333
}

footer {
    margin: top 50px;
    text-align: center
}
</style>