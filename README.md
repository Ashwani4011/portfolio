# portfolio
portfolio using html Css and a little bit Js
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>portfolio</title>
    <style>
        *{
            margin: 2px;
            padding: 2px;
        }
        .main {
            /* background-color: rgba(100, 71, 32, 0.096); */
            height: 100vh;
            width: 70vw;
        }

        #main1 {
            margin: 2px;
            padding: 2px;
            display: flex;
            justify-content: space-around;
            /* background-color: gainsboro; */
            height: 7%;
            width: 100%;

        }

        #main11 h1{
            font-size: 7vh;
            margin: 5px;
            padding: 2px;
            color: rgba(7, 73, 40, 0.61);
            background-color: aliceblue;
            transition: all .5s ease-in .5s ;
        }
        #main11 h1:hover{
            font-size: 9vh;
            color: blue;
        }

        #main12 {
            padding: 2px;
            /* margin: 2px; */
            display: flex;
            flex-direction: row;
        }

        #main12 p {
            margin: 5px;
            font-size: 4vh;
            transition: all 0s ease 0s;
        }
        #main12 p:hover{
            font-size: 5vh;
            color: rgb(131, 131, 131);
        }

        #main2 {
            /* background-color: blanchedalmond; */
            height: 50%;
            width: 100%;
            display: flex;
            flex-direction: row;
            flex-wrap: wrap;
            justify-content: space-around;
            padding-top: 30px;
        }

        #main21 {
            /* background-color: burlywood; */
            height: 100%;
            width: 40%;
            padding: 5px;
            display: flex;
            flex-direction: column;
            justify-content: space-around;

        }

        #main211 h1{
        
            animation: sarebolodamn 3s ease-in 1s 1 normal;
        }
        @keyframes sarebolodamn{
            0%{width: 10%;
            height: 10%;}
            60%{width: 40%;
            height: 40%;}
            100%{width: 90%;
            height: 80%;}
        }
        #main212 button{
            transition: background-color 0s ease 0s;
        }#main212 button:hover{
            background-color: green;
        }
        #main22 {
            background-image: url("pic.jpg");
            background-size: cover;
            background-attachment: scroll;
            border-radius: 100%;
            height: 70%;
            width: 25%;
                   }
        #main3{
            background-color: cadetblue;
            display: flex;
            flex-direction: inherit;
            /* flex-wrap: wrap; */
            justify-content: space-between;
            height: 5%;
            width: 40%;
            transition: all 1s ease-in 0s;
            margin-left: 10% ;
        }
        #main3:hover{
            width: 80%;
            height: 10%;
        }
       
    </style>
</head>

<body>
    <div class="main">
        <nav id="main1">
            <div id="main11"><h1><b>Ashwani Sharma </b> </h1></div>
            <div id="main12">
                <p>Home</p>
                <p>About</p>
                <p>Contact</p>
            </div>
        </nav>
        <div id="main2">
            <div id="main21">
                <div id="main211">
                    <h1>Hey, I'm Ashwani Sharma</h1>
                    <p><b>Front-end Developer</b></p>
                    <p>I'm currently pursuing B.Tech from USICT Delhi</p>
                    <p>I,m from Delhi and currently looking for job</p>
                </div>
                <div id="main212">
                    <button>Hired</button>
                    <button>Resume</button>
                </div>
            </div>
            <div id="main22">
            </div>
        </div>
        <div id="main3">
            <div id="fb">
                <a href="https://www.facebook.com/"><img src="fblogo.jpg" alt="error" width="75%" height="75%"></a>
            </div>
            <div id="linkedin">
                <a href="https://www.linkedin.com"><img src="linkedinlogo.jpg" alt="ram" width="75%" height="75%"></a>
            </div>
            <div id="twitter">
                <a href="https://www.twitter.com"><img src="twtrlogo.jpg" alt="hfashdvh"  width="75%" height="75%"></a>
            </div>
            <div id="insta">
                <a href="https://www.instagram.com"><img src="instalogo.jpg" alt="sdc"  width="30%" height="75%"></a>
            </div>
        </div>
    </div>
    <script>
        
        
        
        a=document.getElementById('main212')  
           
               a.firstElementChild.onclick=function(){
                alert("great choice")
               }
               a.lastElementChild.onclick=function(){
                alert("qualification  skills    experience")
                // alert("skills")
                // alert("experience")
               }
            b=document.getElementById('main12')
            b.lastElementChild.onclick=function(){
                alert("9xxxxxxxxx")
            }
            c=document.getElementById("main3")
            c.lastElementChild.onmouseover=function(){
                alert("insta handle ashwanisharma4011")
            }
            // document.getElementById("main3").firstElementChild.style.background='red'
    </script>
</body>

</html>
