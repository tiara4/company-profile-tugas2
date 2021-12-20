<template>
  <div id="Home">
    <nav class="navbar navbar-expand-lg navbar-dark bg-primary fixed-top">
      <div class="container">
        <a class="navbar-brand" href="#">my website </a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
          <div class="navbar-nav">
            <a class="nav-link active" href="#Home">Home <span class="sr-only">(current)</span></a>
            <a class="nav-link" href="#About">About</a>
            <a class="nav-link" href="#Galeri">Galeri</a>
            <a class="nav-link" href="#Testimonial">Testimonial</a>
            <a class="nav-link disabled">Contact</a>
          </div>
        </div>
      </div>
    </nav>

    <div class="jumbotron jumbotron-fluid">
      <div class="container">
        <h1 class="display-4">Welcome To My Website</h1>
        <p class="lead">This website is made by myself.</p>
      </div>
    </div>

    <section id="about" class="about">
      <div class="container">
        <div class="row mb-4 pt-4">
          <div class="col">
            <h2>About Me</h2>
          </div>
        </div>
      </div>
      <div class="row justify-content-center mb-5 align-items-center">
        <div class="col-md-4 text-center">
          <img src="../assets/image-about.jpg" width="150" height="150" alt="" />
        </div>
        <div class="col-md-4 text-center box-about">
          <p class="text-white">
            Lorem ipsum, dolor sit amet consectetur adipisicing elit. Inventore accusamus rerum quaerat dolorem. Enim libero cumque, nemo blanditiis obcaecati magnam quod sunt, rem impedit sit aut modi et? Officia, velit.
          </p>
        </div>
      </div>
    </section>

    <section id="Galeri" class="Galeri bg-light pb-4">
      <div class="container">
        <div class="row mb-4 pt-4">
          <div class="col">
            <h2>Galeri</h2>
          </div>
        </div>
        <div class="row mb-4">
          <div class="col-md">
            <img src="../assets/gallery1.jpg" width="150" height="150" alt="" />
          </div>
          <div class="col-md">
            <img src="../assets/gallery2.jpg" width="150" height="150" alt="" />
          </div>
          <div class="col-md">
            <img src="../assets/gallery3.jpg" width="150" height="150" alt="" />
          </div>
        </div>
        <div class="row mb-4">
          <div class="col-md">
            <img src="../assets/gallery4.jpg" width="150" height="150" alt="" />
          </div>
          <div class="col-md">
            <img src="../assets/gallery5.jpg" width="150" height="150" alt="" />
          </div>
          <div class="col-md">
            <img src="../assets/gallery6.jpg" width="150" height="150" alt="" />
          </div>
        </div>
      </div>
    </section>

    <section id="Testimonial" class="Testimonial">
      <div class="container">
        <div class="row mb-4 pt-4">
          <div class="col">
            <h2>Testimonial</h2>
          </div>
        </div>
        <div class="row mb-4">
          <div class="col-md">
            <div class="card" style="width: 18rem">
              <img src="../assets/testi1.jpg" class="card-img-top rounded-circle" alt="..." />
              <div class="card-body">
                <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
              </div>
            </div>
          </div>
          <div class="col-md">
            <div class="card" style="width: 18rem">
              <img src="../assets/testi2.jpg" class="card-img-top rounded-circle" alt="..." />
              <div class="card-body">
                <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
              </div>
            </div>
          </div>
          <div class="col-md">
            <div class="card" style="width: 18rem">
              <img src="../assets/testi3.jpg" class="card-img-top rounded-circle" alt="..." />
              <div class="card-body">
                <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section id="contact" class="contact bg-light pb-4">
      <div class="container">
        <div class="row mb-4 pt-4">
          <div class="col">
            <h2>Contact Us</h2>
          </div>
        </div>
        <div class="row justify-content-center">
          <div class="col-md-6">
            <form class="text-left">
              <div class="form-group">
                <label for="Username">Username</label>
                <input type="text" class="form-control" id="Username" />
              </div>
              <div class="form-group">
                <label for="email">Email</label>
                <input type="text" class="form-control" id="email" />
              </div>
              <div class="form-group">
                <label for="password">password</label>
                <input type="text" class="form-control" id="password" />
              </div>
              <div class="formgrup">
                <button type="submit" class="btn btn-primary">submit</button>
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
            <p>&copy; copyright by Tiara 2021</p>
          </div>
        </div>
      </div>
    </footer>
  </div>
</template>
<script>
export default {
  name: "Belajar",
};
</script>
<style scoped>
.jumbotron {
  padding-top: 100px;
  background-image: linear-gradient(rgba(0, 0, 0, 0.3), rgba(0, 0, 0, 0.3)), url("../assets/hero-img.jpg");
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
  color: white;
  margin: 0;
}

.about {
  padding-bottom: 30px;
  background-image: linear-gradient(rgba(0, 0, 0, 0.3), rgba(0, 0, 0, 0.3)), url("../assets/image-about-bg.jpg");
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
  color: whitesmoke;
}

.about .box-about {
  color: white;
  font-family: Arial, Helvetica, sans-serif;
}
.about p {
  color: white;
  font-family: Arial, Helvetica, sans-serif;
  font-size: 18px;
}
.contact {
  padding-top: 100px;
  background-image: linear-gradient(rgba(0, 0, 0, 0.3), rgba(0, 0, 0, 0.3)), url("../assets/contact-bg.jpg");
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
}
.contact form {
  padding-bottom: 80px;
}
.contact label {
  color: white;
  font-family: Arial, Helvetica, sans-serif;
  font-size: 16px;
}
.Galeri {
  padding-bottom: 30px;
  background-image: linear-gradient(rgba(0, 0, 0, 0.3), rgba(0, 0, 0, 0.3)), url("../assets/gallery-bg.jpg");
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
  color: whitesmoke;
}

@media (max-width: 767.98px) {
  .Galeri img {
    margin-bottom: 10px;
  }
  .Testimonial .card {
    margin: auto;
    margin-bottom: 10px;
  }
  .about img {
    margin-bottom: 25px;
  }
}
</style>
