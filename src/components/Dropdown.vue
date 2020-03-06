<template>
    <li class="dropdown">
        <a href="#" class="dropdown-toggle" data-toggle="dropdown" role="button"
           aria-haspopup="true" aria-expanded="false" @click="isOpen = !isOpen">{{ name }} <span class="caret"></span>
        </a>
        <ul class="dropdown-menu" >

            <li v-for="(item, index) in items" :key="index"><a :href="item.link">{{ item.title }}</a></li>

        </ul>
    </li>
</template>

<script>

    export default {
        name: "Dropdown",
        props: ['name', 'items'],
        data() {
            return {
                isOpen: false
            }
        }
    }
</script>

<style scoped>

</style>