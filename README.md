# Geekworm X700 Series UPS HAT
Home Assistant Custom Integration for RPi Extention Board **Geekworm X700 Series UPS HAT** (_Power Management Board_) based from user Beduir https://github.com/Beduir/x720.git and originated from user dincojazz https://github.com/dincojazz/Geekworm_x750

Change fixes:
   - TBD ...

Сompatibility:
   - Geekworm X708
   - Geekworm X720
   - Geekworm X750

configuration.yaml:

	sensor:
  	  - platform: GeekwormUPS
	    name: 'RPi UPS Battery'
