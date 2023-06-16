<script setup>
const miVariable = 5;
const miVariable2 = {
  a: ['5', 'HOLA', 47, 'abc'],
  b: true,
  c: 'Mi objeto'
};

const miVariable3 = 'Mi objeto';
function miFuncion() {
  return 7;
}
</script>

<template>
  <h1>Hola mundo</h1>

  <p>{{ 1 + 3 }}</p>
  <p>{{ (7 < 8) ? 'Si' : 'No' }}</p>
      <p>Mi Variable {{ miVariable }}</p>
      <p>Mi Variable + 4: {{ miVariable + 4 }}</p>

      <p>Mivariable2: {{ miVariable2 }}</p>
      <p>Mivariable2 a: {{ miVariable2.a[0] }}</p>
      <p>Mivariable2 b: {{ miVariable2.b }}</p>
      <p>Mivariable2 b: {{ miVariable2['b'] }}</p>
      <p>Funcion: {{ miVariable3 + " " + miFuncion() }}</p>
</template>

<style scoped></style>
