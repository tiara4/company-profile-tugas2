<template>
  <div>
    <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
      <div class="container">
        <img class="mr-2" src="../assets/logo smkn 15.jpg" width="30" height="30" alt="" />
        <a class="navbar-brand" href="#">Libels</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav ml-auto">
            <li class="nav-item active">
              <a class="nav-link" href="#">Home</a>
            </li>
            <li class="nav-item active">
              <a class="nav-link" href="#">about</a>
            </li>
            <li class="nav-item active">
              <a class="nav-link" href="#">galeri</a>
            </li>
            <li class="nav-item active">
              <a class="nav-link contact">contact</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>

    <div class="jumbotron">
      <h1 class="display-4">SMKN 15 Bandung</h1>
      <p class="lead">This is a vocational high school, majoring in social care, hospitality, catering, multimedia.</p>
      <hr class="my-4" />
      <p>Creativity (C), Adaptability (A), Responsbility (R) dan Emphaty (E).</p>
      <a class="btn btn-warning btn-lg" href="#" role="button">about us</a>
    </div>
    <h1>SMKN 15 Bandung</h1>
    <img class="gambarsmkn" src="../assets/logo smkn 15.jpg" alt="" />
    <h2>VISI:</h2>
    <p>Creativity (C), Adaptability (A), Responsbility (R) dan Emphaty (E)</p>
    <h3>Deskripsi:</h3>
    <p>Membentuk peserta didik yang memiliki kreatifitas tinggi, terampil beradaptasi dengan perubahan dunia, siap bertanggung jawab dalam setiap keputusan yang diambil serta memiliki tenggang rasa antar sesama makhluk.</p>
    <h4>MISI:</h4>
    <ol type="1">
      <li>Memiliki keunggulan dan kompeten di bidang keperawatan sosial, perhotelan, multimedia dan tata boga</li>
      <li>Memiliki kemampuan berinovasi untuk menciptakan karya sesuai dengan tuntutan Dunia Usaha/Dunia Industri (DU/DI)</li>
      <li>Memiliki penyesuaian diri terhadap perubahan di lingkungan sekolah, masyarakat, nasional dan internasional</li>
    </ol>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}

.jumbotron {
  background-color: lightblue;
  color: white;
}

.gambarsmkn {
  width: 350px;
  height: 350px;
}
</style>
