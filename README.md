# STM32_G0_WaveGenerator
This Keil uVision project contains a generic waveform generator class. This generic class generates sample values but does not send them to hardware and has no hardware dependencies. The calling code (in this case STM32 G0) will get the samples and set them up to the DAC output with simple Uart debugging
