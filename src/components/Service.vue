<template>
  <div><br><br><br><br>
    <div>
      <h2 class="heading">OFFERINGS TO MY CLIENTS</h2>
    </div>
    <div>
      <p class="subheading">
        If you are looking at blank cassettes on the web, you may be very
        confused at the difference <br>
        in price. You may see some for as low as $.17
        each.
      </p>
    </div><br><br><br>
    <div>
      <div class="card-group">
        <div class="card" >
          <img
            class="card-img-top"
            src="../assets/web.jpg"
            alt="Card image cap"
          />
          <div class="card-body">
            <h5 class="card-title">Web Design</h5>
            <p class="card-text">
              This is a wider card with supporting text below as a natural
              lead-in to additional content. This content is a little bit
              longer.
            </p>
            <p class="card-text">
              <small class="text-muted">Last updated 3 mins ago</small>
            </p>
          </div>
        </div>
        <div class="card">
          <img
            class="card-img-top"
            src="../assets/database.png"
            alt="Card image cap"
          />
          <div class="card-body">
            <h5 class="card-title">Database Management</h5>
            <p class="card-text">
              This card has supporting text below as a natural lead-in to
              additional content.
            </p>
            <p class="card-text">
              <small class="text-muted">Last updated 3 mins ago</small>
            </p>
          </div>
        </div>
        <div class="card">
          <img
            class="card-img-top"
            src="../assets/data.jpg"
            alt="Card image cap">
          <div class="card-body">
            <h5 class="card-title">Data Structure</h5>
            <p class="card-text">
              This is a wider card with supporting text below as a natural
              lead-in to additional content. This card has even longer content
              than the first to show that equal height action.
            </p>
            <p class="card-text">
              <small class="text-muted">Last updated 3 mins ago</small>
            </p>
          </div>
        </div>
        
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Service",
};
</script>

<style scoped>
.heading {
  text-align: center;
}

.subheading {
    text-align: center;
}

.card {
    padding: 40px;
    border: none;
   
}

.card img {
    height: 250px;
}
</style>