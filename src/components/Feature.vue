<template>
    <div>
      <div class="contentRectangle Content"></div>

      <div class="content">
        
        <div class="blockSymbolTitle">

          <div class="symbolShellHub">
            <img src="@/static/symbol-shell.png">
          </div>
          <div class="titleContent-contentFeture titleContent">
            Every feature you've  come to expect
          </div>

        </div>

        <div class="groupDetails">
          <!-- Primeiro bloco -->
          <div class="details">  
              <div class="bullet">
                <img src="@/static/bullet-01.png">
              </div>

              <div class="blockContentFeature">
                <div class="titleFeature">
                  {{data[0].title}}
                </div>
                <div class="contentFeature">
                  {{data[0].content}}
                </div>
              </div>
          </div>
          <!-- Segundo bloco -->
          <div class="details">
              <div class="bullet">
                <img src="@/static/bullet-01.png">
              </div>

              <div class="blockContentFeature">
                <div class="titleFeature">
                  {{data[1].title}}
                </div>
                <div class="contentFeature">
                  {{data[0].content}}
                </div>
              </div>
          </div>

          <div class="details">  
              <div class="bullet">
                <img src="@/static/bullet-01.png">
              </div>

              <div class="blockContentFeature">
                <div class="titleFeature">
                  {{data[2].title}}
                </div>
                <div class="contentFeature">
                  {{data[0].content}}
                </div>
              </div>
          </div>
          <!-- Segundo bloco -->
          <div class="details">
              <div class="bullet">
                <img src="@/static/bullet-01.png">
              </div>

              <div class="blockContentFeature">
                <div class="titleFeature">
                  {{data[3].title}}
                </div>
                <div class="contentFeature">
                  {{data[0].content}}
                </div>
              </div>
          </div>

        </div>
      
      </div>

    </div>

</template>

<script>
export default {
  data() {
    return {
      data: [
        { 'id': 1, 'title': 'Secure Remote Connections', 'content': 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla ultricies pharetra odio vitae.', },
        { 'id': 2, 'title': 'Full IoT device management', 'content': 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla ultricies pharetra odio vitae.', },
        { 'id': 3, 'title': 'Batch release application', 'content': 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla ultricies pharetra odio vitae.', },
        { 'id': 4, 'title': 'Restrict access to login IP', 'content': 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla ultricies pharetra odio vitae.', },
        { 'id': 5, 'title': 'Software-only solution', 'content': 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla ultricies pharetra odio vitae.', },
        { 'id': 6, 'title': 'Customize API Access', 'content': 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla ultricies pharetra odio vitae.', },
      ],
    }
  }
}
</script>


<style>


.contentRectangle {
  max-width: 1170px;
  height: 34px;
  margin: -68px auto 0 auto;
  background-color: #3d414d;
  border-radius: 20px 20px 0px 0px;
}

.content {
  max-width: 1170px;
  height: 987px;
  margin: auto;
  background-color: #333640;
  border-radius: 0px 0px 20px 20px;
}

.blockSymbolTitle{
  max-width: 514px;
  height: 117px;
  margin-top: 50px;
  margin-left: -20px;
  display: inline-block;
  z-index:4;
}

.symbolShellHub {
  max-width: 111px;
  height: 83px;
  object-fit: contain;
  display: inline-block;
}

.titleContent-contentFeture {
  width: 317px;
  height: 80px;
  margin-top: 37px;
  margin-left: 58px;
  font-size: 28px;
  line-height: 1.43;
  letter-spacing: -2px;
  display: inline-block;
}

.groupDetails{
  max-width: 757px;
  max-height: 160px;
  margin-right: 125px;
  margin-top: 103px;
  float: right;
}

.details{
  max-width: 337px;
  height: 100%;
  margin-left: 55px;
  margin-bottom: 50px;
  display: inline-block;
}

.bullet {
  width: 20px;
  height: 160px;
  margin-top: 4px;
  margin-right: 8px;  
  float: left;
  text-align: center;
}

.blockContentFeature {
  max-width: 317px;
  height: 100%;
  margin-left: 0px;
}

.titleFeature {
  max-width: 317px;
  height: 28px;
  font-family: RobotoSlab;
  font-size: 22px;
  font-weight: bold;
  font-stretch: normal;
  font-style: normal;
  line-height: 1.27;
  letter-spacing: 0.5px;
  color: #ffffff;
}

.contentFeature{
  max-width: 317px;
  height: 84px;
  margin-top: 17px;
  font-family: RobotoSlab;
  font-size: 18px;
  font-weight: normal;
  font-stretch: normal;
  font-style: normal;
  line-height: 1.56;
  letter-spacing: 0.5px;
  color: #ffffff;
}

</style>