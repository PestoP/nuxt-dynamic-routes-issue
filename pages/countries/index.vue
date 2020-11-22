<template>
  <div>
    <p>
      Children global page
    </p>
    <nuxt-link to="/countries/firstCountry">
      First Country
    </nuxt-link>
    <nuxt-link to="/countries/secondCountry">
      Second Country
    </nuxt-link>
    <nuxt-child />
  </div>
</template>
