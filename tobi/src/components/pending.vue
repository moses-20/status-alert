<template>
  <div class="pending">
    <img alt="logo" src="../assets/download.jpg" />
    <div class="container">
      <div class="text">
        <img alt="pending" src="../assets/outline_pending_black_24dp.png" />
        <h4> Dear Customer </h4>
        <div>
          <p>Your reported complaint with incident ID: <strong>is pending </strong>.</p>
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
.pending {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
.container {
  background-color: white;
  border: 1px solid #d81912;
  padding: 8px;
  border-radius: 12px;
}
.text {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  margin: 30px 30px;
}

</style>
