# Research Practicum 2019 – Research Plan 

> * Group Name: It Belongs in a Museum
> * Group participants names: Cornell, Lincoln; Necaise, Aaron; Robkin, Jessica; Vaz, Karina
> * Project Title: Cultural Heritage Transportation Simulation Project

## Topic/Purpose Statement

This study addresses the viability of using computer simulations to identify the relationship between transportation networks and the smuggling of illicit antiquities. The purpose of this research is to provide a tool for law enforcement agencies and cultural heritage workers to recover looted archaeological artifacts before they reach the black market for sale. The first phase of this qualitative study will involve the running of weighted transportation simulations, guided by graph theory, to determine probable routes between selected archaeological sites that are known to have been looted during the 2014 ISIS insurgency in Syria and Iraq and known locations where caches of illicit artifacts have been recovered. The data from these simulations will be used to create a forced-decision survey designed to explore the routes that participants will select when informed of socio-political elements and available transportation networks.

## General Introduction

Throughout the Middle East and North Africa (MENA) region, organized criminal gangs have taken advantage of political instability to loot archaeological sites for the purpose of selling illicit antiquities to fund political insurgency and terrorist organizations (Terrill, 2007). While looting in these areas is a centuries-old practice (Luke & Kersel, 2005), advances in technology and a growing demand for antiquities from this region has caused a dramatic increase in these activites (Terrill, 2007).  

During the insurgency of Syria and Iraq by ISIS in 2014, the terrorist organization often televised the systematic destruction of what they termed “idolatrous” heritage. Using this as justification for the destruction of cultural heritage sites in the region, ISIS quietly looted these sites prior to their televised destruction, with the funds gained on the black market used to further support their effort (Terrill 2017). During this same time period, ISIS routinely issued permits to groups in the areas under their control, allowing for the looting of archaeological and cultural heritage sites, with the permittees sharing a portion of the black market profits with ISIS in exchange for the right to keep some of the profits for themselves. The looting of these sites and the subsequent improvements to structures in the areas bordering the sites has been observed through satellite analysis of the locations (Casana, 2015; Parcak, 2013). In the intervening years, while the presence of ISIS in the region has been marginalized, the looting of archaeological sites continues in the destabilized region (CITE). Oftentimes, the looting of these resources is not known until months after the fact, often seen by satellite imagery or when locals discuss their activities with archaeologists returning to some of the affected areas to continue their research (Casana, 2015; Proulx, 2013). 

The duel impact of the loss of cultural heritage and the monies gained from their sale are motivation to find methods to intercept stolen antiquities before they reach the black market. Understanding the methods of transportation that these groups utilize is essential to understanding how they are moving these goods from the initial archaeological sites, through the countries, across the borders, and into safe houses where they could be held for decades before they are sold. 

Computer simulations offer an option for this research. By first understanding the transportation options available to smugglers, simulations can be informed [following the principles of graph theory] which can provide reliable insight on the routes that smugglers would select when transporting illicit antiquities away from looted archaeological sites. Research into transnational smuggling indicates that when transporting illicit goods, smugglers will often select one of two methods, to either hide in plain sight or to move with stealth (Basu, 2013; Basu, 2014). Following the idea that smugglers will act as normal citizens when they travel (Basu, 2014) this project has several aims, first to use computer simulations to identify travel routes from known looted archaeological sites to locations where caches of illicit goods have been recovered, to then use this data to administer a qualitative survey to better understand which paths a “normal citizen” [DEFINE] would prefer to travel when informed of road conditions, faction-control of roads, and available alternative routes, and, finally, to then use the data gained from these surveys to gauge how accurately a simulation will select the same routes, given the same information (How are we doing this part?). In an attempt to aid cultural heritage workers, international NGO's, and local stakeholders, this project seeks to address this problem through the use of computer simulations based upon in-country transportation networks to illuminate the relationship between this infrastructre and the paths that criminals would use to transport stolen antiquities from archaeological sites. We believe this project will provide proof of concept that computer simulations can reliably predict the routes that smugglers would select when they choose to hide in plain sight. 
 

Hypotheses:

H1: Incorpoarting region specific variables that are related to smuggling behavior (faction border, distance, crime rates, and circuity) will lead to improved prediction of smuggling paths compared to standard shortest-path graph models for routing. 

>> H1 Rationale: Based off previous literature, it is reasonable to believe that smugglers will take actions that help them blend in with civilians in order to avoid detection by authorities. However, in  countries that are  dealing with major geopolitical conflicts, standard shortest-path routes generated by a program like Google maps are not applicable. It can be difficult to predict the routes in a country with unstable infrastructure.  Further, smugglers are likely to be more concerned with the presence of border security or enemy faction control in the region than they are of police presence. From this standpoint, incorpoarting regional specific information--like the circuity of a route or the presence of border security-- into a graph model for routing may lead to improved prediction of smuggling routes.

H2: Given a forced-choice questionnaire where participants are asked to take the perspective of a smuggler choosing routes, survey respondents will tend to prefer indirect, medium risk routes over direct, high risk routes. 

>>H2 Rationale: A major challenge for the current project will be validating our model against historical data. Currently, there are some documented drug smuggling routes that have been made public throughout Central and North America. These routes  will be used as validation data for our model. However, drug smuggling routes may differ from artificat smuggling routes, and the drug smuggling route data is limited to begin with. By administering a survey where participants are asked to make various route decisions, we hope to gain more insight about smugglign behavior and provide further validation for our predicted routes.

H3: Geopolitical conflict will influence region-specific routes. 

>> H3 Rationale: One assumption that we are operating under is that smugglers will generally behave like ordinary citizens in order to lower their visibility to law enforcement. A concern is that--in countries with political instability--law enforcement may not serve as a detriment to smugglers if police corruption is an issue. To better understand how regional instability may influence smuggling and law enforcement behavior, we plan to distribute a qualitative survey to participants who live(d) in those regions.

#### Motivation
The looting of historical sites is both damaging to the culutral heritage of local communities and helping fund dangerous terrorist activity in the MENA region. While there has been a large amount of research focused on drug smuggling, little has addressed the issue of artifact smuggling. This research will address this gap in the literature and potentially have real-world impact on artifact smuggling.

#### Proposed Solution
The current project will utilize graph-theory to develop a series of routes within known smuggling networks. Our modeled smuggling network will take into account highly related factors like circuity and border security in order to generate a  routes with better validity than what can be achieved with shortest-path routing. A series of surveys and questionnaires will be used to gain additional insight about our model and smuggling behavior. The goal is for this model of smuggling to be extended to the MENA region where it can be used to predict artifact smuggling routes.

#### Contributions:
•	Develop a methodology for predicting artifact smuggling routes that can be applied in the MENA region. 

•	Gain insight into smuggling behavior, including information on routing decisions and understanding the influence of geopolitical conflict on smuggling.

## Related Work / Literature Review

  One obstacle for predicting the routes that looters take while transporting goods away from archeological sites is understanding how the political or geographical conditions of a region could influence the routing decisions made by smugglers. While looting in the MENA (Middle East and North Africa) region deserves unique considerations because of the activity’s relationship to terrorist groups, certain behaviors might hold true  across regions (Proulx, 2013).  From this perspective, understanding looting behavior at a global level could serve to inform our model for looting in the MENA region. 
  
  There is some anecdotal evidence to suggest that looters often do not take precautions to avoid detection by archeologists or law officials after they have stolen historical goods (Proulx, 2013). In this study on regional attitudes towards looting,  Proulx (2013) found that the majority of archeological field-workers come into contact with looters while working. Further, nearly half of these field-workers have been solicited by looters to purchase back stolen goods. Data from this study was aggregated from historical sites located broadly throughout the world, which provides some insight on looting activity in MENA. However, this study does not help to explain routing behavior that is dependent on border customs and region-specific faction politics. 

  Transporting illegal antiquities has it's own unique set of complications (proper handling, packaging, packing) (CITE), however the methods selected to transport these items over land shares many similarities with the trafficking of other illicit goods (Alderman, 2012; Basu; 2013, Basu, 2014). Undertanding how these goods are moved over land is useful in informing our transportation models and selecting appropriate variables for study.  To further our understanding of how smugglers historically move illicit goods over land, a review of current research in the field of transnational smuggling was necessary. Transnational smugglers traditionally select two methods to move goods from destination to destination, moving either with stealth or blending in with traditional supply chain movements (Basu, 2013; Basu, 2014). Traffickers make these decisions in a rational way, looking to make the most profits with the fewest risks (Medel et al., 2015). Medel et al. (2015) investigated the movement of drugs from Mexico into the United States, using crime data to inform transportation prediction models. For these models, an understanding of the midset of the drug cartels was necessary. The movement of illicit goods requires planning and precision, with traffickers often making well-informed decisions about the routes they use, taking into consideration the political environments the goods must move through, the quality of available routes, and environmental concerns that may impact transport (Medel et al., 2015). Medel et al. use these factors in conjunction with socio-demographic and crime data to define their cost for moving drugs along the road networks in Mexico. This methodology will inform our own weighting criteria. 
  
## Research Method

## References 
Alderman, K. L. (n.d.). Honor Amongst Thieves: Organized Crime and the Illicit Antiquities Trade. Indiana Law Review, 45, 27.

Basu, G. (2013). The role of transnational smuggling operations in illicit supply chains. Journal of Transportation Security, 6(4), 315–328. https://doi.org/10.1007/s12198-013-0118-y

Basu, G. (2014). The strategic attributes of transnational smuggling: Logistics flexibility and operational stealth in the facilitation of illicit trade. Journal of Transportation Security, 7(2), 99–113. https://doi.org/10.1007/s12198-013-0132-0

Casana, J. (2015). Satellite imagery-based analysis of archaeological looting in Syria. Near Eastern Archaeology, 78(3), 142–152.

Luke, Christina, and Morag Kersel. (2005). A Retrospective and a Look Forward. Journal of Field Archaeology, 30(2), 191-200.

Medel, M., Lu, Y., & Chow, E. (2015). Mexico’s drug networks: Modeling the smuggling routes towards the United States. Applied Geography, 60, 240–247. https://doi.org/10.1016/j.apgeog.2014.10.018

Parcak, Sarah, David Gathings, Chase Childs, Greg Mumford, and Eric Cline. (2016). Satellite Evidence of Archaeological Site Looting in Egypt: 2002–2013. Antiquity, 90(349), 188–205.

Proulx, B. B. (2013). Archaeological Site Looting in “Glocal” Perspective: Nature, Scope, and Frequency. American Journal of  Archaeology, 117(1), 111. https://doi.org/10.3764/aja.117.1.0111

Terrill, W. Andrew. (2017). Antiquities Destruction and Illicit Sales as Sources of ISIS Funding and Propaganda. Carlisle, PA: U.S. Army War College. 
