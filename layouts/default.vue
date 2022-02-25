<template>
  <div>
    <v-app-bar
      color="deep-purple accent-4"
      dense
      dark>
      <Nuxt />
      <v-app-bar-nav-icon></v-app-bar-nav-icon>
      <v-toolbar-title><NuxtLink to="/" style="text-decoration: none; color: #fff;"> DreamDiary</NuxtLink></v-toolbar-title>
      <v-spacer></v-spacer>
      <v-btn><NuxtLink to="/login" style="text-decoration: none; color: #fff;">로그인</NuxtLink></v-btn>
      <v-btn><NuxtLink to="/sign" style="text-decoration: none; color: #fff;">회원가입</NuxtLink></v-btn>
      <v-btn><NuxtLink to="/myhome" style="text-decoration: none; color: #fff;">마이페이지</NuxtLink></v-btn>
    </v-app-bar>
  </div>
</template>

<style lang="css">
</style>
