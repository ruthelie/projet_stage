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
    <div class="container column is-9">
      <main class="column">
        <div class="level">
          <div class="level-left">
            <div class="level-item">
              <div class="title">Liste des patients</div>
            </div>
          </div>
          <div class="column">
            <p class="control has-icons-left has-icons-right">
              <input class="input is-rounded" type="text" placeholder="Rechercher">
              <span class="icon is-small is-left">
                <i class="mdi mdi-magnify"></i>
              </span>
            </p>
          </div>
          <div class="level-right">
            <div class="level-item">
              <button class="button is-fullwidth btn">
                <span class="icon"><i class="mdi mdi-gamepad-round-outline"></i></span>
                <div></div>
                Ajouter
              </button>
            </div>
          </div>
        </div>
        <div id="app" class="container">

          <section>
              <b-table
                  :data="data">
                  <b-table-column field="id" label="Numero du dossier"></b-table-column>
                  <b-table-column field="Nom" label="Nom"></b-table-column>
                  <b-table-column field="Prénom" label="Prénom"></b-table-column>
                  <b-table-column field="Sexe" label="Sexe"></b-table-column>
                  <b-table-column field="Date de naissance" label="Date de naissance"></b-table-column>
                  <b-table-column field="Civilité" label="Civilité"></b-table-column>
                  <b-table-column field="CIN" label="CIN"></b-table-column>
                  <b-table-column field="Profession" label="Profession"></b-table-column>
                  <b-table-column field="Telephone" label="Telephone"></b-table-column>
                  <b-table-column field="Adresse" label="Adresse"></b-table-column>
                  <b-table-column field="Medecin traitant" label="Medecin traitant" ></b-table-column>
                  <b-table-column field="Email" label="Email"></b-table-column>
            </b-table>
          </section>
      </div>
      </main>
    </div>
</section>
</template>

<script>

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

