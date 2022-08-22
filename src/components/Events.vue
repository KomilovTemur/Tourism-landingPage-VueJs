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
          <div class="cart box domestic">
            <h2>For Domestic</h2>
            <a href="#">Start trip taday</a>
          </div>
        </div>
        <div class="col-md-6">
          <div class="cart box international">

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

.domestic {}
</style>