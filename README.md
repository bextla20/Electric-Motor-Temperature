# Electric Motor Temperature

The influencing factors of stator winding temperature and prevent motor insulation ageing, insulation burning, permanent magnet demagnetization and other faults caused by high stator winding temperature, we propose a computer model for PMSM temperature prediction. Ambient temperature, coolant temperature, direct-axis voltage, quadrature-axis voltage, motor speed, torque, direct-axis current, quadrature-axis current, permanent magnet surface temperature, stator yoke temperature, and stator tooth temperature are taken as the input, while the stator winding temperature is taken as the output.

This dataset provides readings from several sensors fitted to monitor the main two pieces of PMSMs, namely the stator and the rotor. Below image showcases the components under consideration.

Generally, due to presence of moving parts working under various states of the motor speed and torque (a point at the motor speed x torque plain) thermal losses will be generated which impact the equipment in the long run shortening its lifespan. The copper loss of a permanent magnet motor stator directly affects the heating degree of the stator winding.

The stator is the stationary component of electromagnetic circuits in motors. In different configurations, stators may act as field magnets that interact with the rotor to create motion, or as armatures that work with moving field coils on the rotor.


![Motor](https://user-images.githubusercontent.com/62169942/153264340-87c2a0c9-01ce-4500-9c1c-48573864d78c.jpg)

The dataset consist of Permanent-Magnet Synchronous Motor (PMSM) attributes of any motor detail such as ambient, pm, stator yoke, stator tooth, stator winding and profile id. The aim is to predict multiple target accuracy. 

#### Profile ID size:

![profileid](https://user-images.githubusercontent.com/62169942/153266070-c94277ff-6211-4cf3-8619-5284e5794beb.png)


#### Stator features by different Profile ID.

Profile ID with 20
![Stators](https://user-images.githubusercontent.com/62169942/153265426-788d4576-2b6d-4d92-ad1b-671cb53a8c42.png)

Profile ID with 47
![Stators1](https://user-images.githubusercontent.com/62169942/153265436-26904d48-92e8-4c63-bfce-e4d527c92e2c.png)





l tried to use some regression models and hyperparameter tuning
