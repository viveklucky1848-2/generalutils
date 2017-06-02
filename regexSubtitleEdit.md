### Find and remove all "Closed Captions" for hearing disableds:
Find: ^\[.*\]\r\n
Replace with:

### Add a color tag around all subtitles actual
Find: ^((?!\d+$|\d{2}:\d{2}:\d{2},\d+ --> \d{2}:\d{2}:\d{2},\d+$).+)
Replace with: <font color="Red">\1</font>
