<template>
  <div class="home">
    <header>
      <div class="header-container container">
        <div class="logo">
          <img src="../assets/logo.png" alt="talballt logo">
        </div>
          <nav>
          <ul class="main-nav">
             <li>
               <a href="#">Offers </a>
             </li>
             <li>
               <a href="#">Become a partner</a>
             </li>
             <li>
               <a href="#">All Restaurants</a>
             </li>
              <li>
               <a href="#"> EN </a>
             </li>
              <li>
               <a href="#" class="btn btn-outline">Login </a>
             </li>
          </ul>
        </nav>
      </div>
      
    </header>
  <main class="container">
    <div class="main-header">
     <div class="bread_crumbs">

      <ul>
        <li>
          <a href="#">Home</a>
        </li>
        <li>
          <a href="#">Restaurants</a>
        </li>
        <li>
          <a href="#">Restaurant name</a>
        </li>
      </ul>
    </div>
    <div class="main-header-content">
      <div class="restaurant-info">
        <div class="resutarant-logo">
          <img src="../assets/800_pizza.webp" alt="800 Degree Pizz">
        </div>
        <div class="restaurant-description">
          <h2>800 Degrees Pizz</h2>
          <p>
            In Dubai Marina UAE <br> Pizza, American, Italian <br> Min.order: AED 10.00
          </p>
        </div>
      </div>
      <div class="payment-and-opening">
        <div class="open-statu">close</div>
        <div class="payment-methods">
          <img src="../assets/click_to_pay_black.webp" alt="Click to pay">
          <img src="../assets/visa_blue.webp" alt="visa">
          <img src="../assets/logo-mastercard.svg" alt="mastercard">
          <img src="../assets/logo-cash.svg" alt="cash">
        </div>
      </div>
    </div>
     <div class="delivery-info-box">
          <p><span class="info-icon">i</span> Delivered by us, with live tracking</p>
        </div>
    </div>
    <div class="main-body">
      <div class="body-header">
        <nav>
          <ul class="body-nav">
            <li class="active">
              <a href="#">
                <span class="icon"><img src="../assets/icon_menu.svg"></span>Menu
                </a>
            </li>
            <li>
              <a href="#">
                <span class="icon"><img src="../assets/icon_reviews.svg"></span>Reviews
                </a>
            </li>
            <li>
              <a href="#">
                <span class="icon"><img src="../assets/icon_info_menu.svg"></span>Info
                </a>
            </li>
          </ul>
        </nav>
      </div>
      <div class="body-content">
        <div class="catogories">
          <div class="card">
            <h2 class="card-header">
              Categories
            </h2>
            <nav>
              <ul class="categories-nav">
                <li>
                  <a href="#">
                  Family Combos
                  </a>
                </li>
                <li>
                  <a href="#">
                    Appetizers
                  </a>
                </li>
                <li>
                  <a href="#">
                    Create Your Own Pizza
                  </a>
                </li>
                <li>
                  <a href="#">
                   10' Specialty Pies
                  </a>
                </li>
                <li>
                  <a href="#">
                  14' Specialty Pies
                  </a>
                </li>
                <li>
                  <a href="#">
                    Signature Sauces
                  </a>
                </li>
                <li>
                  <a href="#">
                   Beverages
                  </a>
                </li>
              </ul>
            </nav>
          </div>
        </div>
        <div class="menu-content">
          Menu content
        </div>
        <div class="cart">
          <div class="card">
            <h2 class="card-header">
              Your Cart
            </h2>
            <h3>800 Degrees Pizz <span> - Dubai Marina</span></h3>
              <div class="cart-content">
                <div class="cart-items-content">
                  <ul class="cart-items">
                    <li class="cart-item">
                      <div class="add-remove">
                        <span class="btn add btn-mini">+</span>
                        <span class="qty">1</span>
                        <span class="btn remove btn-mini">-</span>
                      </div>
                      <span class="menu-item">The TV Dinner <span i>i</span></span>
                      <span class="price">AED 20.00</span>
                      <span class="remove-item">(-)</span>
                    </li>
                    <li class="cart-item">
                      <div class="add-remove">
                        <span class="btn add btn-mini">+</span>
                        <span class="qty">1</span>
                        <span class="btn removen btn-mini">-</span>
                      </div>
                      <span class="menu-item">The TV Dinner <span i>i</span></span>
                      <span class="price">AED 20.00</span>
                      <span class="remove-item">(-)</span>
                    </li>
                    <li class="cart-item">
                      <div class="add-remove">
                        <span class="btn add btn-mini">+</span>
                        <span class="qty">1</span>
                        <span class="btn  remove btn-mini">-</span>
                      </div>
                      <span class="menu-item">The TV Dinner <span i>i</span></span>
                      <span class="price">AED 20.00</span>
                      <span class="remove-item">(-)</span>
                    </li>
                  </ul>
                </div>
              </div>
              <div class="cart-total">
                <div class="cart-total-item">
                  <p class="subtotal">
                    <span>Subtotal</span>
                    <span class="price">AED 20.00</span>
                  </p>
                   <p class="deliveryfee">
                    <span>Delivery Fee</span>
                    <span class="price">AED 5.00</span>
                  </p>
                   <p class="total">
                    <span>Total Amount</span>
                    <span class="price">AED 20.00</span>
                  </p>
                
                  <div class="checkout">
                       <a href="#" class="btn btn-large-green">
                    PROCEED TO CHECKOUT
                  </a>
                  </div>
                </div>
              </div>
        </div>
        </div>
      </div>
    </div>
  </main>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from "@/components/HelloWorld.vue";
export default {
  name: "Home",
  components: {
    // HelloWorld,
  },
};
</script>


<style>

*{
  margin: 0;
  padding: 0;
}
ul{
  list-style: none;
}
a{
  text-decoration: none;
  color: #000;
}
.container{
  max-width: 70%;
  margin: 0 auto;
}
header{
  background-color: rgb(255, 90, 0);
   padding: 15px 0;
}
.header-container{
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 0 20px;
}
.main-body{
  background-color: #fff;
 height: 100vh;
}
ul.main-nav{
  display: flex;
  justify-content: space-between;
  align-items: center;
  gap: 20px;
}
ul.main-nav li a{
  color: white; 
  font-size: 1.2rem;
}
.btn{
  background-color: rgb(255, 90, 0);
  color: white;
  padding: 10px 20px;
  border-radius: 5px;
  font-size: 1.2rem;
}
.btn-outline{
  color: rgb(255, 90, 0);
  padding: 10px 20px;
  border-radius: 5px;
  font-size: 1.2rem;
  border: 1px solid white;
}
.bread_crumbs{
  margin-bottom: 1.2rem;
}
.bread_crumbs ul{
  display: flex;
  justify-content: start;
  align-items: center;
  padding: 20px 20px;
}
.bread_crumbs ul li a{
  color: #444;
  font-size: .9rem;
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}
.bread_crumbs ul li::after{
  content: ">";
  padding: 0 15px;
}
.bread_crumbs ul li:last-child::after{
  content: "";
}
.bread_crumbs ul li a:hover{
  color: rgb(255, 90, 0);
}

main{
  box-shadow: -2px 18px 14px 2px rgba(0,0,0,0.7);
-webkit-box-shadow: -2px 18px 14px 2px rgba(0,0,0,0.7);
-moz-box-shadow: -2px 7px 10px 2px rgba(0,0,0,0.7);
padding: 0 20px;
}
.main-header-content{
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.restaurant-info{
  display: flex;
  gap: 10px;
  text-align: left;
}
.restaurant-info img{
  width: 120px;
  border: 1px solid #ccc;
}
.restaurant-info h2{
  font-size: 1.5rem;
  font-weight: 400;
  color: #444;
}
.restaurant-info h2:hover{
  color: rgb(255, 90, 0);
  cursor: pointer;
}
.restaurant-info p{
  font-size: 1rem;
  color: #444;
}
.payment-and-opening{
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  align-items: start;
  padding: 20px 0;
  min-height: 120px;
}
.payment-methods{
  display: flex;
  justify-content: space-around;
  align-items: center;
  min-width: 120px;
  max-width: 120px;
  gap: 2px;
}
.payment-methods img{
  max-width: 30px;
}

.delivery-info-box{
  text-align: left;
  background-color: rgb(254, 249, 245);
  padding: 10px 20px;
}
.body-nav{
  display: flex;
  min-width: 460px;
  gap: 20px;
  margin-top: 10px;
  align-items: baseline;
  max-height: 50px;
  border-bottom: 1px solid #ccc;
}
.body-nav li{
  max-width: 240px;
  width: 100%;
  display: flex;
  align-items: baseline;
  justify-content: center;
  padding: 10px 0;
}
.body-nav li.active{
  border-bottom: 4px solid rgb(255, 90, 0);
}
.body-nav li a span:first-child img{
  max-height: 20px;
}
.body-nav li a span{
  padding-right: 10px;
}
.body-nav li .icon img{
  width: 20px;
  max-height: 100%;
  display: inline-block;
}

/* Body Content */
.body-content{
  display: grid;
  grid-template-columns: 220px 1fr 290px;
}

/* Categories */
.categories-nav{
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  align-items: start;
  padding: 20px 10px;
  gap: 10px;
  border-radius: 2px;
  box-shadow: rgba(0, 0, 0, 0.12) 0px 2px 1px 0px, rgba(0, 0, 0, 0.14) 0px 1px 1px 0px, rgba(0, 0, 0, 0.02) 0px 1px 3px 0px;
}
.categories-nav li {
  text-align: left;
}

/* Cart */

.cart{
  border: 1px solid #ccc;
  height: 100%;
  text-align: left;
  overflow: auto;
  padding-bottom: 20px;
}
.cart .card-header{
 background-color: rgb(255, 90, 0);
 color: white;
 padding: 5px;
 font-size: 1.3rem;
}
.cart h3{
  font-size: 1.2rem;
  font-weight: 400;
  color: rgb(5, 3, 3);
  box-sizing: border-box;
  font-weight: 500;
  padding: 5px;
  border-bottom: 1px solid #cecece;
  box-shadow: rgba(0, 0, 0, 0.12) 0px 2px 1px 0px, rgba(0, 0, 0, 0.14) 0px 1px 1px 0px, rgba(0, 0, 0, 0.02) 0px 1px 3px 0px;
}
.cart h3 span{
  font-size: 1rem;
  font-weight: 400;
  color: #444;
}

/* Cart items */
.cart-items li{
  display: flex;
  /* justify-content: space-between; */
  align-items: center;
  padding: 10px 20px;
  border-bottom: 1px solid #ccc;
  gap: 5px;
  font-size: .8rem;
}

.cart-items span{
  display: inline-block;
}
.add-remove{
  display: flex;
  border: 1px solid #ccc;
  border-radius: 3px;
}
.cart-item .btn-mini{
    color: rgb(255, 90, 0);
    background: white;
    border-radius: 2px;
    font-size: .5rem;
    max-height: rem;
    max-width: 1.4rem;
    padding: 3px 5px;
  
}
.add-remove .qty{
  min-width: 20px;
  max-width: 50px;
  text-align: center;
}
.add-remove .add{
    border-inline-end: 1px solid rgb(224, 224, 224);
}
.add-remove .remove{
    border-inline-start: 1px solid rgb(224, 224, 224);
}
.cart-items-content{
  background-color: rgb(250, 250, 250);
}

/* totals */
.cart-total-item p{
  display: flex;
  justify-content: space-between;
  padding: 10px 20px;
}
.subtotal{
  color: #444;
  font-weight: 300;
}
.total{
  font-weight: 500;
}
.checkout{
  display: flex;
}
.btn-large-green{
   background: green;
    display: inline-block;
    margin: 0 auto;
    padding: 5px 10px;
    width: 81%;
}
</style>