<template>
   <div>Hello from page home</div> 
   <div v-for="thread in threads" :key="thread.id">
    <h2>{{thread.title}}</h2>
    <div>
        
    </div>
   </div>
</template>
<script>
import sourceData from '@/data.json'
export default {
    data(){
        return{
            threads:sourceData.threads
        }
    }
}
</script>
<style scoped>

</style>