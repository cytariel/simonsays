 <!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>szymon says</title>

<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap.min.css">
<link rel="stylesheet" href=https://cdnjs.cloudflare.com/ajax/libs/animate.css/3.5.1/animate.min.css>
<link rel="stylesheet/less" type="text/css" href="./simon.less">
<script src="https://code.jquery.com/jquery-2.2.4.min.js" type="text/javascript"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/js/bootstrap.min.js" type="text/javascript"></script>
<script src="./less.js" type="text/javascript"></script>
<script src="./simon.js" type="text/javascript"></script>
<!--<link rel="stylesheet" href="./simon.css">-->
    
</head>
<body>

    <div class="container">
  <div class="row">
    <div class="col-md-12">
      <h1 class="text-center">BADUM-Tsssssssss</h1>
    </div>
  </div>
  <div class="row">
    <div class="col-md-12">
      <div class="gamefield">

        <div class="top-row">
          <div id="blue" class="gamebutton" onClick="addToPlayer(this.id)"></div>
        </div>
        <div class="middle-row">
          <div id="green" class="gamebutton" onClick="addToPlayer(this.id)"></div>
          <div id="gameNumber"><h2 id="clickNumber">0</h2></div>
          <div id="red" class="gamebutton" onClick="addToPlayer(this.id)"></div>
        </div>
        <div class="bottom-row">
          <div id="orange" class="gamebutton" onClick="addToPlayer(this.id)"></div>
        <div>
      </div>  
    </div>
  </div>
  
        <div class="row">
          <div class="col-md-12 text-center">
          <h4 class="black">Od nowa?</h4>
          <p class="btn text-center" data-dismiss="modal" onClick="newGame()"> <big>Reset!</big></p>
          </div>
        </div>
        
    </div>
  </div>
</div>
   

</body>

</html> 
