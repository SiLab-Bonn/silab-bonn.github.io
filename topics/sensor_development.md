# Sensor Development

***

From daily use digital cameras, medical X-ray imaging devices to particle tracking detectors in high energy physics (HEP) experiments, silicon pixel sensors efficiently convert photons and charged particles to electric signals. Like all semiconductor devices, the development of pixel sensors follows the cyclic procedure of: design &rarr; produce &rarr; test &rarr; optimize, aiming to achieve high spatial resolution and efficiency as well as low leakage current. Especially in the field of HEP, radiation-tolerant sensors need to be developed to withstand severe radiation damage.

***

## Device Simulation and Optimization

Numerical simulation offers an efficient way for testing and optimzing pixel sensors. TCAD ( **T**echnology **C**omputer **A**ided **D**esign) is a powerful software for such purposes and widely-used in the semiconductor industry. You will first need an insight on the general semiconductor device manufacturing processes and construct the sensor with the software. The device simulation offers you a chance to proceed experiments, while exploring enormous amount of physical models and discovering the physics behind the data. 

***

### Topic: Guard Rings

(_Last modified on_: {{ "2020-01-06 00:00:00 +0000" | date: '%B %d, %Y' }})

- Type: Master
- Location: SiLab
- Contact: [Sinuo Zhang](mailto:s.zhang@physik.uni-bonn.de)
- Description: Guard rings, located outside of the sensitive area of the pixel detector, surround the pixel matrix to supply the voltage and form the electric field on the sensor edge. Nevertheless, the situation there is more complex and the design of guard rings is crucial for suppressing the leakage current and pushing up the limit of breakdown voltage.
- Tool: TCAD
- Tasks: Simulate the guard rings of test structures, find out and discuss the impacts of the design and the operation conditions on related sensor performances.  Find out or design an optimum guard ring geometry.
- Possible extension: include the radiation damage and discuss the impacts.
