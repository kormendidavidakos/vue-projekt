<script setup lang="ts"></script>

<template>
  <q-layout view="hHh LpR fFf">
    <!-- Fejléc -->
    <q-header class="bg-blue-5 text-white" elevated>
      <q-toolbar>
        <q-toolbar-title shrink style="cursor: pointer" title> Dolgozat minta </q-toolbar-title>
        <q-btn class="active" flat label="Home" no-caps to="/"> </q-btn>
      </q-toolbar>
    </q-header>

    <!-- A router ide (router-view) tölti be az oldalt -->
    <q-page-container>
      <router-view />
    </q-page-container>
  </q-layout>
</template>

<style lang="scss">
.active {
  background-color: #44a5f1;
  color: #ff0;
}
</style>