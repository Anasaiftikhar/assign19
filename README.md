<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Assingment 10</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.7.1/css/all.min.css">
    <style>
    *{
        padding: 0;
        margin: 0;
    }
    body{
        background-color: aliceblue;
        ::selection{
            background-color:rgb(251, 0, 125);
            color: white;
        }
    }
    .div-1{
        background-image: url(./images/banner-bg.png);
        background-repeat: no-repeat;
        position: relative;
        width: 100%;
        height: 6700px;
    }
    .div-2{
        position: fixed;
        display: flex;
        background-color: white;
        height: 90px;
        width: 80%;
        margin-top: 40px;
        margin-left: 150px;
        border-radius: 50px;
        font-family: Arial, Helvetica, sans-serif;
        z-index: 2;
    }
    li{
        display: inline;
        font-size: 17px;
        float: left;
        padding-left: 55px;
        padding-top: 35px;
    }
    .anchor-1{
        text-decoration: none;
        color: black;
    }
    .anchor-1:hover{
        color: rgb(253, 88, 157);
    }
    .image-1{
        float: left;
        padding-left: 40px;
        padding-top: 30px;
    }
    .anchor-11{
        color: rgb(253, 88, 157);
        text-decoration: none;
    }
    .anchor-11:hover{
        color: rgb(253, 88, 157);
    }
    .heading1{
        color: white;
        text-align: center;
        font-size: 50px;
        font-family:  Arial, Helvetica, sans-serif;
        font-weight: 200;
    }
    .div-3{
        position: absolute;
        margin-top:280px;
        margin-left: 440px;
    }
    .div-4{
        position: absolute;
        color: white;
        margin-top: 500px;
        margin-left: 480px;
        font-size: 18px;
        padding-left:70px;
    }
    .para1{
        padding-left: 110px;
    }
    .button1{
        background-color: rgb(253, 88, 157);
        color: white;
        padding: 12px;
        border-radius: 20px;
        border: 1px solid rgb(253, 88, 157);
        margin-left: 180px;
        margin-top: 40px;
        text-align: center;
        width: 30%;
    }
    .button1:hover{
        background-color: rgb(129,98,238);
        border: 1px solid rgb(129,98,238);
    }
    .div-5{
        position: relative;
    }
    .div-6{
        position: absolute;
        display: inline;
        background-color: white;
        height: 280px;
        width: 20%;
        margin-top: 720px;
        z-index: 1;
        border-radius: 20px;
        margin-left: 200px;
        animation: move-up 1s ease-in-out;
    }
    .div-9{
        position: absolute;
        border: 1px solid rgb(129,98,238);
        background-color:rgb(129,98,238);
        margin-left:110px;
        margin-top: 30px;
        border-radius: 60px;
        width: 28%;
        height: 80px;
    }
    .image-2{
        margin-left: 15px;
        margin-top: 15px;
    }
    .div-9:hover{
        background-color: rgb(253, 88, 157);
        border: 1px solid rgb(253, 88, 157);
    }
    .heading2{
        text-align: center;
        margin-top: 150px;
        font-weight: 200;
    }
    .para2{
        text-align: center;
        margin-top:20px;
        opacity: 0.5
    }
    .div-7{
        position: absolute;
        display: inline;
        background-color: white;
        height: 280px;
        width: 20%;
        margin-top: 720px;
        z-index: 1;
        border-radius: 20px;
        margin-left: 600px;
        animation: move-up1 1s ease-in-out;
    }
    .div-8{
        position: absolute;
        display: inline;
        background-color: white;
        height: 280px;
        width: 20%;
        margin-top: 720px;
        z-index: 1;
        border-radius: 20px;
        margin-left: 1000px;
        animation: move-up2 1s ease-in-out;
    }
    .div-10{
        position: absolute;
        height: 400px;
        background-color:aliceblue;
        margin-top: 1100px;
        width: 100%;
    }
    .image3{
    position: absolute;
        margin-left: 300px;
        margin-top: 50px;
        float: left;
    }
    .heading3{
        position: absolute;
        color: black;
        margin-left: 780px;
        margin-top: 110px;
        font-weight: 250;
    }
    .para3{
        color: black;
        font-size: 20px;
        margin-left: 750px;
        margin-top: 180px;
        opacity: 0.6;
    }
    .div-11{
        position: absolute;
        height: 400px;
        background-color: aliceblue;
        margin-top: 1600px;
        width: 100%;
    }
    .image4{
        position: absolute;
        margin-left: 500px;
        margin-top: 50px;
        float: right;
    }
    .heading4{
        position: absolute;
        color: black;
        margin-left: 200px;
        margin-top: 110px;
        font-weight: 250;
    }
    .para4{
        color: black;
        font-size: 20px;
      margin-left: 200px;
        margin-top: 180px;
        opacity: 0.6;
    }
    .div-12{
        position: absolute;
        background-image: url(./images/work-process-bg.png);
        background-repeat: no-repeat;
        width: 100%;
        height: 700px;
        margin-top: 2100px;
    }
    .heading5{
        text-align: center;
        color: white;
        margin-top: 100px;
        font-size: 38px;
        font-weight: 200;
    }
    .para5{
        text-align: center;
        color: white;
        margin-top: 35px;
        font-size: 20px;
        font-weight: 100;
    }
    .div-14{
    position: absolute;
        background-color: white;
        width: 10.5%;
        height: 180px;
        border-radius: 20px;
        margin-left: 200px;
        margin-top: 70px;
        box-shadow: rgb(0, 0, 0, 0.20) 12px 12px;
        transition: transform 0.3s ease, box-shadow 0.3s ease;  
    }
    .image5{
        margin-left: 65px;
        margin-top: 25px;
    }
    .heading6{
        text-align: center;
        font-size: 23px;
        margin-top: 13px;
        font-weight: 50;
    }
    .para6{
        text-align: center;
        margin-top: 10px;
        opacity: 0.6;
    }
    .anchor-2{
        color: black;
    }
    .div-15{
        position: absolute;
        background-color: white;
        width: 10.5%;
        height: 180px;
        border-radius: 20px;
        margin-left: 400px;
        margin-top: 70px;
        box-shadow: rgb(0, 0, 0, 0.20) 12px 12px;
        transition: transform 0.3s ease, box-shadow 0.3s ease;  
    }
    .div-16{
        position: absolute;
        background-color: white;
        width: 10.5%;
        height: 180px;
        border-radius: 20px;
        margin-left: 600px;
        margin-top: 70px;
        box-shadow: rgb(0, 0, 0, 0.20) 12px 12px;
        transition: transform 0.3s ease, box-shadow 0.3s ease;  
    }
    .div-17{
        position: absolute;
        background-color: white;
        width: 10.5%;
        height: 180px;
        border-radius: 20px;
        margin-left: 800px;
        margin-top: 70px;
        box-shadow: rgb(0, 0, 0, 0.20) 12px 12px;
        transition: transform 0.3s ease, box-shadow 0.3s ease;  
    }
    .div-18{
        position: absolute;
        background-color: white;
        width: 10.5%;
        height: 180px;
        border-radius: 20px;
        margin-left: 1000px;
        margin-top: 70px;
        box-shadow: rgb(0, 0, 0, 0.20) 12px 12px; 
        transition: transform 0.3s ease, box-shadow 0.3s ease;    
    }
    .div-19{
        position: absolute;
        background-color: white;
        width: 10.5%;
        height: 180px;
        border-radius: 20px;
        margin-left: 1200px;
        margin-top: 70px;
        box-shadow: rgb(0, 0, 0, 0.20) 12px 12px;
        transition: transform 0.3s ease, box-shadow 0.3s ease;  
    }
    .div-19:hover{
        transform: translateY(-10px);
    }
    .div-18:hover{
        transform: translateY(-10px);
    }
    .div-17:hover{
        transform: translateY(-10px);
    }
    .div-16:hover{
        transform: translateY(-10px);
    }
    .div-15:hover{
        transform: translateY(-10px);
    }
    .div-14:hover{
        transform: translateY(-10px);
    }
    .div-20{
        position: absolute;
        height: 770px;
        background-color: rgb(253, 250, 250);
        width: 100%;
        margin-top: 2685px;
    }
    .heading7{
        text-align: center;
        margin-top: 100px;
        font-size: 40px;
        font-weight: 200;
    }
    .para7{
        text-align: center;
        margin-top:33px ;
        font-size: 20px;
        padding: 15px;
        font-weight: 100;
        opacity: 0.5;
    }
    .div-21{
        position: absolute;
        width: 22%;
        height: 320px;
        background-color: white;
        border-radius:20px;
        margin-left: 180px;
        margin-top: 60px;
        z-index: 1;
    }
    .div-22{
        position: absolute;
        width: 22%;
        height: 320px;
        background-color: white;
        border-radius:20px;
        margin-left: 580px;
        margin-top: 60px;
    }
    .div-23{
        position: absolute;
        width: 22%;
        height: 320px;
        background-color: white;
        border-radius:20px;
        margin-left: 980px;
        margin-top: 60px; 
    }
    .image6{
        margin-left: 160px;
        margin-top: 30px;
    }
    .para8{
        font-size: 20px;
        margin-left: 20px;
        margin-top: 40px;
        opacity: 0.6;
    }
    .div-24{
        display: inline;
        position: absolute;
        background-color: darkgray;
        width: 20%;
        height: 70px;
        border-radius: 50px;
        margin-top: 30px;
        margin-left: 25px;
    }
    h5{
        position: absolute;
        margin-top: 25px;
        margin-left: 12px;
        opacity: 0.3;
    }
    .heading8{
        font-size: 22px;
        margin-left:110px;
        margin-top: 40px;
        font-weight: 100;
        transition: transform 0.3s ease;
    }
    .heading8:hover{
        transform: translateX(10px)
    }
    .heading9{
        font-size: 21px;
        margin-left:110px;
        margin-top: 10px;
        font-weight: 100;
        color: rgb(253, 88, 157);
        transition: transform 0.3s ease;
    }
    .heading9:hover{
        transform: translateX(10px)
    }
    .div-25{
        position: absolute;
        background-color: rgb(233, 232, 232);
        width: 100%;
        height: 1000px;
        margin-top: 3400px;
    }
    .heading10{
        position: absolute;
        margin-top: 50px;
        margin-left: 700px;
        font-size: 40px;
        font-weight: 200;
    }
    .para9{
        text-align: center;
        margin-top: 120px;
        font-size: 20px;
        font-weight: 100;
        opacity: 0.5;
    }
    .div-26{
        height: 600px;
        width: 23%;
        background-color: white;
        border-radius: 20px;
        position: absolute;
        margin-top: 100px;
        margin-left: 200px;
        animation: move-up3 1s ease-in-out;
    }
    .div-27{
        height: 600px;
        width: 23%;
        background-color: white;
        border-radius: 20px;
        position: absolute;
        margin-top: 100px;
        margin-left: 600px;
        animation: move-up4 1s ease-in-out;
    }
    .div-28{
        height: 600px;
        width: 23%;
        background-color: white;
        border-radius: 20px;
        position: absolute;
        margin-top: 100px;
        margin-left: 1000px;
        animation: move-up5 1s ease-in-out;
    }
    .heading11{
        font-size: 25px;
        margin-left: 140px;
        margin-top: 40px;
        font-weight: 100;
    }
    .heading12{
        font-size: 25px;
        margin-left: 140px;
        margin-top: 40px;
        font-weight: 100;
    }
    .heading13{
        font-size: 25px;
        margin-left: 140px;
        margin-top: 40px;
        font-weight: 100;
    }
    .div-29{
        height: 130px;
        width: 80%;
        background-color: rgb(129,98,238);
        position: absolute;
        margin-left:40px;
        border-radius: 20px;
        margin-top: 30px;
    }
    .div-30{
        height: 130px;
        width: 80%;
        background-color: rgb(253, 88, 157);
        position: absolute;
        margin-left:40px;
        border-radius: 20px;
        margin-top: 30px; 
    }
    .div-31{
        height: 130px;
        width: 80%;
        background-color: rgb(129,98,238);
        position: absolute;
        margin-left:40px;
        border-radius: 20px;
        margin-top: 30px;
    }
    .span1{
        position: absolute;
        font-size: 50px;
        color: white;
        margin-left: 50px;
        margin-top: 10px;
    }
    .span2{
        position: absolute;
        font-size: 40px;
        color: white;
        margin-left: 90px;
        margin-top: 30px;
    }
    .para10{
        position: absolute;
        color: white;
        font-size: 20px;
       margin-left: 100px;
       margin-top: 90px;
    }
    .para11{
        position: absolute;
        margin-top: 220px;
        margin-left: 140px;
        opacity: 0.6;
    }
    .para12{
        position: absolute;
        margin-top: 250px;
        margin-left: 130px;
        opacity: 0.6;
    }
    .para13{
        position: absolute;
        margin-top: 280px;
        margin-left: 130px;
        opacity: 0.6;
    }
    .para14{
        position: absolute;
        margin-top: 310px;
        margin-left: 130px;
        opacity: 0.6;
    }
    .para15{
        position: absolute;
        margin-top: 340px;
        margin-left: 130px;
        opacity: 0.6;
    }
    .para16{
        position: absolute;
        margin-top: 370px;
        margin-left: 140px;
        opacity: 0.6;
    }
    .button2{
        width: 50%;
        height: 40px;
        background-color: rgb(129,98,238);
        border-radius: 50px;
        border: 1px solid rgb(129,98,238);
        color: white;
        margin-top: 450px;
        margin-left: 90px;
    }
    .button2:hover{
        background-color: rgb(253, 88, 157);
        border: 1px solid rgb(253, 88, 157);
    }
    .div-32{
        position: absolute;
        height: 370px;
        width: 100%;
        background-image: url(./images/featured-item-01.png);
        margin-top: 4400px;
    }
    .heading14{
        position: absolute;
        color: white;
        margin-left: 320px;
        font-size: 45px;
        margin-top: 140px;
        transition: all 0.3s ease; 
    }
    .heading15{
        position: absolute;
        color: white;
        margin-left: 320px;
        font-size: 22px;
        margin-top: 185px;
        font-weight: 100;
        transition: all 0.3s ease; 
    }
    .image7{
        position: absolute;
        margin-left: 460px;
        margin-top: 150px;
    }
    .heading14:hover{
        transform: translateY(-10px);
    }
    .heading15:hover{
        transform: translateY(-10px);
    }
    .heading16{
        position: absolute;
        color: white;
        margin-left: 620px;
        font-size: 45px;
        margin-top: 120px;
        transition: all 0.3s ease; 
    }
    .heading17{
        position: absolute;
        color: white;
        margin-left: 600px;
        font-size: 18px;
        margin-top: 170px;
        font-weight: 100;
        transition: all 0.3s ease; 
    }
    .image8{
        position: absolute;
        margin-left: 770px;
        margin-top: 130px;
    }
    .heading16:hover{
        transform: translateY(-10px);
    }
    .heading17:hover{
        transform: translateY(-10px);
    }
    .heading18{
        position: absolute;
        color: white;
        margin-left: 900px;
        font-size: 45px;
        margin-top: 100px;
        transition: all 0.3s ease; 
    }
    .heading19{
        position: absolute;
        color: white;
        margin-left:880px;
        font-size: 18px;
        margin-top: 155px;
        font-weight: 100;
        transition: all 0.3s ease; 
    }
    .image9{
        position: absolute;
        margin-left: 1020px;
        margin-top: 110px;
    }
    .heading18:hover{
        transform: translateY(-10px);
    }
    .heading19:hover{
        transform: translateY(-10px);
    }
    .heading20{
        position: absolute;
        color: white;
        margin-left: 1140px;
        font-size: 45px;
        margin-top: 80px;
        transition: all 0.3s ease; 
        
    }
    .heading21{
        position: absolute;
        color: white;
        margin-left:1125px;
        font-size: 18px;
        margin-top: 135px;
        font-weight: 100;
        transition: all 0.3s ease; 
    }
    .heading20:hover{
        transform: translateY(-10px);
    }
    .heading21:hover{
        transform: translateY(-10px);
    }
    .div-33{
        position: absolute;
        height: 870px;
        width: 100%;
        background-color: white;
        margin-top: 4760px;
    }
    .heading22{
        text-align: center;
        margin-top: 100px;
        font-weight: 100;
        font-size: 40px;
    }
    .para17{
        text-align: center;
        margin-top: 30px;
        opacity: 0.5;
        font-size: 20px;
    }
    .div-34{
        position: absolute;
        height: 220px;
        width: 23%;
        border-radius: 20px;
        margin-left: 230px;
        margin-top: 70px;
        background-image: url(./images/blog-item-01.png);
    }
    .div-35{
        position: absolute;
        height: 220px;
        width: 23%;
        border-radius: 20px;
        margin-left: 620px;
        margin-top: 70px;
        background-image: url(./images/blog-item-02.png);
    }
    .div-36{
        position: absolute;
        height: 220px;
        width: 23%;
        border-radius: 20px;
        margin-left: 1010px;
        margin-top: 70px;
        background-image: url(./images/blog-item-03.png);
    }
    .div-37{
        position: absolute;
        height: 300px;
        width: 23%;
        margin-left: 230px;
        margin-top: 300px;
    }
    .heading23{
        position: absolute;
        text-align: center;
        font-weight: 100;
        font-size: 22px;
        margin-left: 70px;
        margin-top: 10px;
    }
    .heading23:hover{
        color: rgb(253, 88, 157);
    }
    .div-38{
        position: absolute;
        height: 300px;
        width: 23%;
        margin-left: 620px;
        margin-top: 300px;
    }
    .div-39{
        position: absolute;
        height: 300px;
        width: 23%;
        margin-left: 1010px;
        margin-top: 300px;
    }
    .para18{
        margin-top: 70px;
        margin-left: 10px;
        opacity: 0.5;
    }
    .para19{
        margin-top: 70px;
        margin-left: 10px;
        opacity: 0.5;
    }
    .para20{
        margin-top: 70px;
        margin-left: 10px;
        opacity: 0.5;
    }
    .button3{
        height: 50px;
        width: 34%;
        border-radius: 40px;
        background-color: rgb(129,98,238);
        color: white;
        border: 1px solid rgb(129,98,238);
        margin-left: 120px;
        margin-top: 68px;
    }
    .button3:hover{
        background-color: rgb(253, 88, 157);
        border: 1px solid rgb(253, 88, 157);
    }
    .anchor-12{
        text-decoration: none;
        color: white;
    }
    .button4{
        height: 50px;
        width: 34%;
        border-radius: 40px;
        background-color:rgb(129,98,238);
        color: white;
        border: 1px solid rgb(129,98,238);
        margin-left: 120px;
        margin-top: 50px;
    }
    .button4:hover{
        background-color: rgb(253, 88, 157);
        border: 1px solid rgb(253, 88, 157);
    }
    .button5{
        height: 50px;
        width: 34%;
        border-radius: 40px;
        background-color: rgb(129,98,238);
        color: white;
        border: 1px solid rgb(129,98,238);
        margin-left: 120px;
        margin-top: 70px;
    }
    .button5:hover{
        background-color: rgb(253, 88, 157);
        border: 1px solid rgb(253, 88, 157);
    }
    .div-40{
        position: absolute;
        height: 854px;
        width: 100%;
        background-color: aliceblue;
        margin-top: 5600px;
    }
    .heading24{
        text-align: center;
        font-weight: 100;
        margin-top: 150px;
    }
    .para21{
        text-align: center;
        font-size: 20px;
        margin-top: 10px;
        opacity: 0.5;
    }
    .heading25{
        position: absolute;
        font-weight: 100;
        margin-left: 200px;
        margin-top: 100px;
    }
    .para22{
        position: absolute;
        opacity: 0.5;
        margin-left: 200px;
        margin-top: 170px;
    }
    .para23{
        position: absolute;
        opacity: 0.5;
        margin-left: 200px;
        margin-top: 260px;
    }
    .input1{  
         position: absolute;
        border-radius: 40px;
        background-color: white;
        border: 1px solid white;
        height: 60px;
        width: 22%;
        margin-left: 600px;
        margin-top: 100px;
        padding: 5px;
        transition: outline 0.3s ease;
    }
    .input1:focus{
        outline: 5px solid rgb(144, 202, 238);
    }
    .input2{
        border-radius: 40px;
        background-color: white;
        border: 1px solid white;
        height: 60px;
        width: 22%;
        margin-left: 1000px;
        margin-top: 100px;
        padding: 5px;
        transition: outline 0.3s ease;
    }
    .input2:focus{
        outline: 5px solid rgb(144, 202, 238);
    }
    .input3{
        border-radius: 20px;
        background-color: white;
        border: 1px solid white;
        height: 180px;
        width: 47%;
        margin-left: 600px;
        margin-top: 40px;
        padding: 5px;
        transition: outline 0.3s ease;
    }
    .input3:focus{
        outline: 5px solid rgb(144, 202, 238);
    }
    .button6{
        height: 50px;
        width: 10%;
        border-radius: 40px;
        background-color: rgb(129,98,238);
        color: white;
        border: 1px solid rgb(129,98,238);
        margin-left: 600px;
        margin-top: 20px;
    }
    .button6:hover{
        background-color: rgb(253, 88, 157);
        border: 1px solid rgb(253, 88, 157);
    }
    .anchor-13{
        text-decoration: none;
        color: white;
    }
    .div-41{
        margin-top: 6490px;
        position: absolute;
        height: 200px;
        width: 100%;
        background-color: rgb(158, 80, 215);
    }
    .fa-brands{
        font-size: 20px;
        position: absolute;
        border: 1px solid white;
        padding: 8px;
        background-color: white;
        color: rgb(129,98,238);
        border-radius: 50px;
       margin-left: 550px;
       margin-top: 12px;
    }
    .fa-solid{
        font-size: 20px;
        position: absolute;
        border: 1px solid white;
        padding: 7px;
        background-color: white;
        color: rgb(129,98,238);
        border-radius: 50px;
        margin-left: 550px;
        margin-top: 14px;
    }
    .fa-solid:hover{
        color: white;
        border: 1px solid rgb(253, 88, 157);
        background-color: rgb(253, 88, 157);
    }
    .fa-brands:hover{
        color: white;
        border: 1px solid rgb(253, 88, 157);
        background-color: rgb(253, 88, 157); 
    }
    hr{
        color: black;
        margin-top: 110px;
        width: 60%;
        margin-left: 260px;
        opacity: 0.3;
    }
    .para24{
        color: white;
        position: absolute;
        margin-left: 500px;
        font-size: 17px;
        margin-top: 30px;
        opacity: 0.8;
    }
    @keyframes moveLeftToRight {
        0% {
          left: 0;
        }
        100% {
          left: 100px;
        }
      }
    .image3 {
        position: absolute;
        animation: moveLeftToRight 1s ease-out forwards;
      }
    .image4 {
        position: absolute;
        animation: moveRightToLeft 1s ease-out forwards;
      }
      @keyframes moveRightToLeft {
        0% {
          right: 200px;
        }
        100% {
          right: 400px;
        }
      }
      @keyframes move-up {
        from {
          transform: translateY(160px);
        }
        to {
          transform: translateY(0);
        }
      }
      @keyframes move-up1 {
        from {
          transform: translateY(200px);
        }
        to {
          transform: translateY(0);
        }
      }
      @keyframes move-up2 {
        from {
          transform: translateY(240px);
        }
        to {
          transform: translateY(0);
        }
      }
      @keyframes move-up3 {
        from {
          transform: translateY(160px);
        }
        to {
          transform: translateY(0);
        }
      }
      @keyframes move-up4 {
        from {
          transform: translateY(200px);
        }
        to {
          transform: translateY(0);
        }
      }
      @keyframes move-up5 {
        from {
          transform: translateY(240px);
        }
        to {
          transform: translateY(0);
        }
      }</style>
</head>

<body>
    <div class="div-1">
        <div class="div-2">
            <ul>           
                 <img src="./images/logo.png" alt="Error" class="image-1">
           <a href="#" class="anchor-11"><li>Home</li></a>
           <a href="#"  class="anchor-1"><li>About</li></a>
           <a href="#"  class="anchor-1"><li>Work Process</li></a>
            <a href="#"  class="anchor-1"><li>Testimonials</li></a>
            <a href="#"  class="anchor-1"><li>Pricing Tables</li></a>
            <a href="#"  class="anchor-1"><li>Blog Entries</li></a>
            <a href="#"  class="anchor-1"> <li>Contact Us</li></a>
        </ul>
        </div>

        <div class="div-3">
        <h1 class="heading1 pt-44">We provide the best  <strong><b style="font-size: 65px;">strategy</b></strong><br> 
            to grow up your <strong><b style="font-size:65px ;">business</b></strong> </h1>
        </div>

        <div class="div-4">
            <p>Softy Pinko is a professional Bootstrap 4.0 theme designed by Template Mo</p> <br><p class="para1">for your company at absolutely free of charge</p> 
            <button class="button1">DISCOVER MORE</button>
        </div>

        <div class="div-5">
            <div class="div-6"><div class="div-9"><img src="./images/featured-item-01.png" alt="Error" class="image-2"></div>
            <h2 class="heading2">Modern Strategy</h2>
        <p class="para2">Customize anything in this template to fit <br> your website needs</p></div>

            <div class="div-7"><div class="div-9"><img src="./images/featured-item-01.png" alt="Error" class="image-2"></div> <h2 class="heading2">Best Relationship</h2><p class="para2">Contact us immediately if you have a <br> question in mind</p></div>

            <div class="div-8"><div class="div-9"><img src="./images/featured-item-01.png" alt="Error" class="image-2"></div>
            <h2 class="heading2">Ultimate Marketing</h2>
            <p class="para2">You just need to tell your friends about our <br> free templates</p></div>

            <div class="div-10"><img src="./images/left-image.png" alt="#" class="image3">
            <h1 class="heading3"> Let’s discuss about you project</h1>
            <p class="para3">Nullam sit amet purus libero. Etiam ullamcorper nisl ut augue <br> blandit, at finibus leo efficitur. Nam gravida purus non sapien <br> auctor, ut aliquam magna ullamcorper.</p></div>

            <div class="div-11">
                <img src="./images/right-image.png" alt="#" class="image4">
                <h1 class="heading4">
                    We can help you to grow your business</h1>
                <p class="para4">Aenean pretium, ipsum et porttitor auctor, metus ipsum iaculis <br> nisi, a bibendum lectus libero vitae urna. Sed id leo eu dolor <br> luctus congue sed eget ipsum. Nunc nec luctus libero. Etiam <br> quis dolor elit.</p></div>

                <div class="div-12">
                   <div class="div-13"><h1 class="heading5">Work Process</h1>
                    <p class="para5">Aenean nec tempor metus. Maecenas ligula dolor, commodo in imperdiet <br> interdum, vehicula ut ex. Donec ante diam</p></div>

                    <a href="#" class="anchor-2"><div class="div-14"><img src="./images/work-process-item-01.png" alt="#" class="image5"><h1 class="heading6">Get Ideas</h1><p class="para6">Godard pabst <br> prism fam <br> cliche.</p></div></a>

                    <a href="#" class="anchor-2"><div class="div-15"><img src="./images/work-process-item-01.png" alt="#" class="image5"><h1 class="heading6">Sketch Up</h1><p class="para6">Godard pabst <br> prism fam <br> cliche.</p></div></a>

                        <a href="#" class="anchor-2"><div class="div-16"><img src="./images/work-process-item-01.png" alt="#" class="image5"><h1 class="heading6">Discuss</h1><p class="para6">Godard pabst <br> prism fam <br> cliche.</p></div></a>

                            <a href="#" class="anchor-2"><div class="div-17"><img src="./images/work-process-item-01.png" alt="#" class="image5"><h1 class="heading6">Revise</h1><p class="para6">Godard pabst <br> prism fam <br> cliche.</p></div></a>

                                <a href="#" class="anchor-2"><div class="div-18"><img src="./images/work-process-item-01.png" alt="#" class="image5"><h1 class="heading6">Approve</h1><p class="para6">Godard pabst <br> prism fam <br> cliche.</p></div></a>

                                    <a href="#" class="anchor-2"><div class="div-19"><img src="./images/work-process-item-01.png" alt="#" class="image5"><h1 class="heading6">Launch</h1><p class="para6">Godard pabst <br> prism fam <br> cliche.</p></div></a>
                </div>
                <div class="div-20"><h1 class="heading7">What do they say?</h1><p class="para7">Donec tempus, sem non rutrum imperdiet, lectus orci fringilla nulla, <br> at accumsan elit eros a turpis. Ut sagittis lectus libero.</p>

                    <div class="div-21"><img src="./images/testimonial-icon.png" alt="#" class="image6"><p class="para8">Proin a neque nisi. Nam ipsum nisi,<br> venenatis ut nulla quis, egestas <br> scelerisque orci. Maecenas a finibus <br> odio.</p>
                    <div class="div-24"><h5>60 * 60</h5></div><h1 class="heading8">Catherine Soft</h1><h2 class="heading9">Managing Director</h2></div>

                    <div class="div-22"><img src="./images/testimonial-icon.png" alt="#" class="image6"><p class="para8">Integer molestie aliquam gravida. <br> Nullam nec arcu finibus, imperdiet nulla <br> vitae, placerat nibh. Cras maximus venenatis molestie.</p> <div class="div-24"><h5>60 * 60</h5></div><h1 class="heading8">Kelvin Wood</h1><h2 class="heading9">Digital Marketer</h2></div>

                    <div class="div-23"><img src="./images/testimonial-icon.png" alt="#" class="image6"><p class="para8">Quisque diam odio, maximus ac <br> consectetur eu, auctor non lorem. Cras <br> quis est non ante ultrices molestie. Ut <br> vehicula et diam at aliquam.</p><div class="div-24"><h5>60 * 60</h5></div><h1 class="heading8">David Martin</h1><h2 class="heading9">Website Manager</h2></div>
                </div>
                
                <div class="div-25"><h1 class="heading10">Pricing Plans</h1><p class="para9">Donec vulputate urna sed rutrum venenatis. Cras consequat magna <br> quis arcu elementum, quis congue risus volutpat.</p>
                <div class="div-26"><h1 class="heading11">Starter</h1><div class="div-29"><span class="span1">$</span class><span class="span2">14.50</span>
                <p class="para10">monthly</p></div>
                <p class="para11">60 GB space</p>
                <p class="para12">600 GB transfer</p>
                <p class="para13">Pro Design Panel</p>
                <p class="para14"><s>15-minute support</s></p>
                <p class="para15"><s>Unlimited Emails</s></p>
                <p class="para16"><s>24/7 Security</s></p>   <button class="button2">PURCHASE NOW</button></div>

                <div class="div-27"><h1 class="heading12">Premium</h1><div class="div-30"><span class="span1">$</span class><span class="span2">21.50</span>
                    <p class="para10">monthly</p></div>
                <p class="para11">60 GB space</p>
                <p class="para12">600 GB transfer</p>
                <p class="para13">Pro Design Panel</p>
                <p class="para14">15-minute support</p>
                <p class="para15"><s>Unlimited Emails</s></p>
                <p class="para16"><s>24/7 Security</s></p>   <button class="button2">PURCHASE NOW</button></div>

                <div class="div-28"><h1 class="heading13">Advance</h1><div class="div-31"><span class="span1">$</span class><span class="span2">42.00</span>
                    <p class="para10">monthly</p></div><p class="para11">60 GB space</p>
                    <p class="para12">600 GB transfer</p>
                    <p class="para13">Pro Design Panel</p>
                    <p class="para14">15-minute support</p>
                    <p class="para15">Unlimited Emails</p>
                    <p class="para16">24/7 Security</p><button class="button2">PURCHASE NOW</button></div>
                 
                </div>

                <div class="div-32"><h1 class="heading14">126</h1><br><h2 class="heading15">Projects</h2><img src="./images/circle-dec.png" alt="#" class="image7">

                    <h1 class="heading16">63</h1><br><h2 class="heading17">Happy Clients</h2><img src="./images/circle-dec.png" alt="#" class="image8">

                    <h1 class="heading18">18</h1><br><h2 class="heading19">Award Wins</h2><img src="./images/circle-dec.png" alt="#" class="image9">

                    <h1 class="heading20">27</h1><br><h2 class="heading21">Countries</h2>

                </div>

                <div class="div-33">
                    <h1 class="heading22">Blog Entries</h1><p class="para17">Integer molestie aliquam gravida. Nullam nec arcu finibus, imperdiet <br> nulla vitae, placerat nibh. Cras maximus venenatis molestie.</p>
                    
                    <div class="div-34"></div>
                    
                    <div class="div-35"></div>

                        <div class="div-36"></div>
                        
                        <div class="div-37"><h1 class="heading23">Vivamus ac vehicula dui</h1><p class="para18">Cras aliquet ligula dui, vitae fermentum velit tincidunt <br> id. Praesent eu finibus nunc. Nulla in sagittis eros. <br> Aliquam egestas augue.</p><a href="#" class="anchor-12"><button class="button3">READ MORE</a></button></div>
                        
                        <div class="div-38"><h1 class="heading23">Phasellus convallis augue</h1><p class="para19">Aliquam commodo ornare nisl, et scelerisque nisl <br> dignissim ac. Vestibulum finibus urna ut velit venenatis, <br> vel ultrices sapien mattis.</p><a href="#" class="anchor-12"><button class="button4">READ MORE</a></button></div>
                        
                        <div class="div-39"><h1 class="heading23">Nam gravida purus non</h1><p class="para20">Maecenas eu erat vitae dui convallis consequat vel  <br>gravida nulla. Vestibulum finibus euismod odio, ut <br> tempus enim varius eu.</p><a href="#" class="anchor-12"><button class="button5">READ MORE</a></button></div>

                    </div>

                    <div class="div-40">
                        
                        <h1 class="heading24">Talk To Us</h1><p class="para21">Maecenas pellentesque ante faucibus lectus vulputate sollicitudin. <br> Cras feugiat hendrerit semper.</p><h2 class="heading25">Keep in touch</h2><p class="para22">110-220 Quisque diam odio, maximus ac <br> consectetur eu, 10260 <br>
                        auctor non lorem</p>
                        
                        <p class="para23">You are NOT allowed to re-distribute Softy Pinko <br> template on any template collection websites. <br> Thank you.</p>
                        <input type="text" placeholder="Full Name" required class="input1">
                        
                        <input type="email" placeholder="Email-Address" required class="input2">
                        
                        <input type="text"  placeholder=" Your Message" required class="input3">
                       
                        <a href="#" class="anchor-13"><button class="button6">READ MORE</a></button>
                   
                    </div>
                    
                        <div class="div-41">
                            <ul>
                                <li><a href="#"><i class="fa-brands fa-facebook"></i></a></li>
                                <li><a href="#"><i class="fa-brands fa-twitter"></i></a></li>
                                <li><a href="#"><i class="fa-brands fa-linkedin-in"></i></a></li>
                                <li><a href="#"><i class="fa-solid fa-wifi"></i></a></li>
                                <li><a href="#"><i class="fa-solid fa-basketball"></i></a></li>
                            </ul>
                            <hr class="hr1">
                            <p class="para24">Copyright © 2020 Softy Pinko Company - Design: TemplateMo</p>     
        </div>
    
            </div>
</body>
</html>
