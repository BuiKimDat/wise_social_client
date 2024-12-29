<script setup lang="ts">
import HeaderComponent from '@/components/HeaderComponent.vue';
import UserProfileComponent from '@/components/UserProfileComponent.vue';
import SuggestionComponent from '@/components/SuggestionComponent.vue';
import TimelineComponent from '@/components/TimelineComponent.vue';
import MostFollowerComponent from '@/components/MostFollowerComponent.vue';
import MyFavouriteComponent from '@/components/MyFavouriteComponent.vue';
import FriendRequestComponent from '@/components/FriendRequestComponent.vue';
import ChatComponent from '@/components/ChatComponent.vue';
</script>

<template>
    <div class="wrapper">
        <!--Begin Header-->
        <HeaderComponent/>
        <!--End header-->

        <main>
            <div class="main-section">
                <div class="container">
                    <div class="main-section-data">
                        <div class="row">
                            <div class="col-lg-3 col-md-4 pd-left-none no-pd">
                                <div class="main-left-sidebar no-margin">
                                    
                                    <!--Begin User data-->
                                    <UserProfileComponent/>
                                    <!--End User data-->

                                    <!--user-data end-->

                                    <!--Begin User data-->
                                    <SuggestionComponent/>
                                    <!--End User data-->
                                    
                                    <!--suggestions end-->
                                    <div class="tags-sec full-width">
                                        <div class="cp-sec">
                                            <img src="../assets/images/logo2.png" alt="">
                                            <p>&copy; Copyright 2024.</p>
                                        </div>
                                    </div>
                                    <!--tags-sec end-->
                                </div>
                                <!--main-left-sidebar end-->
                            </div>
                            
                            <!--Begin User data-->
                            <TimelineComponent/>
                            <!--End User data-->

                            <div class="col-lg-3 pd-right-none no-pd">
                                <div class="right-sidebar">
                                    
                                    <!--Begin User data-->
                                    <MostFollowerComponent/>
                                    <!--End User data-->

                                    <!--widget-about end-->
                                    <!-- Top jobs -->
                                    
                                    <!--Begin User data-->
                                    <MyFavouriteComponent/>
                                    <!--End User data-->

                                    <!--Request friend People-->
                                    
                                    <!--Begin User data-->
                                    <FriendRequestComponent/>
                                    <!--End User data-->

                                </div>
                                <!--right-sidebar end-->
                            </div>
                        </div>
                    </div>
                    <!-- main-section-data end-->
                </div>
            </div>
        </main>
        <!--chatbox-list end-->
        <ChatComponent/>
    </div>
</template>