<template>
  <div class="grid grid-cols-1 md:grid-cols-3 gap-4">
    <div v-for="(item, index) in items" :key="index" class="p-4 bg-green-100 rounded flex items-left justify-center flex-col text-left">
      <h4 class="text-5xl font-bold text-green-500 my-2">
        {{ item.number }}
      </h4>
      <p>{{ item.description }}</p>
    </div>
  </div>
</template>
<script setup>
const items = ([
  { number: '100 000 м2+', description: 'уложено газона\nна наших объектах' },
  { number: '900+', description: 'довольных\nклиентов' },
  { number: '50+', description: 'верных поставщиков\nпосадочного материала' },
  { number: '35 000+', description: 'посажено деревьев\nи кустарников' },
  { number: '5-15', description: 'проектов\nежегодно' },
  { number: '$1 000 000', description: 'реализованной\nвыручки' }
])

</script>
<style scoped>

</style>
