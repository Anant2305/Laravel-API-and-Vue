<template>
    <ContactsList endpoint="/api/contacts" />
</template>

<script>

    import ContactsList from "../components/ContactsList";
    export default {
        name: "ContactIndex",
        components: {ContactsList},
        component:{
            ContactsList
        }

    }
</script>

<style scoped>

</style>
