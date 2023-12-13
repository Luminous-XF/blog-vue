<template>
    <div class="container">
        <div style="width: 100%; height: 1000px; background: #21BA45">

        </div>
    </div>
</template>

<script setup lang="ts">
import {onMounted} from 'vue';

const resetMainContentTopValue = () => {
    const mainContent = <HTMLElement>document.getElementsByClassName('main-content')[0];
    mainContent.style.top = '0px';
}

onMounted(() => {
    resetMainContentTopValue();
});

</script>

<style scoped>
.container {
    width: 60%;
    margin-top: 60px;
    margin-left: 20%;
    margin-right: 20%;
    z-index: 200;
}
</style>
