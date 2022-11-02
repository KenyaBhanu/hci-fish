<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title>Kolam</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content :fullscreen="true">
      <ion-header collapse="condense">
        <ion-toolbar>
          <ion-title size="large">Kolam</ion-title>
        </ion-toolbar>
      </ion-header>
    <ion-row>
      <ion-card class="kolam-card">
        <ion-card-header class="kolam-card-head">
          Alpha
          <button ion-button block class="active" style="align:center">Aktif</button>
        </ion-card-header>
        
        <ion-card-content class="kolam-card-content">
          <ion-card-title class="kolam-card-title">
            01-09-2022 <br>
            90 hari <br>
            200 ekor
          </ion-card-title>
          <ion-card-subtitle class="kolam-card-sub">

          </ion-card-subtitle>
        </ion-card-content>
      </ion-card>
    </ion-row>
    <ion-row>
      <ion-card class="kolam-card">
        <ion-card-header class="kolam-card-head">
          Beta
          <button ion-button block class="inactive" style="align:center">Tidak Aktif</button>
        </ion-card-header>
        
        <ion-card-content class="kolam-card-content">
          <ion-card-title class="kolam-card-title">
            01-09-2022 <br>
            90 hari <br>
            200 ekor
          </ion-card-title>
          <ion-card-subtitle class="kolam-card-sub">

          </ion-card-subtitle>
        </ion-card-content>
      </ion-card>
    </ion-row>
    <ion-row>
      <ion-card class="kolam-card">
        <ion-card-header class="kolam-card-head">
          Charlie
          <button ion-button block class="active" style="align:center">Aktif</button>
        </ion-card-header>
        
        <ion-card-content class="kolam-card-content">
          <ion-card-title class="kolam-card-title">
            01-09-2022 <br>
            90 hari <br>
            200 ekor
          </ion-card-title>
          <ion-card-subtitle class="kolam-card-sub">

          </ion-card-subtitle>
        </ion-card-content>
      </ion-card>
    </ion-row>
    <ion-row>
      <ion-card class="kolam-card">
        <ion-card-header class="kolam-card-head">
          Delta
          <button ion-button block class="active" style="align:center">Aktif</button>
        </ion-card-header>
        
        <ion-card-content class="kolam-card-content">
          <ion-card-title class="kolam-card-title">
            01-09-2022 <br>
            90 hari <br>
            200 ekor
          </ion-card-title>
          <ion-card-subtitle class="kolam-card-sub">

          </ion-card-subtitle>
        </ion-card-content>
      </ion-card>
    </ion-row>
    <ion-row>
      <ion-card class="kolam-card">
        <ion-card-header class="kolam-card-head">
          Epsilon
          <button ion-button block class="active" style="align:center">Aktif</button>
        </ion-card-header>
        
        <ion-card-content class="kolam-card-content">
          <ion-card-title class="kolam-card-title">
            01-09-2022 <br>
            90 hari <br>
            200 ekor
          </ion-card-title>
          <ion-card-subtitle class="kolam-card-sub">

          </ion-card-subtitle>
        </ion-card-content>
      </ion-card>
    </ion-row>

    </ion-content>
  </ion-page>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import { IonPage, IonHeader, IonToolbar, IonTitle, IonContent } from '@ionic/vue';

export default defineComponent({
  name: 'Tab2Page',
  components: { IonHeader, IonToolbar, IonTitle, IonContent, IonPage }
});
</script>
