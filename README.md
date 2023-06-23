
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta http-equiv="X-UA-Compatible" content="IE-edge">
<meta name="viewport" content="width=device-width, inital-scale=1.0">
<title> Ismail Web - Developer Protfolio</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Poppins&display=swap" rel="stylesheet">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
.fa {
  padding: 20px;
  font-size: 30px;
  width: 30px;
  text-align: center;
  text-decoration: none;
  margin: 2px 22px;
  border-radius: 50%;
}

    *{
        margin: 0;
        padding: 0;
    }
    body {
        background-color: rgb(0, 0, 40);
        color: white;
        font-family: 'Poppins',sans-serif;
    }
    nav{
         display:  flex;
         justify-content: space-around;
         align-items: center;
         height: 90px;
         background-color:rgb(6, 6, 85) ;
    }
    nav ul{
         display: flex;
         justify-content: center;
    }
    nav ul li{
        list-style: none;
        margin: 0 28px;
    }
    .left{
        font-size: 2rem;
    }
    .firstsection{
         display: flex;
        justify-content: space-around;
        margin: 25px 0;
        }
        .firstsection > div{
            width: 30%;
        }
        .leftsection{
           
           font-size: 2.5rem;
        }
        .rightsection img{
         width: 120%;
         margin: 80px 0;
        }
        .purple{
            color: aqua;
        }
   #element{
        color: aqua;
   }
   .fa-linkedin {
  background: #007bb5;
  color: white;
}

</style>
</head>
<body>
    <header>
        <nav>

            <div class=" left"> Ismail's Protfolio </div>
            <div class="right">
            <ul>
                <li> Home</li>
                <li>About</li>
                <li>Services</li>
                <li>Contact</li>
            </ul>
            </div>
        </nav>
    </header>
    <main>
      <section class="firstsection">
       <div class="leftsection"> Hi, My name is 
        <span class="purple"> Ismail</span>
        <div> i am a passionate</div>
        <span id="element"></span>

    </div>
      
       <div class="rightsection">
       <img src="n.png" alt="">
       </div>
      </section>
      
 
    </main>
    <script src="https://unpkg.com/typed.js@2.0.16/dist/typed.umd.js"></script>

    <script>
        var typed = new Typed('#element', {
          strings: ['Web Developer'],
          typeSpeed: 50,
        });
      </script>
<a href="https://www.linkedin.com/in/ismail-shaik-06b918213/" class="fa fa-linkedin"></a>


</body>



</html>

