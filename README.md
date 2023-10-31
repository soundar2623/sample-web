# sample-web
basic.html
<!DOCTYPE html>
<html lang="en">
<head>
    <link rel="stylesheet" href="style.css">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <script>
        function welcome(){
          window.open("https://blackpekoetea.com/franchise/");
        }
        function hello(){
            window.open("a.html");
        }
    </script>
</head>
<body>

        <h1>BLACK PECKOE</h1>
        <div id="container">
        <button type="button">HOME</button>
        <button onclick="welcome()">ABOUT US</button>
        <button onclick="hello()">orders</button>
        </div>

</body>
</html> 




style.css
h1{
  text-shadow: 2px 2px 5px rgb(16, 76, 187);
}
button{
  font-size: 10px;
  padding:5px;
  margin: 10px;
  background-color: #0a98b1;
}
#container{
  text-align:right;
  position: absolute;
  right: 0;
  top:0;
}
body {
  background-image: url(tea.jpeg);
  background-size: cover;
  background-repeat: no-repeat;
  background-size: 100%;
}
style{
  text-align: right;
}



a.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="a.css">
    <script>
        function alert(){
            prompt("your orders willbe delivered soon!!")
        }
    </script>
</head>
<body>
    <div class="container">
        <input type="tea name"
        placeholder="tea name">
        <input type="quantity"
        placeholder="quantity">
        <button onclick="alert()">Bookurtea</button>

    </div>
</body>
</html>


a.css

        *{
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body{
            height: 100pc;
            display:flex;
            justify-content: center;
        }
        .container{
            display: flex;
            flex-direction: column;
            width:300px;
            border-color: rgba(58, 11, 146, 0.63);
            border-radius: 5px;
        }
        input{
            margin: 5px 0px;
            height: 35px;
            padding:7px;
        }
        button{
            background-color: rgba(27, 187, 6, 0.589);
            border-radius: 5px;
            color: rgba(0, 0, 0, 0.589);
        }
        button:hover{
            background-color: rgba(204, 37, 65, 0.699);
        }
body{
    background-image: url(back.jpg),url(tea1.jpeg),url(tea2.jpeg);
    background-size: cover;
    background-repeat: no-repeat,no-repeat,repeat;
    background-size: 100%;
  }
    
https://github.com/GuruGitHub8858/React_App_Anime.git
https://github.com/GuruGitHub8858/Svec.git
https://yellowanime.netlify.app
