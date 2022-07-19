<!--
author:   Mark Jacob
email:    Mark.Jacob@iuz.tu-freiberg.de
version:  0.1.0
language: de
narrator: Deutsch Female

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

[![LiaScript](https://raw.githubusercontent.com/LiaScript/LiaScript/master/badges/course.svg)](https://liascript.github.io/course/?https://github.com/markjjacob/UNIcertIII/blob/main/BGIP_German_video.md)

# BGIP German Video

```json @grabber
{
  "videoId": "vn318ExQAaQ",
}
```
