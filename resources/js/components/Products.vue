<script setup>

import {ref} from 'vue';

const name = ref('');
</script>

<template>

<h2>Products from vue</h2>

<p>{{name}}</p>
<input type="text" v-model="name"/>

</template>