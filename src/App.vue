<template>
  <div id="app">
    <div class="header">
      <h1>Nagy headline, H1</h1>
    </div>
    <md-card>
      <md-card-media>
        <div class="button-blue-shadow">
          <md-button><p>Kiemelés</p></md-button>
        </div>
        <div class="layer">
          <img src="https://vuematerial.io/assets/examples/card-image-1.jpg" alt="People">
        </div>
      </md-card-media>
      <md-ripple>
      <md-card-header>
          <div class="md-layout md-gutter">
            <div class="md-layout-item">
              <md-field>
                <label>Form 1</label>
                <md-input></md-input>
              </md-field>
            </div>

            <div class="md-layout-item">
              <md-field>
                <label>Form 2</label>
                <md-input></md-input>
              </md-field>
            </div>
            </div>
          <md-field>
            <label>Radio választás</label>

          </md-field>

            <checkbox v-model="disabled" disabled>Kikapcsolt checkbox</checkbox>
            <checkbox v-model="values" color="#0089cf" value="Hover checkbox">Hover checkbox</checkbox>
            <checkbox v-model="values" color="#0089cf" value="Bekapcsolt checkbox" checked>Bekapcsolt checkbox</checkbox>
        </md-card-header>
        </md-ripple>
    </md-card>

    <md-card>
      <md-card-media>
        <div class="button-orange-shadow">
          <md-button><p>Kiemelés</p></md-button>
        </div>
        <img src="https://vuematerial.io/assets/examples/card-image-1.jpg" alt="People">
      </md-card-media>
      <md-ripple>
        <md-card-header>
          <h2>Kis alcím H2</h2>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Etiam ornare tempor quam, non interdum erat gravida et.</p>
        </md-card-header>

        <md-card-content>
          <div class="d-flex">
              <div class="vl"></div>
              <h2>Lorem ipsum dolor sit amet,<br> consectetur adipisicing elit, consectetur</h2>
          </div>
        </md-card-content>

        <md-card-actions>
          <md-button><p>GOMB</p></md-button>
        </md-card-actions>
      </md-ripple>
    </md-card>

    <div class="md-card-out">
      <md-button class="md-fab md-mini">
        <md-icon>close</md-icon>
      </md-button>
    <md-card>
      <md-card-media>
        <img src="https://vuematerial.io/assets/examples/card-image-1.jpg" alt="People">
      </md-card-media>
      <md-ripple>
        <md-card-content>
        </md-card-content>
      </md-ripple>
    </md-card>
    </div>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld'

export default {
  name: 'App'
}
</script>

<style lang="scss" scoped>
  @import './assets/stylesheet/main.scss';
</style>
