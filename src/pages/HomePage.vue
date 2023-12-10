<template>
    <div class="main-content">
        <div class="container">
            <div class="row justify-around">
                <div class="col-3" style="background: #F2C037">
                    <q-card class="main-content-profile-card text-center">
                        <q-card-section>
                            <q-avatar size="xl">
                                <img src="https://github.com/Luminous-XF/NoteImages/blob/main/avatar-1.jpg?raw=true" alt="">
                            </q-avatar>
                        </q-card-section>

                        <q-card-section>
                            <div class="text-h4">Luminous</div>
                        </q-card-section>


                        <q-card-actions class="row justify-center">
                            <q-list class="row">
                                <q-item>
                                    <div>
                                        <div>文章</div>
                                        <div>123</div>
                                    </div>
                                </q-item>
                                <q-item>
                                    <div>
                                        <div>点赞</div>
                                        <div>233</div>
                                    </div>
                                </q-item>
                                <q-item>
                                    <div>
                                        <div>浏览量</div>
                                        <div>12345</div>
                                    </div>
                                </q-item>
                            </q-list>
                        </q-card-actions>
                    </q-card>
                </div>

                <div class="col-8" style="background: #21BA45">
                    <q-list>
                        <q-item>
                            <q-card class="main-content-profile-card" style="width: 100%">
                                <q-card-section>
                                    <div class="text-h6">Our Changing Planet</div>
                                    <div class="text-subtitle2">by John Doe</div>
                                </q-card-section>

                                <q-separator />

                                <q-card-actions vertical>
                                    <q-btn flat>Action 1</q-btn>
                                    <q-btn flat>Action 2</q-btn>
                                </q-card-actions>
                            </q-card>
                        </q-item>
                    </q-list>
                </div>
            </div>
        </div>
    </div>

    <q-footer>

    </q-footer>
</template>

<script setup lang="ts">

</script>

<style scoped>
.main-content {
    width: 100%;
    min-height: 1200px;
    position: absolute;
    background-color: rgba(203, 208, 234, 80%);
    margin-top: 0;
    z-index: 100;
}

.container {
    width: 74%;
    margin-top: 60px;
    margin-left: 13%;
    margin-right: 13%;
    z-index: 200;
}

.main-content-profile-card {
    border-radius: 18px;
    caret-color: transparent;
}
</style>
