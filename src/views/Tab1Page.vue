<template>
  <ion-page>
    <ion-header :translucent="true">
      <ion-toolbar>
        <ion-title>Home</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content :fullscreen="true">
    <ion-header collapse="condense">
       <ion-toolbar>
        <ion-title size="large">Home</ion-title>
      </ion-toolbar>
    </ion-header>
    <div>
      <ion-row>
        <ion-col>
          <ion-card class="white-cards">
            <ion-card-header class="card-head">
             Kolam
            </ion-card-header>

            <ion-card-content class="card-content">
              <ion-card-title class="card-title">
                10
              </ion-card-title>
              <ion-card-subtitle class="card-sub">

              </ion-card-subtitle>
            </ion-card-content>
          </ion-card>
        </ion-col>
        <ion-col>
          <ion-card class="white-cards">
            <ion-card-header class="card-head">
             Kolam Aktif
            </ion-card-header>

            <ion-card-content class="card-content">
              <ion-card-title class="card-title">
                8
              </ion-card-title>
              <ion-card-subtitle class="card-sub">

              </ion-card-subtitle>
            </ion-card-content>
          </ion-card>
        </ion-col>
      </ion-row>

<!-- second row -->
      <ion-row>
        <ion-col>
          <ion-card class="white-cards">
            <ion-card-header class="card-head">
             Ikan Hidup
            </ion-card-header>

            <ion-card-content class="card-content">
              <ion-card-title class="card-title">
                182
              </ion-card-title>
              <ion-card-subtitle class="card-sub">
                ekor
              </ion-card-subtitle>
            </ion-card-content>
          </ion-card>
        </ion-col>
        <ion-col>
          <ion-card class="white-cards">
            <ion-card-header class="card-head">
             Ikan Mati
            </ion-card-header>

            <ion-card-content class="card-content">
              <ion-card-title class="card-title">
                89
              </ion-card-title>
              <ion-card-subtitle class="card-sub">
                ekor
              </ion-card-subtitle>
            </ion-card-content>
          </ion-card>
        </ion-col>
      </ion-row>

<!-- third row -->
      <ion-row>
        <ion-col>
          <ion-card class="white-cards">
            <ion-card-header class="card-head">
             Panen 2022
            </ion-card-header>

            <ion-card-content class="card-content">
              <ion-card-title class="card-title">
                109
              </ion-card-title>
              <ion-card-subtitle class="card-sub">
                ekor
              </ion-card-subtitle>
            </ion-card-content>
          </ion-card>
        </ion-col>
        <ion-col>
          <ion-card class="white-cards">
            <ion-card-header class="card-head">
             Total Pakan
            </ion-card-header>

            <ion-card-content class="card-content">
              <ion-card-title class="card-title">
                223
              </ion-card-title>
              <ion-card-subtitle class="card-sub">
                ekor
              </ion-card-subtitle>
            </ion-card-content>
          </ion-card>
        </ion-col>
      </ion-row>
    </div>

      <!-- slider-->
    <ion-title>TOTAL BERAT IKAN</ion-title>
      <div class="slider">
        <ion-row>
          <ion-col>
            <ion-card class="slider-cards">
              <ion-card-header class="card-head">
                Ikan
              </ion-card-header>
            </ion-card>
          </ion-col>
        </ion-row>
      </div>
      <div class="slider">
        <ion-row>
          <ion-col>
            <ion-card class="slider-cards">
              <ion-card-header class="card-head">
                Ikan
              </ion-card-header>
            </ion-card>
          </ion-col>
        </ion-row>
      </div>
      <!-- slider pH-->
    <ion-title>KUALITAS AIR</ion-title>
    <div class="slider">
        <ion-row>
          <ion-col>
            <ion-card class="slider-cards">
              <ion-card-title class="card-title">
                pH
              </ion-card-title>
            </ion-card>
          </ion-col>
        </ion-row>
      </div>
      </ion-content>

  </ion-page>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import { IonPage, IonHeader, IonToolbar, IonTitle, IonContent } from '@ionic/vue';

export default  defineComponent({
  name: 'Tab1Page',
  components: {IonHeader, IonToolbar, IonTitle, IonContent, IonPage }
});
</script>
