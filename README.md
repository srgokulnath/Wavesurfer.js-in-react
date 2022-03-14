# Wavesurfer.js-in-react

https://wavesurfer-js.org/

Using the wavesurfer.js library in react to create waveform of an audio. 


Plugins such as Regions https://wavesurfer-js.org/plugins/regions.html
Timeline have been added https://wavesurfer-js.org/plugins/timeline.html

For more plugins visit
https://wavesurfer-js.org/plugins/

A function component is created, to sync wavesurfer load and react DOM load the Wavesurfer.create task is done inside useEffect hook.

The Timeline plugin helps in getting the time line of the waveform, the regions plugin was used to create regions, these regions were added in a list of regions which were further mapped 
to playwith the selected region.
After creating a new region the "region-created" returns id and the specific region can be played in loop, once etc. Once a specific region is created using the id the region can be played
in loop or once also can be deleted. The start and the end point of the region is also seen.

The waveform can also be zoomed using the wavesirfer.current.zoom(zoomlevel). by passing a particular zoomlevel the waveform can be zoomed using the built in zoom function. To pass 
zoom values a input is presented which sets the value of zoom



