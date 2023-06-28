<template>
  <nav>
    <ul>
        <li v-for="link in links">
            {{ link.text }}
        </li>
    </ul>
  </nav>
</template>

<script>
      export default {
        components: {
        },
        data() {
            return {
                links: [
                    {
                        text: "Home",
                        href: "#"
                    },
                    {
                        text: "About",
                        href: "#"
                    },
                    {
                        text: "Services",
                        href: "#"
                    },
                    {
                        text: "Journal",
                        href: "#"
                    },
                    {
                        text: "Contact",
                        href: "#"
                    },
                ]
            }
        },
        created() {
            
        },
        mounted() {
            
        },
        props: {
        },
        computed: {
            
        },
        methods: {
            
        },
    }
</script>

<style scoped>
li{
    color: white;
    list-style: none;
    margin-left: 2rem;
    font-size: 1.5rem;
}

ul{
    display: flex;
    align-items: center;
    justify-content: space-between;
}

li:hover{
    text-decoration: underline;
}
</style>