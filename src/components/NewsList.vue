<script>
/*
  ДЗ:
    Вывести список новостей
    адрес - 'https://fakestoreapi.com/products'
  Дополнительно:
    Переход из листа в детальную новость

*/
export default {
  beforeMount: (el) => {
    // Сделать запрос к АПИ, для вывод новостей
  },
  data() {
    return {
      title: "Список новостей"
    };
  },
  setup() {
    return {
    }
  }
}
</script>

<template>
    <h1>{{title}}</h1>
</template>

<style scoped>

</style>