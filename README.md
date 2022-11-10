# OpenFloat's mission is to sail a small autonomous vessel that circumnavigates the earth
This project will stretch the knowledge and aptitude of even the most seasoned engineers. Are you up for the challenge? Join this Open Source community and help us push further into the unkown of the deep blue.


## Proposed path for mission 1
<img width="200" alt="Screen Shot 2022-11-09 at 6 54 01 PM" src="https://user-images.githubusercontent.com/8175253/200967075-8c1b589a-c8e5-4099-9edd-16a6738e0db0.png"> <img width="200" alt="Screen Shot 2022-11-09 at 6 54 43 PM" src="https://user-images.githubusercontent.com/8175253/200967098-b545bdf1-fb63-43fd-9a97-73683b754c6f.png"> <img width="200" alt="Screen Shot 2022-11-09 at 6 54 22 PM" src="https://user-images.githubusercontent.com/8175253/200967100-47863ea1-7e7b-4033-b137-48dcc69d6a38.png">



# Vessel Requirements
- All components must be available off the shelf for a reasonable price or be easy and cheap to assemble

## Vehicle
   - Requirements
      - Small in size
      - Must have ability to upright self in event of capsize
      - Internal bay will require cooling
      - Must be able to survive saltwater, heat, sun, and freeze
      - Ability to pump out water from internal bay
      
   - Materials
      - Plastic body, sail, and components
      - Hard plastic sail for duribility
      
   - Sensors
      - GPS + GLONASS
      - Inertial naviation (https://vetco.net/products/9-axis-inertial-navigation-module-for-arduino-d65)
      - Gyro (https://www.adafruit.com/product/2019)
      - X : Wind speed and direction indicator : NOTE anemometer is not practical for this project
      - Accelerometer (https://www.adafruit.com/product/2019)
      - Temperature internal bay and environment (https://www.adafruit.com/product/1782)
      - Water sensor for internal bay
      - Compass (https://www.adafruit.com/product/5579)
      - Camera

## Communication
  - Unkown

## Power Generation
  - Primary systems : Solar and battery 
  - Use : Provide electricity for propulsion and communication
  - Notes : Vessel has low electricity requirements since propulsion is powered by wind

## Propulsion
  - Primary systems : Wind sail and rudder

## Software
  - Systems on board
    - 3 Raspberry Pi zero's as primary computational hardware and redundency
    - Must be able to keep vessel towards correct heading using rudder and sail regardless of wind speed and direction
  - Remote systems
    - 
