# RPItwopinpwm
Control Raspberry Pi Fan with PWM

install fan plug on to 5v and Gnd, place signal wire on gpio17

place fan_ctrl.py in to /home/pi/Scripts/

in terminal type, "cd /etc/" then "sudo nano rc.local" 

at the top of the document under the "#" comments, add without quotes "sudo python /home/pi/Scripts/fan_ctrl.py &" 
press ctrl+o then enter, then ctrl+x

then type "sudo restart"

if all goes well the fan will barely turn on, and rampup as needed.

this code was witen by Aerandir14 from the instructables website, I only modified it to suit my needs.

USE AT YOUR OWN RISK - I AM NOT responsible for broken or damaged raspberry's or fans.

**if you have the nespi+ case with safe shutdown, your rc.local file will already be there.
