<!--
author:   Mark Jacob
email:    Mark.Jacob@iuz.tu-freiberg.de
version:  0.1.0
language: en
narrator: UK English Female

comment:  This simple description of your course.
          Multiline is also okay.

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

# BGIP ideas

## Students' needs

## How will the SHK benefit the BGIP Students?

## Tools

https://www.youtube.com/watch?v=vn318ExQAaQ

### our channelVideo from 

<iframe src="https://video.tu-freiberg.de/media/embed?key=596b876085d90d5d035205af757d424a&width=560&height=315&autoplay=false&controls=true&autolightsoff=false&loop=false&chapters=false&playlist=false&related=false&responsive=false&t=0" data-src="" class="iframeLoaded" width="560" height="315" frameborder="0" allowfullscreen="allowfullscreen" allowtransparency="true" scrolling="no" aria-label="media embed code" style=""></iframe>

## Without arguments

@gr

## With arguments

```json @grabber
{
  "videoId": "2Wb_mYQEPlw",
  "languageCode": "en",
  "minTime": 30,
  "maxTime": 105
}
```

## The video is fixed but not the language

```json @grabber
{
  "videoId": "2Wb_mYQEPlw",
}
```

## I want the language on this slide to be German

```json @grabber
{
  "videoId": "vn318ExQAaQ",
}
```

## Get Language Code

```json @grabber
{
  "tellLanguageCode": "yes"
}
```




