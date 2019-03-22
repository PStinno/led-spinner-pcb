# led-spinner-pcb
My first two layer PCB, spinning LED effect with no micro-controller or code.

![](images/led_spinner.gif)

The circuit consists of two 4017 decade counters, connected together to create sixteen sequential outputs. The outputs progress on each clock cycle and loop back to the beginning when the end is reached. Each output is connected to an LED on the perimeter of the PCB. The clock input is connected to a 555 timer IC in an astable configuration. This generates a continous square wave, causing the progression of the outputs and the spinning effect.

![](images/led_spinner_front.jpg)
![](images/led_spinner_back.jpg)
