scripts
=======

Example

--Channel--
< div id="wraper">
.wraper
    background: url("http://i.imgur.com/qwnoxQP.png") no-repeat fixed center top #000000;
    position: relative;
    width: 100%;

 <div id="wrapper">
	<a class="campaign left" href="" style="display: block; background: none repeat scroll 0% 0% rgba(0, 255, 0, 0.5); height: 200px; position: absolute; width: 100px; left: 415px;"></a>
	<a class="campaign right" href=""></a>
-------left
	<a class="campaign left" href="" style="display: block; background: none repeat scroll 0% 0% rgba(0, 255, 0, 0.5); height: 100%;left:-500px;position:absolute;width:50%;"></a>
	<a class="campaign right" href=""></a>
--------rigth&left
        <a class="campaign left" href="" style="display: block; background: none repeat scroll 0% 0% rgba(0, 255, 0, 0.5); position: absolute; height: 100%; width: 50%; left: -500px;"></a> 
        <a class="campaign rigth+" href="" style="display: block; background: none repeat scroll 0% 0% rgba(0, 255, 0, 0.5); position: absolute; height: 100%; width: 50%; right: -500px;"></a> 
<br>

============Install============
sudo apt-get update
sudo apt-get install nodejs
sudo apt-get install legacy
node --version // verificar si aparece la versión
sudo apt-get install npm
// dirigirse a la carpeta del proyecto clonado
npm install
// correr la aplicación
npm run serve

