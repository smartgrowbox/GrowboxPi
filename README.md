# GrowboxPi
GrowboxPi is a complete smart growing system for the raspberri pi written in Java.
It can monitor and control the weather of your grow box, feed, water and grow your plants automatically while you can use the GrowboxPi app to see it all.
Designed to be extensible
         - for adding new sensors (digital, analog) and output ports like an extra pump or light sensor
         - for adding new rules & actions


# Features:
- Timelapse video
- Light control
- Watering system
- Live stream video
- Fertilizer dosing system
- Air Temperature, Humidity, Light
- Water Temperature, PH, Level
- Multiple Fan control
- Soil moisture analog sensor support
- Daily pictures
- Built-in Plant list (get started with 1-click)
- Database persistence
- Android & Web Clients

# Upgrading from GrowboxPi v0.X
If you are upgrading from growboxpi v1, check out the migration guide in the docs folder.



# Light control
- CONSTANT: constant vegetation and flowering hours per days DEFAULT
- MAX_YIELD: linearly decreasing at the start of flowering period until min hours
- NATURAL: linearly increasing at the start of vegetation until linearly decreasing at the flowering period until min hours

# Watering control
- CONSTANT: constant vegetation and flowering amount per day DEFAULT
- LINEAR: linearly increasing in vegetation until kept constant throughout flowering
- MIN_MAX: increasing linearly from minimum amount until maximum amount is reached


Dependencies:
<code>sudo aptitude install libav-tools gpac imagemagick
sudo aptitude install sqlite3 lighttpd
sudo aptitude install build-essential python-dev python-openssl
</code>
