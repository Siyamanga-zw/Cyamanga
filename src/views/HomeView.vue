<template>
  <div id="home">
    <img class="img img-fluid" src="https://i.postimg.cc/mDQSKN0t/photo-1517694712202-14dd9538aa97-ixlib-rb-4-0.jpg" alt="firstimg" />
    <div class="container text-center">
      <div class="row align-items-start">
        <div class="col-md-6" id="text">
          <h1 class="animate">Hello, I am Siyamanga Zweni</h1>
          <h3 class="right">An aspiring <span>full stack developer</span></h3>
          <a href="/about">More about me</a>
        </div>
        <div class="col-md-6 mt-4 mt-md-0" id="profile">
          <img class="img-fluid" src="https://i.postimg.cc/6p6WK7pN/C12-C2-Siyamanga-Zweni-2-removebg-preview.png" alt="" loading="lazy"/>
        </div>
      </div>
    </div>
  </div>
</template>

<script></script>

<style scoped>
#home {
  margin: 0;
  background-color: rgba(222, 227, 229, 255);
}

.animate {
  animation: backInLeft;
  animation-duration: 2s;
}

.right {
  animation: backInRight;
  animation-duration: 2s;

}

#home img {
  width: 100%;
  height: 40%;
  object-fit: center;
  object-position: center;
}

#profile img {
  object-fit: cover;
  margin-top:30px;
  width: 150px;
  height: 200px;
  border-radius: 50%;
  border: 3px solid black;
  transform: translateY(-70px);
}

#text {
  font-weight: bold;
  color: black;
}

#text h1 {
  font-size: 50px;
}

#text h3 {
  font-size: 30px;
}

#text a {
  text-decoration: none;
  border: 2px solid#999fa0;
  padding: 8px;
  background-color: #999fa0;
  color: black;
  border-radius: 12px;
  box-shadow: 5px 10px 0px black;
}

p {
  font-size: 20px;
}

@media(width < 770px) {
  #home img {
    width: 100%;
    height: 30%;
    object-fit: center;
    object-position: center;
  }

  #home {
    margin: 0;
    background-color: rgba(222, 227, 229, 255);

  }

  #profile img {
    object-fit: cover;
    width: 170px;
    height: 150px;
    border-radius: 50%;
    border: 3px solid black;
    transform: translateY(-70px);
  }

  #profile img {
    transform: translateY(3px)
  }
}
</style>
