<template>
    <div>
        <div v-for="item in items">{{item}}</div>
    </div>
</template>

<script>
export default {
    name: 'Home',
    data() {
        return {
            items: []
        }
    },
    mounted() {
        console.log('in')
        for (let i = 0; i < 2000; i++) {
            this.items.push(i)
        }
    }
}
</script>

