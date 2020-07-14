<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <title>Github page</title>
    <meta name="viewport" content="width=device-width, initial-scale=1">



</head>

<body>

    <div id="root">

        <div class="header">
            <!-- Negative cut out SVG -->
            <svg class="header-svg" aria-hidden="true" role="presentation" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100" preserveAspectRatio="none">
      <polygon fill="white" points="0,100 100,0 100,100"/>
    </svg>
            <h1 class="header-heading">Github page</h1>
            <p class="strapline">Khayal Baylarov</p>
        </div>

        <div class="body">
            <h2 class="content-heading">Content preparing</h2>

            <p class="body-content">
                <a class="body-link" href="#">Visit Reositories</a>
            </p>
        </div>

        <div class="footer">
            <div class="footer-top">
                <!-- Negative cut out SVG -->
                <svg class="footer-svg" aria-hidden="true" role="presentation" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100" preserveAspectRatio="none">
        <polygon fill="#fff" points="0,0 0,100 100,0"/>
      </svg>
            </div>
            <div class="footer-main">
                <!-- <h3 class="footer-heading">Footer heading</h3>
                <p class="footer-content">Footer content</p> -->
            </div>
        </div>

    </div>


    <style>
        /* all css is here */
        /*Downloaded from https://www.codeseek.co/didoesdigital/inline-svg-diagonal-headerfooter-bMdzNQ */
        
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }
        
        body {
            background-color: #fff;
            color: #444;
            @import url("https://fonts.googleapis.com/css?family=Karla:800,");
            font: 800 16px/1.5 "Karla", "SF Pro Text", "Droid Sans Mono", "Roboto", Tahoma, Geneva, "Helvetica Neue", Helvetica, Arial, sans-serif;
            letter-spacing: .05em;
            margin: 0 auto;
            padding: 0;
        }
        
        h1,
        h2,
        h3 {
            font-weight: 800;
        }
        
        .header {
            position: relative;
            height: 200px;
            background-image: radial-gradient(circle at 62% 38%, #8242a8 0, #402351 100%);
            /*svg*/
            /*h1*/
            /*p*/
        }
        
        .header .header-svg {
            position: absolute;
            bottom: 0;
            width: 100%;
            height: 6vw;
        }
        
        .header .header-heading {
            color: #fff;
            padding-top: 50px;
            text-align: center;
        }
        
        .header .strapline {
            color: #fff;
            padding-top: 12.5px;
            text-align: center;
        }
        
        .body {
            /*h2*/
            /*p*/
        }
        
        .body .content-heading {
            padding-top: 50px;
            text-align: center;
        }
        
        .body .body-link {
            text-decoration: none;
            color: #444;
        }
        
        .body .body-content {
            padding-top: 12.5px;
            padding-bottom: 25px;
            text-align: center;
        }
        
        .footer {
            height: 200px;
            background-color: #402351;
            background-image: radial-gradient(circle at 62% 38%, #8242a8 0, #402351 100%);
            position: relative;
            /*svg*/
            /*h3*/
            /*p*/
        }
        
        .footer .footer-svg {
            position: absolute;
            top: 0;
            width: 100%;
            height: 8vw;
        }
        
        .footer .footer-heading {
            color: #fff;
            padding-top: 100px;
            text-align: center;
        }
        
        .footer .footer-content {
            color: #fff;
            padding-top: 12.5px;
            text-align: center;
        }
        
        #root {
            display: flex;
            flex-direction: column;
            min-height: 100vh;
        }
        
        #root .body {
            flex-grow: 1;
        }
    </style>
</body>
