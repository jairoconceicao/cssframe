<template>
  <main>
    <nav>
      <router-link to="/"> <i class="fa fa-home"></i> </router-link>
      <router-link to="/vanilla">Form e Controls</router-link>
      <router-link to="/cssframe">Layout</router-link>
      <router-link to="/about">About</router-link>
      <select>
        <option>Choose me...</option>
        <option>Action One</option>
        <option>Action Two</option>
        <option>Action Three</option>
      </select>
    </nav>
    <div boxframe>
      <router-view/>
    </div>
  </main>  
</template>

