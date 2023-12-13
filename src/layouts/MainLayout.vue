<template>
    <q-layout view="hHh lpR fFf">
        <q-header elevated class="row items-center justify-between header">
            <q-list class="row header-title-list">
                <q-item clickable v-ripple>
                    <q-item-section class="header-title">Luminous の 部落格</q-item-section>
                </q-item>
            </q-list>

            <q-list class="row header-bar-list">
                <q-item clickable v-ripple to="/home">
                    <q-item-section avatar>
                        <q-avatar square size="md">
                            <img src="../assets/image/icon/Home.svg" alt="">
                        </q-avatar>
                    </q-item-section>

                    <q-item-section class="navigation-bar">首页</q-item-section>
                </q-item>

                <q-item clickable v-ripple to="/categories">
                    <q-item-section avatar>
                        <q-avatar square size="md">
                            <img src="../assets/image/icon/Folder.svg" alt="">
                        </q-avatar>
                    </q-item-section>

                    <q-item-section class="navigation-bar">分类</q-item-section>
                </q-item>

                <q-item clickable v-ripple>
                    <q-item-section avatar>
                        <q-avatar size="md">
                            <img src="../assets/image/icon/PriceTag.svg" alt="">
                        </q-avatar>
                    </q-item-section>

                    <q-item-section class="navigation-bar">标签</q-item-section>
                </q-item>

                <q-item clickable v-ripple>
                    <q-item-section avatar>
                        <q-avatar square size="md">
                            <img src="../assets/image/icon/Message.svg" alt="">
                        </q-avatar>
                    </q-item-section>

                    <q-item-section class="navigation-bar">留言</q-item-section>
                </q-item>

                <q-item clickable v-ripple to="/about">
                    <q-item-section avatar>
                        <q-avatar square size="md">
                            <img src="../assets/image/icon/Fish.svg" alt="">
                        </q-avatar>
                    </q-item-section>

                    <q-item-section class="navigation-bar">关于</q-item-section>
                </q-item>

                <q-item clickable v-ripple>
                    <q-item-section avatar>
                        <q-avatar size="md">
                            <img src="https://github.com/Luminous-XF/NoteImages/blob/main/avatar-1.jpg?raw=true" alt="">
                        </q-avatar>
                    </q-item-section>
                </q-item>
            </q-list>
        </q-header>

        <q-img class="background-image" src="public/image/background/background-001.jpg"></q-img>

        <q-page-container class="main-content">
            <router-view/>
        </q-page-container>
    </q-layout>
</template>

<script lang="ts" setup>

</script>

<style scoped>
.header {
    background: rgba(203, 208, 234, 0.45);
    height: 60px;
    width: 100%;
    font-size: 18px;
    position: fixed;
    top: 0;
    z-index: 997;
    caret-color: transparent;
}

.header-title-list {
    margin-left: 60px;
}

.header-bar-list {
    margin-right: 60px;
}

.header-title {
    font-size: 28px;
    font-weight: bold;
    color: aliceblue;
    font-family: "Open Sans", sans-serif;
}

.background-image {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    object-fit: cover;
    z-index: 0;
}

.main-content {
    width: 100%;
    min-height: 1200px;
    position: absolute;
    margin-top: 0;
    z-index: 100;
}

.navigation-bar {
    font-weight: bold;
    color: white;
}
</style>
