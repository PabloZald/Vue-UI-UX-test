<template>
  <div class=RestaurantDetail>
    <div class="detailHeader"> 
      <TopTabNavigator />

      <div class="logo-container">
        <img class="logoFrame" src='../assets/logoFrameLg.svg' />
        <img class="coriander coriander-left" src='../assets/coriander.svg' />
        <img class="coriander coriander-right" src='../assets/coriander.svg' />
      </div>
    </div>
    <div class="info-container">
      <h1 class="text-accent text-center">Bambinos pizzeria</h1>
      <div class="info-content mt-2">
        <div class="reviews">
          <img class="coriander-left icon-sm" src='../assets/star.svg' />
          <p class="ml-1 d-inline-block"><small>2250+</small></p>
        </div>
        <div class="delay">
          <img class="coriander-left icon-sm" src='../assets/time.svg' />
          <p class="ml-1 d-inline-block"><small>30-45'</small></p>
        </div>
        <div class="delivery">
          <img class="d-inline-block" src='../assets/delivery.svg' />
          <p class="ml-1 d-inline-block"><small>Free delivery</small></p>
        </div>
      </div>
      <div class="info-content mt-1">
        <div class="delivery">
          <img class="d-inline-block" src='../assets/greendot.svg' />
          <p class="ml-1 d-inline-block"><small>Open 8:30 - 22:00</small></p>
        </div>
        <div class="delivery">
          <p class="d-inline-block"><small><b>More</b></small></p>
          <img class="ml-1 d-inline-block icon-sm" src='../assets/chevron-right.svg' />          
        </div>
      </div>
    </div>
    
    <p class="menu-row"><small>Menu</small></p>
    <div class="container-list">
      <div class="list-item">
        <img class="item-thumbnail" src='../assets/pizza-thumbnail.png' />
        <div class="item-info ml-2">
          <p class="mb-1"><b>Pepperoni pizza</b></p>
          <p class=""><small>from $9.99</small></p>
          <div class="">
          <img class="coriander-left icon-sm" src='../assets/star.svg' />
          <p class="ml-1 d-inline-block"><small>58</small></p>
          </div>
        </div>
      </div>

      <div class="list-item">
        <img class="item-thumbnail" src='../assets/spaghetti-thumbnail.png' />
        <div class="item-info ml-2">
          <p class="mb-1"><b>Spaghetti bolognese</b></p>
          <p class=""><small>from $7.99</small></p>
          <div class="">
          <img class="coriander-left icon-sm" src='../assets/star.svg' />
          <p class="ml-1 d-inline-block"><small>53</small></p>
          </div>
        </div>
      </div>

      <div class="list-item">
        <img class="item-thumbnail" src='../assets/sausage-thumbnail.png' />
        <div class="item-info ml-2">
          <p class="mb-1"><b>Pasta in sausage</b></p>
          <p class=""><small>from $4.49</small></p>
          <div class="">
          <img class="coriander-left icon-sm" src='../assets/star.svg' />
          <p class="ml-1 d-inline-block"><small>33</small></p>
          </div>
        </div>
      </div>

      <div class="list-item">
        <img class="item-thumbnail" src='../assets/pastarolls-thumbnail.png' />
        <div class="item-info ml-2">
          <p class="mb-1"><b>Pasta rolls</b></p>
          <p class=""><small>from $7.49</small></p>
          <div class="">
            <img class="coriander-left icon-sm" src='../assets/star.svg' />
            <p class="ml-1 d-inline-block"><small>63</small></p>
          </div>
        </div>
      </div>
    </div>
  <main class="main">
   
  </main>
  </div>
</template>


<script>
import TopTabNavigator from '@/components/TopTabNavigator.vue'

export default {
  name: 'RestaurantDetail',
  components: {
    TopTabNavigator
  }
}
</script>
