<template>
  <v-app-bar :clipped-left="$vuetify.breakpoint.lgAndUp" app color="teal" dark>
    <v-toolbar-title style="width: 350px">
      <a href="/" class="white--text" style="text-decoration: none"
        ><v-icon>mdi-truck</v-icon>&nbsp;ShipIT</a
      >
    </v-toolbar-title>

    <v-text-field
      flat
      solo-inverted
      hide-details
      prepend-inner-icon="mdi-magnify"
      label="Search"
      class="hidden-sm-and-down pl-10 ml-4"
    />

    <v-spacer />

    <v-btn icon>
      <v-icon>mdi-account-circle</v-icon>
    </v-btn>

    <v-btn icon>
      <v-badge content="2" value="2" color="green" overlap>
        <v-icon>mdi-bell</v-icon>
      </v-badge>
    </v-btn>

    <v-btn icon to="/cart">
      <v-badge content="2" value="2" color="green" overlap>
        <v-icon>mdi-cart</v-icon>
      </v-badge>
    </v-btn>
  </v-app-bar>
</template>

<script>
export default {
  name: "AppBar",
};
</script>

<style>
</style>
