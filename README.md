# Measuring PWM Signals
3rd June'24:- I can measure the time duration of the PWM pulses and also their frequencies

Core Learnings:-  
- Remember to set Input Channel Mode in the Timer Configurations
- Use __HAL_TIM_SET_CAPTUREPOLARITY for changing polarities. You can do both duty cycle dn frequency using just 1 channel
- Different channels require different interrupts  
