### Find and remove all "Closed Captions" for hearing disableds:<br>
Find: ^\[.*\]\r\n<br>
Replace with:<br>

### Add a color tag around all subtitles actual:<br>
Find: ^((?!\d+$|\d{2}:\d{2}:\d{2},\d+ --> \d{2}:\d{2}:\d{2},\d+$).+)<br>
Replace with: ```<font color="Red">\1</font>```<br>
