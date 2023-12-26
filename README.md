# Tela-inicial-exerc-cio
HTML 
<!DOCTYPE html>
<html lang="pt-br">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title> tela inicial </title>
</head>

<body>
  <div class="hero">
    <div class="content">
    
    <code>
      <h1>Seja bem-vindo ao B.O</h1>
    </code>
    <p>Com a Bambi óculos</p>
   <div><code> <h2> Você vê o mundo com outros olhos </h2>
    </code>
     </div>
      <a href="" class= "btn">próximo</a>
    </div>
  </div>

</body>
</html>



CSS


* {

  margin:0px;

  padding:0px;

  box-sizing:border-box;

  font-family:sans-serif;

}

.hero{

  min-height:100vh;
  background-image: url("https://i.im.ge/2023/12/26/x987qM.31c9b00622d564737afc87a0cb79c6f7.jpg");

  background-repeat: no-repeat;

  background-size:cover;

  background-position:center;

  display:flex;


  margin-bottom:30px;

}

.content .btn {

  font-size:50px;

  padding:10px 20px;

  background-color:salmon;

  color: #fff;

  border-radius:5px;

  text-decoration:none;

  transition: 0.3s ease;

}
.content .btn:hover{
  ackground-color: white;

}


