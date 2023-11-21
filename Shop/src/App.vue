<template>
    <Header/>
    <h2>Shop Project</h2>
    <div>
        <button @click="addItem">Add item</button>
    </div>
</template>

<script>
import Header from 'Company/Header';
export default {
    components:{
        Header
    },
    methods: {
         addItem() {
             this.$store.state.cartItems += 1
         }
     },  
}
</script>