<template>
    <h1>{{ count }}</h1>
    <h1 :class="color">{{ doubleCount }}</h1>
    <button @click="add">add</button>

    <!--    <div v-for="(item, index) in list" :key="index"> {{ item }} </div>-->
    <!--    <div v-if="color"> {{ color }} </div>-->
</template>

<script setup>
import {computed, ref, watch} from 'vue';

let count = ref(0);

function add() {
    count.value++;
}

let doubleCount = computed(() => {
    return count.value * 2;
});

let color = ref('red');

watch(count, () => {
    if (count.value % 2 === 0) {
        color.value = 'red';
    } else {
        color.value = 'green';
    }
});
</script>

<style>
h1 {
    color: red;
}

.red {
    color: red;
}

.green {
    color: green;
}

.color {
    color: v-bind(color)
}
</style>
