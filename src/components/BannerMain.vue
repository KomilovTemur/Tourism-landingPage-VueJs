<template>
  <!-- banner -->
  <div class="banner">
    <nav>
      <div class="logo">
        <a href="/"><img src="@/assets/images/logo.svg" alt="Logo"></a>
      </div>
      <ul class="navLinks m-0">
        <li>
          <a href="#home">Home</a>
        </li>
        <li>
          <a href="#home">Events</a>
        </li>
        <li>
          <a href="#home">About</a>
        </li>
        <li>
          <a href="#home">Blog</a>
        </li>
        <li>
          <a href="#home">Contact</a>
        </li>
      </ul>
      <div class="phoneNumber">
        <a href="tel:+1(000)000000"><i class="fa-solid fa-phone"></i>+1 (000) 000 000</a>
      </div>
    </nav>
    <div class="hero">
      <div class="row">
        <div class="col-md-6 first">
          <div class="texts">
            <h3 style="color: #fff;">
              <p class="m-0 d-inline" style="color: #F0C53E;">Life is a journey</p>, not a <br> destination
            </h3>
            <p class="m-0" style="color: #fff;">Let's start your journey with us, your dream will <br> come true...
            </p>
          </div>
          <div class="buttonGroup">
            <a href="#Destinations" class="link">Explore destinations</a>
            <button class="play-btn">
              <i class="fa-solid fa-circle-play"></i>
              Watch how it works
            </button>
          </div>
        </div>
        <div class="col-md-6 second">
          <div class="image"></div>
          <div class="plan">
            <i class="fa-regular fa-calendar-days"></i>
            <div class="text">
              <b class="m-0 p-0">250k</b>
              <p class="m-0 p-0">Plan Your Trip</p>
            </div>
          </div>
          <div class="upcoming">
            <img src="@/assets/images/bag.svg" alt="">
            <div>
              <b>Upcoming Trips</b>
              <p class="m-0">Today at 12.00 PM</p>
              <a href="#">Join Now</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

</template>


<style scoped>
.banner {
  position: relative;
  top: 0;
  width: 100%;
  min-height: 100vh;
  padding: 60px 100px;
}

nav {
  display: flex;
  align-items: center;
  justify-content: space-between;
}

nav>.navLinks {
  list-style-type: none;
  display: flex;
  width: 689px;
  align-items: center;
  justify-content: space-around;
}

nav>.navLinks>li>a {
  text-decoration: none;
  font-size: 22px;
  color: #fff;
  font-weight: 400;
}

nav>.phoneNumber>a {
  text-decoration: none;
  color: #fff;
  background-color: #b25a59;
  width: 334px;
  height: 80px;
  display: flex;
  align-items: center;
  justify-content: center;
  border-radius: 80px;
  font-size: 22px;
}

nav>.phoneNumber>a>i {
  padding: 0 20px 0 0;
  font-size: 30px;
}

.hero>.row>.first {
  position: relative;
  top: 25vh;
  width: 704px;
  height: 404px;
}

.hero>.row>.first>.texts>h3 {
  width: 661px;
  height: 148px;
  font-size: 54px;
  margin-bottom: 20px;
}

.hero>.row>.first>.texts {
  margin-bottom: 63px;
}

.hero>.row>.first>.buttonGroup {
  display: flex;
  align-items: center;
}

.hero>.row>.first>.buttonGroup>.link {
  text-decoration: none;
  color: #fff;
  background-color: #b25a59;
  width: 334px;
  height: 80px;
  display: flex;
  align-items: center;
  justify-content: center;
  border-radius: 80px;
  font-size: 24px;
  font-weight: 600;
}

.hero>.row>.first>.buttonGroup>.play-btn {
  margin-left: 26px;
  display: flex;
  align-items: center;
  justify-content: space-between;
  text-decoration: none;
  font-size: 24px;
  width: 343px;
  color: #fff;
  border: none;
  background: none;
}

.hero>.row>.first>.buttonGroup>.play-btn>i {
  font-size: 80px;
  background-color: #23bdee;
  color: #fff;
  border-radius: 50%;
}

.hero>.row>.second {
  width: 704px;
  height: 404px;
}

.hero>.row>.second>.image {
  position: absolute;
  width: 910px;
  height: 745px;
  left: 915px;
  top: 150px;
  background: url("../assets/images/plane.svg");
}

.hero>.row>.second>.plan {
  position: absolute;
  width: 300px;
  height: 100px;
  left: 898px;
  top: 339px;
  background: rgba(255, 255, 255, 0.8);
  /* backdrop-filter: blur(20px); */
  border-radius: 20px;
  padding: 25px;
  display: flex;
  align-items: center;
}

.hero>.row>.second>.plan>i {
  background-color: #ee5060;
  color: #fff;
  width: 50px;
  height: 50px;
  display: flex;
  align-items: center;
  justify-content: center;
  border-radius: 8px;
  font-size: 25px;
}

.hero>.row>.second>.plan>.text {
  padding-left: 35px;
}

.hero>.row>.second>.plan>.text>b {
  font-size: 30px;
  font-weight: 700;
  color: #595959;
}

.hero>.row>.second>.plan>.text>p {
  font-size: 20px;
  font-weight: 600;
  color: #545567;
}

.hero>.row>.second>.upcoming {
  position: absolute;
  width: 390px;
  height: 187px;
  left: 895px;
  top: 665px;
  background: rgba(255, 255, 255, 0.8);
  /* backdrop-filter: blur(20px); */
  border-radius: 20px;
  display: flex;
  padding: 25px 16px;
}

.hero>.row>.second>.upcoming>img {
  width: 82px;
  height: 93px;
}

.hero>.row>.second>.upcoming>div {
  padding: 0 10px;
}

.hero>.row>.second>.upcoming>div>b {
  font-size: 24px;
  font-weight: 700;
  color: #595959;
  display: block;
  padding-bottom: 12px;
}

.hero>.row>.second>.upcoming>div>p {
  font-size: 20px;
  font-weight: 600;
  color: #545567;
  display: block;
  padding-bottom: 17px;
}

.hero>.row>.second>.upcoming>div>a {
  text-decoration: none;
  color: #fff;
  background-color: #b25a59;
  width: 180px;
  height: 50px;
  display: flex;
  align-items: center;
  justify-content: center;
  border-radius: 80px;
  font-size: 20px;
  font-weight: 700;
}

.destination>h2 {
  color: #7f2736;
  padding-top: 35px;
}
</style>