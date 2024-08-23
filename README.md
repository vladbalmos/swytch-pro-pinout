# Swytch PRO Universal Kit (2nd Generation) pinout

The following is the pinout for the Swytch PRO Universal Kit (2nd Generation).

## Pinout for Quick Connect Handlerbar Mount

Front view, pin 1 is left most, pin 12 is right most.

| Pin Number | Description            
|------------|----------------------------
| 1          | Motor HALL sensor signal   
| 2          | +5V rail                  
| 3          | Motor HALL sensor signal 
| 4          | Motor HALL sensor signal 
| 5          | Motor HALL sensor signal *1
| 6          | Motor phase *2
| 7          | Motor phase *2             
| 8          | Motor phase *2            
| 9          | Brake sensor signal    
| 10         | PAS sensor signal    
| 11         | Ground               
| 12         | Throttle sensor signal  

<small>
*1 - Not sure if it's an additional HALL sensor or something else but it is definetely motor related

*2 - Not sure about the phase ordering
</small>


For the battery pack pinout just reverse the direction: pin 12 is left most while pin 1 is right most.


### Connectors pinout (handlebar mount)
The <strong>⮟</strong> character indicates the connector guide pin / keying feature. Pins identified with <strong>-1</strong> indicate <strong>No connection</strong>.

#### Motor (female - black)
Pin 8 is in line with the aligning arrow on the connector
<pre>
     ⮟
     8
  2     1
3   11   6
  5     4
     7
</pre>

| Pin Number | Description  
|------------|-----------------------
| 8          | Motor phase *   
| 2          | +5V rail   
| 3          | Motor HALL sensor signal   
| 5          | Motor HALL sensor signal   
| 7          | Motor phase *   
| 4          | Motor HALL sensor signal   
| 6          | Motor phase *   
| 1          | Motor HALL sensor signal   
| 11         | Ground   

<small>
* - Not sure about the phase ordering
</small>


#### Brake sensors (female - blue)

<pre>
    ⮟
-1     2
 9    11
</pre>

| Pin Number | Description  
|------------|-----------------------
| -1         | Not connected
| 9          | Sensor signal
| 11         | Ground
| 2          | +5V rail

#### PAS sensor (female - orange)

<pre>
    ⮟
 2      10
    11   
</pre>

| Pin Number | Description  
|------------|-----------------------
| 2          | +5V rail
| 11         | Ground
| 10         | Sensor signal

#### Throttle sensor (male - orange)

<pre>
    ⮟
 2      12
    11   
</pre>

| Pin Number | Description  
|------------|-----------------------
| 2          | +5V rail
| 11         | Ground
| 12         | Sensor signal

### Voltages

| Pin Number | Description            
|------------|----------------------------
| 1          | +3.3V
| 2          | +5V rail                  
| 3          | +3.3V
| 4          | +3.3V
| 5          | +3.3V
| 6          | PWM 0 ... +48V
| 7          | PWM 0 ... +48V             
| 8          | PWM 0 ... +48V            
| 9          | +3V when unconnected, 0V when brakes engaged
| 10         | +3.3V
| 11         | Ground               
| 12         | 0 ... ~+4V, 0V when no throttle connected


## Connection map starting at the controller side and ending to the connectors out of the handlebar mount
See the [connector-map.png](./connector-map.png) for a visual guide. The pin numbering scheme is counter clockwise, pin 1 is left most starting from the connector keying feature