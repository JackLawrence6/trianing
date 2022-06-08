<template>
    <div class="de">
        {{PageText}}
    </div>
</template>

<script>

export default{
    name:'myIndex',
    data(){
        return {
            PageText:'New Page',
        }
    },

}
</script>

<style scoped>

.de{
    color: brown;
    border: 1px solid black;
    border-radius: 5px;
    background-color: #006266;
}

</style>