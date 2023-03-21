<template>
  <div class="inputs">
    <p>Message is: {{ nume }}</p>
    nume <input v-model="nume"><br>
    pret <input v-model="pret"><br>
    cantitate <input v-model="cantitate"><br>
    <button type="submit" @click="addProduct">Add Product</button>
    <button type="submit" @click="Reset">Reset</button>
  </div>
</template>

