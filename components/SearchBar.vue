<template>
  <div id="searchbar">
    <svg class="logo" fill="white" viewBox="0 0 124 50" role="banner">
      <path
        d="M50 40v-29.994h8.533a9.326 9.326 0 0 1 6.17 1.9 6.155 6.155 0 0 1 2.28 4.957 7.294 7.294 0 0 1-1.383 4.437 7.43 7.43 0 0 1-3.8 2.676v.084a7.635 7.635 0 0 1 4.852 2.29 7.047 7.047 0 0 1 1.819 5.03 7.843 7.843 0 0 1-2.76 6.233 10.274 10.274 0 0 1-6.968 2.387zm3.514-26.813v9.683h3.6a6.831 6.831 0 0 0 4.54-1.391 4.842 4.842 0 0 0 1.646-3.924q0-4.372-5.752-4.371zm0 12.842v10.79h4.769a7.148 7.148 0 0 0 4.8-1.464 5.013 5.013 0 0 0 1.705-4.016q0-5.312-7.236-5.312zm23.439-14.462a2.129 2.129 0 0 0-.644-1.558 2.172 2.172 0 0 0-1.6-.645 2.121 2.121 0 0 0-1.589.655 2.147 2.147 0 0 0-.634 1.548 2.119 2.119 0 0 0 .644 1.611 2.314 2.314 0 0 0 3.159-.02 2.114 2.114 0 0 0 .664-1.591m-.583 7.146h-3.407v21.275h3.407zm23.342 8.258a10.115 10.115 0 0 0-1.838-6.482 6.467 6.467 0 0 0-5.351-2.289 7.641 7.641 0 0 0-6.981 4.051h-.084v-3.529h-3.408v21.278h3.408v-12.137a7.024 7.024 0 0 1 1.694-4.851 5.409 5.409 0 0 1 4.207-1.9q4.945 0 4.945 6.751v12.137h3.407zm24.053 11.323q0 11.7-11.219 11.7a15.416 15.416 0 0 1-6.9-1.475l.892-2.942a11.942 11.942 0 0 0 5.944 1.529q7.874 0 7.874-8.331v-2.352h-.084a7.958 7.958 0 0 1-7.313 4.093 8.192 8.192 0 0 1-7.708-4.966 13.015 13.015 0 0 1-1.1-5.507q0-5.442 2.65-8.642a8.737 8.737 0 0 1 7.094-3.2 6.936 6.936 0 0 1 6.378 3.449h.084v-2.93h3.407v19.574zm-3.407-7.916v-3.137a5.943 5.943 0 0 0-1.766-4.353 5.747 5.747 0 0 0-4.218-1.776 5.9 5.9 0 0 0-4.954 2.306 10.3 10.3 0 0 0-1.776 6.42 8.773 8.773 0 0 0 1.7 5.63 5.515 5.515 0 0 0 4.549 2.14 5.953 5.953 0 0 0 4.654-2.025 7.527 7.527 0 0 0 1.807-5.2"
      />
      <path d="M35 24.25l-22.177-7.761 4.338 10.82 6.923 3.225h10.916v-6.284z" opacity=".7" />
      <path d="M10 38.642v-35.142l-10-3.5v44.4l10 5.6 25-14.382v-11.368z" />
    </svg>
    <input class="bar" />
    <img class="cameraicon" src="../assets/icons/cameraicon.svg" />
    <svg class="searchicon" viewBox="0 0 25 25" enable-background="new 0 0 25 25">
      <path
        stroke="#007DAA"
        stroke-width="2.5"
        stroke-linecap="round"
        stroke-miterlimit="10"
        fill="none"
        d="M23.75 23.75l-9-9"
      />
      <circle
        stroke="#007DAA"
        stroke-width="2.5"
        stroke-linecap="round"
        stroke-miterlimit="10"
        cx="9"
        cy="9"
        r="7.75"
        fill="none"
      />
      <path fill="none" d="M25 25h-25v-25h25z" />
    </svg>
  </div>
</template>

<script>
export default {
  name: "SearchBar"
};
</script>

<style scoped>
#searchbar {
  margin-top: 11%;
  margin-right: 30%;
}
input.bar {
  height: 55px;
  width: 50%;
  border-top-left-radius: 6px;
  border-bottom-left-radius: 6px;
  border: 1px transparent;
  margin-left: 25px;
  box-shadow: 0px 2px #777777;
  border-right: none;
  
}
svg.logo {
  float: left;
  width: 12%;
  height: 12%;
}
img.cameraicon {
  width: 2.2%;
  height: 2.2%;
  background-color: white;
  margin-top: 0px;
  vertical-align: middle;
  padding-left: 25px;
  padding-right: 15px;
  padding-top: 17px;
  padding-bottom: 16px;
  box-shadow: 0px 2px #777777;
  margin-bottom: 2px;

}
svg.searchicon {
  width: 2.2%;
  height: 2.2%;
  background-color: white;
  vertical-align: middle;
  padding-left: 5px;
  padding-right: 15px;
  padding-top: 17px;
  padding-bottom: 16px;
  border-top-right-radius: 6px;
  border-bottom-right-radius: 6px;
  box-shadow: 0px 2px #777777;
  margin-bottom: 2px;

}
</style>