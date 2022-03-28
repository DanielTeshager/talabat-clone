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
               <a href="#"> Offers </a>
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
               <a href="#" class="btn btn-outline"> Login </a>
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
</style>