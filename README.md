# Three3DExtras
## About
Is an three.js helpful basics methods.

## Usage 
Include dependency
``` html
<script src="three3DExtras.min.js"></script>
```
    

### Example create line using tube geometry
``` js
var line=new three3DExtras.tubeLine([-1,0,1],[1,0,1],0.02,'#B02735');
scene.add(line.getObject3D());
```
