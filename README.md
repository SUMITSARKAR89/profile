<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>front page</title>
    <link rel="stylesheet" href="style.css">
<style>
    @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@600&display=swap');
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family:"poppins",sans-serif;
}
.container{
    width: 100%;
    height: 100vh;
    background: url(/img/319769011_453188326827611_1019298291264687685_n.jpg);
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    display: flex;
    justify-content: center;
    align-items: flex-start;
    flex-direction: column;
    padding:5px;
    transition: all 0.4s;  
}
.container .contains{
    width: 80%;
    padding-left:50px
}
.container .contains .first-letter h1{
    font-size: 90px;
    color: rgba(8, 0, 0, 0.795);
    padding: 15px;
}
.container .contains .first-letter h2{
    font-weight: lighter;
    font-size:40px ;
    padding: 15px; 
}
.text{
    padding:15px;
    font-size: 20px;
    text-align: left;
}
.container .contains .btn{
    text-decoration: none;
    font-size: 20px;
    padding: 6px 5px;
    border: 1px solid white;
    border-radius: 8px;
    margin:5px 15px;
    text-align: center;
    color: rgb(52, 26, 224);
    background-color: rgba(241, 217, 4, 0.616);
    transition: all 0.4s;
}
.container .contains .btn:hover{
    background-color: #f8c009;
    color: rgb(7, 6, 0);
    border: 1px solid rgba(255, 217, 0, 0.548);  
}
@media (max-width:700px){
    .container .contains{
        width: 70%;
        padding-left: 20px;
        transition: all 0.4s;
    }
    .container .contains .first-letter h1{
        font-size: 65px;
    }
    .container .contains .first-letter h2{
        font-size: 25px;
    }
    .text{
        font-size: 15px;
    }
}
@media (max-width:600px){
    .container{
        background: linear-gradient(
            rgba(0,0,0,0.3)
            rgba(218, 25, 19, 0.712),
            rgb(231, 224, 182),
            rgb(74, 74, 182)
        ) url(/img/profile\ pic2.jpg);
        background-size: cover;
        background-position: bottom;
        transition: all 0.4s;
    }
    .container .contains{
        width: 100%;
        color: rgb(231, 213, 213);
        padding: 250px 20px 0;   
    }  
}
</style>
</head>
<body>
    <div class="container">
        <div class="contains">
            <div class="first-letter">
                <h1>Hello</h1>
                <h2>I am Sumit Sarkar</h2>
            </div>
            <p class="text" ><strong style="font-size: 25px; color:#fff">Learner Design Website with <b style="color: rgba(218, 66, 218, 0.938);">HTML & CSS.</b></strong><br>
                Lorem ipsum dolor, sit amet consectetur adipisicing elit. <br> Aperiam temporibus, esse corporis neque laboriosam quisquam, <br> blanditiis dolore unde sit tempore. </p>
            <a href="#" class="btn">My Work</a>
        </div>
    </div>
</body>
</html>
