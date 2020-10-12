<template>
  <div class=home>
    <div class="homeHeader">
      <div class="headerBg">
        <div class="home-title">
          <h1 class="text-accent mb-2">Your majesty,</h1>
          <h2 class="font-weight-light">what would you like to eat?</h2>
        </div>
        <div class="scroll-menu">
            <router-link to="/restaurant-detail">
              <div class="scroll-item bg-secondary-accent">
                  <div class="scroll-img-container">
                    <img class="scroll-img" src='../assets/italian-category-thumbnail.png' />
                  </div>
                  <div class="menu-text">
                    <p class="text-primary"><b><small>Italian</small></b></p>
                  </div>
              </div>
            </router-link>

            <router-link to="/restaurant-detail">
              <div class="scroll-item">
                  <div class="scroll-img-container">
                    <img class="scroll-img" src='../assets/mexican-category-thumbnail.png' />
                  </div>
                  <div class="menu-text">
                    <p><small>Mexican</small></p>
                  </div>
              </div>
            </router-link>

            <div class="scroll-item">
                <div class="scroll-img-container">
                  <img class="scroll-img" src='../assets/chinese-category-thumbnail.png' />
                </div>
                <div class="menu-text">
                  <p><small>Chinese</small></p>
                </div>
            </div>

            <div class="scroll-item">
                <div class="scroll-img-container">
                  <img class="scroll-img" src='../assets/italian-category-thumbnail.png' />
                </div>
                <div class="menu-text">
                  <p><small>Italian</small></p>
                </div>
            </div>

            <div class="scroll-item" >
                <div class="scroll-img-container">
                  <img class="scroll-img" src='../assets/chinese-category-thumbnail.png' />
                </div>
                <div class="menu-text">
                  <p><small>Chinese</small></p>
                </div>
            </div>
            <div class="scroll-item" >
                <div class="scroll-img-container">
                  <img class="scroll-img" src='../assets/mexican-category-thumbnail.png' />
                </div>
                <div class="menu-text">
                  <p><small>Mexican</small></p>
                </div>
            </div>

            
            <div class="scroll-item">
                <div class="scroll-img-container">
                  <img class="scroll-img" src='../assets/italian-category-thumbnail.png' />
                </div>
                <div class="menu-text">
                  <p><small>Italian</small></p>
                </div>
            </div>

            <div class="scroll-item" >
                <div class="scroll-img-container">
                  <img class="scroll-img" src='../assets/chinese-category-thumbnail.png' />
                </div>
                <div class="menu-text">
                  <p><small>Chinese</small></p>
                </div>
            </div>
            <div class="scroll-item" >
                <div class="scroll-img-container">
                  <img class="scroll-img" src='../assets/mexican-category-thumbnail.png' />
                </div>
                <div class="menu-text">
                  <p><small>Mexican</small></p>
                </div>
            </div>

            <div class="scroll-item">
                <div class="scroll-img-container">
                  <img class="scroll-img" src='../assets/italian-category-thumbnail.png' />
                </div>
                <div class="menu-text">
                  <p><small>Italian</small></p>
                </div>
            </div>

            <div class="scroll-item" >
                <div class="scroll-img-container">
                  <img class="scroll-img" src='../assets/chinese-category-thumbnail.png' />
                </div>
                <div class="menu-text">
                  <p><small>Chinese</small></p>
                </div>
            </div>
            <div class="scroll-item" >
                <div class="scroll-img-container">
                  <img class="scroll-img" src='../assets/mexican-category-thumbnail.png' />
                </div>
                <div class="menu-text">
                  <p><small>Mexican</small></p>
                </div>
            </div>
        </div>
      </div>
    </div>

    <main class="main mb-4">
      <h3 class="mb-3">Popular choices</h3>
      <div class="home-container-list">
        <router-link to="/restaurant-detail">
          <div class="home-list-item">
            <div class="home-item-container">
              <img class="home-item-cover" src='../assets/restaurant-cover-thumbnail.png' />
              <div class="home-item-logo-container">
                <div class="home-item-logo-frame">
                  <p class="text-accent logo-text text-secondary-accent">B</p>
                </div>
              </div>
            </div>
            <div class="home-item-info mt-2">
              <p class="mb-3 text-center text-secondary-accent"><b>Bambinos pizzeria</b></p>
              <div class="home-item-info-footer">
                <div class="item"> 
                  <img class="coriander-left icon-sm" src='../assets/star.svg' />
                  <p class="ml-1 d-inline-block"><small>2250</small></p>
                </div>
                <div class="item"> 
                  <img class="d-inline-block" src='../assets/delivery.svg' />
                  <p class="ml-1 d-inline-block"><small>Free delivery</small></p>
                </div>
              </div>
            </div>
          </div>
        </router-link>

        <router-link to="/restaurant-detail">
          <div class="home-list-item">
            <div class="home-item-container">
              <img class="home-item-cover" src='../assets/2-cover-thumbnail.png' />
              <div class="home-item-logo-container">
                <div class="home-item-logo-frame">
                  <p class="text-accent logo-text text-secondary-accent">N</p>
                </div>
              </div>
            </div>
            <div class="home-item-info mt-2">
              <p class="mb-3 text-center text-secondary-accent"><b>Napoletanos restaurant</b></p>
              
              <div class="home-item-info-footer">
                <div class="item"> 
                  <img class="coriander-left icon-sm" src='../assets/star.svg' />
                  <p class="ml-1 d-inline-block"><small>2083</small></p>
                </div>
                <div class="item"> 
                  <img class="d-inline-block" src='../assets/delivery.svg' />
                  <p class="ml-1 d-inline-block"><small>$3 - $5</small></p>
                </div>
              </div>
            </div>
          </div>
        </router-link>

        <router-link to="/restaurant-detail">
          <div class="home-list-item">
          <div class="home-item-container">
            <img class="home-item-cover" src='../assets/3-cover-thumbnail.png' />
            <div class="home-item-logo-container">
              <div class="home-item-logo-frame">
                <p class="text-accent logo-text text-secondary-accent">S</p>
              </div>
            </div>
          </div>
          <div class="home-item-info mt-2">
            <p class="mb-3 text-center text-secondary-accent"><b>Sicilian Palace</b></p>
            <div class="home-item-info-footer">
              <div class="item"> 
                <img class="coriander-left icon-sm" src='../assets/star.svg' />
                <p class="ml-1 d-inline-block"><small>47</small></p>
              </div>
              <div class="item"> 
                <img class="d-inline-block" src='../assets/delivery.svg' />
                <p class="ml-1 d-inline-block"><small>$3 - $5</small></p>
              </div>
            </div>
          </div>
          </div>
        </router-link>

      </div>
    </main>
  <BottomTabNavigator />
  </div>
</template>

<script>

import BottomTabNavigator from '@/components/BottomTabNavigator.vue'

export default {
  name: 'Home',
  components: {
    BottomTabNavigator,
  }
}
</script>
