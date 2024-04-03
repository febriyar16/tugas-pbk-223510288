<script setup>
defineProps({
  msg: {
    type: String,
    required: true,
  },
});
</script>

<template>
  <div class="greetings">
    <h1 class="green">{{ msg }}</h1>
    <h3>
Nama: Febri Yar Darmawansyah P <br>
Tempat, Tgl Lahir: pekanbaru, 16 Februari 2004 <br>
Jenis Kelamin: Laki-Laki <br>
Agama: Islam <br>
Kewarganegaraan: Indonesia <br>
Status: Belum Kawin <br>
Alamat Sekarang: pandau jaya, jl.purnama 2,siak hulu,pekanbaru <br>
Telepon: 089509085698 <br>
Email: febriyardarmawansyah@gmail.com <br>

      <a href="https://vitejs.dev/" target="_blank" rel="noopener"></a>
      <a href="https://vuejs.org/" target="_blank" rel="noopener"></a>
    </h3>
  </div>
</template>

<style scoped>
h1 {
  font-weight: 500;
  font-size: 2.6rem;
  position: relative;
  top: -10px;
  color: rgb(0, 0, 0);
  font-family: 'Times New Roman', Times, serif;
}

h3 {
  font-size: 1.2rem;
  font-family: "Gill Sans", "Gill Sans MT", Calibri, "Trebuchet MS", sans-serif;
  color: black;
}
.greetings h1,
.greetings h3 {
  text-align: center;
}

@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
}
</style>
