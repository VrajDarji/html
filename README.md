# html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<style>
    body{
        background-color: rgb(202, 200, 200);
        
    }
    .container{
        margin-left:110px ;
        width: 1300px;
        margin-top: 110px;
        background-color: aliceblue;
       box-shadow: 16px 16px 16px 16px rgba(0, 0, 0, 0.2), 16px 16px 20px 16px rgba(0, 0, 0, 0.19);
    }
     nav{
        background-color: aliceblue;
        text-align: justify;
    }
    button.mm{
        align-items: center;
        color:black;
        background-color: rgb(255, 255, 255);
        padding:10px 25px;
        margin-left: 11px;
        margin-right: 355px;
        border: rgb(255, 255, 255);
        border-radius: 5px;
        /* box-shadow: 5px; */
        display: inline;
        /* box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(255, 255, 255, 0.19); */
    }
    button.t{
        align-items: center;
        color:black;
        background-color: rgb(255, 255, 255);
        padding:10px 25px;
        margin-left: 11px;
        border: aquamarine;
        border-radius: 5px;
        box-shadow: 5px;
        display: inline-block;
        box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(255, 255, 255, 0.19);
    }
    button:hover{
        color:rgb(0, 0, 0);
        background-color: rgb(231, 224, 224);
        transition: 0.4s;
        box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
    }
    button.su{
        align-items: center;
        color:black;
        background-color: rgb(255, 255, 255);
        padding:10px 25px;
        margin-left: 395px;
        border: rgb(255, 255, 255);
        border-radius: 5px;
        /* box-shadow: 5px; */
        display: inline;
        /* box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(255, 255, 255, 0.19); */
    }
    button.sur{
        align-items: center;
        color:black;
        background-color: rgb(255, 255, 255);
        padding:10px 25px;
        /* margin-left: 56px; */
        border: rgb(255, 255, 255);
        border-radius: 5px;
        /* box-shadow: 5px; */
        display: inline;
        /* box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(255, 255, 255, 0.19); */
    }
    .sp p{
        font-size: medium;
        font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
        font-weight: 300;
        font-size: 17px;
        color: rgb(117, 115, 154);
        border-radius: 7px;
        background-color: rgb(197, 227, 227);
        width: 150px;
    }
    .main {
        margin-left: 20px;
        display: flex;
        font-size: 78px;
        font-weight: 400;
        font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
        color: rgba(42, 47, 97, 0.856);
    }
    .tem{
        margin-left: 60px;
        margin-right: 60px;
        font-size: medium;
        font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
    }
    .main img{
        display: flex;
        align-self: auto;
        margin-top: 0%;
    }
    .tem button.ty{
        align-items: center;
        color:black;
        font-size: 15px;
        background-color: rgb(255, 255, 255);
        padding:20px 55px;
        margin-left: 400px;
        border: rgb(255, 255, 255);
        border-radius: 8px;
        /* box-shadow: 5px; */
        display: inline-block;
        box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(255, 255, 255, 0.19);
    }
    .tem button{
        align-items: center;
        color:black;
        font-size: 15px;
        margin-left: 10PX;
        background-color: rgb(255, 255, 255);
        padding:20px 55px;
        border: rgb(255, 255, 255);
        border-radius: 8px;
        /* box-shadow: 5px; */
        display: inline-block;
        box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(255, 255, 255, 0.19);
    }
    .tem button:hover.ty{
        align-items: center;
        color:black;
        font-size: 15px;
        background-color:rgb(104, 217, 56);
        padding:20px 55px;
        margin-left: 400px;
        border: rgb(104, 217, 56);
        border-radius: 8px;
        box-shadow: 5px;
        display: inline-block;
        box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.2);
    }
    .tem button:hover{
        align-items: center;
        color:black;
        font-size: 15px;
        background-color: rgb(104, 217, 56);
        padding:20px 55px;
        border: rgb(104, 217, 56);
        border-radius: 8px;
        box-shadow: 5px;
        display: inline-block;
        box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
    }
   
</style>
<body>
    <nav>
        <hr>
        <a href=""><button class="mm">COMPANY </button></a>
        <a href=""><button class="t">Home</button></a>
        <a href=""><button class="t">Product</button></a>
        <a href=""><button class="t">Pricing</button></a>
        <a href=""><button class="t">Support</button></a>
        <a href=""><button class="su">Sign In</button></a>
        <a href=""><button class="sur">Sign Up</button></a>
        <hr>
    </nav>
    <div class="container">
    <div class="sp">
        <br>
        <p>&nbsp;&nbsp;Special Promotion&nbsp;</p>
    </div>
    <img width="500" align="right"src="https://classplusapp.com/growth/wp-content/uploads/2022/06/Importance-of-Group-Discussion-In-Teaching-1024x571.jpg" alt="">

    <div class="main">
        Make  Discuusion <br>Become Morebr <br>Comfortable
    </div>
    <div class="tem">
        <br>
        New and modern way to Lorem ipsum dolor sit amet consectetur adipisicing elit. Eos, odit! Rem accusamus quia in? Molestias ab nisi libero iure quia praesentium obcaecati doloribus exercitatibr <br><br>
        <button class="ty">Get Started</button><button>Learn More</button>
        <br><br>
        <hr>
    </div>
    <div class="tru">

    </div>
</div>
</body>
</html>
