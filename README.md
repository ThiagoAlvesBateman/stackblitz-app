<ion-content>
  <ion-header>
    <ion-toolbar>
      <ion-title>Cadastro</ion-title>
    </ion-toolbar>
  </ion-header>
  <ion-content class="ion-padding">
    <ion-card>
      <ion-card-header>
        <ion-card-title class="ion-text-center">Cadastro</ion-card-title>
      </ion-card-header>
      <ion-card-content>
        <ion-list>
          <ion-item>
            <ion-label position="stacked">Nome do Seu Pet</ion-label>
            <ion-input type="text" name="name"></ion-input>
          </ion-item>
          <ion-item>
            <ion-label position="stacked">E-mail</ion-label>
            <ion-input type="email" name="email"></ion-input>
          </ion-item>
          <ion-item>
            <ion-label position="stacked">Senha</ion-label>
            <ion-input type="password" name="password"></ion-input>
          </ion-item>
        </ion-list>
        <div class="ion-text-center">
          <ion-button expand="full">Confirmar</ion-button>
        </div>
      </ion-card-content>
    </ion-card>
  </ion-content>
</ion-content>
