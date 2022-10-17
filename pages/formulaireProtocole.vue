<template>
  <section class="main-content columns is-fullheight">

    <aside class="column is-3 is-narrow-mobile is-fullheight section is-hidden-mobile sidebar">
      <p class="menu-label is-hidden-touch">HOPITAL</p>
      <ul class="menu-list">
        <li>
          <a href="/dasboard" class="is-active is-rounded" style="font-size: 20px; color: white;">
            <span class="icon"><i class="mdi mdi-home"></i></span> Tableau de bord
          </a>
        </li>
        <br>
        <li>
          <a href="#" class="" style="font-size: 20px; color: white;">
            <span class="icon"><i class="mdi mdi-human-white-cane"></i></span> Patients
          </a>
          <ul>
            <li>
              <a href="#" style="font-size: 17px; color: white;">
                <span class="icon is-small"><i class="fa fa-link"></i></span> Liste des patients
              </a>
            </li>
            <li>
              <a href="#" style="font-size: 17px; color: white;">
                <span class="icon is-small"><i class="fa fa-link"></i></span>Dossier des patients
              </a>
            </li>
          </ul>
        </li>
        <li>
          <a href="#" class="" style="font-size:20px; color: white; ">
            <span class="icon"><i class="fa fa-table"></i></span> Consultations
          </a>

          <ul>
            <li>
              <a href="#" style="font-size: 17px; color: white;">
                <span class="icon is-small"><i class="fa fa-link"></i></span> Liste des consultations
              </a>
            </li>
          </ul>
        </li>
        <li>
          <a href="#" class="" style="font-size: 20px; color: white;">
            <span class="icon"><i class="fa fa-table"></i></span> Rendez-vous
          </a>
          <ul>
            <li>
              <a href="#" style="font-size: 17px; color: white; ">
                <span class="icon is-small"><i class="fa fa-link"></i></span> Liste des rendez-vous
              </a>
            </li>
          </ul>
        </li>
        <li>
          <a href="" class="" style="font-size: 20px; color: white;">
            <span class="icon"><i class="fa fa-table"></i></span> Docteurs
          </a>
          <ul>
            <li>
              <a href="" style="font-size: 17px; color: white;">
                <span class="icon is-small"><i class="fa fa-link"></i></span> Liste des docteurs
              </a>
            </li>
            <li>
              <a href="" style="font-size: 17px; color: white;">
                <span class="icon is-small"><i class="fa fa-link"></i></span> Doosier des docteurs
              </a>
            </li>
          </ul>
        </li>
        <li>
          <a href="#" class="" style="font-size: 20px; color: white;">
            <span class="icon"><i class="fa fa-table"></i></span> Paramétrage
          </a>
          <ul>
            <li>
              <a href="#" style="font-size: 19px; color: white; ">
                <span class="icon is-small"><i class="fa fa-link"></i></span> Médicament
              </a>
              <ul>
                <li>
                  <a href="#" style="font-size: 17px; color: white; ">
                    <span class="icon is-small"><i class="fa fa-link"></i></span> Liste des médicaments
                  </a>
                </li>
              </ul>
            </li>
            <li>
              <a href="#" style="font-size: 19px; color: white; ">
                <span class="icon is-small"><i class="fa fa-link"></i></span> Protocoles des reéducations
              </a>
              <ul>
                <li>
                  <a href="#" style="font-size: 17px; color: white; ">
                    <span class="icon is-small"><i class="fa fa-link"></i></span> Liste des protocoles de reéducation
                  </a>
                </li>
              </ul>
            </li>
            <li>
              <a href="#" style="font-size: 17px; color: white; ">
                <span class="icon is-small"><i class="fa fa-link"></i></span> Mode de paiement
              </a>
            </li>
            <li>
              <a href="#" style="font-size: 17px; color: white; ">
                <span class="icon is-small"><i class="fa fa-link"></i></span> Terifs actes médicaux
              </a>
            </li>
            <li>
              <a href="#" style="font-size: 17px; color: white; ">
                <span class="icon is-small"><i class="fa fa-link"></i></span> Types de dépenses
              </a>
            </li>
          </ul>
        </li>
        <li>
          <a href="#" class="" style="font-size: 20px; color: white;">
            <span class="icon"><i class="fa fa-table"></i></span> Facturarion
          </a>

          <ul>
            <li>
              <a href="#" style="font-size: 17px; color: white; ">
                <span class="icon is-small"><i class="fa fa-link"></i></span> Liste des factures
              </a>
            </li>
          </ul>
        </li>
        <li>
          <a href="#" class="" style="font-size: 20px; color: white;">
            <span class="icon"><i class="fa fa-table"></i></span> Imageries
          </a>

          <ul>
            <li>
              <a href="#" style="font-size: 17px; color: white; ">
                <span class="icon is-small"><i class="fa fa-link"></i></span> Liste des factures
              </a>
            </li>
          </ul>
        </li>
        <li>
          <a href="#" class="" style="font-size:20px; color: white;">
            <span class="icon"><i class="fa fa-info"></i></span> About
          </a>
        </li>
      </ul>
    </aside>

    <div class="column is-6 mt-5">
      <div class="columns">
        <div class="column">
          <label for="">Protocole</label>
          <b-field label="" label-position="inside" type="text">
            <b-input placeholder="Protocole" rounded expanded></b-input>
          </b-field>
        </div>
      </div>

      <div class="columns">
        <div class="column">
          <label for="">Nombre de séances</label>
          <b-field label="" label-position="inside" type="text">
            <b-input placeholder="Nombre de séances" rounded expanded></b-input>
          </b-field>
        </div>
      </div>
      <div class="columns">
        <div class="column">
          <label for="">Rythme</label>
          <b-field label="" label-position="inside" type="text">
            <b-input placeholder="Rythme" rounded expanded></b-input>
          </b-field>
        </div>
      </div><br>
      <div class="columns">
        <div class="column">
          <div class="level-item">
            <button class="button is-fullwidth button">
              <span class="icon"><i class="mdi mdi-gamepad-round-outline"></i></span>
              <div></div>
              Annuler
            </button>
          </div>
        </div>
      </div>
      <div class="columns">
        <div class="column">
          <div class="level-item">
            <button class="button is-fullwidth btn">
              <span class="icon"><i class="mdi mdi-gamepad-round-outline"></i></span>
              <div></div>
              Ajouter
            </button>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
<script>
export default {

}
</script>

<style>
.sidebar{
  background-color: rgb(0, 135, 68);
}
.menu-label{
  font-size: 20px;
  font-weight: bold;
}
.is-active{
  background-color:rgb(0, 92, 47) !important;
  border-radius: 30px !important;
}
.menu-list a:hover{
  background-color: rgb(0, 92, 47) !important;
  border-radius: 30px !important;
}
.btn{
  background-color: rgb(0, 135, 68);
  border-radius: 30px !important;
  color: white;
}
.btn:hover{
  color: white;
  background-color:rgb(0, 92, 47) !important;

}
.button{
  border-radius: 30px !important;
}
</style>

