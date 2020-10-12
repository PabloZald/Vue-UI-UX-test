<template>
  <div class="navbar-container">
    <div class="navbar-content">
        <div class="navbar-item">
            <router-link to="/">
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-home"><path d="M3 9l9-7 9 7v11a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2z"></path><polyline points="9 22 9 12 15 12 15 22"></polyline></svg>
                <p><small>Home</small></p> 
            </router-link>
        </div>
        <div class="navbar-item">
            <router-link to="/restaurant-detail">
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-search"><circle cx="11" cy="11" r="8"></circle><line x1="21" y1="21" x2="16.65" y2="16.65"></line></svg>
                <p><small>Search</small></p> 
            </router-link>
        </div>
        <div class="navbar-item">
            <router-link to="/restaurant-detail">
                <svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" class="feather feather-check" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><g stroke="#fff"><path d="M20.12 21.528V3.232H4.966l-.092 18.3 1.824-2.505 1.917 2.549 1.917-2.549 1.918 2.549 1.917-2.549 1.917 2.549 1.917-2.549 1.917 2.549" stroke-width="1.4630813999999999"/><path d="M8.087 14.834h8.826M8.087 9.052h8.826" stroke-width="1.52071794" stroke-linejoin="miter"/></g></svg>
                <p><small>Orders</small></p> 
            </router-link>
        </div>
        <div class="navbar-item">
            <router-link to="/restaurant-detail">
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-user"><path d="M20 21v-2a4 4 0 0 0-4-4H8a4 4 0 0 0-4 4v2"></path><circle cx="12" cy="7" r="4"></circle></svg>
                <p><small>Account</small></p> 
            </router-link>
        </div>

     </div>
  </div>
</template>

<script>
export default {
  name: 'BottomTabNavigator',
}
</script>



