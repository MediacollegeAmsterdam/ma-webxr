# `Ma WebXR`

### Een WebXR library voor 1e jaars SD

Met deze library kunnen jullie eenvoudig een WebXR project maken.

### Welke bestanden en voorbeelden zijn er:
##### index.html 
Dit bestand laat zien hoe je fullscreen een WebXR project kunt laten zien.

##### index-voorbeeld-in-pagina.html 
Dit bestand laat een voorbeeld zien hoe je WebXR als 'component' kunt verwerken in je site. Voor de Museum Online opdracht hebben jullie dit nodig.

##### app.js
Hier kan je je eigen code schrijven. Als voorbeeld hebben we hier alvast wat code voor je neergezet.

### Wat kan je allemaal aanmaken met deze library:

|Wat kun je aanmaken |Hoe maak je het aan|Wat kan je er mee?|
|---|:---|---|
| XRImage | const image = new XRImage('assets/images/sampleImage.jpg'); | Een afbeelding/plaatje laten zien |
| Cube | const testCube = new Cube(); | Hiermee maak je een 3d box aan |
| Sphere | const testSphere = new Sphere(); | Hiermee maak je een sphere aan |
| Plane |  |  |
| Cylinder |  |  |
| Cone |  |  |
| Text |  |  |
| Model |  |  |
| Controls |  |  |
| AmbientLight |  |  |
| DirectionalLight |  |  |
| PointLight |  |  |
| SpotLight |  |  |
| Sky |  |  |

#### Mocht je het interessant vinden: hoe is deze library opgebouwd?
Deze library is gebouwd op A-Frame. Als je hier meer over wilt weten dan kun je kijken op https://aframe.io/ . Hier staan ook simpele voorbeelden over wat je nog meer kunt met A-Frame.
A-Frame maakt zelf weer gebruik van Three.js. Three.js is een JavaScript library die het makkelijker maakt om 3D te laten zien in de browser. Hiervoor gebruikt Three.js WebGL.