<template>
  <div>
    <h1>about</h1>
    <p>On this page the button does <strong>NOT</strong> works creates the the following warning in console</p>
    <pre>[Vue warn]: Failed to resolve component: nuxt-link</pre>
    <p>Uses the built version of MyRouterLink in example-lib</p>
    <hr/>
    <nuxt-link to="/">index page</nuxt-link>
    <br/>
    <my-router-link to="/" is-nuxt>
      <button>index page button</button>
    </my-router-link>
  </div>
</template>
<script setup>
import {MyRouterLink} from "example-lib/dist";
</script>
