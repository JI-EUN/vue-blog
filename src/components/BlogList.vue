<template>
    <div>
        <h5>{{ list.title}}</h5>
        <p>{{ list.date }}</p>
    </div>
</template>
<script>
export default {
    name:'BlogList',
    props:{
        list : Object
    }
}
</script>
<style>
</style>