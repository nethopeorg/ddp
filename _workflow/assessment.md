---
title: Needs Assessment
layout: workflow
wf_order: 6
---

## Needs Assessment
{%- include workflow_nav.html -%}

After conducting a damage assessment, the NetHope Crisis Informatics team will work closely with the deployed NetHope Emergency Response Team to conduct an in-depth needs assessment. Needs assessments are used to pinpoint where NetHope should focus its operations.

These can be conducted in two scenarios:

**Remotely**: Where the Crisis Informatics team will hyper focus its information products on the impacted population, gathering data from open repositories and on-site entities NetHope has relationships with.
**In the field**: Where the NetHope Emergency Response Team will deploy several team members to the impacted country. Team members will survey the government, humanitarian organizations, and impacted communities on where

From a remote distance, NetHope Crisis Informatics will look to gather information from data sources that provide both historical (pre-crisis) and current (in-crisis) information. Historical data can provide context on existing patterns of population needs, such as: population and other demographic baselines, nutrition surveys, quality of health or education facilities, and infrastructure surveys. Just as in the damage assessment phase, information can come from a wide variety of  sources for needs assessments: including such as media reports, social media, personal reports from key informants who have visited or live in the area, aerial imagery for infrastructure damage (e.g. provided by UNOSAT, NDMA, or crowdsourcing), and formal situation reports from government entities or international agencies. Initial

Gathering information remotely, which can also be referred to as “secondary data” is crucial for humanitarian needs assessments and forms the foundation for all decision making. Secondary data inform what kind of primary data, that which is directly collected in the field, should be gathered. It is especially important due to the usual resource constraints, either financial and logistical, that limit the collection of new primary data.

If NetHope deploys an assessment team to a country, that assessment team - often staffed by NetHope Emergency Response - will survey local partners to understand what kind of connectivity aid is needed and where. This information is collected on an Excel spreadsheet and stored on Box. NetHope Crisis Informatics will then take the Box file and create visual dashboards for NetHope leadership and Emergency Response to view and interact with. Depending on the severity of the disaster and the potential for launching a full-on response effort, NetHope may also share visuals with donors, so they may also get an understanding of what’s happening on the ground and what the need is for connectivity support.

In the survey, the assessment team will gather the following information:

<table>
<tr><td>NetHope ID:</td><td>Assigned number the assessment team has given to a connectivity site</td></tr>
<tr><td>City:</td><td>Name of the city or town the survey is being conducted in</td></tr>
<tr><td>Country:</td><td>Name of the country the survey</td></tr>
<tr><td>Coordinates:</td><td>Latitude and longitude, recorded in decimal form</td></tr>
<tr><td>Total population:</td><td>Count of persons in the town, city or shelter</td></tr>
<tr><td>Date of survey:</td><td>When the survey was conducted</td></tr>
<tr><td>Member NGO presence:</td><td>Describes which, if any, NetHope members would access connectivity through the site</td></tr>
<tr><td>Status:</td><td>Whether that particular connectivity site is actively providing connectivity or has been closed</td></tr>
<tr><td>Connection type:</td><td>The type of device that has been setup. Example: LTE, VSAT, or P2P</td></tr>
<tr><td>Date operational:</td><td>A record of when the device went live and connectivity became available for intended users (i.e. the public or the local government building)</td></tr>
<tr><td>Internet provider:</td><td>Which mobile network operator is providing service on the device</td></tr>
<tr><td>Bandwidth:</td><td>Maximum amount of data that can transferred at any given time on the device</td></tr>
<tr><td>Team:</td><td>The letter of the NetHope emergency response team that collected the information. (Example: Team A)</td></tr>
<tr><td>Comments:</td><td>Any additional notes the assessment team wants to record, but doesn’t belong in the previous data fields</td></tr>
</table>

NetHope Crisis Informatics is currently developing a mobile form version of the assessment survey, so (1.) future assessments teams can conduct surveys more efficiently (2.) NetHope Crisis Informatics can automate the visualization process. The collective goal is to see and share the information assessment teams are collecting in real-time.

## Appeals

One of the primary sources of data on humanitarian funding, the Financial Tracking Service (FTS), is managed by the UN Office for the Coordination of Humanitarian Affairs (OCHA). The FTS was established in 1992, but in recent years has made significant progress in applying standard methodologies and data structures, with a updated platform release in 2017. The service is not and never will be a comprehensive digest of all humanitarian funding - even for the highest profile events - but it is a very useful resource in tracking the funding from donors to local humanitarian actors, and in comparing the scopes and degrees of response to consolidated humanitarian appeals. The FTS is particularly useful in tracking data voluntarily submitted by government donors, UN-administered funds, UN agencies, NGOs, and increasingly the private sector.

### List of Commonly-Used Data Sets for Needs Assessments:

NetHope Crisis Informatics will commonly develop and/or utilize the following external datasets in this phase of the information management cycle:

**Hydrography**: Identify bodies of water and their potential impacts on response efforts
Sample datasets: Current flooding extents, Levee/barrier breaches

**Weather**: Identify event related conditions that may influence response
Sample datasets: NOAA NWS weather trajectories

**Utilities**: Identifies impacted infrastructure that could be damaged or hazardous.
    Sample datasets: Power outages, phone (land-line) outages, and cell phone outages, damaged cell towers

**Transportation**: Identifies impacted access routes to the incident and other related transportation reference points.  
Sample datasets: Road closures, airport closures, rail & subway stoppages, bridge closures, ferry stoppages, and port closures

**Population**: Identifies clusters of impacted and at-risk populations.
Sample datasets: Population density, socio-economic data (income, gender, age etc.), nighttime population vs. daytime population, seasonal population, businesses, at-need population (schools, day care, nursing homes, assisted care facilities, universities, hospitals/clinics, urgent care, mental health and correctional facilities, etc.)

**Public Safety**: Identifies potential response sites at public safety and incident command facilities
Sample datasets: Fire stations, police stations EOCs (local, State, national), Public Safety Answering Points (PSAPs)/911 Call Centers, shelters, evacuation zones

### List of Commonly-Used Data Sources:

NetHope Crisis Informatics will commonly utilize these data sources and repositories in this phase of the information management cycle:
* Satellite imagery providers: Planet, DigitalGlobe, Esri
* UN Agencies: UN OCHA, UNOSAT,  WFP, Emergency Telecommunications Cluster
* Alert portals: Reliefweb, Global Disaster Alerting Coordination System (GDACS), Pacific Disaster Center (PDC)
* News outlets: CNN, BBC, Al Jazeera, local news
* Humanitarian Data Exchange
* NetHope NGO members and tech partners
