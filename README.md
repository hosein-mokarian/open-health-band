# open-health-band
It's an open source health band. It monitors some vital symtoms of body. Ultra low power BLE MCU and E-Paper LCD is used to get a very low power device.
It just operates based on a coin cell battery. The custom knob is designed. It is based on optical rotary encoder. Users can have diffrent experence to when they use it.
It is really suitable to monitor patinets. BLE connection allow to send important data to PC or a cloud. It consits diffrent parts which are discribed in the following.
<h3>MCU</h3>
<h3>Antenna</h3>
<h3>Analog Device PPG</h3>
ADPD144RI-ACEZ-RL7
</br>
The ADPD144RI is a highly integrated, photometric front end optimized for photoplethysmography (PPG) detection of blood oxygenation (SpO2) by synchronous detection in red and infrared wavelengths. Synchronous measurement allows rejection of both dc and ac ambient light interference with extremely low power consumption.

The module combines highly efficient, light emitting diode (LED) emitters and a sensitive 4-channel, deep diffusion photodiode (PD1 to PD4) with a custom application specific integrated circuit (ASIC) in a compact package that provides optical isolation between the integrated LED emitters and the detection photodiodes to improve through tissue, signal-tonoise ratio (SNR).

The ASIC consists of a 4-channel analog front end (AFE) with two independently configurable datapaths with separate gain and filter settings, a 14-bit analog-to-digital converter (ADC) with a burst accumulator, two flexible, independently configurable, LED drivers, and a digital control block. The digital control block provides AFE and LED timing, signal processing, and communication. Data output and functional configuration occur over a 1.8 V I2C interface.

Applications

Optical heart rate monitoring
Reflective SpO2 measurement

<h3>Maxim PPG</h3>
MAX30102EFD+T
</br>
The MAX30102 is an integrated pulse oximetry and heart-rate monitor biosensor module. It includes internal LEDs, photodetectors, optical elements, and low-noise electronics with ambient light rejection. The MAX30102 provides a complete system solution to ease the design-in process for mobile and wearable devices.

The MAX30102 operates on a single 1.8V power supply and a separate 3.3V power supply for the internal LEDs. Communication is through a standard I2C-compatible interface. The module can be shut down through software with zero standby current, allowing the power rails to remain powered at all times.

Applications

Fitness Assistant Devices
Smartphones
Tablets
Wearable Devices

<h3>TI PPG</h3>
AFE4404YZPT
</br>
The AFE4404 is an analog front-end (AFE) for optical bio-sensing applications, such as heart-rate monitoring (HRM) and saturation of peripheral capillary oxygen (SpO2). The device supports three switching light-emitting diodes (LEDs) and a single photodiode. The current from the photodiode is converted into voltage by the transimpedance amplifier (TIA) and digitized using an analog-to-digital converter (ADC). The ADC code can be read out using an I2C interface. The AFE also has a fully-integrated LED driver with a 6-bit current control. The device has a high dynamic range transmit and receive circuitry that helps with the sensing of very small signal levels.

</br></br>
BAV99W-7-F
</br>
switching diode

<h3>Body Temp</h3>
TMP117MAIDRVR
</br>
The TMP117 is a high-precision digital temperature sensor. It is designed to meet ASTM E1112 and ISO 80601 requirements for electronic patient thermometers. The TMP117 provides a 16-bit temperature result with a resolution of 0.0078 °C and an accuracy of up to ±0.1 °C across the temperature range of –20 °C to 50 °C with no calibration. The TMP117 has in interface that is I2C- and SMBus™-compatible, programmable alert functionality, and the device can support up to four devices on a single bus. Integrated EEPROM is included for device programming with an additional 48-bits memory available for general use.

The low power consumption of the TMP117 minimizes the impact of self-heating on measurement accuracy. The TMP117 operates from 1.7 V to 5.5 V and typically consumes 3.5 µA.

For non-medical applications, the TMP117 can serve as a single chip digital alternative to a Platinum RTD. The TMP117 has an accuracy comparable to a Class AA RTD, while only using a fraction of the power of the power typically needed for a PT100 RTD. The TMP117 simplifies the design effort by removing many of the complexities of RTDs such as precision references, matched traces, complicated algorithms, and calibration.

The TMP117 units are 100% tested on a production setup that is NIST traceable and verified with equipment that is calibrated to ISO/IEC 17025 accredited standards.

<h3>IR Emitter</h3>
GP2S60B

<h3>Phototransistor Reciever</h3>
TLV8542RUGR
</br>
The TLV854x ultra-low-power operational amplifiers (op amps) are intended for cost-optimized sensing applications in wireless and low-power wired equipment. The TLV854x family of op amps minimize power consumption in equipment such as motion detecting security systems (like microwave and PIR motion sensing) where operational battery life is critical. They also have a carefully designed CMOS input stage, enabling very low, femto-ampere bias currents, thereby reducing IBIAS and IOS errors that would otherwise impact sensitive applications. Examples of these include transimpedance amplifier (TIA) configurations with megaohm feedback resistors, and high source impedance sensing applications. Additionally, built-in EMI protection reduces sensitivity to unwanted RF signals from sources such as mobile phones, WiFi, radio transmitters and tab readers.

The TLV854x op amps operates with a single supply voltage down to 1.7 V supply, providing continuous performance in low battery situations over the extended temperature range of –40°C to +125°C. All versions are specified for operation from –40°C to 125°C. The TLV8541 (single version) is available in the 5-pin SOT-23 while the TLV8542 (dual version) is available in the 8-pin SOIC package. The 4-channel TLV8544 (quad version) is available in the industry standard 14-pin TSSOP package.

TLV3691IDPFR
</br>
The TLV3691 offers a wide supply range, low quiescent current 150 nA (maximum), and rail-to-rail inputs. All of these features come in industry-standard and extremely small packages, making this device an excellent choice for low-voltage and low-power applications for portable electronics and industrial systems.

Available as a single channel, the low-power, wide supply, and temperature range makes this device flexible enough to handle almost any application from consumer to industrial. The TLV3691 is available in SC70-5 and 1-mm × 1-mm DFN-6 packages. This device is specified for operation across the expanded industrial temperature range of –40°C to 125°C.

<h3>IR LED Driver</h3>
TLV9002SIRUGR
</br>
The TLV900x family includes single (TLV9001), dual (TLV9002), and quad-channel (TLV9004) low-voltage (1.8 V to 5.5 V) operational amplifiers (op amps) with rail-to-rail input and output swing capabilities. These op amps provide a cost-effective solution for space-constrained applications such as smoke detectors, wearable electronics, and small appliances where low-voltage operation and high capacitive-load drive are required. The capacitive-load drive of the TLV900x family is 500 pF, and the resistive open-loop output impedance makes stabilization easier with much higher capacitive loads. These op amps are designed specifically for low-voltage operation (1.8 V to 5.5 V) with performance specifications similar to the TLV600x devices.

The robust design of the TLV900x family simplifies circuit design. The op amps feature unity-gain stability, an integrated RFI and EMI rejection filter, and no-phase reversal in overdrive conditions.

The TLV900x devices include a shutdown mode (TLV9001S, TLV9002S, and TLV9004S) that allow the amplifiers to switch off into standby mode with typical current consumption less than 1 µA.

Micro-size packages, such as SOT-553 and WSON, are offered for all channel variants (single, dual, and quad), along with industry-standard packages such as SOIC, MSOP, SOT-23, and TSSOP packages.

CSD17483F4
</br>
This 200-mΩ, 30-V N-Channel FemtoFET™ MOSFET technology is designed and optimized to minimize the footprint in many handheld and mobile applications. This technology is capable of replacing standard small signal MOSFETs while providing at least a 60% reduction in footprint size.

<h3>E-Paper LCD Driver</h3>
<h3>Opto Switch</h3>
GP2S60B
