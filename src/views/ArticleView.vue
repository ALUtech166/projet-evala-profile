<template>
     <div class="body">
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


          <div class="main">
               <h1>Acheter un article</h1>
               <p>On va ecrire quelque chose ici</p>
          </div>

          <shop-view></shop-view>

     </div>
</template>

<script>
     import ShopView from './ShopView.vue'
     export default {
          components: {
               ShopView
          }

     }
</script>

<style scoped>
     h1 {
          color: #006A4A;
          font-size: 45px;
     }

     p {
          color: #006A4A;
          font-size: 20px;
     }

     .header-search {
          background-image: linear-gradient(to right, #ffcc00, #006a4a3d);
          padding: 5rem;
     }

     .body {
          font-family: 'jost';
     }

     .main {
          padding: 2rem;
     }
</style>