<template>
    <div>
        <h1>Porject details for {{ id }}</h1>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. 
        Impedit repudiandae nesciunt numquam blanditiis possimus ratione sed eveniet, 
        distinctio, sint enim, deleniti similique. Voluptate accusamus optio fugit non cum, 
        cupiditate perspiciatis!</p>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. 
        Impedit repudiandae nesciunt numquam blanditiis possimus ratione sed eveniet, 
        distinctio, sint enim, deleniti similique. Voluptate accusamus optio fugit non cum, 
        cupiditate perspiciatis!</p>
        
    </div>
</template>

<script setup>
    const { id } = useRoute().params;
</script>

<style  scoped>

</style>