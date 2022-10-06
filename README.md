# sharkygamer7082.github.io
Website for games
[Car Game](https://3hk0.netlify.app/projects/scrapmetal/index.html)


<!DOCTYPE html>
<html lang="en-us">
  <head>
    <meta charset="utf-8">
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8">
    <title>Scrap Metal 3 Infernal Trap | 3kh0</title>
    <link rel="shortcut icon" href="img/utka.ico">
    <link rel="icon" href="img/utka.ico">
    <link rel="stylesheet" href="zombies11.css">
    <script src="utkaUnityProgress.js"></script>
    <script src="scrapUnityLoader.js"></script>
    <script>
      var unityInstance = UnityLoader.instantiate("unityContainer", "ScrapMetal3.json", {onProgress: UnityProgress});
    </script>
  </head>
  <body>
    <div class="webgl-content">
      <div id="unityContainer" style="width: 960px; height: 100%"></div>
      <div class="footer">
        <div class="webgl-logo"></div>
        <div class="fullscreen" onclick="unityInstance.SetFullscreen(1)"></div>
        <div class="title">Scrap Metal 3 Infernal Trap</div>
      </div>
    </div>
    <script src="https://3kh0.github.io/js/main.js"></script>
  </body>
</html>
