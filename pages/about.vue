<template>
  <div>
    <h1>about</h1>
    <p>On this page the button works and contains a nuxt-link which is defined in the example-lib</p>
    <p>Uses the src version of MyRouterLink in example-lib</p>
    <p>&nbsp;</p>
    <hr/>
    <nuxt-link to="/">index page</nuxt-link>
    <br/>
    <my-router-link to="/" is-nuxt>
      <button>index page button</button>
    </my-router-link>
  </div>
</template>
<script setup>
import {MyRouterLink} from "@timvdeijnden/example-lib/src";
</script>
