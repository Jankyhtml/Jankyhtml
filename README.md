<!DOCTYPE html>
<html>
    <head>
        <title>Summrs</title>

        <style type="text/css">
        
            * {
                margin: 0;
                padding: 0;
            }
        
            body {
                font-family: Calibri, sans-serif;
            }
            
            .background-wrap {
                position: fixed;
                z-index: -1000;
                width: 100%;
                height: 100%;
                overflow: hidden;
                top: 0;
                left: 0;
            }

            #video-bg-elem {
                position: absolute;
                top: 0;
                left: 0;
                min-height: 100%;
                min-width: 100%;
            }

            .content {
                position: absolute;
                width: 100%;
                min-height: 100%;
                z-index: 1000%;
                background-color: rgba(0, 0, 0, 0, 7)
            }
            .content h1 {
                font-size: 100px;
                text-align: center;
                font: 65px;
                text-transform: uppercase;
                font-weight: 300;
                color:#bc13fe;
                padding-top: 15%;
                margin-bottom: 10px;
            }
            .content p {
                text-align: center;
                font-size: 30px;
                letter-spacing: 3px;
                color:red;
            }


        
        
        </style>
    

    </head>
    <body>

            <div class="background-wrap">

                <video id="video-bg-elem" preload="auto" autoplay="true" loop="loop" muted="muted">
                        <source src="video.mp4" type="video/mp4">
                        Video Not Supported
                </video>

            </div>




            <div class="content">

                <h1>Summrs</h1>
                <p>Discord Anti Nuke</p>
                <p>Made By Skids</p>

            </div>








    </body>
</html>
