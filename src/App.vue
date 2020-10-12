<template>
  <div id="app">
    <div id="nav">
    </div>
    <router-view/>
  </div>
</template>

<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Kumbh+Sans:wght@300;400;700&family=Sansita+Swashed:wght@700&display=swap');
$primary: rgb(57,51,64);
$primaryAccent: rgb(242,100,87);
$secondaryAccent: rgb(242,181,107);
$thirdAccent: rgb(60,70,90);
$lightestColor: rgb(101,89,111);
$gradientTop: rgb(73,65,82);
$darkestColor: rgb(35,31,40);

.mb-1{margin-bottom: 0.5rem;}

.mb-2{margin-bottom: 1rem;}

.mb-3{margin-bottom: 1.5rem;}

.mb-4{margin-bottom: 2.5rem;}

.mt-1{margin-top: .75rem;}

.mt-2{margin-top: 2rem;}

.mt-3{margin-top: 2rem;}

.mt-4{margin-top: 3rem;}

.mt-5{margin-top: 4rem;}

.ml-1{margin-left: .5rem;}

.ml-2{margin-left: 1rem;}

.mr-2{margin-right: 1rem;}

.font-weight-bold{font-weight: 700;}

.font-weight-light{font-weight: 300;}

*{margin:0; padding:0;}

body{background-color: $primary};

.text-primary{color: $primary;} 

.text-accent{font-family: 'Sansita Swashed', cursive;} 

.text-secondary-accent{color: $secondaryAccent;}

.bg-secondary-accent{background-color: $secondaryAccent!important;}

#app {
  font-family: 'Kumbh Sans', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  // text-align: center;
  color: white;
}

main{padding: 15px;}

.navbar-top-container{
  width: 100%;
  position: absolute;
  top:0;
  text-align: center;
  .navbar-top-content{
    display: flex;
    justify-content: space-between;
    padding: 20px;
    .header-icon{
      display: flex;
        a {
          color: white;
          text-decoration: none;
          &.router-link-exact-active{
            font-weight: bold;
          }
        }
      }
    }
  }
.navbar-container{
  width: 100%;
  background-color: $primary;
  position: fixed;
  bottom:0;
  text-align: center;
  z-index: 100;
  .navbar-content{
    display: flex;
    justify-content: space-between;
    padding: 20px;
    .navbar-item{
        display: flex;
        a {
          color: white;
          text-decoration: none;
          &.router-link-exact-active{
            color: $primaryAccent;
            font-weight: bold;
        }
      }
    }
  }
}
.homeHeader {
  height: 375px;
  .headerBg{
  padding-top: 40px;
  border-radius: 0 0 1rem 1rem;
  height: 250px;
  background-color:$primaryAccent;
  }

  .home-title{
    padding: 0 20px;
  }
  .scroll-menu {
      overflow-x: auto;
      display: flex;
      margin-top: 17px;
      height: 250px;
      &.scroll-menu::-webkit-scrollbar{
        width:0;
        scrollbar-width: none; /* Firefox 64 */
      }

    a {
        color: white;
        text-decoration: none;
        &.router-link-exact-active{
          font-weight: bold;
        }
      }
    .scroll-item{
        background-color: $thirdAccent;
        height: 175px;
        width:115px;
        border-radius: 1rem;
        margin: 20px 15px;
        box-shadow: 0 15px 25px $darkestColor;
        .scroll-img-container{
          width: 100%;
          height: 130px;
          overflow: hidden;
          border-radius: 1rem 1rem 0 0;
          .scroll-img{
            height: 130px;
          }
        }
        .menu-text{
          display: flex;
          align-items: center;
          text-align: center;
          justify-content: center;
          height:45px;
        }
    }
  }
}


.detailHeader {
  height: 250px;
  background-color:$primaryAccent;
  background: url("./assets/coverRestaurant.jpg");
  background-attachment: fixed;
  background-position: top;
  background-repeat: no-repeat;
  background-size: contain;
  position:relative;
  border-radius: 0 0 6rem 6rem;
  .logo-container{
    .logoFrame{
      height:200px;
      width:200px;
      position:absolute;
      bottom:-210px;
      left: 50%;
      transform: translate(-50%, -50%);
    }
    .coriander {
      height:50px;
      width:50px;
      position:absolute;
      bottom:-50px;
    }
    .coriander-right{
      right: 15%;
    }
    .coriander-left{
      left: 15%;
      transform: scaleX(-1);
    }
  }
}
.info-container{
  margin-top: 6rem;
  padding: 0 20px;
  .info-content{
    display: flex;
    justify-content: space-between;
  }
}
.menu-row{
  margin-top: 1rem;
  padding: 1rem 25px;
  border-bottom: 2px solid $darkestColor;
}
.container-list{
  width: 100%;
  .list-item{
    padding: 25px 15px;
    align-items: center;
    background: rgb(72,64,81);
    background: linear-gradient(-180deg, $gradientTop 0%, $primary 100%);
    border-top: 2px solid $lightestColor;
    border-bottom: 2px solid $darkestColor;
    display: flex;
    .item-thumbnail{
      height: 150px;
      width: 150px;
    }
  }
}
.home-container-list{
  width: 100%;
  margin-top: 3rem;
  display: flex;
  flex-direction: column;
  a {
        color: white;
        text-decoration: none;
         display: flex;
        justify-content: center;
        &.router-link-exact-active{
          font-weight: bold;
        }
    }
  .home-list-item{
    align-items: center;
    min-height: 300px;
    width:100%;
    max-width: 347px;
    margin-bottom: 3rem;
    background: rgb(72,64,81);
    background: linear-gradient(-180deg, $gradientTop 0%, $primary 100%);
    border-top: 2px solid $lightestColor;
    border-radius: 1rem;
    box-shadow: 0 5px 10px $darkestColor, 0 15px 40px$darkestColor;
    .home-item-container{
      position:relative;
      height: 175px;
      width:100%;
      &.home-item-container .home-item-cover {
        height: 100%;
        width: 100%;
        object-fit: cover;
        -webkit-mask-size: contain;
        -webkit-mask-repeat: no-repeat;
        mask-size: contain;
        mask-repeat: no-repeat;
      }
      .home-item-cover{
        -webkit-mask-image: url("./assets/restaurant-item-img-mask.png");
        mask-image: url("./assets/restaurant-item-img-mask.png");
        position: absolute;
        top:-20px;
      }
      .home-item-logo-frame{
        height: 100px;
        width: 100px;
        z-index:10;  
        position: absolute;
        bottom:-70px;
        left: 50%;
        transform: translate(-50%, -50%);
        background: url('./assets/logoFrame.svg');
        background-repeat: none;
        background-size:cover;
        .logo-text{
          font-size: 3rem;
          text-align: center;
          line-height: 90px;
        }
      }
    }
    .home-item-info{
        .home-item-info-footer{
          padding: 0 15px;
          display: flex;
          justify-content: space-between;
        }
    }
  }
}
.text-center{text-align: center;}
.d-inline-block{display:inline-block}
.icon-sm{
  height:20px;
  width:20px;
}
@media screen and (min-width: 992px) {
  .home-container-list  {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    a {
      width: 30%;
    }
  }
  .home-list-item {
    align-items: center;
    width: 25%;
  }
  .detailHeader {
    height: 350px;
    background-position: center;
    background-size: cover;
    .coriander-left {
      left: 40%!important;
    }
    .coriander-right {
      right: 40%!important;
    }
  }
}
</style>

