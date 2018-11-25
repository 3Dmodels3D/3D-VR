# 3D-VR

<!--
  3D VR
  
<!DOCTYPE html>
<html xmlns='http://www.w3.org/1999/xhtml'>
  <head>
    <meta http-equiv="X-UA-Compatible" content="IE=Edge"/>
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8"/>
    <meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1">
    <title>KeyShotVR</title>
    <style type="text/css">
      body { -ms-touch-action: none; }
    </style>
    <script type="text/javascript" src="2-EWP-T-M/files/KeyShotVR.js"></script>
    <script type="text/javascript">
      var keyshotVR;
      function initKeyShotVR() {
        var nameOfDiv = "Loading...";
        var folderName = "2-EWP-T-M";
        var imageWidth = 720;
        var imageHeight = 480;
        var backgroundColor = "#FFFFFF";
        var uCount = 300;
        var vCount = 1;
        var uWrap = true;
        var vWrap = false;
        var uMouseSensitivity = -0.833333;
        var vMouseSensitivity = 1.000000;
        var uStartIndex = 299;
        var vStartIndex = 0;
        var minZoom = 1.000000;
        var maxZoom = 1.000000;
        var rotationDamping = 0.960000;
        var downScaleToBrowser = true;
        var addDownScaleGUIButton = false;
        var downloadOnInteraction = false;
        var imageExtension = "jpg";
        var showLoading = true;
        var loadingIcon = "Loading.jpg"; // Set to empty string for default icon.
        var allowFullscreen = true; // Double-click in desktop browsers for fullscreen.
        keyshotVR = new keyshotVR(nameOfDiv,folderName,imageWidth,imageHeight,backgroundColor,uCount,vCount,uWrap,vWrap,uMouseSensitivity,vMouseSensitivity,uStartIndex,vStartIndex,minZoom,maxZoom,rotationDamping,downScaleToBrowser,addDownScaleGUIButton,downloadOnInteraction,imageExtension,showLoading,loadingIcon,allowFullscreen);
      }
      window.onload = initKeyShotVR;
    </script>
  </head>
  <body oncontextmenu="return false;">
    <div id="Loading..."></div>
  </body>
</html>
