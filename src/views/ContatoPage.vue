<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title>Contato</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content :fullscreen="true">
      <ion-header collapse="condense">
        <ion-toolbar>
          <ion-title size="large">Contato</ion-title>
        </ion-toolbar>
      </ion-header>
      
      <ion-text color="danger">
        <h1> cd nome_do_projeto</h1>
        <h1> code .</h1>
        <h1> ionic start</h1>
        
      </ion-text>

      <p>
        Utilize o <ion-text color="success">Ionic</ion-text>
        Para seus projetos mobile.
      </p>

      <ion-grid>
        <ion-row>
          <ion-col>
            <b>Item 01</b>
          </ion-col>
          <ion-col>
            <b> Item 02</b>
          </ion-col>
        </ion-row>
        <ion-row>
          <ion-col>
            Valor 01
          </ion-col>
          <ion-col>
            Valor 02
          </ion-col>
        </ion-row>
      </ion-grid>
  
    </ion-content>
  </ion-page>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import { IonPage, IonHeader, IonToolbar, IonTitle, IonContent, IonGrid, IonRow, IonCol, IonText } from '@ionic/vue';

export default  defineComponent({
  name: 'contatoPage',
  components: { IonHeader, IonToolbar, IonTitle, IonContent, IonPage, IonGrid, IonRow, IonCol, IonText }
});
</script>
