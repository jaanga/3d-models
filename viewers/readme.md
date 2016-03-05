<span style=display:none; >[You are now in a GitHub source code view - click this link to view this read me file as a web page]( http://jaanga.github.io/3d-models/viewers/ "View file as a web page." ) </span>
<input onclick=window.location.href='https://github.com/jaanga/3d-models/tree/gh-pages/viewers'; type=button  value='You are now in a GitHub web page view - Click this button to view this read me file as source code' />

[Jaanga]( http://jaanga.github.io ) »

[Viewers Read Me]( index.html )
===

_Simple OBJ file viewers based on [Three.js]( http://threejs.org )_




## [OBJ Viewer Basic]( http://jaanga.github.io/3d-models/viewers/obj-viewer-basic/index.html )

* Reads an OBJ file with a URL specified in location.hash 

* Supports the following further parameters
	* Camera position: cpx, cpy, cpz
	* Camera rotation: ctx, cty, ctz
	* Object scale: scx, scy, scz
	* Object position: pox, poy, poz
	* Object rotation: tox, roy, roz
* Tries to be the simplest possible reader
* Converts all materials to MeshNormalMaterial

### Viewers Road Map

* Read OBJ MTL fles
* Supply alternate materials
* Supply skyboxes and other backgrounds
* Toggle rotation
* Toggle wireframe
* Toggle helpers
* Export files with current parameters such as scale, position and rotation


## Three.js OBJ support

<https://github.com/mrdoob/three.js/blob/master/examples/js/loaders/OBJLoader.js>  

<https://github.com/mrdoob/three.js/blob/master/examples/js/exporters/OBJExporter.js>
