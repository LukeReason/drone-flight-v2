# drone-flight-v2
from djitellopy import Tello
import time

#step one

tello.connect()
tello.takeoff()

#step two

tello.send_rc_control(0,0,50,0)
sleep(3.92)

#step three

tello.send_rc_control(0,0,0,-50)
sleep(0.47)

#step four

tello.send_rc_control(0,50,0,0)
sleep(3.89)

#step five

tello.send_rc_control(0,0,0,0)
tello.land

