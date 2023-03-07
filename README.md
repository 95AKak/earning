




<!DOCTYPE html>
<html>
<head>
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8">
    <meta name="viewport" content="width=1920"/>
    <meta name="description"
          content="Tizen Download API Demo" />

    <title>Tizen Download API</title>

    <script type='text/javascript' src='$WEBAPIS/webapis/webapis.js'></script>
    <link rel="stylesheet" type="text/css" href="style.css" />

</head>

<body>

    <h1>Tizen Download API</h1>

    <div class="left">
        <h2>Available buttons/actions:</h2>

        <div>
            1 - Downloaded file lists<br>
            2 - Start download - small file<br>
            3 - Start download - large file<br>
            Pause - Pause download<br>
            Play - Resume download<br>
            Stop - Cancel download<br>
            0 - Clear logs
        </div>

        <div id="progress" class="progress">
            <div id="bar" class="bar"></div>
        </div>

        <fieldset>
            <legend>Downloaded files:</legend>
            <div id="fileList" class="logs"></div>
        </fieldset>

        <fieldset>
            <legend>Logs</legend>
            <div id="logs" class="logs"></div>
        </fieldset>
    </div>
    <div class="right">
        <h2>Info</h2>

        <p>This application demonstrates the usage of Tizen download API</p>

        <p>The application downloads files from <code>http://techslides.com</code> and <code>http://download.blender.org</code>. If these domains are not accessible it will not work.<br>

            You can change the source location of files to download by changing the contents of <code>url1</code> and <code>url2</code> variables in <code>main.js</code> file</cide></p>
    </div>

    <script src="main.js"></script>
</body>
</html>
