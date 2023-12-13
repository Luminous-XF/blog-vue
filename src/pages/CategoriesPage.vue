<template>
    <div class="container">
        <div class="row justify-around">
            <div class="col-8">
                <q-card class="title-card">
                    <q-img src="https://cdn.quasar.dev/img/parallax2.jpg" style="height: 100%;">
                        <div class="text-h5 absolute-bottom text-right">
                            算法
                        </div>
                    </q-img>
                </q-card>

                <q-card class="title-card">
                    <q-img src="https://cdn.quasar.dev/img/parallax2.jpg" style="height: 100%;">
                        <div class="text-h5 absolute-bottom text-right">
                            数据结构
                        </div>
                    </q-img>
                </q-card>

                <q-card class="title-card">
                    <q-img src="https://cdn.quasar.dev/img/parallax2.jpg" style="height: 100%;">
                        <div class="text-h5 absolute-bottom text-right">
                            Python
                        </div>
                    </q-img>
                </q-card>


                <q-card class="title-card">
                    <q-img src="https://cdn.quasar.dev/img/parallax2.jpg" style="height: 100%;">
                        <div class="text-h5 absolute-bottom text-right">
                            读书笔记
                        </div>
                    </q-img>
                </q-card>
            </div>
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
    margin-top: 64px;
    margin-left: 20%;
    margin-right: 20%;
    z-index: 200;
}

.title-card {
    height: 380px;
    border-radius: 12px;
    margin-bottom: 30px;
}
</style>
