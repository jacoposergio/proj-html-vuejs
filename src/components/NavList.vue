<template>
    <li>
        <a :class="{ 'active-link': item.current, 'apply': item.apply }" :href="item.url">{{item.text}}</a>
    </li>
</template>

<script>
export default {
      name: 'NavList',
      props: {
         item: Object
       }
   }
</script>

<style>
</style>