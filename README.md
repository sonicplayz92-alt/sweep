<!DOCTYPE HTML>
<html>
    <head>
        <meta charset='utf8'>
    </head>
    <body>
        <div id='ruffle'></div>
        <script src='https://www-sites-opensocial.googleusercontent.com/gadgets/proxy/refresh=600&container=enterprise/https://sites.google.com/site/s019i5h/ruffle.js'></script>
        <script>
var swfobject = {};

swfobject.embedSWF = function(url, cont, width, height){
    var ruffle = window.RufflePlayer.newest(),
        player = Object.assign(document.getElementById(cont).appendChild(ruffle.createPlayer()), {
            width: 1000,
            height: 800,
            style: 'width: ' + width + 'px; height: ' + height + 'px',
        });
    
    player.load({ url: url });
}

swfobject.embedSWF('https://www-sites-opensocial.googleusercontent.com/gadgets/proxy/refresh=600&container=enterprise/insertlinkhere', 'ruffle', 850, 600);
        </script>
    </body>
</html>
