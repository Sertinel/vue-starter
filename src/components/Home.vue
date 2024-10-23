<template>
    <div>
        <h1>{{ title }}</h1>
        <button @click="changeTitle">Başlığı Değiştir</button>
        <input v-model="newItem">
        <ul>
          <li v-for="item in items" :key="item.id">
            {{ item.text }}
          </li>
        </ul>
      </div>
  </template>
  
  <script>
  // JavaScript kodu buraya yazılır
  export default {
    name: 'ComponentName',
    props: {
      // Dışarıdan alınan özellikler
    },
    data() {
      return {
        // Bileşenin verileri
      }
    },
    methods: {
      // Metodlar
    }
  }
  </script>
  
  <style>
  /* CSS kodları buraya yazılır */
  </style>