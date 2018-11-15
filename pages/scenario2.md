---
layout: col-lg-12
title: Scenario B
---

# Cooperative EV charging

The growing diffusion of EVs is likely to threaten the stability of the grid, due to the increase of the load during night periods, where PV production is not sufficient to counter the additional load. The growing load may be especially difficult to handle in cases where large numbers of fast charging stations are deployed on the same radial such as e.g. in the case of places where commercial fleets of of EVs are charged.

The coordinated use of Storage technologies may help reducing the unbalance, thus deferring the need of investments to reinforce grid assets and architecture. An exemplary case of the situation is provided by the Alto Adige – Sudtirol region in northern Italy, an alpine region characterized by the presence of two medium cities (Merano and Bolzano), and with strong seasonal changes in electricity demand and use of EVs due to the touristic nature of the site.

Two classes of charging systems are currently in operations in the area:

1. Individual charging systems in use in private houses (residential case): private EV users mostly charge their vehicles at home, using a dedicated 3 kW charging box. While many EV users also own PV installations, cars are mostly charged in non-working hours, causing a peak of demand during night. It should be also mentioned that EV chargers are accounted and billed using the normal home meter, thus hindering the possibility of having e.g. dedicated prices for EV charging.

2. Large charging installation for EV company fleets (commercial case): a number of local companies (and EDYNA itself, which owns a fleet of 22 vehicles) are investing in fleets of EVs to support company operators. This causes the necessity to deploy charging parks characterized by support significant load capacity (e.g. from 500 kW for slow-charging, up to 900 kW to support simultaneous fast-charging of the whole fleet), which is currently not possible in all LV radials with the current grid.

Moreover, a number of public charging stations are operated by EDYNA and used by private users whose access and billing is controlled by using personal user cards. This latter case, except for billing aspects, is equivalent to the commercial case from the grid management point of view.

Overall, as of today, all configurations result in a low exploitation of RES and in the need of over-dimensioning the distribution grid. In order to allow EU utilities to pursue their ambitious EV charging infrastructure deployment plans while avoiding heavy investments in strengthening the grid, S4G will study methodologies for planning, evaluating and controlling storage installations communicating and cooperating with EV charging systems.

Figure below depicts the reference architecture of the "Cooperative EV Charging" scenario and test site, covering both the commercial and residential case. 

<img style="width: 75%; border: 1px solid #1e3040; padding: 15px;" class="img-responsive center-block" src="{{site.baseurl}}/img/Cooperative_EV_charging.png">

In the commercial case, a substation-level ESS, compliant with S4G interfaces and models will be used in conjunction with a commercial charging station featuring a combination of slow and fast Charging Points (CP), for a total of 10.

S4G will deploy modified "smart charge boxes" in each of the charging points so to enable fine-grained monitoring and control of the charging process from the DSO SCADA. Thanks to
the deployed infrastructure, a number of predictive control algorithms will be developed, deployed and tested to establish a cooperative behaviour between the EV charging and storage control processes.

From the planning point of view, the S4G DSF, will be employed in this scenario to study optimal sizing and design of the ESS. At this purpose, the S4G DSF will provide key information about the costs and benefits of such installations, as well as suggesting the best control strategy for such system once the storage enters the operational phase, therefore benefiting DSOs, service providers and organizations interested in jointly investing in EV fleets and their charging infrastructure. Overall, the commercial case will also be significant for DSOs interested in
planning charging station in city centres where the process of reinforcing the grid e.g. by digging new distribution cables is expensive and cumbersome.

In the residential case, S4G will consider a prosumer owning a residential PV installation integrated with a local ESS, as well as a plug-in EV, normally recharged at home during nightly hours through a dedicated 3kW residential CP. In this case, a dedicated USM will be deployed and interconnected to the storage, PV and CP, enabling also in this case the possibility to run predictive control algorithms aiming at maximizing self-consumption and minimizing energy costs for the user.

Moreover, a dedicated local Graphical User Interface (GUI) interconnected to the USM will allow the user to enter preferences and be more aware about the storage and EV status. From the planning point of you, in such case, the S4G DSF will be employed to support the design and sizing of local storage system and their impact on the cost, manageability and environmental sustainability of the EV charging process, both from the private users and from the local DSO point of view. As a part of this case, S4G will also consider the deployment of a standard sub-meter interface, part of existing smart metering standards, allowing for separate accounting and billing of EV charging costs, as well as the introduction of DR signals to reduce the impact of EV charging. This will allow deployed storage systems to implement an optimal control strategy for jointly controlling the charging process and the storage, to benefit the end-user and minimize impact on the grid.

Overall, analysis, development and evaluation activities for this scenario will be deployed in the Bolzano test site and led by partner EDYNA.
