<template>
    <div class='items'>
        <li>All</li>
        <li>Images</li>
        <li>Videos</li>
        <li>Maps</li>
        <li>News</li>
        <li>|</li>
        <li>MSN</li>
        <li>Office</li>
        <li>Outlook.com</li>
    
    <div class='right'>
        <li>Sign in</li>
        <li><img class='userpic' src="../assets/Images/user.png" alt=""></li>
        <li>63</li>
        <li><img class='scorepic' src="../assets/Images/score.png" alt=""></li>
        <li><img class='menupic' src="../assets/Images/menu.png" alt=""></li>

    </div>

    </div>

    
</template>

<script>
export default {
    name: 'TopBar'
}
</script>

<style scoped>
.buffer {
    display: inline;
    margin-right: 600px;
}
.items li{
    color: white;
    display: inline;
    margin-right: 35px;
    font-size: 14px;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; 
}
.right {
display: inline;
float: right;

}
li.right {
    float: right;
}

img.userpic {
    height: 33px;
      vertical-align: middle;
      margin-left: -25px;

}

img.scorepic {
    height: 33px;
      vertical-align: middle;
      margin-left: -25px;

}
img.menupic {
    height: 16px;
      vertical-align: middle;
      margin-left: -15px;

}
</style>