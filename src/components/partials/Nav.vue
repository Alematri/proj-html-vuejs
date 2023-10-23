<script>
  export default{
  name: 'Nav'
}
</script>

<template>

  <nav>
    <div class="container">
      <div class="row">

        <div class="col logo">
          <img src="../../assets/img/Others/logo.png">
        </div>

        <div class="col-6 d-flex justify-content-end">
          <ul class="d-flex">
            <li><a href="#">Home</a></li>
            <li><a href="#">Services</a></li>
            <li><a href="#">About</a></li>
            <li><a href="#">Videos</a></li>
            <li><a href="#">Blog</a></li>
            <li><a href="#">Store </a><span>new</span></li>
          </ul>
        </div>

        <div class="col actions d-flex align-items-center">
          <button class="btn btn-primary" type="submit">Schedule a workout</button>
          <a href="#"><i class="fa-solid fa-cart-shopping"></i></a>
          <a href="#"><i class="fa-solid fa-magnifying-glass"></i></a>
        </div>

      </div>
    </div>
  </nav>
 
</template>

<style lang="scss" scoped>

  @use '../../scss/partials/vars' as *;

  a{
    text-decoration: none;
    color: $gray;
    &:hover{
      color: $white;
    }
  }

  nav{
    background-color: $black;
    position: fixed;
    top: 0;
    width: 100%;
    z-index: 99;
    .container{
      height: 100px;
      color: $gray;
      .row{
        height: 100%;
        .col{
          height: 100%;
        }
        .logo{
          line-height: 100px;
          img{
            height: 33px;
          }
        }
        .col-6{
          line-height: 100px;
          height: 100%;
          ul{
            li{
              list-style: none;
              margin-right: 44px;
              font-size: 15px;
              span{
                padding: 2px 5px 4px 4px;
                background-color: $yellow;
                color: $black;
                border-radius: 3px;
              }
            }
          }
        }
        .actions{
          height: 100px;
          button{
            border-radius: 20px;
            padding: 11px 26px;
            font-size: 13px;
            margin: auto 0;
            border: 0;
            &:hover{
              background-color: $red;
            }
          }
          i{
            margin-left: 44px;
          }
        }
      }
    }
  }
</style>