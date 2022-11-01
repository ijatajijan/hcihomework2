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

      <ion-grid>
        <ion-row>
          <ion-col>
            <ion-card color="dark">
              <ion-card-header>
                <ion-card-subtitle>Kolam</ion-card-subtitle>
                <ion-card-detail>10</ion-card-detail>
              </ion-card-header>
            </ion-card>
          </ion-col>
          <ion-col>
            <ion-card color="dark">
              <ion-card-header>
                <ion-card-subtitle>Kolam Aktif</ion-card-subtitle>
                <ion-card-detail>8</ion-card-detail>
              </ion-card-header>
            </ion-card>
          </ion-col>
        </ion-row>
        <ion-row>
          <ion-col>
            <ion-card color="dark">
              <ion-card-header>
                <ion-card-subtitle>Ikan Hidup</ion-card-subtitle>
                <ion-card-detail>182 Ekor</ion-card-detail>
              </ion-card-header>
            </ion-card>
          </ion-col>
          <ion-col>
            <ion-card color="dark">
              <ion-card-header>
                <ion-card-subtitle>Ikan Mati</ion-card-subtitle>
                <ion-card-detail>89 Ekor</ion-card-detail>
              </ion-card-header>
            </ion-card>
          </ion-col>
        </ion-row>
        <ion-row>
          <ion-col>
            <ion-card color="dark">
              <ion-card-header>
                <ion-card-subtitle>Panen 2022</ion-card-subtitle>
                <ion-card-detail>109 Kg</ion-card-detail>
              </ion-card-header>
            </ion-card>
          </ion-col>
          <ion-col>
            <ion-card color="dark">
              <ion-card-header>
                <ion-card-subtitle>Total Pakan</ion-card-subtitle>
                <ion-card-detail>223 Kg</ion-card-detail>
              </ion-card-header>
            </ion-card>
          </ion-col>
        </ion-row>
      </ion-grid>
      <ion-title>TOTAL BERAT IKAN</ion-title>
      <div id="container-fluid">
        <ion-grid>
          <ion-row>
            <ion-col>
              <ion-card color="dark">
                <img
                  src="https://png.pngtree.com/png-vector/20220705/ourmid/pngtree-catfish-vector-png-image_5687106.png"
                  height="500"
                  width="500"
                />
                <ion-card-header>
                  <ion-card-title>LELE</ion-card-title>
                  <ion-card-subtitle color="secondary">
                    <span style="color: #2c96f1; display: inline-block"
                      >200 Kg</span
                    ></ion-card-subtitle
                  >
                </ion-card-header>
              </ion-card>
            </ion-col>
            <ion-col>
              <ion-card color="dark">
                <img
                  src="https://media.istockphoto.com/vectors/illustration-tilapia-on-white-background-vector-id505167168?k=20&m=505167168&s=170667a&w=0&h=wBa4w5gdJADz3y-2rl4g8eYhWQMayYX7zLvclUgY3W4="
                  height="500"
                  width="500"
                />
                <ion-card-header>
                  <ion-card-title>NILA MERAH</ion-card-title>
                  <ion-card-subtitle color="secondary">
                    <span style="color: #2c96f1; display: inline-block"
                      >200 Kg</span
                    ></ion-card-subtitle
                  >
                </ion-card-header>
              </ion-card>
            </ion-col>
          </ion-row>
        </ion-grid>
      </div>
      <ion-title>KUALITAS AIR</ion-title>
      <ion-grid>
        <ion-row>
          <ion-col>
            <ion-card color="dark">
              <ion-card-header>
                <ion-card-title>pH</ion-card-title>
              </ion-card-header>
              <ion-card-content>
                <ion-card-subtitle
                  >Normal
                  <span
                    style="
                      color: #2c96f1;
                      display: inline-block;
                      font-size: 30px;
                    "
                  >
                    6 Kolam</span
                  >
                </ion-card-subtitle>
                <ion-card-subtitle
                  >Abnormal
                  <span
                    style="
                      color: #2c96f1;
                      display: inline-block;
                      font-size: 30px;
                    "
                    >6 Kolam</span
                  ></ion-card-subtitle
                >
              </ion-card-content>
            </ion-card>
          </ion-col>
          <ion-col>
            <ion-card color="dark">
              <ion-card-header>
                <ion-card-title>DO</ion-card-title>
              </ion-card-header>
              <ion-card-content>
                <ion-card-subtitle
                  >Normal
                  <span
                    style="
                      color: #2c96f1;
                      display: inline-block;
                      font-size: 30px;
                    "
                    >6 Kolam</span
                  ></ion-card-subtitle
                >
                <ion-card-subtitle
                  >Abnormal
                  <span
                    style="
                      color: #2c96f1;
                      display: inline-block;
                      font-size: 30px;
                    "
                    >6 Kolam</span
                  ></ion-card-subtitle
                >
              </ion-card-content>
            </ion-card>
          </ion-col>
        </ion-row>
      </ion-grid>
    </ion-content>
  </ion-page>
</template>

<script lang="ts">
import {
  IonContent,
  IonHeader,
  IonPage,
  IonTitle,
  IonToolbar,
  IonCard,
  IonCardContent,
  IonCardHeader,
  IonCardSubtitle,
  IonCardTitle,

} from "@ionic/vue";
import { defineComponent } from "vue";


export default defineComponent({
  name: "Tab1Page",
  components: {
    IonContent,
    IonHeader,
    IonPage,
    IonTitle,
    IonToolbar,
    IonCard,
    IonCardHeader,
    IonCardSubtitle,
    IonCardContent,
    IonCardTitle,

  },
});
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Poppins&display=swap');
* {
  font-family: 'Poppins', sans-serif;
}
#container {
  text-align: start;
  position: absolute;
  top: 60%;
  transform: translateY(-45%);
}
#container-fluid {
  overflow: visible;
  text-align: left;
  border-radius: 15px;
}
ion-card-title {
  font-weight: 1000;
  font-size: 25px;
  text-align: left;
}
ion-card-detail {
  font-weight: 1000;
  font-size: 30px;
  text-align: left;
}
ion-card-subtitle {
  font-weight: 550;
  font-size: 25px;
  text-align: left;
}
</style>
