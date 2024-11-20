<template>
  <v-bottom-navigation color="teal" horizontal>
    <v-btn to="/">
      <span>Home</span>
      <v-icon>mdi-home</v-icon>
    </v-btn>

    <v-btn to="/shop">
      <span>Shop</span>
      <v-icon>mdi-store</v-icon>
    </v-btn>

    <v-btn to="/product">
      <span>Product</span>
      <v-icon>mdi-shopping</v-icon>
    </v-btn>
  </v-bottom-navigation>
</template>

<script>
export default {
  name: "BottomNav",
};
</script>

<style>
</style>
