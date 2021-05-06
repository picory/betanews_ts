<template>
  <div>
    <layout-page />
    <layout-auth />
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator'
import LayoutAuth from '@/components/Layout/Auth.vue'
import LayoutPage from '@/components/Layout/Page.vue'

@Component({
  LayoutPage,
  LayoutAuth
})
export default class App extends Vue {
  isAuth = false
}
</script>

<style scoped>

</style>
