<template>
  <div class="resolve">
    <img alt="logo" src="../assets/download.jpg" />
    <div class="text">
      <img alt="resolve" src="../assets/outline_pending_black_24dp.png" />
      <h4> Dear Customer </h4>
      <div>
        <p>Your reported complaint with incident ID: <strong>is pending </strong>.</p>
        <p>We are working speedily to resolve it. To follow up on your complaint</p>
        <p>please send an SMS to 655.</p>
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
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

.text {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  border: 1px solid black;
  border-radius: 50px;
  padding: 20px;
  margin-top: 30px;
}

</style>
