Dispa-SET for the Balkans region
================================

### Description
This code is a forked version of the Dispa-SET model, applied to the Balkans Countries: Albania, Bosnia and Herzegovina, Kosovo, Macedonia, Montenegro and Serbia. 

The model has the ability to describe every single unit, or a cluster of units powered by the same fuel type and technology, with a high level of detail can be modelled together with a large number of RES units with separate hourly distribution curves. For this purpose, a reference case and two alternative scenarios. The model has been validated on the year 2010. To optimise the development of the system for the 20 years’ period and to show the robustness of the model and provide more future alternatives, two additional scenarios are modelled. In Scenario A analyses the implementation of national energy strategies for the years 2020 and 2030. Scenario B analyses the integration of high share of renewable energy sources for the same years. Simulations show that a large-scale RES integration in the analysed region can decrease the marginal cost of electricity by almost double. 
 
### Features
The model is expressed as an optimization problem. Continuous variables include the individual unit dispatched power, the shedded load and the curtailed power generation. The binary variables are the commitment status of each unit. The main model features can be summarized as follows:

- Minimum and maximum power for each unit
- Power plant ramping limits
- Reserves up and down
- Minimum up/down times
- Load Shedding
- Curtailment
- Pumped-hydro storage
- Non-dispatchable units (e.g. wind turbines, run-of-river, etc.)
- Start-up, ramping and no-load costs
- Multi-nodes with capacity constraints on the lines (congestion)
- Constraints on the targets for renewables and/or CO2 emissions
- Yearly schedules for the outages (forced and planned) of each units
- CHP power plants and thermal storage

The demand is assumed to be inelastic to the price signal. The MILP objective function is therefore the total generation cost over the optimization period. 

### Documentation
The general documentation of the Dispa-SET model and the stable releases are available on the main Dispa-SET website: http://www.dispaset.eu

### Licence
Dispa-SET is a free software licensed under the “European Union Public Licence" EUPL v1.1. It can be redistributed and/or modified under the terms of this license.

### Main developpers
- Matija Pavičević (KU Leuven) - gathered and analysed the data, performed the computations, analysed and verified the results
- Sylvain Quoilin (University of Liège) -  designed the model and the computational framework, verified the results 
- Andreas Zucker (Joint Research Centre, European Commission) - supervised the whole process

### References
More details regarding the model and its implementation are available in the following publications:
Pavičević, M., Kavvadias, K. & Quoilin, S. (2018). Impact of model formulation on power system simulations - Example with the Dispa-SET Balkans model, EMP-E conference 2018: Modelling Clean Energy Pathways, Brussels. 
Pavičević, M., Quoilin, S. & Pukšec, T., (2018). Comparison of Different Power Plant Clustering Approaches for Modeling Future Power Systems, Proceedings of the 3rd SEE SDEWES Conference, Novi Sad.
Tomić, I., Pavičević, M., Quoilin, S., Zucker, A., Pukšec, T., Krajačić. G. & Duić, N., (2017). Applying the Dispa-SET model on the seven countries from the South East Europe. 8th Energy Planning and Modeling of Energy Systems-Meeting, Belgrade. https://bib.irb.hr/prikazi-rad?rad=901595
Pavičević, M., Tomić, I., Quoilin, S., Zucker, A., Pukšec, T., Krajačić. G. & Duić, N., (2017). Applying the Dispa-SET model on the Western Balkans power systems. Proceedings of the 2017 12th SDEWES Conference, Dubrovnik. http://hdl.handle.net/2268/215095


### Other contributors
- Ivan Tomić (University of Zagreb) - gathered and analysed the initial data
- Tomislav Pukšec (University of Zagreb) - analysed the inital results
- Goran Krajačić (University of Zagreb) - supervised inital project
- Neven Duić (University of Zagreb) - supervised inital project 