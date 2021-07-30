<template>
  <div>
    <a href="https://vodafone.com.gh" alt="" target="_blank">
      <img class="vodafone" alt="logo" src="../assets/vodafone.png" />
    </a>
    <div class="resolve">
      <img alt="logo" class="logo" src="../assets/download.jpg" />
      <div class="container">
        <img class="image" alt="resolve" src="../assets/outline_check_circle_outline_black_24dp.png" />
        <h4> Dear Customer </h4>
        <div>
          <p>
            Your reported complaint with incident ID: <strong class="strong"> has been Closed</strong>.
            For further details, please send an SMS to 655 for indivduals or email
            info.gh@vodafone.com for enterprise customers.
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
  width: 100px;
}
.vodafone {
  position: fixed;
  top: 0;
  left: 0;
  width: 50px;
}
.strong {
  color: green;
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
  margin: 100px 0 130px 50px;
  width: 35%;
}
.container:hover {
  box-shadow: 0 8px 16px 0 rgba(0, 0, 0, 0.2);
}
.image { 
  -webkit-filter: brightness(111%) contrast(135%) invert(67%) sepia(35%) hue-rotate(75deg) saturate(4577%);
  filter: brightness(111%) contrast(111%) invert(67%) sepia(35%) hue-rotate(75deg) saturate(4577%);
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
