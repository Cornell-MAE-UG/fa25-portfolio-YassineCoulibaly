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

Nulla et magna urna. Morbi a ipsum sollicitudin, rhoncus risus volutpat, ultricies nunc. Quisque mollis finibus ante id imperdiet. Quisque vehicula elit sit amet felis facilisis fermentum.

Aenean tincidunt aliquam arcu, in euismod dui dapibus eu. In placerat, mi et ultrices consequat, quam ligula cursus mauris, in semper neque nibh at est. Maecenas hendrerit dignissim porta. Phasellus nec fringilla dolor. Etiam efficitur nisi sit amet velit pharetra feugiat. Etiam ultrices turpis at leo semper, eleifend scelerisque neque malesuada. Aliquam molestie congue rhoncus. Donec blandit neque dolor, nec tristique mi pretium ac. Mauris tincidunt ullamcorper magna, nec pellentesque mi sagittis quis.

I was inspired by this old radio when I made this rendering:

![Photo of blade]({{ "/assets/images/bladepicture.jpg" | relative_url }}){: .inline-image-l}

Aenean tincidunt aliquam arcu, in euismod dui dapibus eu. In placerat, mi et ultrices consequat, quam ligula cursus mauris, in semper neque nibh at est. Maecenas hendrerit dignissim porta. Phasellus nec fringilla dolor. Etiam efficitur nisi sit amet velit pharetra feugiat. Etiam ultrices turpis at leo semper, eleifend scelerisque neque malesuada. Aliquam molestie congue rhoncus. Donec blandit neque dolor, nec tristique mi pretium ac. Mauris tincidunt ullamcorper magna, nec pellentesque mi sagittis quis.

Aenean tincidunt aliquam arcu, in euismod dui dapibus eu. In placerat, mi et ultrices consequat, quam ligula cursus mauris, in semper neque nibh at est. Maecenas hendrerit dignissim porta. Phasellus nec fringilla dolor. Etiam efficitur nisi sit amet velit pharetra feugiat. Etiam ultrices turpis at leo semper, eleifend scelerisque neque malesuada. Aliquam molestie congue rhoncus. Donec blandit neque dolor, nec tristique mi pretium ac. Mauris tincidunt ullamcorper magna, nec pellentesque mi sagittis quis.
