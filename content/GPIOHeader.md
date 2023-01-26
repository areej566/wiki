<img src="../files/img/2018_MistyWest_LogoCombo_FINAL_RGB.png" alt="MistyWest" width="400"/><div style="text-align: right">back to [index](../README.md)</div>

# GPIO Header								

|func5| func1|func0|desc|pin#|pin#|desc|func0|func1|
|-----|------|-----|----|----|----|----|-----|-----|
||||	5V| 1|2|3.3V | |
||||	1.8V	|3|	4|	GND	| |
||||	GND|	5|	6|	1.2V	||
|||RIIC1_SDA|	dedicated I2C|	7|	8|	GND	||
|||RIIC1_SCL|	dedicated I2C|	9|	10|	2.5V	||
||RIIC2_SDA|	P42_3|	3.3V GPIO|	11|	12|	GND	||
||RIIC2_SCL|	P42_4|	3.3V GPIO	|13	|14	|GND		||
|||NMI	|input	|15	|16	|Analog	|ADC_CH0	|
|||			|GND	|17	|18	|Analog	|ADC_CH1	||
|shared with Laird|	SCIF2_TXD	|P48_0	|3.3V GPIO|	19	|20|	Analog|	ADC_CH2	|
|shared with Laird|	SCIF2_RXD	|P48_1	|3.3V GPIO|	21	|22	|Analog|	ADC_CH3	|
|shared with Laird|	SCIF2_CTS	|P48_3	|3.3V GPIO|	23	|24	|Analog|ADC_CH4	|
|shared with Laird|	SCIF2_RTS	|P48_4	|3.3V GPIO|	25	|26	|Analog|	ADC_CH5	|
||||	GND	|27	|28	|Analog	|ADC_CH6	|
||||GND	|29	|30	|Analog	|ADC_CH7	|
||||GND	|31	|32	|GND		
|SCIF3_TXD|		|P0_0	|3.3V GPIO|	33|	34|	3.3V GPIO|	P43_0|RSPI0_CK
|SCIF3_RXD|		|P0_1	|3.3V GPIO|	35|	36|	3.3V GPIO|	P43_1|SPI0_MOSI
|SCIF3_SCK|		|P1_0	|3.3V GPIO|	37|	38|	3.3V GPIO|	P43_2|SPI0_MISO
||||	GND|	39|	40|	3.3V GPIO|	P43_3|	RSPI0_SSL