<script lang="ts" setup>

/**
 * NestedLevel1-2 多级菜单 一级菜单 1-2（目录层级）
 */
defineOptions({
  name: 'Wdfwefwefew'
})

const route = useRoute()

const router = useRouter()

const pageTitle = ref('NestedLevel1-2 多级菜单 一级菜单 1-2（目录层级）')

const inputValue = ref(pageTitle.value)


</script>

<template>
  <div class="p-16px">
    <h1>{{ pageTitle }}</h1>
    <n-input v-model:value="inputValue" />
  </div>
</template>

<style lang="scss" scoped>
</style>
