# Calculator
#  Meet my calculator I made with only HTML and CSS. The entire process took about a week to come up with the Design,coding,Reasearch and Scripting.
<html>
 <p>Also pls Check out my blog</p>
  <a href="journeyofcod.blogspot.com">
    <button id="bingo" medium="">Link to My BLog </button>
  </a> 
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Calculator</title>
    <link rel="stylesheet" href="index.css">
    
</head>
<body>
    
</body>
<div class="container">
    
    <div class="calculator">
        <form>
            
            <div class="display">
                <input type="text" name="display">
            </div>
            
            <div>
                <input type="button" value="AC" onclick="display.value=''">
                <input type="button" value="DE">
                <input type="button" value="." onclick="display.value+='.'">
                <input type="button" value="/" onclick="display.value+='/'">

            </div>
            <div>
                <input type="button" value="7" onclick="display.value+='7'">
                <input type="button" value="8" onclick="display.value+='8'">
                <input type="button" value="9" onclick="display.value+='9'">
                <input type="button" value="*"onclick="display.value+='*'">

            </div>
            <div>
                <input type="button" value="4" onclick="display.value+='4'">
                <input type="button" value="5" onclick="display.value+='5'">
                <input type="button" value="6" onclick="display.value+='6'">
                <input type="button" value="-" onclick="display.value+='-'">

            </div>
            <div>
                <input type="button" value="1" onclick="display.value+='1'">
                <input type="button" value="2" onclick="display.value+='2'">
                <input type="button" value="3" onclick="display.value+='3'">
                <input type="button" value="+" onclick="display.value+='+'">

            </div>
            <div>
                <input type="button" value="00" onclick="display.value+='00'">
                <input type="button" value="0" onclick="display.value+='0'">
                <input type="button" value="=" onclick="display.value=eval(display.value)" class="equal">

            </div>
      
        </form>

<style>
 .container{
    flex-direction: column;
    overflow: hidden;
    justify-content: center;
    display: flex;
    align-items: center;
    width: 100;
    height: 100vh;



}
.calculator{
    background-color: #16141d;
    padding: 20px;
    border-radius: 10px;
}
.calculator form input{
border: 0;
outline: 0;
width: 60px;
height: 60px;
border-radius: 10px;
background: #24212e;
font-size: 20px;
color: #ffff;
cursor: pointer;
margin: 10px;
}
form .display{
display: flex;
justify-content: flex-end;
margin: 20px 0;
color: #312d3f;
}
form .display input{
text-align: right;
flex: 1;
font-size: 45px;
box-shadow: none;

}
form input.equal{
    width: 145px;
    
 }

</style>




    </div>
</div>
<script>
    window.alert("lets calculate")
</script>
</html>
 
</html>
