<template>
  <div class="nav">
    <div class="space"></div>
    <button class="button-21" role="button">Home</button>
    <button class="button-21" role="button">Projects</button>
    <button class="button-21" role="button">About us</button>
    <button class="button-21" role="button">Contact page</button>
  </div>
</template>

<script>
export default {
  
}
</script>

<style>
  .nav {
    align-items: center;
    border-style: solid;
    border-width: 1px;
    border-radius: 50px;
    border-color: grey;
    box-shadow: rgba(17, 17, 26, 0.1) 0px 4px 16px, rgba(17, 17, 26, 0.1) 0px 8px 24px, rgba(17, 17, 26, 0.1) 0px 16px 56px;
    width: 50%;
    height: 50px;
    margin-left: 25%;
  }

  .space {
    width: 75px;
    height: auto;
    display: inline-block;
  }
/* CSS */
.button-21 {
  margin-top: 0.5%;
  margin-right: 0.5%;
  margin-left: 7%;
  align-items: center;
  appearance: none;
  background-color: #fdf03e;
  background-image: linear-gradient(1deg, #966f04, #a8f049 99%);
  background-size: calc(100% + 20px) calc(100% + 20px);
  border-radius: 100px;
  border-width: 0;
  box-shadow: none;
  box-sizing: border-box;
  color: #FFFFFF;
  cursor: pointer;
  display: inline-flex;
  font-family: CircularStd,sans-serif;
  font-size: 1rem;
  height: auto;
  justify-content: center;
  line-height: 1.5;
  padding: 6px 20px;
  position: relative;
  text-align: center;
  text-decoration: none;
  transition: background-color .2s,background-position .2s;
  user-select: none;
  -webkit-user-select: none;
  touch-action: manipulation;
  vertical-align: top;
  white-space: nowrap;
}

.button-21:active,
.button-21:focus {
  outline: none;
}

.button-21:hover {
  background-position: -20px -20px;
}

.button-21:focus:not(:active) {
  box-shadow: rgba(40, 170, 255, 0.25) 0 0 0 .125em;
}
</style>
