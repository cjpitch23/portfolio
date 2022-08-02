<template>
  <q-layout view="hHh lpR fFf">

    <q-header elevated class="bg-primary text-white">
      <q-toolbar>
        <q-toolbar-title>
          <q-avatar>
            <img src="https://cdn.quasar.dev/logo-v2/svg/logo-mono-white.svg">
          </q-avatar>
          Chad Pitchford
        </q-toolbar-title>

        <q-space />

        <q-btn flat dense label="Home" class="q-pa-lg" />
        <q-btn flat dense label="Project" class="q-pa-lg" />
        <q-btn flat dense label="About" class="q-pa-lg" />

        <q-separator vertical spaced />

        <q-btn flat round icon="fa-brands fa-github" class="q-mx-xs" />
        <q-btn flat round icon="fa-brands fa-linkedin" class="q-mx-xs" />
      </q-toolbar>
    </q-header>
    <q-page-container>
      <router-view />
    </q-page-container>

  </q-layout>
</template>
