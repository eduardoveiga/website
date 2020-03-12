<template>
  
  <!-- <div class="Shellhub-LP-1280"> -->

    <div class="textura">
          <div class="menu">
            
            <b-navbar :fixed-top="false"  :is-transparent="true">
              
              <template slot="brand">
                <!-- <b-navbar-item tag="router-link" :to="{ path: '/' }"> -->
                  <img class="ShellHub-Logo-Negativo" src="@/static/logo-inverted.png">
                <!-- </b-navbar-item> -->
              </template>
              
              <template slot="start">
              </template>

              <template slot="end">
                <b-navbar-item class="vbar-iten" href="#">
                    Documentation
                </b-navbar-item>
                <b-navbar-item class="vbar-iten" href="#">
                    Login
                </b-navbar-item>
                <b-navbar-item class="vbar-iten" href="#">
                    Register
                </b-navbar-item>
              </template>
            
            </b-navbar>

          </div>

          <div class="about">

            <div class="title">
              Get seamless remote access to any Linux device
            </div>

            <div class="title-content">
              ShellHub is a modern SSH server for remotely accessing Linux devices via command line (using any SSH client) or web-based user interface. 
            </div>

            <div class="resgister">
                <div class="rectangle_1">
                  <div class="font_ret">
                    Resgister
                  </div>
                </div>
                <div class="rectangle_2">
                  <div class="font_ret">
                    <br> 
                    <img src="@/static/bullet-01.png">
                  </div>

              </div>
            </div>
          </div>

    </div>

</template>

<style>

body{
  padding-top: 0px!important;
}

/* change navbar background color */
nav.navbar {
  z-index: 2;
  background: transparent;
  /* margin-top: 41px; */
  margin-left: 55px;
  margin-right: 149px;
}

.textura {
  z-index: 1;
  /* width: 1280px; */
  height: 771px;
  background-image: url('../static/nuvem.png'), url('../static/forkme-dark-background.png');
  background-repeat: no-repeat;
  /* float: right; */
  background-position: top right;
}

.Content {
  /* width: 1170px; */
  height: 987px;
  background-color: #333640;
  margin-left: 55px;
  margin-right: 55px;
  /* margin-top: -17px; */
}

.Content-Rectangle {
  /* width: 1170px; */
  height: 34px;
  border-radius: 20px 20px 0px 0px;
  background-color: #3d414d;
  margin-top: -17px;
}

.Nuvem {
  height: 755px;
  object-fit: contain;
  opacity: 0.9;
  float: right;
  background-repeat: no-repeat;
  background-position: right;
  position:relative;
  z-index: 0;
}

.forkme_dark_background {
  max-width: 149px;
  height: 149px;
  object-fit: contain;
  /* transform: rotate(90deg); */
  /* background: url('../static/forkme-dark-background.png'); */
  background-repeat: no-repeat;

  float: right;
  background-position: right;
  position: absolute;
  z-index: 1;
  /* position:absolute; */
}

.ShellHub-Logo-Negativo {
  width: 200px;
  height: 52px;
}

.vbar-iten{
  font-family: RobotoSlab;
  font-size: 18px;
  font-weight: normal;
  font-stretch: normal;
  font-style: normal;
  line-height: 1.67;
  letter-spacing: 0.5px;
  color: #dce3ff;
  margin-left: 40px;
}

.menu{
  /* margin-top: 41px; */

  height: 93px;
}

.about{
  /* margin-top: 111px; */
  /* margin-left: 155px; */
  max-width: 1170px;
  height: auto;
  margin: 111px auto 0 auto;
  /* margin: 20px auto 0 auto; */

}

.title{
  max-width: 670px;
  min-height: 130px;
  font-family: OverpassMono;
  font-size: 44px;
  font-weight: bold;
  font-stretch: normal;
  font-style: normal;
  line-height: 1.48;
  letter-spacing: -3px;
  color: #ffffff;
}

.title-content{
  max-width: 495px;
  height: 90px;
  font-family: RobotoSlab;
  font-size: 18px;
  font-weight: normal;
  font-stretch: normal;
  font-style: normal;
  line-height: 1.67;
  letter-spacing: 0.5px;
  color: #ffffff;
  margin-bottom: 50px;
}

.register{
  width: 185px;
  height: 40px;
  opacity: 0.9;
}

.rectangle_1 {
  width: 163px;
  height: 40px;
  opacity: 0.9;
  background-color: #394573;
display: inline-block;
  

  /* position: relative; */
  /* display: block; */
}

.rectangle_2 {
  width: 31px;
  height: 40px;
  opacity: 0.9;
  background-color: #667acc;
  display: inline-block;

  /* position: relative; */
  /* display: block; */
}


.font_ret{
  font-family: RobotoSlab;
  font-size: 18px;
  font-weight: normal;
  font-stretch: normal;
  font-style: normal;
  line-height: 1.67;
  letter-spacing: 0.5px;
  /* text-align: center; */
  color: #ffffff;
  width: 100%;
  height: 100%;

  display: flex;
  justify-content: center;
  align-items: center;
}

.font_ret_2{
  font-family: RobotoSlab;
  font-size: 18px;
  font-weight: normal;
  font-stretch: normal;
  font-style: normal;
  line-height: 1.67;
  letter-spacing: 0.5px;
  /* text-align: center; */
  color: #ffffff;
  width: 100%;
  height: 100%;

  display: flex;
  justify-content: center;
  align-items: center;
/* bullet-01.png */
  background-image: url('../static/bullet-01.png');
  background-repeat: no-repeat;
  /* float: right; */
  background-position: center;
}
</style>