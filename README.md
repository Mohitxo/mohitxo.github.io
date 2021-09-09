<!DOCTYPE html>
<html>

<head>
    
    <link rel="preconnect" href="Toma4025-Rumax-Folder.ico" type="image/x-icon">
    <link rel="shortcut icon" href="Toma4025-Rumax-Folder.ico" type="image/x-icon">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Raleway:wght@100&display=swap" rel="stylesheet">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <style>
        * {
            box-sizing: border-box;
        }

        body {

            margin: 0;
            font-family: Arial;
            font-size: 17px;
        }

        #myVideo {
            position: fixed;
            right: 0;
            bottom: 0;
            min-width: 100%;
            min-height: 100%;
            
        }

        .content {
            position: fixed;
            bottom: 0;
            background: rgba(0, 0, 0, 0.5);
            color: #f1f1f1;
            width: 100%;
            padding: 200px;
            padding-left: 3%;
        }

        #myBtn {
            width: 200px;
            font-size: 18px;
            padding: 10px;
            border: none;
            background: rgb(240, 41, 41);
            color: #fff;
            cursor: pointer;
        }

        #myBtn:hover {
            background: #ddd;
            color: black;
        }

        p{
            font-family: Raleway;
            font-size: 36px;
            text-align: center;

        }

        h1 {
            font-family: Raleway;
            text-align: center;



        }

        .navbar {

            border-radius: 5px;
        }

        .navbar {
            overflow: auto;
        }

        .navbar li:hover {
            color: red;
        }

        .navbar li {

            font-family: 'Times New Roman', Times, serif;
            font-size: 25px;
            color: yellow;
            float: inline-start;
            list-style: none;
            padding: 10px;
            margin-bottom: auto;
            border-radius: 1px;
            margin: auto;


        }

        .image {
            overflow-wrap: normal;
            overflow: auto;
        }
       
        
        
    </style>
</head>

<body>



    <video autoplay loop id="myVideo" controls >
        <source src="Motorcycle Cinematic Video.mp4" type="video/mp4">
        Your browser does not support HTML5 video.
    </video>

 
    <div class="content">
        <h1>Miles Roamer</h1>
        <!-- <p> roamer: someone who leads a wandering unsettled life</p> -->
        <button id="myBtn" onclick="myFunction()">Play/Stop</button>
        <header>
            <nav class="navbar">
                <ul>
                    <li>Home</li>
                    <li>About</li>
                    <li>Services</li>
                    <a href="https://www.instagram.com/miles_roamer/" style="font-family: 'Times New Roman', Times, serif;
                    font-size: 25px;
                    color: yellow;
                    float: inline-start;
                    list-style: none;
                    padding: 10px;
                    margin-bottom: auto;
                    border-radius: 1px;
                    margin: auto; text-decoration: none; padding-top: 5px; border-radius: 5px;">Instagram</a> 
                    
                </ul>
            </nav>
        </header>




    </div>




    <script>
        var video = document.getElementById("myVideo");
        var btn = document.getElementById("myBtn");

        function myFunction() {
            if (video.paused) {
                video.play();
                btn.innerHTML = "Pause";
            } else {
                video.pause();
                btn.innerHTML = "Play";
            }
        }
    </script>

</body>

</html>
