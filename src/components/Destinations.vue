<!-- eslint-disable -->
<!-- Destinations -->
<template>
  <div id="Destinations" class="destinations">
    <div class="title">
      <h2>
        <p class="d-inline">Check Our Best </p>Promotional Tour
      </h2>
      <p class="mb-5">Lorem Ipsum is simply dummy text of the printing and typesetting <br> industry. Lorem Ipsum has
        been the
        industry's standard dummy text <br> ever since the 1500s, when an unknown printer took a galley of type <br>
        and 
        scrambled it to make a type specimen book.</p>
    </div>
    <div class="row">
      <div class="col-md-4" v-for="dest in destinations">
        <div class="destination">
          <img :src="dest.src" :alt="dest.name">
          <h2>{{ dest.name }}</h2>
        </div>
      </div>
    </div>
  </div>

</template>

<script>
export default {
  data() {
    return {
      destinations: [
        { src: require("../assets/images/Bejing.png"), name: "Bejing" },
        { src: require("../assets/images/Turkey.png"), name: "Turkey" },
        { src: require("../assets/images/Pakistan.png"), name: "Pakistan" }
      ]
    }
  }
}
</script>