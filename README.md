# Resilience-Oriented Planning Map
#### Authors: Patrick Campbell, Kensuke Onishi, Adhiraj Shekhawat, Haoran Yan, Shule Chen, Chanté Solomon
#### May 17, 2020

## I.	 Introduction

In an effort to implement local solutions to the challenges posed by climate change, the City of Pittsburgh signed the Climate Protection Agreement on February 9, 2007. As a result of this agreement, the Green Government Task Force, the group charged with developing actionable plans to enforce the agreement, produced the Pittsburgh Climate Action Plan (PCAP 3.0) in 2017.  The PCAP 3.0 set reduction goals for Pittsburgh to achieve by 2030 and provided a methodology to measure progress towards those goals. 
The Climate Action Plan is based on six areas of interest, including:
-	Energy Generation and Distribution
-	Buildings and End Use Efficiency
-	Transportation and Land Use
-	Waste and Resource Recovery
-	Food and Agriculture
-	Urban Ecosystems

In collaboration with various agencies, the City has worked diligently to address the issues that Pittsburgh faces in all six of the aforementioned areas of interest. In regards to the Buildings and End Use Efficiency area in particular, the Sustainability and Resilience division partnered with the Rocky Mountain Institute (RMI) to create detailed plans designed to help the City improve and upgrade their buildings in ways that achieve the goals set forth by PCAP 3.0.  These plans focus on how the City’s budget can be efficiently invested in order to prioritize the PCAP 3.0 goals. 

*1.1 About the Client*

Through their work with partner institutions, the City of Pittsburgh’s Sustainability and Resilience (S&R) division, located within the City Planning Department, promotes and advocates for preventative resilience measures that seek to mitigate the many environmental hazards faced by the city. Such hazards include air pollution, flooding, extreme weather, public health challenges, and infrastructure failure. The division seeks to push progress on environmental stewardship so as to address these chronic stressors and ensure that all Pittsburgh residents live well. Beyond their work with their partners, the division achieves this goal by advising other City departments in ways that lead to more holistic decision-making and guide residents toward a more adaptable city.  

*1.2 Context and Problem Statement*

The City of Pittsburgh would like to better anticipate and respond to the impacts of climate change on public facilities and the communities they serve. Such information is essential for ensuring that this critical infrastructure remains open and operational even as many climate-related hazards become more frequent and intense. The City intends to use this fine-grained information about the exposure of each of their buildings to various hazards to make sure that each building receives the right retrofits at the right time to mitigate financial losses and prevent closures and/or suspension of public services.

Given the context provided above, the team formulated the following problem statement to guide its efforts:

> Problem statement: *How should the City allocate funding to the maintenance and renovation of its building stock in order to maximize resilience value to the community while minimizing long-term costs?*

(For the purposes of this project, the term ”building stock” will be constrained to the city’s Healthy Active Living Centers. See the scope section below for more details.)

*1.3 Scope*

Within the scope of this project, the term Healthy Active Living Center (HALC) is used to refer to the thirteen Healthy Active Living Centers (Senior Community Centers), the ten community recreation centers, and twelve other public facilities managed by Citiparks.
Healthy Active Living is a program managed by the City of Pittsburgh’s Department of Parks and Recreation (Citiparks) committed to ensuring that all persons 60 and older live active and healthy lives. According to their website, “Citiparks Community Services operates 13 Healthy Active Living Centers open year round, Mondays through Fridays. Each center focuses on improving the lives of older Pittsburghers—physically, intellectually, socially, culturally and financially.”  

Similarly, Community Recreation Centers operate year round and help to engage their community members through a multitude of outdoor, sporting, educational, and leisure programs.  Additionally, they operate many youth targeted programs such as summer camps and afterschool programs. 

Of these thirty-five centers, the client has identified six priority centers. These six centers, enumerated below, were prioritized because of their extended hours of operation, additional use as heating and cooling facilities, and higher capacity. 

Priority Centers:
1.	Ammon Recreation Center
2.	Brighton Heights Senior Center
3.	Homewood Senior Center
4.	Magee Recreation Center
5.	Sheraden Senior Center
6.	Southside Market House

Figure 1 below maps all thirty-five centers, highlights the six priority centers in blue, and displays a 1/2-mile radius, denoted by a pink circle, around the priority centers. For the purposes of this project we will use this 1/2-mile radius measurement as the service area for that HALC. 

*Figure 1. Map of Pittsburgh’s Healthy Active Living Centers*

<p align="center">
<img width="100%" height="100%" src="https://user-images.githubusercontent.com/32546509/83976868-dcd49180-a8ca-11ea-8fb5-705bbc28c2a6.JPG">
</p>

## Resilience-Oriented Planning Map

The Resilience-Oriented Planning Map is a geodatabase file created in ArcGIS Pro (v. 2.5.0) in order to provide quick reference of the 35 Healthy Active Living Centers in relation to the various hazards and other feature layers of interests. The user can easily turn on and off feature layers to answer specific queries, or add additional layers to open up entirely new fields of inquiry. Complete documentation of the data layers included in this map can be found in the accompanying Data Documentation file.

*Figure 2. Resilience-oriented planning map, Pittsburgh zoom extent*

<p align="center">
<img width="100%" height="100%" src="https://user-images.githubusercontent.com/32546509/83976894-fd045080-a8ca-11ea-8ab0-9ec6ffc15c3e.JPG">
</p>
 
The map includes a number of hazard feature layers, which enable the user to assess the risk posed to specific Healthy Active Living Centers by proximity to established flood zones and landslide prone areas as well as a wide variety of discrete hazards, including storm damage, stormwater runoff, and sewage overflows. Within the map, these features are overlaid with tenth-mile and quarter-mile buffers around the Healthy Active Living Center to more accurately assess the risk exposure of each center (Fig. 3).

*Figure 3. Hazard feature layers*

<p align="center">
<img width="100%" height="100%" src="https://user-images.githubusercontent.com/32546509/83976906-0beb0300-a8cb-11ea-89a8-663f662febe5.JPG">
</p>

Likewise, S&R staff can use the trees and air quality layers to identify centers where black carbon (shown) or other pollutants may pose a threat to patrons for prioritizing the installation of air purifiers, filters, or planting trees (Figure 4). 

*Figure 4. Air quality and trees features*

<p align="center">
<img width="100%" height="100%" src="https://user-images.githubusercontent.com/32546509/83976840-9ed76d80-a8ca-11ea-96ca-81921e18c34e.JPG">
</p>

Also included in the map are feature layers useful for scoping suitable sites for the development of green infrastructure, including green roofs, permeable pavement, and rain gardens (Fig. 5). These layers were imported from a more comprehensive study into the siting and cost effectiveness of such green infrastructure projects for the city of Pittsburgh. For more information on this study and its findings, as well as links to project documentation, visit the project’s website at https://wetweather.pitt.edu/green/. 

*Figure 5. Features for siting of green infrastructure projects*

<p align="center">
<img width="100%" height="100%" src="https://user-images.githubusercontent.com/32546509/83976913-1a391f00-a8cb-11ea-8a37-9df43d10b812.JPG">
</p>

View the full report [here]().
