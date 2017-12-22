# Stratagy #1:
#  - Detect ball being struck
#  - After struck start recording accelerometer data
#  - Detect ball coming to a stop (accel< some value)
#  - Send out radio signal from phone to turn on switch
#  - Switch will connect battery to coil to turn on active RFID chip
#  - Either accelerometer data will be streamed or onboard calculations will take place in microprocessor and then be streamed

# Strategy #2:
#  - Have app turned on passively during round of golf and ready to receive information
#  - Detect ball being struck
#  - After struck start recording accelerometer data and immediately flip switch to send data to phone
#  - Once data has been streamed to phone, do projectile calculations and estimated location on phone
#  - Then using this information, set your current phone location and move towards "pin" set on map of golfcourse
#  - Could be in collaboration with golf mapped out courses

# - Considerations: Power draw, cost, size, weight distribution
