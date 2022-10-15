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
                <span class="icon is-small"><i class="fa fa-link"></i></span>Antecedents
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
        <label for="">Le numéro du dossier du patient</label>
        <b-field label="" label-position="inside" type="text">
          <b-input placeholder="Numero du dossier patient" rounded expanded></b-input>
        </b-field>
      </div>
      <div class="column">
        <label for="">Votre nom</label>
        <b-field label="" label-position="inside" type="text">
          <b-input placeholder="Nom" rounded expanded></b-input>
        </b-field>
      </div>
    </div>

    <div class="columns">
      <div class="column">
        <label for="">Votre prénom</label>
        <b-field label="" label-position="inside" type="text">
          <b-input placeholder="Prenom" rounded expanded></b-input>
        </b-field>
      </div>
      <div class="column">
        <label for="">Votre adresse</label>
        <b-field label="" label-position="inside" type="text">
          <b-input placeholder="Adresse" rounded expanded></b-input>
        </b-field>
      </div>
    </div>

    <div class="columns">
      <div class="column">
        <label for="">Votre numeréro de téléphone</label>
        <b-field label="" label-position="inside" type="text">
          <b-input placeholder="Telephone" rounded expanded></b-input>
        </b-field>
      </div>
      <div class="column">
        <label for="">Votre email</label>
        <b-field label="" label-position="inside" type="email">
          <b-input placeholder="Email" rounded expanded></b-input>
        </b-field>
      </div>
    </div>

    <div class="columns">
      <div class="column">
        <label for="">Votre date de naissance</label>
        <b-field label="" label-position="inside" type="text">
          <b-input placeholder="Date de naissance" rounded expanded></b-input>
        </b-field>
      </div>
      <div class="column">
        <label for="">Votre Age</label>
        <b-field label="" label-position="inside" type="text">
          <b-input placeholder="Age" rounded expanded></b-input>
        </b-field>
      </div>
    </div>

    <div class="columns">
      <div class="column">
        <label for="">Votre civilité</label>
        <b-field label="" label-position="inside" type="text">
          <b-input placeholder="Civilité" rounded expanded></b-input>
        </b-field>
      </div>
      <div class="column">
        <label for="">Le nom du medecin traitant</label>
        <b-field label="" label-position="inside" type="text">
          <b-input placeholder="Nom du medecin traitant" rounded expanded></b-input>
        </b-field>
      </div>
    </div>
    <div class="columns">
      <div class="column">
        <b-field label="" label-position="inside" type="text">
          <b-input placeholder="Nom" rounded expanded></b-input>
        </b-field>
      </div>
      <div class="column">
        <b-field label="" label-position="inside" type="text">
          <b-input placeholder="Adresse" rounded expanded></b-input>
        </b-field>
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
label{
  font-size: 20px;
}
</style>

