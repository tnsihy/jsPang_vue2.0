<template>
    <div>
        <h2>{{msg}}</h2>
        <hr>
        <h3>{{$store.state.count}}</h3>
    </div>
</template>
<script>
import store from '@/vuex/store';
export default {
    data(){
        return {
            msg:'Hello vuex'
        }
    },
    store    
}
</script>
<style scoped>

</style>
