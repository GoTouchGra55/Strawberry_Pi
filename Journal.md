# Strawberry_Pi

## Day 1

I spent the entire day configuring the wiring up the strawberry pi board. Originally I wanted to use the stm32h757ZIYxx, but it was just way too complex due to the dual mcu architecture. I spent a whole lot of time on cubemx configuring that but it eventually went to waste. But I then went up with my trusty stm32h743vitx. Sure I had to remove some features like display but what it lost in functionality, it gained in it's convenience.

https://lapse.hackclub.com/timelapse/_1ylYZns9QVY

Then, I just read datasheets for the stm32 (On a separate device. So you won't see me changing windows very often.) and wired it up. Then the power components and finally the memory section.

https://lapse.hackclub.com/timelapse/YPAaonDyC28P

Finally, I wired up the ethernet and the camera connectors. I was pretty confused at first regarding the etherned wiring as the references showed differential paris while cubemx had configured something else. But after a quick google search, I came to know that it was because of the RMII setting I had set up in cubemx. I just needed a small chip and a suitable ethernet connector.

https://lapse.hackclub.com/timelapse/z4tXTK4zzKuB

## Day 2

Today was spent on finishing schematics!!!
I wired up the fan and breakout connectiors for SPI, I2C, UART, and 10 GPIO ports. I also wired the audio input connector and fixed any broken/error-prone connections. We had originally planned on a raspberry pi 4 form-factor board but due to the lack of USB-A ports, it's not feasible at the moment. So, I think we'll go with a raspberry pi zero form-factor but with ethernet capabilities like board.

https://lapse.hackclub.com/timelapse/AY0L5Gldac55
