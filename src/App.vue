<template>
  <table class="table">
    <thead>
      <tr>
        <th scope="col">Nombre</th>
        <th scope="col">Apellido</th>
        <th scope="col">RUT</th>
        <th scope="col">Edad</th>
        <th scope="col">Fecha de Nacimiento</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>{{ persona1.nombre }}</td>
        <td>{{ persona1.apellido }}</td>
        <td>{{ persona1.rut }}</td>
        <td>{{ persona1.edad }}</td>
        <td>{{ persona1.fechaDeNacimiento }}</td>
      </tr>
      <tr>
        <td>{{ persona2.nombre }}</td>
        <td>{{ persona2.apellido }}</td>
        <td>{{ persona2.rut }}</td>
        <td>{{ persona2.edad }}</td>
        <td>{{ persona2.fechaDeNacimiento }}</td>
      </tr>
      <tr>
        <td>{{ persona3.nombre }}</td>
        <td>{{ persona3.apellido }}</td>
        <td>{{ persona3.rut }}</td>
        <td>{{ persona3.edad }}</td>
        <td>{{ persona3.fechaDeNacimiento }}</td>
      </tr>
    </tbody>
  </table>
  
</template>

<script>
export default {
  data() {
    return {
    persona1: {
        nombre: "Darka",
        apellido: "Lunar Espacial",
        rut: "00004",
        edad: 1,
        fechaDeNacimiento: "15-04-2020"},
    persona2:  {
        nombre: "Pulga",
        apellido: "María",
        rut: "00001",
        edad: 20,
        fechaDeNacimiento: "27-11-2012"},
    persona3:  {
        nombre: "Freud",
        apellido: "Larito",
        rut: "00002",
        edad: 6,
        fechaDeNacimiento: "28-02-2015"},
    }
  }
}

</script>

<style></style>