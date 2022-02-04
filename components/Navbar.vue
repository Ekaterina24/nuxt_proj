<template>
  <v-container>
    <v-toolbar
      color="purple lighten-1"
      flat
    >
      <v-img
        alt="logo"
        src="LEGO-Logo.png"
        max-width="70"
      ></v-img>
      <v-toolbar-items>
        <v-btn
          text
          color="#FFFFFF"
        >
          <nuxt-link
            to="/"
            color="#FFFFFF"
          >
            Главная
          </nuxt-link>
        </v-btn>
        <v-btn
          text
          color="#FFFFFF"
        >
          <nuxt-link to="/posts">Новости</nuxt-link>
        </v-btn>
        <v-btn
          text
          color="#FFFFFF"
        >
          <nuxt-link to="/about">О нас</nuxt-link>
        </v-btn>
        <v-btn
          text
          color="#FFFFFF"
        >
          <nuxt-link to="/gallery">Галерея</nuxt-link>
        </v-btn>
      </v-toolbar-items>
      <v-spacer></v-spacer>
    </v-toolbar>
  </v-container>
</template>

<script>
export default {
  name: 'Navbar'
}
</script>

<style scoped>
.v-application a {
  color: white!important;
  text-decoration: none;
}
</style>
