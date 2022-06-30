<!--
author:   Mark Jacob
email:    Mark.Jacob@iuz.tu-freiberg.de
version:  0.1.0
language: en
narrator: UK English Female

comment:  This simple description of your course.
          Multiline is also okay.

icon:     https://tu-freiberg.de/sites/default/files/media/institute-of-geophysics-and-geoinformatics-575/infobild/institute_winter_2.png?1605098321

link:     https://cdn.jsdelivr.net/chartist.js/latest/chartist.min.css

script:   https://cdn.jsdelivr.net/chartist.js/latest/chartist.min.js

script: https://nethiri.github.io/YTScriptGrabber/LiaScriptVersion/base.js
script: https://nethiri.github.io/YTScriptGrabber/LiaScriptVersion/consys.js
script: https://nethiri.github.io/YTScriptGrabber/LiaScriptVersion/grabber.js
script: https://nethiri.github.io/YTScriptGrabber/LiaScriptVersion/grabber-lia-bridge.js
script: https://nethiri.github.io/YTScriptGrabber/LiaScriptVersion/lul-lia-bridge.js
script: https://nethiri.github.io/YTScriptGrabber/LiaScriptVersion/lul.js
link: https://cdn.jsdelivr.net/gh/nethiri/YTScriptGrabber@main/LiaScriptVersion/lul.css
link: https://cdn.jsdelivr.net/gh/nethiri/YTScriptGrabber@main/LiaScriptVersion/consys.css

script: https://cdn.jsdelivr.net/gh/Nethiri/EnglishImageDescriber@main/LiaScriptImageDescriber/imageDescriberFunctions.js
script: https://cdn.jsdelivr.net/gh/Nethiri/EnglishImageDescriber@main/LiaScriptImageDescriber/ImageDescriber.js
script: https://cdn.jsdelivr.net/gh/Nethiri/EnglishImageDescriber@main/LiaScriptImageDescriber/userTasks.js

link: https://cdn.jsdelivr.net/gh/Nethiri/EnglishImageDescriber@main/LiaScriptImageDescriber/style.css
link: https://cdn.jsdelivr.net/gh/Nethiri/EnglishImageDescriber@main/LiaScriptImageDescriber/print.css

script: https://cdn.jsdelivr.net/gh/kaptn-seebar/english-lia@latest/base.js
import: https://raw.githubusercontent.com/liaTemplates/TextAnalysis/main/README.md

test: @Textanalysis.FULL

@gr: @grabber({})

@grabber
<script id="script_@uid" input="hidden">
  window['grabberArg'] = @0;
</script>
@startgrabber(@uid)
@end

@startgrabber
<script id="script_@uid" input="hidden">
  window['grabberUid'] = 'id_@0';
  setTimeout(function() {
    startGrabber();
  }, 100);
</script>
<div id='id_@0'></div>
@end

-->

[![LiaScript](https://raw.githubusercontent.com/LiaScript/LiaScript/master/badges/course.svg)](https://liascript.github.io/course/?https://github.com/markjjacob/UNIcertIII/blob/main/BGIP_ideas.md)

# BGIP SHK

??[BGIP news](https://tu-freiberg.de/presse/geophysik-studieren-und-netzwerken)

## YouTube Script Grabber

> Without arguments

@gr

### With arguments

```json @grabber
{
  "videoId": "2Wb_mYQEPlw",
  "languageCode": "en",
  "minTime": 30,
  "maxTime": 105
}
```

### The video is fixed but not the language

```json @grabber
{
  "videoId": "2Wb_mYQEPlw",
}
```

### Geophysics lecture

```json @grabber
{
  "videoId": "2wiV0Ow5oT0",
}
```

### Video from our channel

<iframe src="https://video.tu-freiberg.de/media/embed?key=596b876085d90d5d035205af757d424a&width=560&height=315&autoplay=false&controls=true&autolightsoff=false&loop=false&chapters=false&playlist=false&related=false&responsive=false&t=0" data-src="" class="iframeLoaded" width="560" height="315" frameborder="0" allowfullscreen="allowfullscreen" allowtransparency="true" scrolling="no" aria-label="media embed code" style=""></iframe>


## Image Desccriber

To begin your describing adventures you need to figure out what you want to describe.
You can either describe a picture, an graph or a piece of code...

**What do you want to describe:**

<div id="TypeSelectorPlace">if you can see this, the function placeSelect() has not loaded properly...</div>

<script>placeSelect();</script>

---
Now that we have the general idea of what you want to do, we need the very object you would like to train describing on.  

For the current iteration of this program, please insert a Link into the input box below which is a direct link to an image of what you want to describe.

Here is an example Link: https://c7.alamy.com/compde/2gr9e0w/seismograph-2gr9e0w.jpg

**Link to your Image:**
<div id="ImageLinkPlace">if you can see this, the function placeLinkReader() has not loaded properly... </div>

<script>placeLinkReader();</script>

---
Some of you may already have started a project earlier... if that is the case... feel free to open it here...
<div id="FileReaderPlace">if you can see this, the function placeFileReader() has not worked properly...</div>

<script>placeFileReader()</script>

---

Once you have entered everything correctly, a script, generated just for you, should display your tasks below.

<div id="UserTaskPlace">if you can see this, the function userTask() has not worked properly...</div>

<script modify="false">
setTimeout(function() {
    document.getElementById("UserTaskPlace").innerHTML = "";
    document.getElementById("LaunchButton").onclick = function() {
        ImgUrlLink = document.getElementById("LinkTextBox").value;
        send.liascript(userTask());
    }
    document.getElementById("LinkTextBox").addEventListener("change", function() {
        ImgUrlLink = document.getElementById("LinkTextBox").value;
        send.liascript(userTask());
    });
    if(ImgUrlLink != undefined){
        send.liascript(userTask());
    }

}, 1000);
"";
</script>

### Last minute edits

<div id="TextEditor">If you can see this, then TextEditor() did not load properly... </div>

<script>TextEditor()</script>

### Text Analysis

On this page, you shall have an automated evaluation of your text below:
<div id="TestPlace"></div>

<script> PlaceTest() </script>

### Print / Save it!

If you want to save your work, so you may come back later to it... please press the button below:
<div id="Saver">If you can see this, then PlaceSaver() function has not loaded</div>
<script>PlaceSaver()</script>

---

If you want to print your work, you can do so below, though maybe add some nice information like... your name and stuff first :)

Name:

<input id="NameBox" oninput="OnNameChange(this)">

Degree subject:

<input id="MatBox" oninput="OnNameChange(this)">



<div id="Printer">If you can see this, the PlacePrinter() function has not loaded properly...</div>

<script> PlacePrinter() </script>


