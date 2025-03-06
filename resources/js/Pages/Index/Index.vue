
<template>
<!--        <div>Hello  {{ // counter }}!</div>-->
        <p>THe message is: {{ message }}</p>
        <Link href="/hello">Show page</Link>
</template>

<script setup>a
// import {ref} from 'vue';
import {Link} from '@inertiajs/vue3';

defineProps({
    message: String
})

// const counter = ref(0)
// setInterval(() => counter.value++, 1000)
</script>

