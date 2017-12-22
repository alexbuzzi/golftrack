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

# - Considerations: Power consumption, cost, size, weight distribution, precession, flight path

#Dates & Deliverables:
#End of January: Have code worked out to reliably collect wired data using arduino and calculate position within 95% accuracy
#End of February: Wireless streaming of data to arduino using rfid & begin brainstorming circuitry
#End of March: Create dedicated ASIC to handle on board calculations and wireless transmission
#End of April: Iterate on March circuit design and make smaller
#End of May: Have an MVP completed
