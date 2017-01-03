---
layout: col-lg-12
title: Scenario A
---

# Advanced Cooperative Storage Systems

Lower-TRL solutions proposed by S4G, namely the introduction of the Energy Router and the use of storage in joint with DC buses cannot currently be tested in real electrical home systems, due to current regulations and lower maturity of the proposed solutions. Also V2G services cannot be tested because commercial EV and standard charging points only provide G2V services.

One solution for increasing the use of renewables is to find new strategies to promote the connection of distributed energy resources (DERs) within the existing power system. A solution that allows a flexible integration of distributed generation (DG) into energy networks is the use of DC at user premises.

This seems a reasonable choice since several renewable sources and the presently available storage systems deliver electricity in DC form (e.g., fuel cells and solar cells). Anticipating the extensive use of low-power DC-based intelligent devices, one can avoid losses in energy transfer by using a dc layer within the distribution networks, at least where the energy is produced in DC form. 

DC grids in buildings are thus expected to be especially promising for a number of scenarios.

Firstly, the use of DC buses to serve critical loads to allow 24/7 functionality as well as selected loads in home which are related to survivability would remove the need of employing a wide number of AC/DC transformers that is currently needed for many of today’s DC home appliances, resulting in high stand-by consumption.

Secondly, while simple control capabilities can be achieved by altering the working parameters of existing hybrid inverters, more sophisticated use cases e.g. engaging distributed
inverters and ESS to collaborate to provision of ancillary services is not possible.

The home DC bus will support DSO with 24/7 observability, as it will supply critical equipment of the project (SMX, energy router, telecommunication equipment) and may allow in future even black-start support, in an islanded grid. To be noted that the local DC gird will be able to supply its critical loads also during small AC voltage interruptions or during black-outs, as the inverter connection to the grid will be kept during this period un-operational, to be compatible with existing network codes, but also will allow opening for future, e.g. for black-start inside a micro-grid.

In order to experiment with such concepts in controlled conditions, S4G has devised a dedicated lab-scale technical
scenario, namely the "Advanced Cooperative Storage Systems" scenario.

<img style="width: 75%; border: 1px solid #1e3040; padding: 15px;" class="img-responsive center-block" src="{{site.baseurl}}/img/advanced-cooperative-storage-system.png">

The reference, emulated house is instrumented with, beyond the traditional AC bus, with 3 DC buses to directly interconnect PV systems, DC Home loads and any available battery management system.

The Energy Router, derived from the power electronics solid state transformer concept, acts as "power gateway" between the local renewable PV production, the local electrical storage through the battery pack and the prosumer’s power network. 

Various configuration and sizes of Energy Router could be tested (e.g. 3 kW mono-phase or 6 kW three-phases solutions). The setup includes an USM integrated with a commercial smart meter
(MID, metrology enforced, used for billing) connected to a set of Smart Meter eXtension (SMX) for each relevant bi-directional sub-meter or sensor of interest.

The SMX reads meter data from the commercial meter in real-time and use the information for various local purposes (local optimization of generation, storage and consumption) and for remote purposes – e.g. for DSO observability and control using the appropriate communication standards.

In the lab configuration, all loads and PV sources are logically interconnected with the hybrid simulation sub-system of the S4G DSF, so to enable the generation of synthetic test scenarios, including various combination of AC or DC load patterns simulating a wide set of sources and loads including: EV chargers; heat pumps; HVAC; white goods; etc. The chosen hybrid simulation approaches has been devised to allow evaluation of predictive control algorithms logically deployed in different physical locations of the simulation scenarios. For instance, the set-up could be used to test the effect of remote signals sent by the DSO SCADA via the USM, as well as simulating the behavior of a local control algorithm performing user side ESS control, running on-board the Energy Router.

In the setup, various combination of batteries can be evaluated, including packs of second-life car batteries arranged to cope with the Energy Router specifications.

The proposed setup will enable controlled evaluations about the performance in terms of: ability to store and exploit produced energy; the ability to store efficiently and exploit cheap energy available from the DSO network; assess the ability of the Energy Router to act as a secondary Voltage controller reacting to DSO signals by using active power modulation (reference project INCREASE); assess the ability of the Energy Router to act as a Frequency variations mitigating unit e.g. as part of a scenario where several Energy Routers are controlled by an aggregator; assess the ability of the Energy Router to provide phase balancing services; assess the self-consumption possibilities; assess the ability for the overall system to react to complex demand response requests only employing storage and without shaving non-controllable loads; assess the ability of the Energy Router and Storage system for peak shaving and to cope with high shares of variable renewables in the grid.

Moreover, the setup will be used as a test bench to devise other innovative market and grid services, e.g. V2G.

The "Advanced Cooperative Storage Systems" scenario will be set up in Bucharest and operated by partner UPB in the MicroDERLab facilities.
