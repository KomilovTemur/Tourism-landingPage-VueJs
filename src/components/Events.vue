<!-- eslint-disable -->
<template>
  <div class="container">
    <div class="events">
      <h2 class="events-title">
        <p class="d-inline m-0">Globally</p> Accepted
      </h2>
      <p class="m-0">Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum <br> has
        been the
        industry's
        standard dummy text ever since the 1500s, when an unknown <br> printer took a galley of type and scrambled it to
        make a
        type specimen book.
      </p>
      <div class="row">
        <div class="col-md-6">
          <div class="cart domestic">
            <div class="box">
              <h2>For Domestic</h2>
              <a href="#">Start trip taday</a>
            </div>
          </div>
        </div>
        <div class="col-md-6">
          <div class="cart international">
            <div class="box">
              <h2>For International</h2>
              <a href="#">Start trip taday</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
</script>

<style scoped>


/* Events */

.events {
  min-height: 100vh;
  display: flex;
  flex-direction: column;
}

.events>.events-title {
  font-size: 44px;
  font-weight: 600;
  text-align: center;
  padding-bottom: 44px;
  color: #2C2D32;
}

.events>.events-title>p {
  color: #7f2736;
}

.events>p {
  text-align: center;
  font-size: 24px;
  font-weight: normal;
  padding-bottom: 87px;
  color: #2C2D32;
}

.cart {
  width: 600px;
  height: 400px;
  border-radius: 20px;
  overflow: hidden;
  background-position: center;
  background-repeat: no-repeat;
}

.domestic {
  background-image: url('../assets/images/domestic.png');
}

.international {
  background-image: url('../assets/images/international.png');
}

.cart>.box {
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
  width: 100%;
  height: 100%;
  background-color: #7f2736e0;
  color: #fff;
}

.cart>.box>h2 {
  font-size: 32px;
  font-weight: 600;
  padding-bottom: 30px;
}

.cart>.box>a {
  display: block;
  border: 1px solid #fff;
  border-radius: 80px;
  width: 283px;
  height: 80px;
  font-size: 22px;
  font-weight: 500;
  text-decoration: none;
  color: #fff;
  display: grid;
  place-items: center;
  transition: all 0.5s ease;
}

.cart>.box>a:hover {
  transform: scale(1.1);
  font-size: 25px;
}
</style>