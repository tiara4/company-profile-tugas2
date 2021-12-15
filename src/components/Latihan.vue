<template>
  <div>
    <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
      <div class="container">
        <a class="navbar-brand" href="#">Tiara Khoirunnisa</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
          <div class="navbar-nav">
            <a class="nav-link active" href="#">Home <span class="sr-only">(current)</span></a>
            <a class="nav-link" href="#">About</a>
            <a class="nav-link" href="#">Portfolio</a>
            <a class="nav-link disabled">Contact</a>
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

    <div class="container">
      <div class="row">
        <div class="col">
          <h1>About</h1>
        </div>
      </div>
    </div>
    <div class="row">
      <div class="col">
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Assumenda maiores recusandae maxime saepe ea voluptates eos minus ex eligendi praesentium eaque minima, velit aliquid facilis? Voluptatem nostrum nulla praesentium quisquam.
        </p>
      </div>
      <div class="col">
        <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Adipisci optio neque cupiditate nisi voluptate perspiciatis aut cumque amet ab ad praesentium totam incidunt, doloribus fuga maxime itaque blanditiis sit illo?</p>
      </div>
    </div>

    <div class="container">
      <div class="row">
        <div class="col">
          <h1>Portfolio</h1>
        </div>
      </div>
      <div class="row">
        <div class="col">
          <div class="card" style="width: 18rem">
            <img src="../assets/download.jpg" class="card-img-top" alt="..." />
            <div class="card-body">
              <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
            </div>
          </div>
        </div>
        <div class="col">
          <div class="card" style="width: 18rem">
            <img src="../assets/ipad.jpg" class="card-img-top" height="191" alt="..." />
            <div class="card-body">
              <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
            </div>
          </div>
        </div>
        <div class="col">
          <div class="card" style="width: 18rem">
            <img src="../assets/pc.jpg" class="card-img-top" alt="..." />
            <div class="card-body">
              <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "Latihan",
};
</script>
<style scoped></style>
