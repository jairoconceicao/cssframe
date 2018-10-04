<template>
  <div id="app">
    <header class="p-navigation">
      <ul class="p-navigation__links" role="menu">
        <li class="p-navigation__link" role="menuitem">
          <router-link to="/">Home</router-link>
        </li>

        <li class="p-navigation__link" role="menuitem">
          <router-link to="/vanilla">Vanilla CSS</router-link>
        </li>

        <li class="p-navigation__link" role="menuitem">
          <router-link to="/about">About</router-link>
        </li>
      </ul>
    </header>
    <router-view/>
  </div>
</template>
