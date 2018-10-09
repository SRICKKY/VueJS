<template>
    <div class="hello">
        <h1>From AnotherComponent</h1>
        I guess this is rendering string {{ anothermsg }}
    </div>
</template>


<script>
export default {
    name: "AnotherComponent",
    props: {
        anothermsg: String
    }    
}
</script>

<style>

</style>
