<template>
  <div id="Home">
    <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
      <div class="container">
        <a class="navbar-brand" href="#">Tiara Khoirunnisa</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
          <div class="navbar-nav ml-auto">
            <a class="nav-link active" href="#Home">Home <span class="sr-only">(current)</span></a>
            <a class="nav-link" href="#About">About</a>
            <a class="nav-link" href="#Portfolio">Portfolio</a>
            <a class="nav-link" href="#Contact">Contact</a>
          </div>
        </div>
      </div>
    </nav>

    <div class="jumbotron jumbotron-fluid">
      <div class="container text-center">
        <img class="rounded-circle" src="../assets/tiara.jpg" width="300" height="300" alt="" />
        <h1 class="display-4">Tiara Khoirunnisa</h1>
        <p class="lead">welcome to my website.</p>
      </div>
    </div>

    <section id="About" class="about">
      <div class="container">
        <div class="row mb-4">
          <div class="col">
            <h2>About</h2>
          </div>
        </div>
      </div>
      <div class="row justify-content-center mb-5 align-items-center">
        <div class="col-md-4 text-center">
          <ol>
            <li>Nama:Tiara Khoirunnisa</li>
            <li>Tempat/Tgl Lahir:Bandung,2-Februari-2004</li>
            <li>id instagram:@tiarakh.04</li>
          </ol>
        </div>
        <div class="col-md-4 text-center">
          <img src="../assets/tiara.jpg" width="150" height="150" alt="" />
        </div>
      </div>
    </section>

    <section id="Portfolio" class="portfolio bg-light pb-4">
      <div class="container">
        <div class="row mb-4 pt-4">
          <div class="col">
            <h2>Portfolio</h2>
          </div>
        </div>

        <div class="row mb-4">
          <div class="col-md">
            <div class="card" style="width: 18rem">
              <img src="../assets/download.jpg" class="card-img-top" alt="..." />
              <div class="card-body">
                <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
              </div>
            </div>
          </div>
          <div class="col-md">
            <div class="card" style="width: 18rem">
              <img src="../assets/ipad.jpg" class="card-img-top" height="191" alt="..." />
              <div class="card-body">
                <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
              </div>
            </div>
          </div>
          <div class="col-md">
            <div class="card" style="width: 18rem">
              <img src="../assets/pc.jpg" class="card-img-top" alt="..." />
              <div class="card-body">
                <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
              </div>
            </div>
          </div>
        </div>
        <div class="row mb-4">
          <div class="col-md">
            <div class="card" style="width: 18rem">
              <img src="../assets/download.jpg" class="card-img-top" alt="..." />
              <div class="card-body">
                <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
              </div>
            </div>
          </div>
          <div class="col-md">
            <div class="card" style="width: 18rem">
              <img src="../assets/ipad.jpg" class="card-img-top" height="191" alt="..." />
              <div class="card-body">
                <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
              </div>
            </div>
          </div>
          <div class="col-md">
            <div class="card" style="width: 18rem">
              <img src="../assets/pc.jpg" class="card-img-top" alt="..." />
              <div class="card-body">
                <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section id="Contact" class="contact mb-5">
      <div class="container">
        <div class="row pt-4 mb-4">
          <div class="col">
            <h2>contact us</h2>
          </div>
        </div>
        <div class="row justify-content-center">
          <div class="col-lg-4">
            <div class="card text-white bg-primary mb-3">
              <div class="card-body">
                <h5 class="card-title">contact us</h5>
                <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
              </div>
            </div>
            <ul class="list-group">
              <li class="list-group-item"><h1>location</h1></li>
              <li class="list-group-item">my home</li>
              <li class="list-group-item">Jl. palasari Blk.113 RT.11 RW.07, Kel.Turangga, Kec.Lengkong, Kota Bandung, Jawa Barat, Indonesia 40264</li>
              <li class="list-group-item">west java, Indonesia</li>
            </ul>
          </div>
          <div class="col-lg-6">
            <form class="text-left">
              <div class="form-group">
                <label for="nama">Nama</label>
                <input type="text" class="form-control" id="nama" />
              </div>
              <div class="form-group">
                <label for="email">Email</label>
                <input type="text" class="form-control" id="email" />
              </div>
              <div class="form-group">
                <label for="telp">No.Telp</label>
                <input type="text" class="form-control" id="telp" />
              </div>
              <div class="form-group">
                <label for="pesan">pesan</label>
                <textarea name="pesan" id="pesan" class="form-control"></textarea>
              </div>
              <div class="formgrup">
                <button type="submit" class="btn btn-primary">kirim</button>
              </div>
            </form>
          </div>
        </div>
      </div>
    </section>
    <footer class="bg-dark text-white">
      <div class="container">
        <div class="row pt-3">
          <div class="col">
            <p>&copy; copyright by Tiara khoirunnisa 2021</p>
          </div>
        </div>
      </div>
    </footer>
  </div>
</template>
<script>
export default {
  name: "Latihan",
};
</script>
<style scoped></style>
