<template>
  <table >
    <thead>
    <tr>
      <th>Nr</th>
      <th>Numele Produsului</th>
      <th>Pretul unei cantitati</th>
      <th>Numarul de cantitati</th>
      <th>Pretul total</th>
    </tr>
    </thead>
    <tbody>

    <tr v-for="product in products">
      <td > index </td>
      <td >{{ product.nume }}</td>
      <td >{{ product.pret }}</td>
      <td >{{ product.cantitate }}</td>
      <td >{{ product.totalul }}</td>
    </tr>
    </tbody>
  </table>
</template>

<script>
      products:[{
        nume: 'catalin',
        pret: 12,
        cantitate: 2,
        totalul: 24
      }]
</script>