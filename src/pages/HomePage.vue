<template>
    <div class="container">
        <div class="row justify-around">
            <div class="col-3">
                <q-card class="main-content-profile-card text-center">
                    <q-card-section>
                        <q-avatar size="80px">
                            <img :src="profileCardInfo.headerUrl"
                                 alt="">
                        </q-avatar>
                    </q-card-section>

                    <q-card-section>
                        <div class="text-h4">{{ profileCardInfo.nickname }}</div>
                    </q-card-section>


                    <q-card-actions class="row justify-center">
                        <q-list class="row">
                            <q-item>
                                <div>
                                    <div>文章</div>
                                    <div>{{ profileCardInfo.postCount }}</div>
                                </div>
                            </q-item>
                            <q-item>
                                <div>
                                    <div>点赞</div>
                                    <div>{{ profileCardInfo.likes }}</div>
                                </div>
                            </q-item>
                            <q-item>
                                <div>
                                    <div>浏览量</div>
                                    <div>{{ profileCardInfo.pageViews }}</div>
                                </div>
                            </q-item>
                        </q-list>
                    </q-card-actions>
                </q-card>
            </div>

            <div class="col-8">
                <q-list>
                    <q-item class="xxx">
                        <q-card class="main-content-post-card">
                            <q-card-section horizontal style="height: 80%">
                                <q-card-section class="overflow-hidden">
                                    Orange fickle blue guy maze chase. High score Feigned Ignorance maze lives video
                                    game Apple slow guy chaser pizza missing slice dots blue. He was willing to find the
                                    depths of the rabbit hole in order to be with her. Pac-Man Namco Toru Iwatani
                                    Pac-Man Fever maze dots. Fluffy pink unicorns are a popular status symbol among
                                    macho men. As she walked along the street and looked in the gutter, she realized
                                    facemasks had become the new cigarette butts. Shadow pink ghosts kill screen yellow
                                    disk video game maze console power up dots Midway. I hear that Nancy is very pretty.
                                    She had the gift of being able to paint songs. Patricia loves the sound of nails
                                    strongly pressed against the chalkboard.
                                    Orange fickle blue guy maze chase. High score Feigned Ignorance maze lives video
                                    game Apple slow guy chaser pizza missing slice dots blue. He was willing to find the
                                    depths of the rabbit hole in order to be with her. Pac-Man Namco Toru Iwatani
                                    Pac-Man Fever maze dots. Fluffy pink unicorns are a popular status symbol among
                                    macho men. As she walked along the street and looked in the gutter, she realized
                                    facemasks had become the new cigarette butts. Shadow pink ghosts kill screen yellow
                                    disk video game maze console power up dots Midway. I hear that Nancy is very pretty.
                                    She had the gift of being able to paint songs. Patricia loves the sound of nails
                                    strongly pressed against the chalkboard.
                                    Orange fickle blue guy maze chase. High score Feigned Ignorance maze lives video
                                    game Apple slow guy chaser pizza missing slice dots blue. He was willing to find the
                                    depths of the rabbit hole in order to be with her. Pac-Man Namco Toru Iwatani
                                    Pac-Man Fever maze dots. Fluffy pink unicorns are a popular status symbol among
                                    macho men. As she walked along the street and looked in the gutter, she realized
                                    facemasks had become the new cigarette butts. Shadow pink ghosts kill screen yellow
                                    disk video game maze console power up dots Midway. I hear that Nancy is very pretty.
                                    She had the gift of being able to paint songs. Patricia loves the sound of nails
                                    strongly pressed against the chalkboard.
                                </q-card-section>

                                <q-img
                                    class="col-5"
                                    src="https://cdn.quasar.dev/img/parallax1.jpg"
                                />
                            </q-card-section>

                            <q-separator/>

                            <q-card-actions class="row justify-between" style="height: 20%">
                                <div>
                                    <q-btn flat round icon="event"/>
                                    <q-btn flat>
                                        5:30PM
                                    </q-btn>
                                    <q-btn flat>
                                        7:00PM
                                    </q-btn>
                                </div>

                                <div>
                                    <q-btn flat class="" color="primary">
                                        <span>详情 <strong>></strong></span>
                                    </q-btn>
                                </div>
                            </q-card-actions>

                        </q-card>
                    </q-item>

                    <q-item>
                        <q-card class="main-content-post-card">
                            <q-card-section horizontal style="height: 80%">
                                <q-card-section class="overflow-hidden">
                                    Orange fickle blue guy maze chase. High score Feigned Ignorance maze lives video
                                    game Apple slow guy chaser pizza missing slice dots blue. He was willing to find the
                                    depths of the rabbit hole in order to be with her. Pac-Man Namco Toru Iwatani
                                    Pac-Man Fever maze dots. Fluffy pink unicorns are a popular status symbol among
                                    macho men. As she walked along the street and looked in the gutter, she realized
                                    facemasks had become the new cigarette butts. Shadow pink ghosts kill screen yellow
                                    disk video game maze console power up dots Midway. I hear that Nancy is very pretty.
                                    She had the gift of being able to paint songs. Patricia loves the sound of nails
                                    strongly pressed against the chalkboard.
                                    Orange fickle blue guy maze chase. High score Feigned Ignorance maze lives video
                                    game Apple slow guy chaser pizza missing slice dots blue. He was willing to find the
                                    depths of the rabbit hole in order to be with her. Pac-Man Namco Toru Iwatani
                                    Pac-Man Fever maze dots. Fluffy pink unicorns are a popular status symbol among
                                    macho men. As she walked along the street and looked in the gutter, she realized
                                    facemasks had become the new cigarette butts. Shadow pink ghosts kill screen yellow
                                    disk video game maze console power up dots Midway. I hear that Nancy is very pretty.
                                    She had the gift of being able to paint songs. Patricia loves the sound of nails
                                    strongly pressed against the chalkboard.
                                    Orange fickle blue guy maze chase. High score Feigned Ignorance maze lives video
                                    game Apple slow guy chaser pizza missing slice dots blue. He was willing to find the
                                    depths of the rabbit hole in order to be with her. Pac-Man Namco Toru Iwatani
                                    Pac-Man Fever maze dots. Fluffy pink unicorns are a popular status symbol among
                                    macho men. As she walked along the street and looked in the gutter, she realized
                                    facemasks had become the new cigarette butts. Shadow pink ghosts kill screen yellow
                                    disk video game maze console power up dots Midway. I hear that Nancy is very pretty.
                                    She had the gift of being able to paint songs. Patricia loves the sound of nails
                                    strongly pressed against the chalkboard.
                                </q-card-section>

                                <q-img
                                    class="col-5"
                                    src="https://cdn.quasar.dev/img/parallax1.jpg"
                                />
                            </q-card-section>

                            <q-separator/>

                            <q-card-actions class="row justify-between" style="height: 20%">
                                <div>
                                    <q-btn flat round icon="event"/>
                                    <q-btn flat>
                                        5:30PM
                                    </q-btn>
                                    <q-btn flat>
                                        7:00PM
                                    </q-btn>
                                </div>

                                <div>
                                    <q-btn flat class="" color="primary">
                                        <span>详情 <strong>></strong></span>
                                    </q-btn>
                                </div>
                            </q-card-actions>

                        </q-card>
                    </q-item>

                    <q-item>
                        <q-card class="main-content-post-card">
                            <q-card-section horizontal style="height: 80%">
                                <q-card-section class="overflow-hidden">
                                    Orange fickle blue guy maze chase. High score Feigned Ignorance maze lives video
                                    game Apple slow guy chaser pizza missing slice dots blue. He was willing to find the
                                    depths of the rabbit hole in order to be with her. Pac-Man Namco Toru Iwatani
                                    Pac-Man Fever maze dots. Fluffy pink unicorns are a popular status symbol among
                                    macho men. As she walked along the street and looked in the gutter, she realized
                                    facemasks had become the new cigarette butts. Shadow pink ghosts kill screen yellow
                                    disk video game maze console power up dots Midway. I hear that Nancy is very pretty.
                                    She had the gift of being able to paint songs. Patricia loves the sound of nails
                                    strongly pressed against the chalkboard.
                                    Orange fickle blue guy maze chase. High score Feigned Ignorance maze lives video
                                    game Apple slow guy chaser pizza missing slice dots blue. He was willing to find the
                                    depths of the rabbit hole in order to be with her. Pac-Man Namco Toru Iwatani
                                    Pac-Man Fever maze dots. Fluffy pink unicorns are a popular status symbol among
                                    macho men. As she walked along the street and looked in the gutter, she realized
                                    facemasks had become the new cigarette butts. Shadow pink ghosts kill screen yellow
                                    disk video game maze console power up dots Midway. I hear that Nancy is very pretty.
                                    She had the gift of being able to paint songs. Patricia loves the sound of nails
                                    strongly pressed against the chalkboard.
                                    Orange fickle blue guy maze chase. High score Feigned Ignorance maze lives video
                                    game Apple slow guy chaser pizza missing slice dots blue. He was willing to find the
                                    depths of the rabbit hole in order to be with her. Pac-Man Namco Toru Iwatani
                                    Pac-Man Fever maze dots. Fluffy pink unicorns are a popular status symbol among
                                    macho men. As she walked along the street and looked in the gutter, she realized
                                    facemasks had become the new cigarette butts. Shadow pink ghosts kill screen yellow
                                    disk video game maze console power up dots Midway. I hear that Nancy is very pretty.
                                    She had the gift of being able to paint songs. Patricia loves the sound of nails
                                    strongly pressed against the chalkboard.
                                </q-card-section>

                                <q-img
                                    class="col-5"
                                    src="https://cdn.quasar.dev/img/parallax1.jpg"
                                />
                            </q-card-section>

                            <q-separator/>

                            <q-card-actions class="row justify-between" style="height: 20%">
                                <div>
                                    <q-btn flat round icon="event"/>
                                    <q-btn flat>
                                        5:30PM
                                    </q-btn>
                                    <q-btn flat>
                                        7:00PM
                                    </q-btn>
                                </div>

                                <div>
                                    <q-btn flat class="" color="primary">
                                        <span>详情 <strong>></strong></span>
                                    </q-btn>
                                </div>
                            </q-card-actions>

                        </q-card>
                    </q-item>

                    <q-item>
                        <q-card class="main-content-post-card">
                            <q-card-section horizontal style="height: 80%">
                                <q-card-section class="overflow-hidden">
                                    Orange fickle blue guy maze chase. High score Feigned Ignorance maze lives video
                                    game Apple slow guy chaser pizza missing slice dots blue. He was willing to find the
                                    depths of the rabbit hole in order to be with her. Pac-Man Namco Toru Iwatani
                                    Pac-Man Fever maze dots. Fluffy pink unicorns are a popular status symbol among
                                    macho men. As she walked along the street and looked in the gutter, she realized
                                    facemasks had become the new cigarette butts. Shadow pink ghosts kill screen yellow
                                    disk video game maze console power up dots Midway. I hear that Nancy is very pretty.
                                    She had the gift of being able to paint songs. Patricia loves the sound of nails
                                    strongly pressed against the chalkboard.
                                    Orange fickle blue guy maze chase. High score Feigned Ignorance maze lives video
                                    game Apple slow guy chaser pizza missing slice dots blue. He was willing to find the
                                    depths of the rabbit hole in order to be with her. Pac-Man Namco Toru Iwatani
                                    Pac-Man Fever maze dots. Fluffy pink unicorns are a popular status symbol among
                                    macho men. As she walked along the street and looked in the gutter, she realized
                                    facemasks had become the new cigarette butts. Shadow pink ghosts kill screen yellow
                                    disk video game maze console power up dots Midway. I hear that Nancy is very pretty.
                                    She had the gift of being able to paint songs. Patricia loves the sound of nails
                                    strongly pressed against the chalkboard.
                                    Orange fickle blue guy maze chase. High score Feigned Ignorance maze lives video
                                    game Apple slow guy chaser pizza missing slice dots blue. He was willing to find the
                                    depths of the rabbit hole in order to be with her. Pac-Man Namco Toru Iwatani
                                    Pac-Man Fever maze dots. Fluffy pink unicorns are a popular status symbol among
                                    macho men. As she walked along the street and looked in the gutter, she realized
                                    facemasks had become the new cigarette butts. Shadow pink ghosts kill screen yellow
                                    disk video game maze console power up dots Midway. I hear that Nancy is very pretty.
                                    She had the gift of being able to paint songs. Patricia loves the sound of nails
                                    strongly pressed against the chalkboard.
                                </q-card-section>

                                <q-img
                                    class="col-5"
                                    src="https://cdn.quasar.dev/img/parallax1.jpg"
                                />
                            </q-card-section>

                            <q-separator/>

                            <q-card-actions class="row justify-between" style="height: 20%">
                                <div>
                                    <q-btn flat round icon="event"/>
                                    <q-btn flat>
                                        5:30PM
                                    </q-btn>
                                    <q-btn flat>
                                        7:00PM
                                    </q-btn>
                                </div>

                                <div>
                                    <q-btn flat class="" color="primary">
                                        <span>详情 <strong>></strong></span>
                                    </q-btn>
                                </div>
                            </q-card-actions>

                        </q-card>
                    </q-item>

                    <q-item>
                        <q-card class="main-content-post-card">
                            <q-card-section horizontal style="height: 80%">
                                <q-card-section class="overflow-hidden">
                                    Orange fickle blue guy maze chase. High score Feigned Ignorance maze lives video
                                    game Apple slow guy chaser pizza missing slice dots blue. He was willing to find the
                                    depths of the rabbit hole in order to be with her. Pac-Man Namco Toru Iwatani
                                    Pac-Man Fever maze dots. Fluffy pink unicorns are a popular status symbol among
                                    macho men. As she walked along the street and looked in the gutter, she realized
                                    facemasks had become the new cigarette butts. Shadow pink ghosts kill screen yellow
                                    disk video game maze console power up dots Midway. I hear that Nancy is very pretty.
                                    She had the gift of being able to paint songs. Patricia loves the sound of nails
                                    strongly pressed against the chalkboard.
                                    Orange fickle blue guy maze chase. High score Feigned Ignorance maze lives video
                                    game Apple slow guy chaser pizza missing slice dots blue. He was willing to find the
                                    depths of the rabbit hole in order to be with her. Pac-Man Namco Toru Iwatani
                                    Pac-Man Fever maze dots. Fluffy pink unicorns are a popular status symbol among
                                    macho men. As she walked along the street and looked in the gutter, she realized
                                    facemasks had become the new cigarette butts. Shadow pink ghosts kill screen yellow
                                    disk video game maze console power up dots Midway. I hear that Nancy is very pretty.
                                    She had the gift of being able to paint songs. Patricia loves the sound of nails
                                    strongly pressed against the chalkboard.
                                    Orange fickle blue guy maze chase. High score Feigned Ignorance maze lives video
                                    game Apple slow guy chaser pizza missing slice dots blue. He was willing to find the
                                    depths of the rabbit hole in order to be with her. Pac-Man Namco Toru Iwatani
                                    Pac-Man Fever maze dots. Fluffy pink unicorns are a popular status symbol among
                                    macho men. As she walked along the street and looked in the gutter, she realized
                                    facemasks had become the new cigarette butts. Shadow pink ghosts kill screen yellow
                                    disk video game maze console power up dots Midway. I hear that Nancy is very pretty.
                                    She had the gift of being able to paint songs. Patricia loves the sound of nails
                                    strongly pressed against the chalkboard.
                                </q-card-section>

                                <q-img
                                    class="col-5"
                                    src="https://cdn.quasar.dev/img/parallax1.jpg"
                                />
                            </q-card-section>

                            <q-separator/>

                            <q-card-actions class="row justify-between" style="height: 20%">
                                <div>
                                    <q-btn flat round icon="event"/>
                                    <q-btn flat>
                                        5:30PM
                                    </q-btn>
                                    <q-btn flat>
                                        7:00PM
                                    </q-btn>
                                </div>

                                <div>
                                    <q-btn flat class="" color="primary">
                                        <span>详情 <strong>></strong></span>
                                    </q-btn>
                                </div>
                            </q-card-actions>

                        </q-card>
                    </q-item>
                </q-list>

                <div class="q-pa-lg flex flex-center">
                    <q-pagination
                        v-model="currentPage"
                        :max="5"
                        direction-links
                        boundary-links
                        icon-first="skip_previous"
                        icon-last="skip_next"
                        icon-prev="fast_rewind"
                        icon-next="fast_forward"
                        color="indigo-1"
                    />
                </div>
            </div>
        </div>
    </div>

    <q-footer>

    </q-footer>
</template>

<script lang="ts" setup>
import {onMounted, reactive, ref} from 'vue'
import {api} from 'boot/axios';

const profileCardInfo = reactive({
    nickname: '',
    postCount: 0,
    likes: 0,
    pageViews: 0,
    headerUrl: ''
});

const currentPage = ref(3)

const getProfileCardInfo = async () => {
    api.get('/api/user-name/').then((response) => {
        profileCardInfo.nickname = response.data.data.nickname;
        profileCardInfo.postCount = response.data.data.postCount;
        profileCardInfo.likes = response.data.data.likes;
        profileCardInfo.pageViews = response.data.data.pageViews;
        profileCardInfo.headerUrl = response.data.data.headerUrl;
    }).catch(err => {
        console.log(err)
    });
};

const resetMainContentTopValue = () => {
    const homeFirstBackgroundImage = <HTMLElement>document.getElementsByClassName('background-image')[0];
    const mainContent = <HTMLElement>document.getElementsByClassName('main-content')[0];
    mainContent.style.top = homeFirstBackgroundImage.offsetHeight + 'px';
}

onMounted(() => {
    resetMainContentTopValue();
    getProfileCardInfo();
});

</script>


<style scoped>
.container {
    width: 74%;
    margin-top: 60px;
    margin-left: 13%;
    margin-right: 13%;
    z-index: 200;
}

.main-content-profile-card {
    margin-top: 8px;
    border-radius: 18px;
    caret-color: transparent;
}

.main-content-post-card {
    width: 100%;
    height: 280px;
    border-radius: 18px;
    margin-bottom: 22px;
    caret-color: transparent;
}
</style>
