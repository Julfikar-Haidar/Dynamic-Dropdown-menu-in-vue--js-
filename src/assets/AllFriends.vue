<template>
    <div id="all-friend">
        <h2>All friends</h2>
    </div>
</template>

<script>
    export default {
        name:'Allfriend',
        data(){
            return{
                friends:[
                    { name: 'julfikar', online:true},
                    { name: 'tajal', online:false},
                    { name: 'siyam', online:true},
                    { name: 'maruf', online:true},
                    { name: 'farhana', online:false},
                ]
            }
        }
    }
</script>

<style>

</style>