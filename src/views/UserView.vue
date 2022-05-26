<template>
     <div class="home">
          <div class="header-search">
               <div class="input-group mb-3">
                    <input type="text" class="form-control" placeholder="Recherche" aria-label="Recipient's username"
                         aria-describedby="basic-addon2">
                    <div class="input-group-append">
                         <span class="input-group-text" id="basic-addon2">Recherche <i
                                   class="fa-solid fa-magnifying-glass"></i></span>
                    </div>
               </div>
          </div>

          <div class="body">
               <h1>Profil Utilisateur</h1>
               <p>Vos informations de compte Utilisateur</p>
          </div>

          <base-card>
          
               <table class="table">
                    <tbody>
                         <tr>
                              <th scope="row">Nom</th>
                              <td>NEVERDIE</td>
                         </tr>
                         <tr>
                              <th scope="row">Prenoms</th>
                              <td>Leinad's</td>
                         </tr>

                         <tr>
                              <th scope="row">Adresse de Provenance</th>
                              <td>Haiti</td>
                         </tr>

                         <tr>
                              <th scope="row">Pays de Provenance</th>
                              <td>Jamaique</td>
                         </tr>
                         <tr>
                              <th scope="row">Date de naissance</th>
                              <td>15 novembre 1990</td>
                         </tr>
                         <tr>
                              <th scope="row">Email</th>
                              <td>leinads@neverdie.com</td>
                         </tr>

                         <tr>
                              <th scope="row">Mot de passe</th>
                              <td>Jamaique</td>
                         </tr>

                         <tr>
                              <th scope="row">Numero piéce identité</th>
                              <td>1145-5007-8455</td>
                         </tr>

                         <tr>
                              <th scope="row">Numero Téléphone</th>
                              <td>+12 8890556775</td>
                         </tr>

                    </tbody>
               </table>


               <div class="" style="text-align: right">
                    <button type="button" class="btn btn-danger">Quitter</button>
               </div>

   
          </base-card>

     </div>
</template>

<script>
import BaseCard from '@/components/UI/BaseCard.vue'
     export default {
          components: {
               BaseCard
          }
     }
</script>

<style scoped>
     .home {
          font-family: 'jost';
     }

     th {
          text-align: left;
          font-size: 20px;
     }

     td {
          text-align: right;
          font-size: 20px;
     }

     h1 {
          color: #006A4A;
          font-size: 45px;
     }

     p {
          color: #006A4A;
          font-size: 15px;
     }

     tr {
          border: 1px #ffcc00;
     }

     .header-search {
          background-image: linear-gradient(to right, #ffcc00, #006a4a3d);
          padding: 5rem;
     }

     .body {
          padding: 2rem;
     }
</style>