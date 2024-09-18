<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>css assignment 1</title>
    <link rel="stylesheet" href="../CSS/css/css/all.min.css">
    <style>
         body
        {
            background-color: white;
        }
        
        @media screen and (max-width:1200px){
         body
         {
            background-color:crimson;
         }
        }
        @media screen and (max-width:768px){
         body
         {
            background-color: rgb(58, 145, 100);
         }
        }
        @media screen and (max-width:576px){
         body
         {
            background-color: rgb(173, 27, 93);
         }
        }
        * {
            padding: 0px;
            margin: 0px;
            box-sizing: border-box;
        }

        .container {
            width: 800px;
            height: 600px;
            border: 1px solid;
            display: inline-block;
            position: absolute;
            margin: 50px 320px;
            box-shadow: 0px 0px 15px;
        }

        #child {
            width: 800px;
            height: 80px;
            top: 0px;
            position: absolute;
            background-color:darkcyan;
        }


        #get {
            top: 15px;
            padding: 7px;
            color: white;
            font-size: 20px;
            position: absolute;
            left: 20px;
        }

        #btn {
            top: 15px;
            padding: 7px;
            color: white;
            background-color: gray;
            position: absolute;
            right: 30px;
            border: 1px solid;
            box-shadow: 0px 0px 5px;
            border-radius: 10px;
        }

        .head {
            position: relative;
            display: inline-block;
        }

        #child2 {
            width: 50%;
            height: 530px;
            position: absolute;
            bottom: 0px;
            left: 0px;
            display: inline-block;
            border: 1px solid transparent;
            background-color: white;
            padding: 30px;
        }

        #child2data {
            justify-content: right;
        }

        .bottom {
            position: absolute;
            bottom: 25px;
            left: 50px;
        }

        #startbtn {
            bottom: 55px;
            margin: 15px auto;
            left: 35px;
            padding: 15px;
            background-color:steelblue;
            color: white;
            font-size: 20px;
            position: absolute;
            right: 30px;
            border: 1px solid transparent;
            border-radius: 10px;
        }
        .terms
        {
            color: blue;
        }

        #child3 {
            width: 50%;
            height: 530px;
            bottom: 0px;
            position: absolute;
            right: 0px;
            border: 3px solid black dotted;
            background-color: rgb(237, 237, 237);
            padding: 30px;
        }
        .icon
        {
            width: 10%;
            padding: 1px 0px;
            background-color: lightgreen;
            float: left;
            margin: 4px 1%;
            text-align: center;
        }
        #header1
        {
            color: green;
        }
        #header2
        {
            color: green;
        }
        #header3
        {
            color: green;
        }
        p
        {
            justify-content: center;

        }
    </style>
</head>

<body>
    <div class="container">

        <div class="head" id="child">
            <label for="" id="get">Get Started for FREE!!!</label>
            <button type="button" id="btn">CLOSE</button>
        </div>
   
        <div class="child" id="child2">
            <div id="child2data">
                <label for="">Your name:</label>
                <input type="text"><br><br>

                <label for="">Company name:</label>
                <input type="text"><br><br>

                <label for="">Comapny size:</label>
                <select name="" id="">
                    <option value="Choose one...   ">Choose one...
                    <option value=""> 1.Small Businesses</option>
                    <option value="">2.Medium-Sized Businesses</option>
                    <option value="">3.Large Businesses</option>
                    <option value="">4.Startups</option>
                    <option value=""> 5.Corporations</option>
                    </option>
                </select><br><br>

                <label for="">Business model:</label>
                <select name="" id="">
                    <option value="choose one...">Choose one...
                    <option value="">1.Product-Based</option>
                    <option value="">2.Service-Based</option>
                    <option value="">3.Subscription</option>
                    <option value="">4.Freemium</option>
                    <option value="">5.Marketplace</option>
                    </option>
                </select><br><br>

                <label for="">Company website:</label>
                <input type="text"><br><br>

                <label for="">Telephone number:</label>
                <input type="text"><br><br>

                <label for="">Enail address:</label>
                <input type="text"><br><br>

                <label for="">Password</label>
                <input type="text"><br><br>
            </div>


            <div class="leftbottom">
                <input type="button" id="startbtn" value="START YOUR FREE TRIAL NOW">
            </div>

            <div class="bottom">
                <p>By Clicking this button, you agree with our<br>
                    <span class="terms"><u>Terms.</u></span>
                </p>
            </div>
        </div>


        <div class="child" id="child3">

        
        <div>
            <h3 id="header1"> We Help you to get to Know your People</h3>
            <p style="color: black;" align="justify-content">
                The lifeblood of your business is the <br>people that interact with you and even <br>pay you....
                your users... your<br> customers.
            </p><br><br>
        </div>
        <div>
            <h3 id="header2">A Complex Business Service Built & Designed Simply</h3>
            <p style="color: black;" align="justify-content">You are trying to acquire, activate,retain<br> and delight your customers every
                single<br> minute of every day</p>
        </div><br><br>
        <div>
           
            <h3 id="header3">People not Pageviews goodbye Vanity metrics</h3>
            <p style="color: black;" align="justify-content"> No Longer will you just view a percentage<br> of people coming and going we'll
                tell you<br> who's coming, viewing what and why</p>
        </div>
    </div>
    </div>
</body>

</html>
