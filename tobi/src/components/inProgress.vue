<template>
  <div>
    <a href="https://vodafone.com.gh" alt="" target="_blank">
      <img class="vodafone" alt="logo" src="../assets/vodafone.png" />
    </a>
    <img class="logo" alt="logo" src="../assets/download.jpg" />
  
    <div class="progress">
      <div class="card">
        <img class="loading" alt="loading" src="../assets/loading.png" />
        <div>
          <h4> Dear Customer </h4>
          <p>
            Your reported complaint with incident ID: <strong class="strong">is in progress</strong>.
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
  name: 'inProgress',
}
</script>

<style scoped>
.progress {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
.logo {
  position: absolute;
  top: 130px;
  left: 380px;
  width: 100px;
}
.vodafone {
  position: fixed;
  top: 0;
  left: 0;
  width: 50px;
}
.loading {
  width: 100px;
}
.card {
  background-color: white;
  border: 1px solid black;
  border-radius: 12px;
  width: 35%;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  margin-top: 100px;
  margin-bottom: 100px;
  padding: 0 60px;
  padding-bottom: 20px;
}
.strong {
  color: #ce9603;
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
@media only screen and (max-width: 1200px) {
  .logo {
    left: auto;
    top: auto;
    
  }

}
</style>
