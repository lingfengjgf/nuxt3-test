<template>
  <div>
    <NuxtLayout name="custom">
      <template #header>
        <h3>Special1111 Page</h3>
      </template>
      <template #default>
        <div>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Ex quaerat cupiditate odit voluptate perferendis exercitationem aut aperiam ipsam! Velit officiis doloremque ipsum consectetur temporibus illo ratione sit, ut ad itaque.</div>
      </template>
    </NuxtLayout>
    <NuxtLayout>
      <template>
        <h3>Special1111 Page default</h3>
      </template>
    </NuxtLayout>
  </div>
</template>

<script>
export default {
  layout:false
}
</script>