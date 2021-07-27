<template>
  <div>
  <img class="logo" alt="logo" src="../assets/download.jpg" />
  <div class="resolve">
    <img alt="resolve" src="../assets/progress.png" />
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
</template>

<script>
export default {
  name: 'resolved',
}
</script>


<style scoped>
.resolve {
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  margin-top: 10%;
}
.logo {
  position: fixed;
  top: 0;
  left: 0;
}

.text {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

</style>
