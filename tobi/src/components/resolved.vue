<template>
  <div class="resolve">
    <img alt="logo" class="logo" src="../assets/download.jpg" />
    <div class="vl" />
    <div class="container">
      <div class="text">
        <img alt="resolve" src="../assets/outline_check_circle_outline_black_24dp.png" />
        <h4> Dear Customer </h4>
        <div>
          <p>Your reported complaint with incident ID: <strong> has been Closed</strong>.</p>
          <p>For further details, please send an SMS to 655 for indivduals or email</p>
          <p>info.gh@vodafone.com for enterprise customers.</p>
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
}
.logo {
  margin-right: 5%;
}
.text {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  margin-left: 30px;
}
.vl {
  border-left: 1px solid black;
  height: 500px;
}
</style>
