# amgauna.github.io
amgauna.github.io

<!DOCTYPE html>
<html lang="BR">
<head>
  <title>Ana Gauna</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.1.1/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
  
  
  <style>    
/*  fixando o tamanho da imagem do caroussel  */
.fixedHeightImg > img {
    max-height: 500px;
    margin-left: auto;
    margin-right: auto;
    width: auto;
  }
  /*
    Definir uma altura padrão (fixa) para a classe .fixedHeightImg faz com que qualquer imagem que esteja
    listada no carrosel, dentro de um div com a classe "item", permaneça com essa altura. Nesse exemplo a
    altura máxima é de  500 pixels, que vai ser a altura da imagem, portanto, do carrosel inteiro.
    Importante: Dentro do elemento de cada imagem a altura deve ser definida com um estilo inline
    */
/*   */
  </style>
  
</head>
  
<body>
<div class="container">
  <br>
  <div id="myCarousel" class="carousel slide" data-ride="carousel">
    <!-- Indicators -->
    <ol class="carousel-indicators">
      <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
      <li data-target="#myCarousel" data-slide-to="1"></li>

    </ol>
    <!-- Wrapper for slides -->
    <div class="carousel-inner" role="listbox"> 
      <!-- 
          A classe "fixedHeightImg" tem que estar no div que tem a classe "item".
          Nesse exemplo eu coloquei uma imagem 1300x800 e outra 800x1300 e, mesmo
          com a diferença nos tamanhos, as imagens são mostradas no carrosel com
          o mesmo tamanho.
          Nota que cada imagem tem um estilo inline com a altura definida em 500px,
          que é a altura máxima colocada na classe "fixedHeightImg"
      -->       
      <div class="item active fixedHeightImg">
        <!--  <img src="http:// " alt="imagem1" style="height: 500px;">  -->
      </div>
      <div class="item fixedHeightImg">
        <!--  <img src="http:// " alt="Imagem2"  style="height: 500px;">  -->
      </div>
    </div>
    <!-- Left and right controls -->
    <a class="left carousel-control" href="#myCarousel" role="button" data-slide="prev">
      <span class="glyphicon glyphicon-chevron-left" aria-hidden="true"></span>
      <span class="sr-only">Previous</span>
    </a>
    <a class="right carousel-control" href="#myCarousel" role="button" data-slide="next">
      <span class="glyphicon glyphicon-chevron-right" aria-hidden="true"></span>
      <span class="sr-only">Next</span>
    </a>
  </div>
</div>
</body>
</html>

