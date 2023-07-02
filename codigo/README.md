# Código do Projeto

PAGINA PRINCIPAL:
HTML:
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <meta charset="utf-8" />
        <title>IdoS.O.S</title>
        <link rel="stylesheet" href="style.css">
        <script src="https://kit.fontawesome.com/c84e2bf84f.js" crossorigin="anonymous"></script>
        <meta name="viewport" content="width=device-width">
        <script src="script.js"></script>
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
      </head>
 <body>
    
 <ul>
    <li><a href="/principal/index.html" id="btnback">IdoS.O.S</a></li>
    <li><a href="/sobreNos/sobrenos.html">Sobre Nós</a></li>
    <li><a href="/cadastro/cadastro.html">Login</a></li> 
    <li><a href="/myaccount/myaccount.html">Minha Conta</a></li>
 </ul>


 <div class="conteiner_busca">
    <input type="text" class="input_busca" id="inpt_busca" placeholder="   Busque por algo...">
    <a href="/chat/chat.html" id="btnchat"><i id="img_chat" class="fa-solid fa-comments fa-lg"></i></a>
  </div>
  <a href="/search/search.html" ><img src="img/foto_filtro.png" alt="" id="img_filtro"></a>
  

    <a href="/calendario/calendario.html"/><img src="img/calend.png" alt="Calendário" class="calendario" id="imagem"></a>
 <script>

    var imagem = document.getElementById("imagem");
    imagem.addEventListener("mouseover", function(){
        imagem.src = "img/calend2.png";
    });
    imagem.addEventListener("mouseout", function(){
        imagem.src = "img/calend.png";
    });
    </script>

<footer class="footer">
    <div id="divFooter">
      <div class="credits">
      <p class="credit">
       <i>@Todos os direitos reservados</i></p>
      <div class="payment">
        <p class="paymeth">Métodos de Pagamentos</p>
        <i class="fa-brands fa-cc-paypal" id="paypal"></i>
        <i class="fa-brands fa-pix" id="pix"></i>
        <i class="fa-solid fa-credit-card" id="credit"></i>
      </div>
      <div class="social">
        <p class="letsbe">Redes Sociais</p>
        <a href="#insta" target="_blank" class="fa-brands fa-instagram" id="insta"></a>
        <a href="#twitter" target="_blank" class="fa-brands fa-twitter" id="twitter"></a>
        <a href="#email" target="_blank" class="fa-solid fa-envelope" id="email"></a>
      </div>
      <div class="contact">
        <p class="cont">Contato</p>
        <a href="#+55 49 3382-3126" class="fa-solid fa-phone" id="phone"></a>
        <a class="num"> +55 49 3382-3126</a>
      </div>
      <div class="search">
        <p class="news">Newletter</p>
        <i class="fa-solid fa-envelope" id="email" style="color: black;"></i>
        <input type="text" class="text" placeholder="Escreva seu email aqui...">
      </div>
      </div>

    </div>
    <br>
    <br>
    <br>
    <br>
    <br>
    </div>
    
  </div>

  </footer>
  <script src="https://kit.fontawesome.com/bfbfec3ece.js" crossorigin="anonymous"></script>
</body>
</html>

CSS:
html {
    background-color: #b59566;
  }
  
  ul {
    list-style-type: none;
    margin: 0 auto;
    padding: 10px;
    overflow: hidden;
    background-color: #ffd992c1;
    text-align: center;
    display: flex;
    align-items: center; /* Alinha verticalmente os itens */
    width: 98%;
  }
  
  li {
    display: inline-block;
    margin: 0 6%; /* Ajuste a margem horizontal conforme necessário */
    font-size: 20px;
    font-family: 'Times New Roman', Times, serif;
    color: #b89371;
    text-decoration: none;
  }
  
  li:hover a {
    background-color: #b89371;
    color: #fff;
    border: 2px solid #ffd992c1;
  }
  
  ul li a {
    display: flex;
    align-items: center;
    justify-content: center;
    padding: 10px 10px;
    text-decoration: none;
    color: #000000;
    border-radius: 10px;
    border: 2px solid #b89371;
    background-color: #ffd992c1;
    transition: 0.3s;
    height: 50px;
    width: 150px;
  }
  
  .calendario {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    margin-top: 50px;
    float: right;
    margin-right: 110px;
    height: 600px;
    width: 600px;
  }
  
  .conteiner_busca {
    display: flex;
    justify-content: flex-start;
    margin-left: 5%;
    margin-top: 20px;
  }
  
  #inpt_busca.input_busca {
    width: 70%;
    border-radius: 20px;
    border: 0px;
    
  } 

  #img_chat {
    margin-top: 32px;
    margin-left: 20px;
    font-size: 50px;
    cursor: pointer;
    color: #000000;
  }

  #btnchat{
    background-color:#ffd992c1 ;
    margin-left: 30px;
    border-radius: 10px;
    height: 70px;
    width: 100px;
  }
  #btnchat:hover{
    background-color: #fff;
  }

  #btnback{
    font-size: 40px;
    border-radius: 10px;
    cursor: pointer; 
    margin-left: 15px;
    background-color: #b89371;
    color: #fff;
    text-decoration: none;
    border-color: #79500d;
    border-style:groove;
    border: 2px solid #ffd992c1;
}

#img_filtro:hover{
  width: 540px;
  height: 360px;
}

#img_filtro{
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    margin-top: 10%;
    float: left;
    margin-left: 110px;
    width: 500px;
    height: 320px;

}
.footer {
  background-color: #ffffff;
  height: 120px;
  text-align: center;
  width: 100%;
  font-family: Arial, Helvetica, sans-serif;
}
.credit {
  color: black;
  float: right;
  margin-right: 40px;
  margin-top: 30px;
  font-family: Arial, Helvetica, sans-serif;
  font-size: 14px;
}

.payment {
  font-family: Arial, Helvetica, sans-serif;
  font-weight: bolder;
  font-size: 10px;
  margin-left: 20px;
  margin-top: 10px;
  margin-right: 40px;
  margin-bottom: 30px;
  float: left;
}

#paypal,
#pix,
#credit {
  font-size: 20px;
}

.paymeth {
  color: black;
  margin-left: 10px;
}

.fa-brands {
  text-decoration: none;
  color: black;
  padding: 5px;
  background-color: #ffd992c1;
  margin-right: 10px;
  border-radius: 5px;
}

#paypal {
  margin-left: 40px;

}

#credit {
  text-decoration: none;
  color: black;
  padding: 5px;
  background-color: #ffd992c1;
  margin-right: 5px;
  border-radius: 5px;
  ;
}

.social {
  float: left;
  margin-top: 30px;
  font-family: Arial, Helvetica, sans-serif;
  font-weight: bolder;
  font-size: 10px;
  margin-left: 20px;
  margin-top: 10px;
  margin-bottom: 30px;
  float: left;
  margin-right: 40px;
}

.contact {
  float: left;
  margin-top: 30px;
  font-family: Arial, Helvetica, sans-serif;
  font-weight: bolder;
  font-size: 10px;
  margin-left: 10px;
  margin-top: 10px;
  margin-bottom: 30px;
  float: left;
}
.cont {
  margin-left: -110px;
}

.num {
  font-size: 15px;
  margin-left: 10px;
  font-weight: lighter;
}

.letsbe {
  margin-left: -45px;
}

#insta,
#twitter,
#email,
#phone {
  font-size: 20px;
}

#email,
#phone {
  text-decoration: none;
  color: black;
  padding: 5px;
  background-color: #ffd992c1;
  border-radius: 5px;
}

.search {
  position: absolute;
  margin-top: 6px;
  margin-left: 640px;
  padding: 6px;
  padding-left: 7px;
  border-radius: 4px;
  font-size: 10px;
  font-weight: bold;
}

.news {
  margin-left: -160px;
}

#busca {
  margin-right: 10px;
  font-size: 20px;
  background-color: #ffffff7c;
  padding: 5px;
  border-radius: 5px;
}

.text {
  background: none;
  border: 0;
  outline: 0;
  padding: 5px;
}


.footer{
  margin-top: 700px;
  background-color: #ffd992c1;
}

.text{
  color: black;
}

#divFooter{
  align-items: center;
}


PAGINA SOBRE NOS:
HTML:
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        .centrado {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 65vh;
        }
        .centrado img {
            max-width: 100%;
            max-height: 100%;
        }
        li {
            list-style-type: none;
        }
        .backbtn {
            font-size: 50px; 
        }
        body {
    background-color: #b59566;
}

.backbt{
    font-size: 30px;
    border-radius: 10px;
    cursor: pointer;
    background-color: transparent;
    color: #fff;
    border: 1.6px solid #4e340a;
    margin-left: 100px;
    position: absolute;
    margin-top: 11px;
}

.backbt:hover{
    background-color:#79500d;
}

h1{
    color: white;
    font-size: 50px;
    display: flex;
    justify-content: center;
    align-items: center;
    
}

a{
    text-decoration: none;
}
    </style>

    <title>IdoS.O.S</title>
</head>
<body>

    <div>
        <li>
            <a class="backbt" href="/principal/index.html">IdoS.O.S</a>
        </li>   
        <h1>Sobre Nós</h1>
    </div>

    <div class="centrado">
        <img src="img/foto_nossa.png" alt="Imagem" class="centrado">
    
    </div>
</body>
</html>


PAGINA MY ACCOUNT:
HTML:
<!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>IdoS.O.S</title>

    <!-- Custom Css -->
    <link rel="stylesheet" href="myaccount.css">

    <!-- FontAwesome 5 -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.12.1/css/all.min.css">
</head>
<body>
    <!-- Navbar top -->
    <div class="navbar-top">
        <div class="title">
            <h1>Minha Conta</h1>
        </div>

        <!-- Navbar -->

        <ul>
            <li>
                <a class="backbtn" href="/principal/index.html">IdoS.O.S</a>

        </script>
            </li>           
        </ul>
        <!-- End -->
    </div>
    <!-- End -->

    <!-- Sidenav -->
    <div class="sidenav">
        <div class="profile">
            <img src="myaccountimg/userimg.png" alt="" width="100" height="100">

            <div class="name" id="d_name">
                
            </div>
            <div class="job" id="d_mail">
                
            </div>
        </div>

        <div class="sidenav-url">
            <div class="url">
                <a href="#profile" class="active">Sair</a>
                <hr align="center">
            </div>
        </div>
    </div>
    <!-- End -->

    <!-- Main -->
    <div class="main">
        <h2>Meus Dados</h2>
        <div class="card">
            <div class="card-body">
                <button id="editbtn"><i class="fa fa-pen fa-xs edit"></i></button>
                <table>
                    <tbody>
                        <tr>
                            <td>Nome</td>
                            <td>:</td>
                            <td> </td>                            
                        </tr>
                        <tr>
                            <td>Email</td>
                            <td>:</td>
                            <td> </td>
                        </tr>
                        <tr>
                            <td>Número</td>
                            <td>:</td>
                            <td> </td>
                        </tr>
                        <tr>
                            <td>Endereço</td>
                            <td>:</td>
                            <td> </td>
                        </tr>
                        <tr>
                            <td>Profissão</td>
                            <td>:</td>
                            <td></td>
                        </tr>
                        <tr>
                            <td>Habilidades</td>
                            <td>:</td>
                            <td></td>
                        </tr>
                    </tbody>
                </table>
            </div>
        </div>

        <h2>Redes Sociais</h2>
        <div class="card">
            <div class="card-body">
                <div class="social-media">
                    <button class="botao" onclick="gotolink(this)" value="https://pt-br.facebook.com/">
                    <span class="fa-stack fa-sm">
                        <i class="fas fa-circle fa-stack-2x"></i>
                        <i class="fab fa-facebook fa-stack-1x fa-inverse"></i>
                    </span>
                    </button>    
                    <button class="botao" onclick="gotolink(this)" value="https://twitter.com/home?lang=pt">
                    <span class="fa-stack fa-sm">
                        <i class="fas fa-circle fa-stack-2x"></i>
                        <i class="fab fa-twitter fa-stack-1x fa-inverse"></i>
                    </span>
                    </button>
                    <button class="botao"  onclick="gotolink(this)" value="https://www.instagram.com/">
                    <span class="fa-stack fa-sm">
                        <i class="fas fa-circle fa-stack-2x"></i>
                        <i class="fab fa-instagram fa-stack-1x fa-inverse"></i>
                    </span>
                    </button>
                <script>
                    function gotolink(link){
                        console.log(link.value);
                        location.href = link.value;
                    };
                </script>
                </div>
            </div>
        </div>
    </div>
    <!-- End -->

    <script src="https://kit.fontawesome.com/bfbfec3ece.js" crossorigin="anonymous"></script>
    <script src="myaccount.js"></script>
</body>
</html>

CSS:
* {
    margin: 0;
}

body {
    background-color: #b59566;
    font-family: Arial;
    overflow: hidden;
}

/* NavbarTop */
.navbar-top {
    background-color: #ffd992c1;
    color: #fffefe;
    height: 90px;
}

.title {
    padding-top: 25px;
    position: absolute;
    left: 45%;
}

 .navbar-top ul{
    float: right;
    list-style-type: none;
    margin: 0;
    overflow: hidden;
    padding: 25px 40px 100px 40px;
    font-size: 30px;
    color: #fff;
} 

.backbtn{
    font-size: 30px;
    border-radius: 10px;
    cursor: pointer;
    background-color: transparent;
    color: #fff;
    border-color: #b59566;
    border-style:groove;
}

.backbtn:hover{
    background-color:#b59566;
}

.navbar-top ul li {
    float: left;
}

.navbar-top ul li a {
    color: #333;
    padding: 14px 16px;
    text-align: center;
    text-decoration: none;
}

.icon-count {
    background-color: #ff0000;
    color: #fff;
    float: right;
    font-size: 11px;
    left: -25px;
    padding: 2px;
    position: relative;
}

/* End */

/* Sidenav */
.sidenav {
    background-color: #896b3d;
    color: #ffffff;
    border-bottom-right-radius: 25px;
    height: 86%;
    left: 0;
    overflow-x: hidden;
    padding-top: 20px;
    position: absolute;
    top: 90px;
    width: 250px;
}

.profile {
    margin-bottom: 20px;
    margin-top: 10px;
    text-align: center;
}

.profile img {
    border-radius: 50%;
    box-shadow: 0px 0px 5px 1px grey;
}

.name {
    font-size: 20px;
    font-weight: bold;
    padding-top: 20px;
}

.job {
    font-size: 16px;
    font-weight: bold;
    padding-top: 10px;
}

#editbtn{
    float: right;
    height: 60px;
    width: 60px;
    margin-right: 14px;
    background-color: transparent;
    cursor: pointer;
    border-radius: 100px;
    font-size: 50px;
    color: #000;
}

#editbtn:hover{
    background-color: #b59566;
}

.card-body .fa{
    color: #000;
}

.card-body .fa:hover{
    color: #fff;
}

.url, hr {
    text-align: center;
}

.url hr {
    margin-left: 20%;
    width: 60%;
}

.url a {
    color: #ffffff;
    display: block;
    font-size: 20px;
    margin: 10px 0;
    padding: 6px 8px;
    text-decoration: none;
}

.url a:hover, .url .active {
    background-color: #e8f5ff;
    border-radius: 28px;
    color: #000;
    margin-left: 14%;
    width: 65%;
}

/* End */

/* Main */
.main {
    margin-top: 2%;
    margin-left: 29%;
    font-size: 28px;
    padding: 0 10px;
    width: 58%;
}

.main h2 {
    color: #333;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    font-size: 24px;
    margin-bottom: 10px;
}

.main .card {
    background-color: #fff;
    border-radius: 18px;
    box-shadow: 1px 1px 8px 0 grey;
    height: auto;
    margin-bottom: 20px;
    padding: 20px 0 20px 50px;
}

.main .card table {
    border: none;
    font-size: 16px;
    height: 270px;
    width: 80%;
}

.social-media {
    text-align: center;
    width: 90%;
}

.savebtn{
    border-radius: 20px;
    background-color: #fff;
    cursor: pointer;
    height: 30px;
}

.savebtn:hover{
    background-color: #b59566;
}

.social-media span {
    margin: 0 30px;
}

.botao{
    border: transparent;
    background-color: transparent;
    height: 30px;
    font-size: 30px;
    margin-bottom: 25px;
}
.fas{
    height: 50px;
    width: 50px;
}

.fa-facebook:hover {
    color: #4267b3 !important;
    cursor: pointer;
}

.fa-twitter:hover {
    color: #1da1f2 !important;
    cursor: pointer;
    height: 50px;
}

.fa-instagram:hover {
    color: #ce2b94 !important;
    cursor: pointer;
}

JAVASCRIPT:
window.addEventListener("DOMContentLoaded", function () {
  var editButton = document.getElementById("editbtn");
  var tableCells = document.querySelectorAll(".card-body table td:last-child");

  var displayName = document.querySelector("#d_name");
  var displayEmail = document.querySelector("#d_mail");

  var logout = document.querySelector(".sidenav-url .active");
  
  logout.addEventListener("click", function () {
    localStorage.removeItem("user_active");
    alert("Você saiu do sistema");
    window.location.href='/principal/index.html'
  });

  editButton.addEventListener("click", function () {
    tableCells.forEach(function (cell) {
      cell.contentEditable = true;
      cell.style.backgroundColor = "lightyellow";
    });

    editButton.disabled = true;

    var saveButton = document.createElement("button");
    saveButton.innerHTML = '<i class="fa fa-save fa-xs save"></i>';
    saveButton.classList.add("savebtn");
    tableCells[0].parentNode.appendChild(saveButton);

    saveButton.addEventListener("click", function () {
      tableCells.forEach(function (cell) {
        cell.contentEditable = false;
        cell.style.backgroundColor = "";
      });

      editButton.disabled = false;
      tableCells[0].parentNode.removeChild(saveButton);

      var userData = JSON.parse(localStorage.getItem("users"));
      var uid = localStorage.getItem('user_active');

      // Salvar os dados modificados no localStorage
      userData[uid] = {
        name: tableCells[0].textContent.trim(),
        email: tableCells[1].textContent.trim(),
        numero: tableCells[2].textContent.trim(),
        endereco: tableCells[3].textContent.trim(),
        profissao: tableCells[4].textContent.trim(),
        habilidades: tableCells[5].textContent.trim(),
      };

      localStorage.setItem("users", JSON.stringify(userData));
    });
  });

  // Carregar dados salvos do localStorage, se houver
  var savedUserData = JSON.parse(localStorage.getItem("users"));
  var uid = localStorage.getItem('user_active');
  var savedUserData = [savedUserData[uid]];

  if (savedUserData) {
    //savedUserData = JSON.parse(savedUserData);
    tableCells[0].textContent = savedUserData[0].name;
    tableCells[1].textContent = savedUserData[0].email;
    tableCells[2].textContent = savedUserData[0].numero;
    tableCells[3].textContent = savedUserData[0].endereco;
    tableCells[4].textContent = savedUserData[0].profissao;
    tableCells[5].textContent = savedUserData[0].habilidades;
    //
    displayName.textContent = savedUserData[0].name;
    displayEmail.textContent = savedUserData[0].email;
  }
});

window.onload = function() {
  // Verifica SE usuário está logado
  var logged = localStorage.getItem('user_active') || -1;
  if (!(logged >= 0)) {
    alert("Você não está logado!");
    window.location.href='/principal/index.html'
  }
};


PAGINA CHAT EXTERNO:
HTML:
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8" />
        <meta name="viewport" content="width=device-width, initial-scale=1.0" />
        <meta http-equiv="X-UA-Compatible" content="ie=edge" />
        <title>IdoS.O.S</title>
        <link rel="stylesheet" href="chat.css" />
    </head>
    <body> 
        <a class="backbtn" href="/principal/index.html">IdoS.O.S</a>
        
        <script>
            function gotolink(link){
                console.log(link.value);
                location.href = link.value;
            };
        </script>
        <div class="container">
            <h1>CHAT</h1>
            <div id="searchWrapper">
                <input
                    type="text"
                    name="searchBar"
                    id="searchBar"
                    placeholder="Pesquisar uma conversa"
                />
            </div>
            <ul id="charactersList"></ul>
        </div>
        <script src="chat.js"></script>
        <script src="https://kit.fontawesome.com/bfbfec3ece.js" crossorigin="anonymous"></script>
    </body>
</html>

CSS:
body {
    font-family: sans-serif;
    background-color: #b59566;
}

* {
    box-sizing: border-box;
}
h1 {
    color: #eee;
    margin-bottom: 30px;
    font-size: 65px;
}
.container {
    padding: 40px;
    margin: 0 auto;
    max-width: 1000px;
    text-align: center;
}

#charactersList {
    padding-inline-start: 0;
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(480px, 1fr));
    grid-gap: 20px;
    
}

.character {
    list-style-type: none;
    background-color: #896b3d;
    border-radius: 10px;
    padding: 10px 20px;
    display: grid;
    grid-template-columns: 3fr 1fr 1fr;
    grid-template-areas: 
        'name image'
        'house image';
    text-align: left;
    
}

.character > h2 {
    grid-area: name;
    margin-bottom: 0px;
    grid-template-columns: 1fr 5fr;
    color: #fff;
}

.character > p {
    grid-area: house;
    margin: 0;
    margin-top: -18px;
    font-size: 20px;
    color: #fff;
}

.character > img {
    max-height: 100px;
    grid-area: image;
}

#searchBar {
    width: 100%;
    height: 50px;
    border-radius: 3px;
    border: 1px solid #eaeaea;
    padding: 5px 10px;
    font-size: 20px;
    border-radius: 8px;
}

#searchWrapper {
    position: relative;
}

#searchWrapper::after {
    content: '🔍';
    position: absolute;
    top: 13px;
    right: 15px;
}

.backbtn{
    font-size: 40px;
    border-radius: 10px;
    cursor: pointer;
    margin-top: 25px;
    margin-left: 15px;
    background-color: transparent;
    color: #fff;
    text-decoration: none;
    border-color: #79500d;
    border-style:groove;
}

.backbtn:hover{
    background-color:#79500d;
}

#btnSendMessage{
    border-radius: 7px;
    height: 50px;
    width: 100px;
    font-size: 20px;
    cursor: pointer;
}
#btnSendMessage:hover{
    background-color: #79500d;
    color: #fff;
}
#messageBox{
    border-radius: 7px;
    width: 70%;
    height: 50px;
}
.digite{
    font-size: 25px;
}
.chatbtn{
    font-size: 50px;
    color: #fff;
    margin-top: 20px;
    margin-left: 30px;
}


#forumList {
    margin-top: 15px;
    text-align: left;
    font-size: 125%;
}
#forumList div {
    background: #896b3d;
    border-radius: 10px;
    padding: 8px;
    margin: 8px 0;
}
#forumList span {
    font-size: 80%;
    font-style: italic;
}

JAVASCRIPT:
const charactersList = document.getElementById('charactersList');
const characterForum = document.getElementById('characterForum');
const searchBar = document.getElementById('searchBar');
let hpCharacters = [];

searchBar.addEventListener('keyup', (e) => {
    const searchString = e.target.value.toLowerCase();

    const filteredCharacters = hpCharacters.filter((character) => {
        return (
            character.name.toLowerCase().includes(searchString) ||
            character.house.toLowerCase().includes(searchString)
        );
    });
    displayCharacters(filteredCharacters);
});

const loadCharacters = async () => {
    try {
        //const res = await fetch('https://hp-api.onrender.com/api/characters');
        //hpCharacters = await res.json();

        var hpCharacters = JSON.parse(localStorage.getItem('users')) || [];

        displayCharacters(hpCharacters);
    } catch (err) {
        console.error(err);
    }
};

const displayCharacters = (characters) => {
    const htmlString = characters
        .map((character, index) => {
            return `
            <li class="character">
                <h2>${character.name}</h2>
                <p>e-mail: ${character.email}</p>
                <a class="chatbtn"  href="char.html?id=${index}"><i class="fa-solid fa-comments fa-lg"></i></a>
            </li>
        `;
        })
        .join('');
    charactersList.innerHTML = htmlString;
};

loadCharacters();

window.onload = function() {
    // Verifica SE usuário está logado
    var logged = localStorage.getItem('user_active') || -1;
    if (!(logged >= 0)) {
      alert("Você não está logado!");
      window.location.href='/principal/index.html'
    }
  };


  PAGINA CHAT INTERNO:
  HTML:
  <!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8" />
        <meta name="viewport" content="width=device-width, initial-scale=1.0" />
        <meta http-equiv="X-UA-Compatible" content="ie=edge" />
        <title>IdoS.O.S</title>
        <link rel="stylesheet" href="chat.css" />
    </head>
    <body>
        <a class="backbtn" href="/chat/chat.html">IdoS.O.S</a>
        <script>
            function gotolink(link){
                console.log(link.value);
                location.href = link.value;
            };
        </script>
        <div class="container">
            <div id="characterProfile"></div>
            <div id="forumList"></div>
            <div id="messageControl">
                <hr>
                <p class="digite">Digite sua Mensagem:</p>
                <p><textarea id="messageBox"></textarea></p>
                <p><button id="btnSendMessage">Enviar</button></p>
            </div>
        </div>
        <script src="script-forum.js"></script>
        <script src="https://kit.fontawesome.com/bfbfec3ece.js" crossorigin="anonymous"></script>
    </body>
</html>

JAVASCRIPT:
const characterProfile = document.getElementById('characterProfile');
const btnSendMessage = document.getElementById('btnSendMessage');
const messageBox = document.getElementById('messageBox');
const forum = document.getElementById('forumList');
let hpCharacter = [];
let lid;
let uid;
let username;

btnSendMessage.addEventListener('click', (e) => {
    const msg = messageBox.value;
    console.log(msg);

    displayMessages(msg, username);

    messageBox.value = "";

    // Salvar mensagens no localStorage
    const savedMessages = localStorage.getItem('forumMessages');
    let messages = [];

    if (savedMessages) {
        messages = JSON.parse(savedMessages);
    }

    let user_msg = {};
    user_msg.from_id = lid;
    user_msg.to_id = uid;
    user_msg.msg = msg;

    messages.push(user_msg);
    localStorage.setItem('forumMessages', JSON.stringify(messages));
});


const displayMessages = (msg, from) => {
    forum.innerHTML = forum.innerHTML + `
        <div>
            <span>${from}:</span>
            <br>
            ${msg}
        </div>
    `;
};

const loadForum = async () => {
    try {
        const url_string = window.location.href;
        const url = new URL(url_string);
        uid = url.searchParams.get('id');
        //const res = await fetch('https://hp-api.onrender.com/api/character/' + uid);
        //hpCharacter = await res.json();

        var hpCharacters = JSON.parse(localStorage.getItem('users')) || [];
        var hpCharacter = [hpCharacters[uid]];

        displayOneCharacter(hpCharacter);
        displayOneCharacterMessages(uid);
    } catch (err) {
        console.error(err);
    }
};

const displayOneCharacter = (characters) => {
    const htmlString = characters
        .map((character) => {
            return `
            <li class="character">
                <h1>${character.name}</h1>
                <p>e-mail: ${character.email}</p>
            </li>
        `;
        })
        .join('');
    characterProfile.innerHTML = htmlString;

};

const displayOneCharacterMessages = (ind) => {
    var charMessages = JSON.parse(localStorage.getItem('forumMessages')) || [];
    var msg = charMessages.filter((message) => {
        return message.to_id == ind
    });

    var users = JSON.parse(localStorage.getItem('users')) || [];
    msg.map((message) => {
        displayMessages(message.msg, users[message.from_id].name);
    });
    
};

loadForum();

window.onload = function() {
    // Verifica SE usuário está logado
    var logged = localStorage.getItem('user_active') || -1;
    if (!(logged >= 0)) {
      alert("Você não está logado!");
      window.location.href='/principal/index.html'
    }

    // informação do usario logado
    var logged_user = JSON.parse(localStorage.getItem('users')) || [];
    lid = logged;
    username = logged_user[logged].name;
  };


PAGINA DE PESQUISA:
HTML:
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8" />
        <meta name="viewport" content="width=device-width, initial-scale=1.0" />
        <meta http-equiv="X-UA-Compatible" content="ie=edge" />
        <title>IdoS.O.S</title>
        <link rel="stylesheet" href="search.css" />
    </head>
    <body>
        <script>
            function gotolink(link){
                console.log(link.value);
                location.href = link.value;
            };
        </script>
            <a href="/principal/index.html" type="submit" id="backbtn"><i id="" class="fa-solid fa-caret-left"></i></a> </div> </form>

        <div class="container">
          <section class="info">
            <h1>Procure o Profissional</h1>
            <h2>O melhor do nosso serviço? Tudo.</h2>
            <p>Encontre o profissional certo pelo preço ideal!<br>Consiga serviços de qualidade de maneira simples e rápida!</br></p>
          </section>
            <div id="searchWrapper">
                <input
                    type="text"
                    name="searchBar"
                    id="searchBar"
                    placeholder="Buscar..."
                />
            </div>
            <ul id="charactersList"></ul>
        </div>
        
        <script src="https://kit.fontawesome.com/bfbfec3ece.js" crossorigin="anonymous"></script>
        <script src="search.js"></script>
    </body>
</html>


CSS:
body {
    font-family: sans-serif;
    background-color: #b59566;
}

 #backbtn{
    height: 60px;
    width: 200px;
    border-radius: 10px;
    font-size: 50px;
    background-color: transparent;
    border-color: black;
    border-style: groove;
    text-decoration: none;
    cursor: pointer;
    margin-top: 35px;
    margin-left: 35px;

}


a{
    text-decoration: none;
    color: black;
    margin-left: 4px;

}

#backbtn:hover{
    background-color:#ffffff;
}

* {
    box-sizing: border-box;
}
h1 {
    color: #ffffff;
    margin-bottom: 100px;
    margin-top: 0px;
    font-size: 80px;

}
.container {
    padding: 40px;
    margin: 0 auto;
    max-width: 1000px;
    text-align: center;
}

#charactersList {
    padding-inline-start: 0;
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(400px, 1fr));
    grid-gap: 30px;
}

.character {
    list-style-type: none;
    background-color: #856e4c;
    border-radius: 10px;
    padding: 10px 20px;
    display: grid;
    grid-template-columns: 3fr 1fr;
    grid-template-areas:
        'name image'
        'house image';
    text-align: left;
}

.character > h2 {
    grid-area: name;
    margin-bottom: 0px;
    color: #fff;
}

.character > p {
    grid-area: house;
    margin: 0;
    margin-top: -18px;
    color: #fff;
    
}

.character > img {
    max-height: 200px;
    grid-area: image;
}

#searchBar {
    width: 100%;
    height: 60px;
    border-radius: 15px;
    border: 1px solid #fffcfc;
    padding: 5px 10px;
    font-size: 30px;
}

#searchWrapper {
    position: relative;
}

#searchWrapper::after {
    content: '🔍';
    position: absolute;
    top: 18px;
    right: 15px;
    cursor: pointer;
}

.chatbtn{
    cursor: pointer;
    border-radius: 10px;
    max-height: 22px;
    margin-bottom: 20px;
}

.chatbtn:hover{
    background-color: #b59566;
}

h2{
    font-size: 40px;
}

p{
    font-size: 25px;
}

.info{
    color: #f2f2f2;   
}


JAVASCRIPT:
const charactersList = document.getElementById('charactersList');
const searchBar = document.getElementById('searchBar');
let hpCharacters = [];

searchBar.addEventListener('keyup', (e) => {
    const searchString = e.target.value.toLowerCase();

    const filteredCharacters = hpCharacters.filter((character) => {
        return (
            character.name.toLowerCase().includes(searchString) ||
            character.house.toLowerCase().includes(searchString)
        );
    });
    displayCharacters(filteredCharacters);
});

const loadCharacters = async () => {
    try {
        //const res = await fetch('https://hp-api.onrender.com/api/characters');
        //hpCharacters = await res.json();

        var hpCharacters = JSON.parse(localStorage.getItem('users')) || [];

        displayCharacters(hpCharacters);
    } catch (err) {
        console.error(err);
    }
};

const displayCharacters = (characters) => {
    const htmlString = characters
        .map((character, index) => {
            return `
            <li class="character">
                <h2>${character.name}</h2>
                <p>Email: ${character.email}</p>
                <button class="chatbtn" onclick="location.href='/chat/char.html?id=${index}'">Converse com o profissional</button>
            </li>
        `;
        })
        .join('');
    charactersList.innerHTML = htmlString;
};

loadCharacters();

/*let btnback = document.querySelector('button');
    btnback.addEventListener('click', () => {
    window.history.back();
});*/


PAGINA CADASTRO:
HTML:
<!DOCTYPE html>
<html lang="pt -BR">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>IdoS.O.S</title>
    <link rel="stylesheet" href="cadastro.css">
</head>
<body>
    <div class="container">
        <div class="signin">
            <form name='form-login'>
                
                <button id="voltar" ><</button>

                <h1>Registrar</h1>
        
                <label for="name"></label>
                <input type="text" id="name" placeholder="Nome:" required><br>
        
                <label for="name"></label>
                <input type="text" id="idade" placeholder="Idade:" required><br>

                <label for="name"></label>
                <input type="text" id="telefone" placeholder="Telefone:" required><br>

                <label for="name"></label>
                <input type="text" id="endereco" placeholder="Endereco:" required><br>

                <label for="name"></label>
                <input type="text" id="emergencia" placeholder="Contato de Emergência:" required><br>

                <label for="name"></label>
                <input type="email" id="email" placeholder="Email:" required><br>

                <label for="pw"></label>
                <input type="password"
                    id= "pw"
                    placeholder="Senha:" required><br>
        
                <!--
                <ul class="helper-text">
                    <li class="length">A senha deve conter no máximo 8 caracteres.</li>
                    <li class="lowercase">A senha deve conter uma letra minúscula.</li>
                    <li class="uppercase">A senha deve conter uma letra maiúscula.</li>
                    <li class="special">A senha deve conter um número ou um caracter especial.</li>
                </ul>
                 -->
            <input id="rgstr_btn" type="submit" value="Registrar" onclick="store()">
        
        
            </form>
        </div>
        
        <div class="login">
            <form name='form-login'>
                <a class="backbtn" href="/principal/index.html">IdoS.O.S</a>

        
                <h1>Entrar</h1>
        
                <label for="userEmail"></label>
                <input type="email" id="userEmail" placeholder="Email:" required>
        
                <label for="userPw"></label>
                <input type="password" id= "userPw" placeholder="Senha:" required>
        
                <div id="check">
                    <label for="checkbox">Login de trabalhador</label>
                    <input type="checkbox" id="checkbox">
                    
                </div>

                <input id= "login_btn" type="submit" value="Login" onclick="realizarLogin()">

                <p class="form__text">
                    <a class="form__link" href="./" id="linkCreateAccount">Não tem uma conta? Registre-se</a>
                </p>
                <p class="form__text">
                    <a class="form__link" href="./" id="linkCreateAccountTrab">Registre-se como trabalhador</a>
                </p>
        
            </form>
        </div>

        <div class="signinTrabalhador">
            <form name='form-signinTrabalhador'>
                
                <button id="voltarTrab" ><</button>

                <h1>Registrar como Trabalhador</h1>
        
                <label for="name"></label>
                <input type="text" id="nameTrab" placeholder="Nome:" required><br>
        
                <label for="name"></label>
                <input type="text" id="idadeTrab" placeholder="Idade:" required><br>

                <label for="name"></label>
                <input type="text" id="telefoneTrab" placeholder="Telefone:" required><br>

                <label for="name"></label>
                <input type="text" id="enderecoTrab" placeholder="Endereco:" required><br>

                <label for="name"></label>
                <input type="text" id="CPFTrab" placeholder="CPF:" required><br>

                <label for="name"></label>
                <input type="text" id="carteiraTrab" placeholder="Carteira de Trabalho:" required><br>

                <label for="name"></label>
                <input type="text" id="servicosTrab" placeholder="Serviços:" required><br>

                <label for="name"></label>
                <input type="text" id="emergenciaTrab" placeholder="Contato de Emergência:" required><br>

                <label for="name"></label>
                <input type="email" id="emailTrab" placeholder="Email:" required><br>

                <label for="pw"></label>
                <input type="password"
                    id= "pwTrab"
                    placeholder="Senha:" required><br>
                <!-- 
                <ul class="helper-text">
                    <li class="length">A senha deve conter no máximo 8 caracteres.</li>
                    <li class="lowercase">A senha deve conter uma letra minúscula.</li>
                    <li class="uppercase">A senha deve conter uma letra maiúscula.</li>
                    <li class="special">A senha deve conter um número ou um caracter especial.</li>
                </ul>
            -->
            <input id="rgstr_btnTrab" type="submit" value="Registrar Trabalhador" onclick="storeTrab()">
        
        
            </form>
        </div>
    </div>
    <script src="cadastro.js"></script>
</body>
</html>

CSS:
@charset "utf-8";
        @import url(http://weloveiconfonts.com/api/?family=fontawesome);

        [class*="fontawesome-"]:before {
          font-family: 'FontAwesome', sans-serif;
        }

        body {
          background: #b59566;
          color: white;
          font: 87.5%/1.5em 'Open Sans', sans-serif;
          margin: 0;
        }

        .conteiner{
          width: 100%;
          height: 100%;
          border-radius: 50px;
          border: 10px;
        }

        p {
          line-height: 1.5em;
        }

        after { clear: both; }

        .login {
          margin: 0 auto;
          width: 85%;
          height: 100%;
        }

        .login form {
          margin: auto;
          padding: 22px 22px 22px 22px;
          width: 100%;
          border-radius: 5px;
          background: #896b3d;
          border-top: 3px solid #745b35;
          border-bottom: 3px solid #745b35;
        }

        .login form span {
          background-color: #ffffff;
          border-radius: 3px 0px 0px 3px;
          border-right: 3px solid #ffffff;
          color: #ffffff;
          display: block;
          float: left;
          line-height: 50px;
          text-align: center;
          width: 50px;
          height: 50px;
        }

        .login form input[type="email"] {
          background-color: #ffffff;
          border-radius: 10px;
          color: #000000;
          margin-bottom: 1em;
          padding: 0 16px;
          width: 95%;
          height: 50px;
        }


        .login form input[type="password"] {
          background-color: #ffffff;
          border-radius: 10px;
          color: #000000;
          margin-bottom: 1em;
          padding: 0 16px;
          width: 95%;
          height: 50px;
        }

        .login form input[type="submit"] {
          background: rgb(190, 166, 135);
          border: 0;
          width: 100%;
          height: 40px;
          border-radius: 3px;
          color: white;
          cursor: pointer;
          transition: background 0.3s ease-in-out;
        }

        #login form input[type="submit"]:hover {
          background: #727975;
        }

        .form__text{
          color: #ffffff;
          font-size: 12px;
          margin-top: 1em;
          text-align: center;
        }

        a{
          color: #ffffff;
          text-decoration: none;
        }

        /* Sign in */
        .signin {
            margin: 0 auto;
            width: 85%;
          }
  
          .signin form {
            margin: auto;
            padding: 22px 22px 22px 22px;
            width: 100%;
            border-radius: 5px;
            background: #896b3d;
            border-top: 3px solid #745b35;
            border-bottom: 3px solid #745b35;
          }
  
          .signin form span {
            background-color: #ffffff;
            border-radius: 3px 0px 0px 3px;
            border-right: 3px solid #ffffff;
            color: #ffffff;
            display: block;
            float: left;
            line-height: 50px;
            text-align: center;
            width: 50px;
            height: 50px;
          }
  
          .signin form input[type="email"] {
            background-color: #ffffff;
            border-radius: 10px;
            color: #000000;
            margin-bottom: 1em;
            padding: 0 16px;
            width: 95%;
            height: 50px;
          }
  
  
          .signin form input[type="password"] {
            background-color: #ffffff;
            border-radius: 10px;
            color: #000000;
            margin-bottom: 1em;
            padding: 0 16px;
            width: 95%;
            height: 50px;
          }

          .signin form input[type="text"] {
            background-color: #ffffff;
            border-radius: 10px;
            color: #000000;
            margin-bottom: 1em;
            padding: 0 16px;
            width: 95%;
            height: 50px;
          }
  
          .signin form input[type="submit"] {
            background: rgb(190, 166, 135);
            border: 0;
            width: 100%;
            height: 40px;
            border-radius: 3px;
            color: white;
            cursor: pointer;
            transition: background 0.3s ease-in-out;
          }

          #voltar{
            background-color: rgb(190, 166, 135);
            border-radius: 10px;
            margin: 0 auto;
            border: 0px;
            cursor: pointer;
            color: #79500d;
            width: 30px;
            height: 20px;
            font-size: 15px;
          }

          #login form input[type="submit"]:hover {
            background: #16aa56;
          }

        /* Signin Trabalhador */
        .signinTrabalhador {
          margin: 0 auto;
          width: 85%;
        }

        .signinTrabalhador form {
          margin: auto;
          padding: 22px 22px 22px 22px;
          width: 100%;
          border-radius: 5px;
          background: #896b3d;
          border-top: 3px solid #745b35;
          border-bottom: 3px solid #745b35;
        }

        .signinTrabalhador form span {
          background-color: #ffffff;
          border-radius: 3px 0px 0px 3px;
          border-right: 3px solid #ffffff;
          color: #ffffff;
          display: block;
          float: left;
          line-height: 50px;
          text-align: center;
          width: 50px;
          height: 50px;
        }

        .signinTrabalhador form input[type="email"] {
          background-color: #ffffff;
          border-radius: 10px;
          color: #000000;
          margin-bottom: 1em;
          padding: 0 16px;
          width: 95%;
          height: 50px;
        }


        .signinTrabalhador form input[type="password"] {
          background-color: #ffffff;
          border-radius: 10px;
          color: #000000;
          margin-bottom: 1em;
          padding: 0 16px;
          width: 95%;
          height: 50px;
        }

        .signinTrabalhador form input[type="text"] {
          background-color: #ffffff;
          border-radius: 10px;
          color: #000000;
          margin-bottom: 1em;
          padding: 0 16px;
          width: 95%;
          height: 50px;
        }

        .signinTrabalhador form input[type="submit"] {
          background: rgb(190, 166, 135);
          border: 0;
          width: 100%;
          height: 40px;
          border-radius: 3px;
          color: white;
          cursor: pointer;
          transition: background 0.3s ease-in-out;
        }

        #voltarTrab{
          background-color: rgb(190, 166, 135);
          border-radius: 10px;
          margin: 0 auto;
          border: 0px;
          cursor: pointer;
          color: #79500d;
          width: 30px;
          height: 20px;
          font-size: 15px;
        }

        #login form input[type="submit"]:hover {
          background: #16aa56;
        }

        #rgstr_btnTrab{
            margin-top: 1.5%;
        }
       
        #rgstr_btn{
          margin-top: 1.5%;
        }

        .backbtn{
          font-size: 40px;
          border-radius: 10px;
          cursor: pointer;
          margin-left: 15px;
          background-color:#b59566;
          color: #fff;
          border-color: #b59566;
          border-style:groove;
      }
      
      .backbtn:hover{
        background-color: rgb(190, 166, 135);

      }

      input{
        border: 0;
      }

      .backbtn{
        border: 0;
      }

      JAVASCRIPT:
      function store(){
    var name = document.getElementById('name').value;
    var pw = document.getElementById('pw').value;
    var idade = document.getElementById('idade').value;
    var telefone = document.getElementById('telefone').value;
    var email = document.getElementById('email').value;
    var emergencia = document.getElementById('emergencia').value;
    var endereco = document.getElementById('endereco').value;
    /*
    var lowerCaseLetters = /[a-z]/g;
    var upperCaseLetters = /[A-Z]/g;
    var numbers = /[0-9]/g;

     if(name.length == 0 || pw.length == 0 || idade.length == 0 || telefone.length == 0 || email.length == 0 || emergencia.length == 0 || endereco.length == 0){
        alert('Por favor, preencha todos os campos');
    }else if(pw.length > 8){
        alert('Máximo de 8 caracteres na senha');
    }else if(!pw.match(numbers)){
        alert('Por favor, adicione pelo menos 1 número na senha');
    }else if(!pw.match(upperCaseLetters)){
        alert('Por favor, adicione pelo menos 1 letra maiúscula na senha');
    }else if(!pw.match(lowerCaseLetters)){
        alert('Por favor, adicione pelo menos 1 letra minúscula na senha');
    }else{ */

        // Cria um objeto com os dados do novo usuário
        var newUser = {
            name: name,
            pw: pw,
            idade: idade,
            telefone: telefone,
            email: email,
            emergencia: emergencia,
            endereco: endereco
        };

        // Recupera o array de usuários do localStorage, ou cria um novo array se ele não existir ainda
        var users = JSON.parse(localStorage.getItem('users')) || [];

        // Adiciona o novo usuário ao array de usuários
        users.push(newUser);

        // Armazena o array atualizado de usuários no localStorage
        localStorage.setItem('users', JSON.stringify(users));

        var users = JSON.parse(localStorage.getItem('users')) || [];
        alert('Sua conta foi criada com sucesso');

        localStorage.setItem('user_active', users.length);

    // } //
}

function check(){
    var userEmail = document.getElementById('userEmail').value;
    var userPw = document.getElementById('userPw').value;

    // Recupera o array de usuários do localStorage
    var users = JSON.parse(localStorage.getItem('users')) || [];

    // Verifica se o usuário existe no array
    var user = users.findIndex(function(u){
        return u.email == userEmail && u.pw == userPw;
    });

    if(user >= 0){
        localStorage.setItem('user_active', user);
        alert('Você está logado como '+users[user].name);
        location.href='/principal/index.html'
    }else{
        alert('Erro no login');
    }
}

//Fazendo a transição de login para cadastro 
window.onload = function() {
  document.getElementsByClassName("signin")[0].style.display = "none";
  var botaoIrParaCadastro = document.getElementById("linkCreateAccount");


  // Evento de clique do botão "nao tem uma conta? registre-se"
  botaoIrParaCadastro.addEventListener("click", function() {
      var divLogin = document.getElementsByClassName("login")[0];
      var divSignin = document.getElementsByClassName("signin")[0];

      divLogin.style.display = "none";
      divSignin.style.display = "block";
  });

  // Verifica SE usuário está logado

  var logged = localStorage.getItem('user_active') || -1;
  if (logged >= 0) {
    window.location.href='/principal/index.html'
  }

};


// Esconde a div "signin"
var telaSignin = document.getElementsByClassName("signin")[0];
telaSignin.style.display = "none";

// Adiciona evento de clique ao botão "Não tem uma conta? Registre-se"
var botaoIrParaCadastro = document.getElementById("linkCreateAccount");
botaoIrParaCadastro.addEventListener("click", function(event){
  event.preventDefault(); // previne o comportamento padrão do link


  // Verifica se a div "signin" está visível ou não e alterna entre as telas
  if (telaSignin.style.display === "none") {
    telaSignin.style.display = "block";
    document.getElementsByClassName("login")[0].style.display = "none";
  } else {
    telaSignin.style.display = "none";
    document.getElementsByClassName("login")[0].style.display = "block";
  }
});

// Adicionando botão para voltar à tela de login
var telaLogin = document.getElementsByClassName("login")[0];
var botaoVoltar = document.getElementById("voltar");

botaoVoltar.addEventListener("click", function(){
  telaSignin.style.display = "none";
  telaLogin.style.display = "block";
  divVisivel = false;
});






function storeTrab() {
    var nameTrab = document.getElementById('nameTrab').value;
    var pwTrab = document.getElementById('pwTrab').value;
    var idadeTrab = document.getElementById('idadeTrab').value;
    var telefoneTrab = document.getElementById('telefoneTrab').value;
    var emailTrab = document.getElementById('emailTrab').value;
    var emergenciaTrab = document.getElementById('emergenciaTrab').value;
    var enderecoTrab = document.getElementById('enderecoTrab').value;
    var CPFTrab = document.getElementById('CPFTrab').value;
    var servicosTrab = document.getElementById('servicosTrab').value;
    var carteiraTrab = document.getElementById('carteiraTrab').value;
    /*
    var lowerCaseLetters = /[a-z]/g;
    var upperCaseLetters = /[A-Z]/g;
    var numbers = /[0-9]/g;
  
    if (
      nameTrab.length == 0 ||
      pwTrab.length == 0 ||
      idadeTrab.length == 0 ||
      telefoneTrab.length == 0 ||
      emailTrab.length == 0 ||
      emergenciaTrab.length == 0 ||
      enderecoTrab.length == 0 ||
      CPFTrab.length == 0 ||
      servicosTrab.length == 0 ||
      carteiraTrab.length == 0
    ) {
      alert('Por favor, preencha todos os campos');
    } else if (pwTrab.length > 8) {
      alert('A senha deve ter no máximo 8 caracteres');
    } else if (!pwTrab.match(numbers)) {
      alert('A senha deve conter pelo menos um número');
    } else if (!pwTrab.match(upperCaseLetters)) {
      alert('A senha deve conter pelo menos uma letra maiúscula');
    } else if (!pwTrab.match(lowerCaseLetters)) {
      alert('A senha deve conter pelo menos uma letra minúscula');
    } else {
      */
      var newUserTrab = {
        nameTrab: nameTrab,
        pw: pwTrab,
        idade: idadeTrab,
        telefone: telefoneTrab,
        email: emailTrab,
        emergencia: emergenciaTrab,
        endereco: enderecoTrab,
        CPF: CPFTrab,
        servicos: servicosTrab,
        carteira: carteiraTrab
      };
  
      var usersTrab = JSON.parse(localStorage.getItem('usersTrab')) || [];
      usersTrab.push(newUserTrab);
      localStorage.setItem('usersTrab', JSON.stringify(usersTrab));
  
      alert('Sua conta de trabalhador foi criada com sucesso');

      localStorage.setItem('user_active', usersTrab.length);
    // } //
  }
  
  
  function checkTrab() {
    var email = document.getElementById('userEmail').value;
    var pw = document.getElementById('userPw').value;
    var users = JSON.parse(localStorage.getItem('usersTrab'));
    var userTrab = users.findIndex(function(userTrab) {
        return userTrab.email == email && userTrab.pw == pw;
    });

    if (userTrab >= 0) {
      localStorage.setItem('user_active', JSON.stringify(userTrab));
        //alert('Você está logado como trabalhador!');
        location.href='/principal/index.html';
    } else {
        alert('Erro no login de trabalhador!');
    }
}
  
        



// Esconde a div "signinTrabalhador"
var telaSigninTrabalhador = document.getElementsByClassName("signinTrabalhador")[0];
telaSigninTrabalhador.style.display = "none";

// Adiciona evento de clique ao botão "Registre-se como trabalhador"
var botaoIrParaCadastroTrab = document.getElementById("linkCreateAccountTrab");
botaoIrParaCadastroTrab.addEventListener("click", function(event){
    event.preventDefault(); // previne o comportamento padrão do link

    // Verifica se a div "signinTrabalhador" está visível ou não e alterna entre as telas
    if (telaSigninTrabalhador.style.display === "none") {
        telaSigninTrabalhador.style.display = "block";
        telaLogin.style.display = "none";
    }
    else {
        telaSigninTrabalhador.style.display = "none";
        telaLogin.style.display = "block";
    }
});

// Adicionando botão para voltar à tela de login
var telaLogin = document.getElementsByClassName("login")[0];
var botaoVoltarTrab = document.getElementById("voltarTrab");

botaoVoltarTrab.addEventListener("click", function(){
    telaSigninTrabalhador.style.display = "none";
    telaLogin.style.display = "block";
    divVisivel = false;
});

//Evento de clique no botão "Entrar"
function realizarLogin() {
  var checkbox = document.getElementById("checkbox");
  
  if (checkbox.checked) {
    // Executar o login de trabalhador
    checkTrab();
    // Restante do código para o login de trabalhador...
  } else {
    // Executar o login normal
    check();
    // Restante do código para o login normal...
  }
}


PAGINA CALENDARIO:
HTML:
<!DOCTYPE html>
<html lang="pt-br">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta
      name="description"
      content="Stay organized with our user-friendly Calendar featuring events, reminders, and a customizable interface. Built with HTML, CSS, and JavaScript. Start scheduling today!"
    />
    <meta
      name="keywords"
      content="calendar, events, reminders, javascript, html, css, open source coding"
    />
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.2.0/css/all.min.css"
      integrity="sha512-xh6O/CkQoPOWDdYTDqeRdPCVd1SpvCA9XXcUnZS2FmJNp1coAFzvtCN9BmamE+4aHK8yyUHUSCcJHgXloTyT2A=="
      crossorigin="anonymous"
      referrerpolicy="no-referrer"
    />
    <link rel="stylesheet" href="calendario.css" />
    <title>Calendario</title>
  </head>
  <body>

    <a class="backbtn" href="/principal/index.html"><i id="backbtn" class="fa-solid fa-caret-left"></i></a>
    <div class="container">
      <div class="left">
        <div class="calendar">
          <div class="month">
            <i class="fas fa-angle-left prev"></i>
            <div class="date">dezembro 2015</div>
            <i class="fas fa-angle-right next"></i>
          </div>
          <div class="weekdays">
            <div>Dom</div>
            <div>Seg</div>
            <div>Ter</div>
            <div>Qua</div>
            <div>Qui</div>
            <div>Sex</div>
            <div>Sab</div>
          </div>
          <div class="days"></div>
          <div class="goto-today">
            <div class="goto">
              <input type="text" placeholder="mes/ano" class="date-input" />
              <button class="goto-btn">Enviar</button>
            </div>
            <button class="today-btn">Hoje</button>
          </div>
        </div>
      </div>
      <div class="right">
        <div class="today-date">
          <div class="event-day">quarta</div>
          <div class="event-date">12 de dezembro 2022</div>
        </div>
        <div class="events"></div>
        <div class="add-event-wrapper">
          <div class="add-event-header">
            <div class="title">Adicionar Compromisso</div>
            <i class="fas fa-times close"></i>
          </div>
          <div class="add-event-body">
            <div class="add-event-input">
              <input type="text" placeholder="Compromisso" class="event-name" />
            </div>
            <div class="add-event-input">
              <input
                type="text"
                placeholder="Horário de entrada"
                class="event-time-from"
              />
            </div>
            <div class="add-event-input">
              <input
                type="text"
                placeholder="Horário de saída"
                class="event-time-to"
              />
            </div>
          </div>
          <div class="add-event-footer">
            <button class="add-event-btn">Adicionar Compromisso</button>
          </div>
        </div>
      </div>
      <button class="add-event">
        <i class="fas fa-plus"></i>
      </button>
    </div>

    <script src="calendario.js"></script>
  </body>
</html>

CSS:
:root {
    --primary-clr: #745d34c1;
  }
  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: "Poppins", sans-serif;
  }
  /* nice scroll bar */
  ::-webkit-scrollbar {
    width: 5px;
  }
  ::-webkit-scrollbar-track {
    background: #f5f5f5;
    border-radius: 50px;
  }
  ::-webkit-scrollbar-thumb {
    background: var(--primary-clr);
    border-radius: 50px;
  }
  
  body {
    position: relative;
    min-height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
    padding-bottom: 30px;
    background-color: #b89371;
  }
  .container {
    position: relative;
    width: 1200px;
    min-height: 850px;
    margin: 0 auto;
    padding: 5px;
    color: #fff;
    display: flex;
  
    border-radius: 10px;
    background-color: #ffd992c1;
  }
  .left {
    width: 60%;
    padding: 20px;
  }
  .calendar {
    position: relative;
    width: 100%;
    height: 100%;
    display: flex;
    flex-direction: column;
    flex-wrap: wrap;
    justify-content: space-between;
    color: #000000;
    border-radius: 5px;
    background-color: #fff;
  }
  /* set after behind the main element */
  .calendar::before,
  .calendar::after {
    content: "";
    position: absolute;
    top: 50%;
    left: 100%;
    width: 12px;
    height: 97%;
    border-radius: 0 5px 5px 0;
    background-color: #d3d4d6d7;
    transform: translateY(-50%);
  }
  .calendar::before {
    height: 94%;
    left: calc(100% + 12px);
    background-color: rgb(153, 153, 153);
  }
  .calendar .month {
    width: 100%;
    height: 150px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 0 50px;
    font-size: 1.2rem;
    font-weight: 500;
    text-transform: capitalize;
  }
  .calendar .month .prev,
  .calendar .month .next {
    cursor: pointer;
  }
  .calendar .month .prev:hover,
  .calendar .month .next:hover {
    color: var(--primary-clr);
  }
  .calendar .weekdays {
    width: 100%;
    height: 100px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 0 20px;
    font-size: 1rem;
    font-weight: 500;
    text-transform: capitalize;
  }
  .weekdays div {
    width: 14.28%;
    height: 100%;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  .calendar .days {
    width: 100%;
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    padding: 0 20px;
    font-size: 1rem;
    font-weight: 500;
    margin-bottom: 20px;
  }
  .calendar .days .day {
    width: 14.28%;
    height: 90px;
    display: flex;
    align-items: center;
    justify-content: center;
    cursor: pointer;
    color: var(--primary-clr);
    border: 1px solid #f5f5f5;
  }
  .calendar .days .day:nth-child(7n + 1) {
    border-left: 2px solid #f5f5f5;
  }
  .calendar .days .day:nth-child(7n) {
    border-right: 2px solid #f5f5f5;
  }
  .calendar .days .day:nth-child(-n + 7) {
    border-top: 2px solid #f5f5f5;
  }
  .calendar .days .day:nth-child(n + 29) {
    border-bottom: 2px solid #f5f5f5;
  }
  
  .calendar .days .day:not(.prev-date, .next-date):hover {
    color: #fff;
    background-color: var(--primary-clr);
  }
  .calendar .days .prev-date,
  .calendar .days .next-date {
    color: #b3b3b3;
  }
  .calendar .days .active {
    position: relative;
    font-size: 2rem;
    color: #000000;
    background-color: var(--primary-clr);
  }
  .calendar .days .active::before {
    content: "";
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    box-shadow: 0 0 10px 2px var(--primary-clr);
  }
  .calendar .days .today {
    font-size: 2rem;
  }
  .calendar .days .event {
    position: relative;
  }
  .calendar .days .event::after {
    content: "";
    position: absolute;
    bottom: 10%;
    left: 50%;
    width: 75%;
    height: 6px;
    border-radius: 30px;
    transform: translateX(-50%);
    background-color: var(--primary-clr);
  }
  .calendar .days .day:hover.event::after {
    background-color: #fff;
  }
  .calendar .days .active.event::after {
    background-color: #fff;
    bottom: 20%;
  }
  .calendar .days .active.event {
    padding-bottom: 10px;
  }
  .calendar .goto-today {
    width: 100%;
    height: 50px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 5px;
    padding: 0 20px;
    margin-bottom: 20px;
    color: var(--primary-clr);
  }
  .calendar .goto-today .goto {
    display: flex;
    align-items: center;
    border-radius: 5px;
    overflow: hidden;
    border: 1px solid var(--primary-clr);
  }
  .calendar .goto-today .goto input {
    width: 100%;
    height: 30px;
    outline: none;
    border: none;
    border-radius: 5px;
    padding: 0 20px;
    color: var(--primary-clr);
    border-radius: 5px;
  }
  .calendar .goto-today button {
    padding: 5px 10px;
    border: 1px solid var(--primary-clr);
    border-radius: 5px;
    background-color: transparent;
    cursor: pointer;
    color: var(--primary-clr);
  }
  .calendar .goto-today button:hover {
    color: #fff;
    background-color: var(--primary-clr);
  }
  .calendar .goto-today .goto button {
    border: none;
    border-left: 1px solid var(--primary-clr);
    border-radius: 0;
  }
  .container .right {
    position: relative;
    width: 40%;
    min-height: 100%;
    padding: 20px 0;
  }
  
  .right .today-date {
    width: 100%;
    height: 50px;
    display: flex;
    flex-wrap: wrap;
    gap: 10px;
    align-items: center;
    justify-content: space-between;
    padding: 0 40px;
    padding-left: 70px;
    margin-top: 50px;
    margin-bottom: 20px;
    text-transform: capitalize;
  }
  .right .today-date .event-day {
    font-size: 2rem;
    font-weight: 500;
  }
  .right .today-date .event-date {
    font-size: 1rem;
    font-weight: 400;
    color: #000000;
  }
  .events {
    width: 100%;
    height: 100%;
    max-height: 600px;
    overflow-x: hidden;
    overflow-y: auto;
    display: flex;
    flex-direction: column;
    padding-left: 4px;
  }
  .events .event {
    position: relative;
    width: 95%;
    min-height: 70px;
    display: flex;
    justify-content: center;
    flex-direction: column;
    gap: 5px;
    padding: 0 20px;
    padding-left: 50px;
    color: #000000;
    background: linear-gradient(90deg, #f8edd8, transparent);
    cursor: pointer;
  }
  /* even event */
  .events .event:nth-child(even) {
    background: transparent;
  }
  .events .event:hover {
    background: linear-gradient(90deg, var(--primary-clr), transparent);
  }
  .events .event .title {
    display: flex;
    align-items: center;
    pointer-events: none;
  }
  .events .event .title .event-title {
    font-size: 1rem;
    font-weight: 400;
    margin-left: 20px;
  }
  .events .event i {
    color: var(--primary-clr);
    font-size: 0.5rem;
  }
  .events .event:hover i {
    color: #fff;
  }
  .events .event .event-time {
    font-size: 0.8rem;
    font-weight: 400;
    color: #000000;
    margin-left: 15px;
    pointer-events: none;
  }
  .events .event:hover .event-time {
    color: #fff;
  }
  /* add tick in event after */
  .events .event::after {
    content: "✓";
    position: absolute;
    top: 50%;
    right: 0;
    font-size: 3rem;
    line-height: 1;
    display: none;
    align-items: center;
    justify-content: center;
    opacity: 0.3;
    color: var(--primary-clr);
    transform: translateY(-50%);
  }
  .events .event:hover::after {
    display: flex;
  }
  .add-event {
    position: absolute;
    bottom: 30px;
    right: 30px;
    width: 40px;
    height: 40px;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 1rem;
    color: #000000;
    border: 2px solid #000000;
    opacity: 0.5;
    border-radius: 50%;
    background-color: transparent;
    cursor: pointer;
  }
  .add-event:hover {
    opacity: 1;
  }
  .add-event i {
    pointer-events: none;
  }
  .events .no-event {
    width: 100%;
    height: 100%;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 1.5rem;
    font-weight: 500;
    color: #000000;
  }
  .add-event-wrapper {
    position: absolute;
    bottom: 100px;
    left: 50%;
    width: 90%;
    max-height: 0;
    overflow: hidden;
    border-radius: 5px;
    background-color: #fff;
    transform: translateX(-50%);
    transition: max-height 0.5s ease;
  }
  .add-event-wrapper.active {
    max-height: 300px;
  }
  .add-event-header {
    width: 100%;
    height: 50px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 0 20px;
    color: #000000;
    border-bottom: 1px solid #f5f5f5;
  }
  .add-event-header .close {
    font-size: 1.5rem;
    cursor: pointer;
  }
  .add-event-header .close:hover {
    color: var(--primary-clr);
  }
  .add-event-header .title {
    font-size: 1.2rem;
    font-weight: 500;
  }
  .add-event-body {
    width: 100%;
    height: 100%;
    display: flex;
    flex-direction: column;
    gap: 5px;
    padding: 20px;
  }
  .add-event-body .add-event-input {
    width: 100%;
    height: 40px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 10px;
  }
  .add-event-body .add-event-input input {
    width: 100%;
    height: 100%;
    outline: none;
    border: none;
    border-bottom: 1px solid #f5f5f5;
    padding: 0 10px;
    font-size: 1rem;
    font-weight: 400;
    color: #000000;
  }
  .add-event-body .add-event-input input::placeholder {
    color: #000000;
  }
  .add-event-body .add-event-input input:focus {
    border-bottom: 1px solid var(--primary-clr);
  }
  .add-event-body .add-event-input input:focus::placeholder {
    color: var(--primary-clr);
  }
  .add-event-footer {
    display: flex;
    align-items: center;
    justify-content: center;
    padding: 20px;
  }
  .add-event-footer .add-event-btn {
    height: 40px;
    font-size: 1rem;
    font-weight: 500;
    outline: none;
    border: none;
    color: #fff;
    background-color: var(--primary-clr);
    border-radius: 5px;
    cursor: pointer;
    padding: 5px 10px;
    border: 1px solid var(--primary-clr);
  }
  .add-event-footer .add-event-btn:hover {
    background-color: transparent;
    color: var(--primary-clr);
  }
  
  /* media queries */
  
  @media screen and (max-width: 1000px) {
    body {
      align-items: flex-start;
      justify-content: flex-start;
    }
    .container {
      min-height: 100vh;
      flex-direction: column;
      border-radius: 0;
    }
    .container .left {
      width: 100%;
      height: 100%;
      padding: 20px 0;
    }
    .container .right {
      width: 100%;
      height: 100%;
      padding: 20px 0;
    }
    .calendar::before,
    .calendar::after {
      top: 100%;
      left: 50%;
      width: 97%;
      height: 12px;
      border-radius: 0 0 5px 5px;
      transform: translateX(-50%);
    }
    .calendar::before {
      width: 94%;
      top: calc(100% + 12px);
    }
    .events {
      padding-bottom: 340px;
    }
    .add-event-wrapper {
      bottom: 100px;
    }
  }
  @media screen and (max-width: 500px) {
    .calendar .month {
      height: 75px;
    }
    .calendar .weekdays {
      height: 50px;
    }
    .calendar .days .day {
      height: 40px;
      font-size: 0.8rem;
    }
    .calendar .days .day.active,
    .calendar .days .day.today {
      font-size: 1rem;
    }
    .right .today-date {
      padding: 20px;
    }
  }
  #backbtn{
    margin-left: 17px;
    text-decoration: none;
    color: #000000;
  }

  .backbtn{
    float: 10%;
    height: 70px;
    width: 70px;
    border-radius: 70px;
    font-size: 60px;
    background-color: transparent;
    border-color: rgb(0, 0, 0);
    border-style: groove;
    cursor: pointer;
    margin-bottom: 20px;
    margin-left: 45px;
    margin-bottom: 900px;
    margin-top: 20px;
}



.backbtn:hover{
    background-color:#ffffff;
}
  
JAVASCRIPT:
const calendar = document.querySelector(".calendar"),
  date = document.querySelector(".date"),
  daysContainer = document.querySelector(".days"),
  prev = document.querySelector(".prev"),
  next = document.querySelector(".next"),
  todayBtn = document.querySelector(".today-btn"),
  gotoBtn = document.querySelector(".goto-btn"),
  dateInput = document.querySelector(".date-input"),
  eventDay = document.querySelector(".event-day"),
  eventDate = document.querySelector(".event-date"),
  eventsContainer = document.querySelector(".events"),
  addEventBtn = document.querySelector(".add-event"),
  addEventWrapper = document.querySelector(".add-event-wrapper "),
  addEventCloseBtn = document.querySelector(".close "),
  addEventTitle = document.querySelector(".event-name "),
  addEventFrom = document.querySelector(".event-time-from "),
  addEventTo = document.querySelector(".event-time-to "),
  addEventSubmit = document.querySelector(".add-event-btn ");

let today = new Date();
let activeDay;
let month = today.getMonth();
let year = today.getFullYear();

const months = [
  "Janeiro",
  "Fevereiro",
  "Março",
  "Abril",
  "Maio",
  "Junho",
  "Julho",
  "Agosto",
  "Setembro",
  "Outubro",
  "Novembro",
  "Dezembro",
];

// const eventsArr = [
//   {
//     day: 13,
//     month: 11,
//     year: 2022,
//     events: [
//       {
//         title: "Event 1 lorem ipsun dolar sit genfa tersd dsad ",
//         time: "10:00 AM",
//       },
//       {
//         title: "Event 2",
//         time: "11:00 AM",
//       },
//     ],
//   },
// ];

const eventsArr = [];
getEvents();
console.log(eventsArr);

//function to add days in days with class day and prev-date next-date on previous month and next month days and active on today
function initCalendar() {
  const firstDay = new Date(year, month, 1);
  const lastDay = new Date(year, month + 1, 0);
  const prevLastDay = new Date(year, month, 0);
  const prevDays = prevLastDay.getDate();
  const lastDate = lastDay.getDate();
  const day = firstDay.getDay();
  const nextDays = 7 - lastDay.getDay() - 1;

  date.innerHTML = months[month] + " " + year;

  let days = "";

  for (let x = day; x > 0; x--) {
    days += `<div class="day prev-date">${prevDays - x + 1}</div>`;
  }

  for (let i = 1; i <= lastDate; i++) {
    //check if event is present on that day
    let event = false;
    eventsArr.forEach((eventObj) => {
      if (
        eventObj.day === i &&
        eventObj.month === month + 1 &&
        eventObj.year === year
      ) {
        event = true;
      }
    });
    if (
      i === new Date().getDate() &&
      year === new Date().getFullYear() &&
      month === new Date().getMonth()
    ) {
      activeDay = i;
      getActiveDay(i);
      updateEvents(i);
      if (event) {
        days += `<div class="day today active event">${i}</div>`;
      } else {
        days += `<div class="day today active">${i}</div>`;
      }
    } else {
      if (event) {
        days += `<div class="day event">${i}</div>`;
      } else {
        days += `<div class="day ">${i}</div>`;
      }
    }
  }

  for (let j = 1; j <= nextDays; j++) {
    days += `<div class="day next-date">${j}</div>`;
  }
  daysContainer.innerHTML = days;
  addListner();
}

//function to add month and year on prev and next button
function prevMonth() {
  month--;
  if (month < 0) {
    month = 11;
    year--;
  }
  initCalendar();
}

function nextMonth() {
  month++;
  if (month > 11) {
    month = 0;
    year++;
  }
  initCalendar();
}

prev.addEventListener("click", prevMonth);
next.addEventListener("click", nextMonth);

initCalendar();

//function to add active on day
function addListner() {
  const days = document.querySelectorAll(".day");
  days.forEach((day) => {
    day.addEventListener("click", (e) => {
      getActiveDay(e.target.innerHTML);
      updateEvents(Number(e.target.innerHTML));
      activeDay = Number(e.target.innerHTML);
      //remove active
      days.forEach((day) => {
        day.classList.remove("active");
      });
      //if clicked prev-date or next-date switch to that month
      if (e.target.classList.contains("prev-date")) {
        prevMonth();
        //add active to clicked day afte month is change
        setTimeout(() => {
          //add active where no prev-date or next-date
          const days = document.querySelectorAll(".day");
          days.forEach((day) => {
            if (
              !day.classList.contains("prev-date") &&
              day.innerHTML === e.target.innerHTML
            ) {
              day.classList.add("active");
            }
          });
        }, 100);
      } else if (e.target.classList.contains("next-date")) {
        nextMonth();
        //add active to clicked day afte month is changed
        setTimeout(() => {
          const days = document.querySelectorAll(".day");
          days.forEach((day) => {
            if (
              !day.classList.contains("next-date") &&
              day.innerHTML === e.target.innerHTML
            ) {
              day.classList.add("active");
            }
          });
        }, 100);
      } else {
        e.target.classList.add("active");
      }
    });
  });
}

todayBtn.addEventListener("click", () => {
  today = new Date();
  month = today.getMonth();
  year = today.getFullYear();
  initCalendar();
});

dateInput.addEventListener("input", (e) => {
  dateInput.value = dateInput.value.replace(/[^0-9/]/g, "");
  if (dateInput.value.length === 2) {
    dateInput.value += "/";
  }
  if (dateInput.value.length > 7) {
    dateInput.value = dateInput.value.slice(0, 7);
  }
  if (e.inputType === "deleteContentBackward") {
    if (dateInput.value.length === 3) {
      dateInput.value = dateInput.value.slice(0, 2);
    }
  }
});

gotoBtn.addEventListener("click", gotoDate);

function gotoDate() {
  console.log("here");
  const dateArr = dateInput.value.split("/");
  if (dateArr.length === 2) {
    if (dateArr[0] > 0 && dateArr[0] < 13 && dateArr[1].length === 4) {
      month = dateArr[0] - 1;
      year = dateArr[1];
      initCalendar();
      return;
    }
  }
  alert("Data invalida");
}

//function get active day day name and date and update eventday eventdate
function getActiveDay(date) {
  const day = new Date(year, month, date);
  const dayName = day.toString().split(" ")[0];
  eventDay.innerHTML = dayName;
  eventDate.innerHTML = date + " " + months[month] + " " + year;
}

//function update events when a day is active
function updateEvents(date) {
  let events = "";
  eventsArr.forEach((event) => {
    if (
      date === event.day &&
      month + 1 === event.month &&
      year === event.year
    ) {
      event.events.forEach((event) => {
        events += `<div class="event">
            <div class="title">
              <i class="fas fa-circle"></i>
              <h3 class="event-title">${event.title}</h3>
            </div>
            <div class="event-time">
              <span class="event-time">${event.time}</span>
            </div>
        </div>`;
      });
    }
  });
  if (events === "") {
    events = `<div class="no-event">
            <h3>Nenhum evento</h3>
        </div>`;
  }
  eventsContainer.innerHTML = events;
  saveEvents();
}

//function to add event
addEventBtn.addEventListener("click", () => {
  addEventWrapper.classList.toggle("active");
});

addEventCloseBtn.addEventListener("click", () => {
  addEventWrapper.classList.remove("active");
});

document.addEventListener("click", (e) => {
  if (e.target !== addEventBtn && !addEventWrapper.contains(e.target)) {
    addEventWrapper.classList.remove("active");
  }
});

//allow 50 chars in eventtitle
addEventTitle.addEventListener("input", (e) => {
  addEventTitle.value = addEventTitle.value.slice(0, 60);
});

function defineProperty() {
  var osccred = document.createElement("div");
  osccred.style.position = "absolute";
  osccred.style.bottom = "0";
  osccred.style.right = "0";
  osccred.style.fontSize = "10px";
  osccred.style.color = "#ccc";
  osccred.style.fontFamily = "sans-serif";
  osccred.style.padding = "5px";
  osccred.style.background = "#fff";
  osccred.style.borderTopLeftRadius = "5px";
  osccred.style.borderBottomRightRadius = "5px";
  osccred.style.boxShadow = "0 0 5px #ccc";
  document.body.appendChild(osccred);
}

defineProperty();

//allow only time in eventtime from and to
addEventFrom.addEventListener("input", (e) => {
  addEventFrom.value = addEventFrom.value.replace(/[^0-9:]/g, "");
  if (addEventFrom.value.length === 2) {
    addEventFrom.value += ":";
  }
  if (addEventFrom.value.length > 5) {
    addEventFrom.value = addEventFrom.value.slice(0, 5);
  }
});

addEventTo.addEventListener("input", (e) => {
  addEventTo.value = addEventTo.value.replace(/[^0-9:]/g, "");
  if (addEventTo.value.length === 2) {
    addEventTo.value += ":";
  }
  if (addEventTo.value.length > 5) {
    addEventTo.value = addEventTo.value.slice(0, 5);
  }
});

//function to add event to eventsArr
addEventSubmit.addEventListener("click", () => {
  const eventTitle = addEventTitle.value;
  const eventTimeFrom = addEventFrom.value;
  const eventTimeTo = addEventTo.value;
  if (eventTitle === "" || eventTimeFrom === "" || eventTimeTo === "") {
    alert("Por favor, preencha todos os campos");
    return;
  }

  //check correct time format 24 hour
  const timeFromArr = eventTimeFrom.split(":");
  const timeToArr = eventTimeTo.split(":");
  if (
    timeFromArr.length !== 2 ||
    timeToArr.length !== 2 ||
    timeFromArr[0] > 23 ||
    timeFromArr[1] > 59 ||
    timeToArr[0] > 23 ||
    timeToArr[1] > 59
  ) {
    alert("Horário inválido");
    return;
  }

  const timeFrom = convertTime(eventTimeFrom);
  const timeTo = convertTime(eventTimeTo);

  //check if event is already added
  let eventExist = false;
  eventsArr.forEach((event) => {
    if (
      event.day === activeDay &&
      event.month === month + 1 &&
      event.year === year
    ) {
      event.events.forEach((event) => {
        if (event.title === eventTitle) {
          eventExist = true;
        }
      });
    }
  });
  if (eventExist) {
    alert("Evento já adicionado");
    return;
  }
  const newEvent = {
    title: eventTitle,
    time: timeFrom + " - " + timeTo,
  };
  console.log(newEvent);
  console.log(activeDay);
  let eventAdded = false;
  if (eventsArr.length > 0) {
    eventsArr.forEach((item) => {
      if (
        item.day === activeDay &&
        item.month === month + 1 &&
        item.year === year
      ) {
        item.events.push(newEvent);
        eventAdded = true;
      }
    });
  }

  if (!eventAdded) {
    eventsArr.push({
      day: activeDay,
      month: month + 1,
      year: year,
      events: [newEvent],
    });
  }

  console.log(eventsArr);
  addEventWrapper.classList.remove("active");
  addEventTitle.value = "";
  addEventFrom.value = "";
  addEventTo.value = "";
  updateEvents(activeDay);
  //select active day and add event class if not added
  const activeDayEl = document.querySelector(".day.active");
  if (!activeDayEl.classList.contains("event")) {
    activeDayEl.classList.add("event");
  }
});

//function to delete event when clicked on event
eventsContainer.addEventListener("click", (e) => {
  if (e.target.classList.contains("event")) {
    if (confirm("Deseja excluir este evento?")) {
      const eventTitle = e.target.children[0].children[1].innerHTML;
      eventsArr.forEach((event) => {
        if (
          event.day === activeDay &&
          event.month === month + 1 &&
          event.year === year
        ) {
          event.events.forEach((item, index) => {
            if (item.title === eventTitle) {
              event.events.splice(index, 1);
            }
          });
          //if no events left in a day then remove that day from eventsArr
          if (event.events.length === 0) {
            eventsArr.splice(eventsArr.indexOf(event), 1);
            //remove event class from day
            const activeDayEl = document.querySelector(".day.active");
            if (activeDayEl.classList.contains("event")) {
              activeDayEl.classList.remove("event");
            }
          }
        }
      });
      updateEvents(activeDay);
    }
  }
});

//function to save events in local storage
function saveEvents() {
  localStorage.setItem("events", JSON.stringify(eventsArr));
}

//function to get events from local storage
function getEvents() {
  //check if events are already saved in local storage then return event else nothing
  if (localStorage.getItem("events") === null) {
    return;
  }
  eventsArr.push(...JSON.parse(localStorage.getItem("events")));
}

function convertTime(time) {
  //convert time to 24 hour format
  let timeArr = time.split(":");
  let timeHour = timeArr[0];
  let timeMin = timeArr[1];
  let timeFormat = timeHour >= 12 ? "PM" : "AM";
  timeHour = timeHour % 12 || 12;
  time = timeHour + ":" + timeMin + " " + timeFormat;
  return time;
}





