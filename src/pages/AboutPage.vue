<template>
    <div class="container">
        <q-card style="width: 100%; border-radius: 15px;">
            <q-card-section class="text-center">
                <div style="font-size: 18px; font-weight: bold;">与 xxx 对话中...</div>
            </q-card-section>

            <q-separator/>

            <q-card-section>
                <div class="q-pa-md row justify-center">
                    <div style="width: 100%;">
                        <q-chat-message
                            :text="['Hi! 😊']"
                            style="margin-bottom: 20px"
                        />
                        <q-chat-message
                            :text="['这个一个 Vue3 Quasar-UI 与 Django 结合的产物~']"
                            style="margin-bottom: 20px"
                        />

                        <q-chat-message
                            :text="['然后呢? 😊😕']"
                            sent
                            style="margin-bottom: 20px"
                        />

                        <q-chat-message
                            :text="['拥有自己的独立网站难道不酷吗 😒']"
                            style="margin-bottom: 20px"
                        />

                        <q-chat-message
                            :text="['那就摸鱼吧 🐬']"
                            style="margin-bottom: 20px"
                        />
                    </div>
                </div>
            </q-card-section>
        </q-card>
    </div>
</template>

<script setup lang="ts">

</script>

<style scoped>
.container {
    width: 60%;
    margin-top: 64px;
    margin-left: 20%;
    margin-right: 20%;
    z-index: 200;
}
</style>
