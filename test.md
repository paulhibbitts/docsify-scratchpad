# Create a Lume scene

View this page in [Docsify-This](https://docsify-this.net) to see it [rendered](https://docsify-this.net/?executeScript=true&basePath=https://raw.githubusercontent.com/trusktr/tmp/main&homepage=test.md#/). 

The following is a [Lume](https://lume.io) scene with a rotating box:

<div style="width: 400px; height: 300px;">
  <lume-scene webgl>
    <lume-box id="box" size="100 100 100" mount-point="0.5 0.5 0.5" color="royalblue" rotation="10 20 30"></lume-box>
    <lume-camera-rig initial-distance="500" min-distance="100" max-distance="1200">
      <lume-point-light color="white" position="-500 -500 500"></lume-point-light>
    </lume-camera-rig>
  </lume-scene>
</div>
