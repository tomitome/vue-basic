<template>
  <!-- <div>
    <h2>Boostrap</h2>
    <div class="container">
      <div class="row">
        <div class="col-12 col-sm-3 bg-primary">A</div>
        <div class="col-12 col-sm-4 bg-success">B</div>
        <div class="col-12 col-sm-5 bg-warning">C</div>
      </div>
    </div>
    <h2>Boostrap-Vue</h2>
    <b-container>
      <b-row>
        <b-col cols="12" sm="3" class="bg-primary">D</b-col>
        <b-col cols="12" sm="4" class="bg-success">D</b-col>
        <b-col cols="12" sm="5" class="bg-warning">D</b-col>
      </b-row>
    </b-container>
  </div> -->



  <!-- <div>
    <b-jumbotron header="Bootstrap Vue" lead="Bootstrap 4 Compornents for Vue.js 2">
    <p>For more information visit website</p>
      <b-button variant="primary" href="#">More Info</b-button>
    </b-jumbotron>
  </div> -->

  <!-- <div>
    <b-card
      title="tomitome"
      sub-title="dennsetu no otoko"
      style="max-width: 20rem;"
      img-src="https://placekitten.com/1000/300">
      <b-card-text>
        gagagagagagga
      </b-card-text>

      <b-card-text>
        fafafafafafafafa
      </b-card-text>

      <a href="#" class="card-link">aでのリンク</a>
        <b-link href="https://placekitten.com/1000/3000" class="card-link">b-linkのリンク</b-link>
      </b-card>
  </div> -->

  <b-container>
    <!-- Using compornents -->
    <b-input-group prepend="name" class="mt-3">
      <b-form-input/>
      <b-input-group-append>
        <b-button variant="info">Button</b-button>
      </b-input-group-append>
    </b-input-group>

    <b-input-group prepend="0" append="100" class="mt-3">
      <b-form-input type="range" min="0" max="100"/>
    </b-input-group>

    <b-input-group class="mt-5">
      <b-input-group-prepend is-text>
        <input type="checkbox">
      </b-input-group-prepend>
      <b-form-input type="text"/>
    </b-input-group>
  </b-container>
</template>