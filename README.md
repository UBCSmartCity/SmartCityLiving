# Smart City Living
A sub-division of UBC Smart City. Attempt to build integrated IOT products which allow a more modern & smarter living environment. 

## Ambient Lighting Control
A product that automates the lighting of a given environment, mimicking true tone technology.

MCU - STM32

Sensor - VEML3328

### Design Log

**Project Board:**

<img width="648" alt="Screenshot 2023-03-07 133434" src="https://user-images.githubusercontent.com/63937643/223567901-7bc8200e-584f-443f-806a-970c9ed68c27.png">

#### March 2023

- Demo the sensor behaviour by manipulating the PWM signal from sensor input.
  - The threshold values for light changes are reconfigured after each reset. 
  
  

![image](https://user-images.githubusercontent.com/63937643/227748010-a660aa50-5d34-43ca-bd4f-f38160efa235.png)


- Use ESP8266 to establish connection between STM32 and smart light bulb. Send and receive packets
  - Use already made bulb for initial design, and move on to desgning our own if possible. 

#### April 2023

- Sensor Header -> make sensor configuration one-line thing
- Implement hysteresis on the demo
- Smart Light Bulb Header -> Try to make a generalized header that allows ESP8266 to connect to various companies product
