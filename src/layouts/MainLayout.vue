<template>
  <q-layout view="lHh Lpr lFf" class="bg-warning">
    <q-header class="bg-warning">
      <q-toolbar>
        <q-toolbar-title
          ><q-img src="~assets/logo-new@2x.png" width="150px" /></q-toolbar-title>
      </q-toolbar>
      <q-tabs>
        <q-tab name="Home" label="Home" />
        <q-tab name="About us" label="About us" />
        <q-tab name="Pages" label="Pages"/>
        <q-tab name="Contact Us" label="Contact Us" />
      </q-tabs>
    </q-header>

    <q-page-container>
      <router-view />
    </q-page-container>
  </q-layout>
</template>

