---
layout: col-lg-12
title: The Storage4Grid Concept
---

Storage4Grid looks at scenarios in the low- and medium-voltage grid where storage installations are installed in the DSO domain and/or in user premises. 

Storage4Grid looks both at planning and control aspects and is therefore organized around both *Decision Support* and *Operations* concept.

## The Storage4Grid Decision Support Concept

S4G develops a Decision Support Framework (DSF) tool suitable to analyse, monitor and plan (MV and LV) grid scenarios.

The main goal of the tool is to evaluate and estimate the **technicaland business feasibility and sustainability** of MV and LV scenarios where storage solutions and EV charging solutions are installed. 

S4G tools builds upon standardized Common Information Model (CIM) and interfaces, pre-designed by the project and compatible with existing Smart Grid Standards. Whereas possible, such model and interfaces map towards existing models, only introducing where needed new storage-related features.

The tool allows professional users (e.g. DSO planning engineers, but also ESCOs professionals interested in evaluating storage investments, etc.) to model (MV and LV) grid scenarios by combining existing models of grid elements (loads, distributed sources, radials, sub-stations, etc.) and constraints (contractual limits, etc.) leveraging existing commercial and open tools.

<img style="width: 75%; border: 1px solid #1e3040; padding: 15px;" class="img-responsive center-block" src="{{site.baseurl}}/img/S4G-DSC.png">

The DSF tool allows the definition and inclusion in scenarios of new, pre-designed models and interfaces of controllable storages, so to enable what-if analysis of scenarios including components which are not yet existing or standardized e.g. controllable storage at user premises, public ―storage stations‖ acting both as a grid-side storage and a fast-charge station for vehicles, etc. The DSF tool also allow the exploitation of statistical and predictive control models built upon collections of historical data (load, generation, voltage, reactive/active power, etc.) collected by Unbundled Smart Meter (USM), Energy Router, SCADA systems from DSO meters and LV substations.

The DSF tool allows professional users such as planning engineers to draw conclusions about existing or hypothetical LV grid scenarios including: the technical feasibility of configurations of interest, their economical or environmental sustainability, the associated security of supply.

In practice, this means providing DSF users with a tool able to analyze (e.g. avoid energy curtailment from RES-based DGs or inefficient self-consumption, etc.), predict (e.g. the likelihood of the need to dispatch expensive generators because the available storage will not be sufficient to counter a load peak situation, EV charging impacts, life-time estimation, etc.) and plan (e.g. the optimal type/size/location/cost/distribution of storage mix to be deployed to improve performance).

## The Storage4Grid Operations Concept

Control configurations designed and preliminarily evaluated by means of the S4G DSF can be deployed to actual scenarios by means of Real-Time Storage control systems, allowing user-side and substation-level storage units to be controlled in Smart Grid scenario. At least two classes of ESS are expected to benefit from controls developed by means of S4G tools i.e. grid- and prosumer-side ESS. 

The objective of grid-side ESS control is to globally optimize grid network operations at LV level while user side ESS is to local optimize the local energy flows. Both control algorithm works in function of RES production, storage capacity available, load demand, generated and consumed energy prices. As the DSF tool, the control system is integrated also with the Smart Grid infrastructure, including DSO-owned systems such as GIS, SCADA.

<img style="width: 75%; border: 1px solid #1e3040; padding: 15px;" class="img-responsive center-block" src="{{site.baseurl}}/img/S4G-Operation-Concept.png">

S4G will also study and test an Energy Router with the goal to have distributed device able to manage energy at the local level and to be supervised and controlled by the S4G DSF. This tool will be built upon the 4-quadrant inverter with full functionality, that allows bi-directional energy transfer and information communication at the PCC level, e.g. between residential prosumer and grid. The inverter will provide classical DC bus connections for the generator and the ESS and a third additional DC bus dedicated to local loads, directly connected to the DC bus.

This last will enable demonstrating the feasibility and efficiency of using a DC home network with currently existing technology and appliances and thus saving energy dissipation.

DG dedicated bus will be managed using state-of-art Maximum Power Point Tracking algorithms (MPPT) for PV panels (to be tested in the project) or will potentially extract DC energy from wind-based local production. ESS dedicated bus will be managed through dedicated Battery Management System. An additional bus will be dedicated to EV charging points to enable vehicle to grid (V2G) service. The Energy Router will managed local energy flows using user side ESS control algorithms enhancing the possible services and flexibility given by the ESS presence.

The Energy Router will be integrated by the Unbundled Smart Meter (USM) which concept is developed in [NobelGrid](http://nobelgrid.eu/) and [FlexMeter](http://flexmeter.polito.it/) project and a Smart Meter eXtension (SMX), enabling: loads real time metering, communication with the ESS, monitoring of local RES production and moreover connection to the DSF through the local IP network. 

Through distributed SMX the DSF will be able to monitor and control distributed ESS using Grid side ESS control algorithm while acting also on the power quality due to the full 4 quadrant inverter functionalities given by the distributed Energy Router.
