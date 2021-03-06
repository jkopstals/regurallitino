# Regurallitino
DIY regularity rally computer project

## Main goals of project
- basic chronometer to time stage and checkpoint times
- wheelspeed sensing from ABS sensor for speedometer, distance travelled and live average speed calculation in stage/between checkpoints
- speedometer calibration mode by measuring given distance and entering wheelspeed signal count for a given distance (1km?)
- acceleration measuring mode (0-100kph)
- buttons should be separate for start and stop, and for checkpoint (probably need a dedicated mode button)

### Optional goals
- enter stage target time and average speed (get notifications about finish time with buzzer, e.g. 10,5,4,3,2,1 secs out)
- trackday mode, for timing laps
- replay mode, for repeat/double regularity stages
- possibility to restart arduino without losing chrono time (RTC chrono + EEPROM / SD card storage?)
- possibility to adjust the distance covered during a stage (e.g. if a mistake has been made and arriving at a checkpoint, the distance covered needs to be reduced to match rally legend).

## Basic hardware
- Arduino (code is for UNO, but should be possible to adapt to any Arduino)
- Nokia 5110 LCD display
- a few pushbuttons for start, checkpoint, stop and mode switching
- (optional) DS3231 RTC module (for RTC precision mode)
- (optional) LED's for visual notifications
- (optional) piezo speaker for audible notifications
