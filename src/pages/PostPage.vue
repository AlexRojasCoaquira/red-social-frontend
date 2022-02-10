<template>
  <dashboard-layout>
    <post-component></post-component>
  </dashboard-layout>
</template>

<script>
import PostComponent from "../components/PostComponent/component"
import dashboard from "../layouts/dashboard"
export default {
    name:'PostPage',
    components:{
    "dashboard-layout":dashboard,
    "post-component":PostComponent
    }
}
</script>
<style >

</style>