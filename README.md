<!DOCTYPE html>
<html>

    <link href="https://fonts.googleapis.com/css?family=Josefin+Sans" rel="stylesheet">

    <link href="https://fonts.googleapis.com/css?family=Roboto+Mono" rel="stylesheet">

    <link href="https://fonts.googleapis.com/css?family=Rajdhani" rel="stylesheet">

    <link href="https://fonts.googleapis.com/css?family=Russo+One" rel="stylesheet">

    <head>
        <meta charset="utf-8">
        <title>New Webpage</title>

        <style>
            body {
                background-image: url("https://www.khanacademy.org/computer-programming/new-program/5597856712982528/5685265389584384.png");
                background-repeat: no-repeat;
                background-size: 100%;
                background-attachment: fixed;
                margin: auto;
                overflow-x: hidden;
                font-family: 'Roboto Mono', monospace;
                font-family: 'Josefin Sans', sans-serif;
            }



            h1 {
                color: #fff;
                font-family: 'Russo One', sans-serif;
                margin-left: 8.3%;
                font-size: 38px;
                border-bottom: dashed;
                border-width: 2px;
                border-color: rgb(255, 255, 255);
                width: 16.5%;
            }

            .typing-content {
                color: rgb(109, 109, 109);
                background-color: rgb(255, 255, 255);
                padding: 10px;
                border-radius: 10px;
                width: 80%;
                margin-left: 8.3%;
                line-height: 1.5em;
                font-size: 27px;
                border: solid;
                border-width: 4px;
                border-color: #cecece;
                height: 530px;
                overflow-y: auto;
                overflow-x: hidden;
            }

            footer {
                font-size: 13px;
                color: #fff;
                background-color: rgb(20, 20, 20, 0.6);
                padding: 15px;
                border-top-left-radius: 10px;
                border-top-right-radius: 10px;
                width: 78%;
                margin-left: 8.3%;
                margin-top: 100px;
                line-height: 1.8em;
                border-bottom: solid;
                border-color: rgb(0, 0, 0, 0.3);
                border-width: 10px;
                box-shadow: 0px 0px 4px rgb(0, 0, 0, 0.2);
            }

            #updatelog {

                width: 40%;
                float: right;
                margin-top: -200px;
            }

            #updateconbox {
                overflow-y: auto;
                padding-left: 5px;
                color: #ababab;
                height: 140px;
                border: solid;
                border-width: 2px;
                border-color: rgb(0, 0, 0, 0.1);
            }

            .footer-link {
                font-size: 16px;
                padding: 15px;
                line-height: 2.5em;
            }

            .footer-link:hover {
                text-decoration: underline;
                cursor: pointer;
            }

            #stbtn {
                background-color: #c52020;
                padding: 10px;
                font-size: 25px;
                border-radius: 5px;
                width: 180px;
                color: #fff;
                transition: 0.2s;
                float: right;
                margin-right: 55%;
                margin-top: -6%;
                text-align: center;
                font-family: Arial, Helvetica, sans-serif;
                cursor: pointer;
            }

            #stbtn span {
                cursor: pointer;
                display: inline-block;
                position: relative;
                transition: 0.5s;
            }

            #stbtn span:after {
                content: '\00bb';
                position: absolute;
                opacity: 0;
                top: 0;
                right: -20px;
                transition: 0.5s;
            }

            #stbtn:hover span {
                padding-right: 25px;

            }

            #stbtn:hover span:after {
                opacity: 1;
                right: 0;
            }
        </style>

    </head>

    <body>
        <div id="main">
            <h1>Key Speed</h1>
            <h2 id="stbtn"><span>Start Typing</span></h2>

            <p class="typing-content"><a style="color:#40a350;"> He</a><a
                    style="background-color:rgba(255, 0, 0, 0.199); padding-top: 2px; color:rgb(0, 0, 0);">l</a>lo
                random
                reader who is
                reading this text that keeps
                on repeating over and over again. Hello
                random reader who is reading this text that keeps on repeating over and over again. Hello random reader
                who
                is reading this text that keeps on repeating over and over again. Hello random reader who is reading
                this
                text that keeps on repeating over and over again. Hello random reader who is reading this text that
                keeps on
                repeating over and over again. Hello random reader who is reading this text that keeps on repeating over
                and
                over again. Hello random reader who is reading this text that keeps on repeating over and over again.
                Hello
                random reader who is reading this text that keeps on repeating over and over again. Hello random reader
                who
                is reading this text that keeps on repeating over and over again. Hello random reader who is reading
                this
                text that keeps on repeating over and over again. Hello random reader who is reading this text that
                keeps on.

            </p>

            <footer>
                <a class="footer-link">Undefined</a><a class="footer-link">Undefined</a><a
                    class="footer-link">Undefined</a><br>
                <a class="footer-link">Undefined</a><a class="footer-link">Undefined</a><a
                    class="footer-link">Undefined</a><br>
                <a class="footer-link">Undefined</a><a class="footer-link">Undefined</a><a
                    class="footer-link">Undefined</a><br>
                <br>
                <br><a style="font-family: 'Rajdhani';">copyright © 2019 KeySpeed.com</a>
                <a style="font-family: 'Rajdhani'; margin-left: 35px;">v 0 . 1 . 3</a><br>

                <div id="updatelog">
                    <h3>Update Log:</h3>

                    <div id="updateconbox">
                        <p>- Created the websites base design</p>
                    </div>

                </div>

            </footer>

        </div>
    </body>

</html>
