<template>
<div>
  <a href="https://vodafone.com.gh" alt="" target="_blank">
    <img class="vodafone" alt="logo" src="../assets/vodafone.png" />
  </a>
  <div class="pending">
    <img class="logo" alt="logo" src="../assets/download.jpg" />
    <div class="container">
      <img class="image" alt="pending" src="../assets/outline_pending_black_24dp.png" />
      <h4> Dear Customer </h4>
      <div>
        <p>
          Your reported complaint with incident ID: <strong class="strong">is pending </strong>.
          We are working speedily to resolve it. To follow up on your complaint
          please send an SMS to 655.
        </p>
      </div>
    </div>
  </div>
  <footer>
    <p> Vodafone Ghana does not share your data with any party. </p>
    <p> 
      Read our <a href="https://vodafone.com.gh/personal/privacy-portal" target="_blank" > Privacy Policy </a>  here.
      <a href="https://vodafone.com.gh/terms-and-conditions" target="_blank" > Terms and Conditions </a>  apply.
    </p> 
  </footer>
</div>
</template>

<script>
export default {
  name: 'pending',
}
</script>

<style scoped>
.pending {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
.logo {
  width: 100px;
}
.vodafone {
  position: fixed;
  top: 0;
  left: 0;
  width: 50px;
}
.strong {
  color: red;
}
.container {
  background-color: white;
  border: 1px solid black;
  padding: 20px;
  border-radius: 12px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  width: 35%;
  margin: 0 0 110px 50px;
}
.image { 
  -webkit-filter: brightness(91%) contrast(126%) invert(21%) sepia(99%) hue-rotate(355deg) saturate(6463%);
  filter: brightness(91%) contrast(126%) invert(21%) sepia(99%) hue-rotate(355deg) saturate(6463%);
}
a {
  color: red;
  text-decoration: none;
}
footer {
  background: black;
  color: white;
  padding: 20px;
  font-size: 13px;
  clear: both;
  position: absolute;
  bottom: 0;
  width: 96%;
  height: 50px;
}
</style>
