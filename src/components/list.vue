<template>
    <ul>
        <li> 
           <router-link :to="{name:'helloworld',params:{worldmsg:'你好啊世界'}}">HELLO EARTH 33</router-link>
        </li>
        <li>
            <router-link :to="{name:'helloearth',params:{earthmsg:'你好啊地球！'}}">HELLO WORLD 22</router-link>
        </li>
    </ul>
</template>

<script>
export default {
  name: 'list',
}
</script>

<style scoped>

</style>
