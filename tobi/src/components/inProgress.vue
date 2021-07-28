<template>
  <div>
  <img class="logo" alt="logo" src="../assets/download.jpg" />
  <div class="card">
  <div class="progress">
    
    <img class="image" alt="progress" src="../assets/progress.png" />
    
    <div class="text">
      <h4> Dear Customer </h4>
      <div>
        <p>Your reported complaint with incident ID: <strong>is in progress</strong>.</p>
        <p>We are working speedily to resolve it. To follow up on your complaint</p>
        <p>please send an SMS to 655.</p>
      </div>
    </div>
    </div>
  </div>
  </div>
</template>

<script>
export default {
  name: 'resolved',
}
</script>


<style scoped>
.progress {
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
}
.logo {
  position: fixed;
  top: 50px;
  left: 270px;
}
.card {
  background-color: white;
  border: 1px solid #ceca58;
  border-radius: 12px;
  width: 60%;
  margin: 10% 20%;
}
.text {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  margin: 60px 40px;
}
.image {
  margin: 60px 0 30px 30px;
}

</style>
