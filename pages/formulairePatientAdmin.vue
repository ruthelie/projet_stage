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
            <span class="icon"><i class="fa fa-table"></i></span> Param??trage
          </a>
          <ul>
            <li>
              <a href="#" style="font-size: 19px; color: white; ">
                <span class="icon is-small"><i class="fa fa-link"></i></span> M??dicament
              </a>
              <ul>
                <li>
                  <a href="#" style="font-size: 17px; color: white; ">
                    <span class="icon is-small"><i class="fa fa-link"></i></span> Liste des m??dicaments
                  </a>
                </li>
              </ul>
            </li>
            <li>
              <a href="#" style="font-size: 19px; color: white; ">
                <span class="icon is-small"><i class="fa fa-link"></i></span> Protocoles des re??ducations
              </a>
              <ul>
                <li>
                  <a href="#" style="font-size: 17px; color: white; ">
                    <span class="icon is-small"><i class="fa fa-link"></i></span> Liste des protocoles de re??ducation
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
                <span class="icon is-small"><i class="fa fa-link"></i></span> Terifs actes m??dicaux
              </a>
            </li>
            <li>
              <a href="#" style="font-size: 17px; color: white; ">
                <span class="icon is-small"><i class="fa fa-link"></i></span> Types de d??penses
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
        <label for="">Le num??ro du dossier du patient</label>
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
        <label for="">Votre pr??nom</label>
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
        <label for="">Votre numer??ro de t??l??phone</label>
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
        <label for="">Votre civilit??</label>
        <b-field label="" label-position="inside" type="text">
          <b-input placeholder="Civilit??" rounded expanded></b-input>
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
          <label for="">Choisissez votre genre :</label>
        </div>
        <div class="column">
          <div class="block">
            <b-radio v-model="radio"
                name="name"
                native-value="Flint">
                Homme
            </b-radio>
            <b-radio v-model="radio"
                name="name"
                native-value="Flint">
                Femme
            </b-radio>
        </div>
      </div>
    </div>

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
          data() {
              return {
                  radio: 'default'
              }
          }
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

