Notes

Inspired by "Billie Jean" Michael Jackson video.

 <a href="https://player.vimeo.com/video/344918190"> Watch BILLIE JEAN on Vimeo</a>.</p>
 
Things needed
##
[] sound sensor module
[] led light
[] wire or battery
[] ethernet adapter (can't use wifi or bluetooth - damn hacker infested.)
[] thermal module (considering)
[] raspberry zero w 
[] camera module
[] self built router/firewall

##
Requirements
##
Steps


Do not feed 5V into a Pi GPIO. Can only tolerant 3V3. 
Use resistors to form a voltage divider to dropping 5V output to 3V3.
Turn small pot with a screw - adjust audio threshold level for the output pin to be switched high. 
Select desired level.
