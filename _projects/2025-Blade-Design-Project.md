---
layout: project
title: Wind Turbine Blade Design 
description: Advanced CAD Project
technologies: [Autodesk Fusion, MATLAB, Excel]
image: /assets/images/bladepicture.jpg
---

Project overview: 

For the Fluids and Heat Transfer Lab class, we were tasked with designing and testing a small scale three blade wind turbine. Our goal was to maximize the power output of the turbine at a representative wind speed that was obtained using the Weibull probability distribution, with parameters k and c equal to 5. We were given geometric and operational constraints: a maximum length/ radius of 6 inches, integration with a 1inch radius hub, and a max rotational speed limit of 2000 RPM. An experimental wind turbine was designed taking into account these constraints as well as material properties to ensure that it would fail under its operational loading. An airfoil profile, along with parameters such as twist and pitch were chosen according to what would provide a highly efficient turbine maximizing lift while reducing drag and optimal power extraction.  

Design Process: 

The blade geometry was developed using blade element aerodynamic modelling in MATLAB, where lift, drag, and the relative angle of attack were evaluated along the span. We divided the blade into 10 elements. Using these results were able to select an airfoil profile, the NACA 4412, as well as the twist angle of 90 degrees for improved lift across operating conditions. The structural integrity of our turbine was ensured through strength and bending analysis, which confirmed that the blade would remain below its flexural strength and prevent failure during testing. 

![Shaded rendering of earlier version]({{ "/assets/images/codeflowchart.jpg" | relative_url }}){: .inline-image-r style="width: 200px"}

![Photo of blade]({{ "/assets/images/blade-design.jpg" | relative_url }}){: .inline-image-l}

Testing Summary: 

In order to effectively evaluate our design, we tested our three blades in Big Blue. The purpose of the test was to quantify our turbine performance at operating speeds up to a maximum of 2000RPM. The goal was to obtain power curves at each tested speed, tip speed ratio, and efficiency. Testing was conducted in the lab in the big blue tunnel using our prototyped three-blade design attached to the hub. Using the LabVIEW interface for data acquisition to acquire power, rpm, voltage, and current readings. 

Once we had set up our blade with the hub, we ran the wind tunnel at five different wind speeds corresponding to a rotational speed of 250 to 550 RPM. At each of these speeds, we first recorded the free spin and baseline power, torque, rpm, voltage, and current data. We proceed to increase the electrical load on the turbine incrementally, going up by about 0.5V each time. At each of those increments, the turbine was allowed to reach steady state before the data was collected. Loading was continued until the rotor speed dropped significantly and the turbine was barely spinning, or when the turbine stalled completely. 

From the data obtained during testing, performance calculations were able to be conducted. 
![Photo of blade]({{ "/assets/images/calcs.png" | relative_url }}){: .inline-image-l}

The measured power curves show that mechanical power with rotational speed under increasing electrical load, reaching a maximum before declining as stall behaviour is approached. We obtained a maximum measured power output of about 1.1W. This occurred at the third rotational speed at which the test was run, at 400 RPM, rather than at the maximum rpm condition. The calculated efficiency curve indicates a maximum efficiency occurring at the condition of our maximum power output, with a corresponding tip-speed ratio of 0.51. The peak efficiency occurring at a tip speed ratio less than 1 suggests that the rotor operated at a relatively low blade tip speed compared to the incoming flow. For a more efficient turbine, we would expect a higher tip speed ratio closer to three.


![Photo of blade]({{ "/assets/images/powercurves.jpg" | relative_url }}){: .inline-image-l}

My Contribution: 
Throughout the design phase, I worked on the experimental protocol and came up with the best procedure to test our design during the 60-minute timeslot we were assigned. I used knowledge from previous labs’ experiments and lessons learned to make the process as smooth and straightforward as possible. After the experiment was conducted, I worked on postprocessing our data from Big Blue, calculating our tip ratio and efficiency, as well as making power and efficiency curves. 


