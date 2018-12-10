---
title: Data Scramble
layout: workflow
wf_order: 1
---
# Workflow for NGO Information Managers
## Data Scramble
{%- include workflow_nav.html -%}

For a humanitarian organization, the minutes and hours following the onset of a disaster are characterized by a swirl of information gathering, with queries and exchanges that are both internal and external. In the context of information management, this phase is known as the ‘data scramble.’

In the case of weather events and other natural hazards for which there has been some element of advance warning, the data scramble begins well before a storm makes landfall or a wildfire reaches a populated place. In the ‘best case’ scenarios–often in geographies that experience hazards with regular frequency–much of the baseline information required to develop an initial high-level snapshot has already been identified and is readily accessible. But even in these cases, it is likely that some information will have to be updated, or that more granular data will need to be obtained or created to address the specific context of the event.

While good data preparedness may reduce the complexity of the data scramble phase, it will never obviate it. Some things can be prepared ahead of time, such as maps of facilities and lists of key in-country contacts. But many data sets only come into focus as it becomes clear which organizations are deploying teams to meet the challenges of specific emergencies. And however good data preparedness may be, few organizations have the resources to constantly update data. As the World Bank describes in the Open Data for Resilience Field Guide, data are rarely in a form that international responders would like:

<blockquote>
<p>"Data describe a dynamic reality. Cities are growing at extraordinary rates, with formal and informal settlements sprouting up faster than cartographers can build maps. Alongside this rapid urbanization, hazards are changing in ways that make it far less likely that historical understandings will inform prudent decisions about probable futures. Climate change is altering weather patterns and bringing extreme weather to places that have never seen such variation. Existing stocks of data about a nation’s infrastructure and its relation to natural hazards each need to updated more frequently and at higher resolutions than ever before. In a time of economic hardship and unequal globalization, few governments possess the resources to collate existing data, collect new data, and feed them all into an ecosystem of analysts who can make sense of them so that practitioners can design and implement projects that get ahead of the disaster cycle." {% sidenote 'mn-id-opendrifg' 'The <a href="https://www.gfdrr.org/en/publication/open-data-resilience-initiative-field-guide">OpenDRI Field Guide</a>, see Executive Summary.' %}</p>
</blockquote>

However, efforts to create a template for how to perform a data scramble exist for the UN system and the Red Cross Movement. Around 2011, OCHA advanced the idea of a Coordinated Data Scramble, using a Trello board as a templatized checklist for various data sets to collect. {% sidenote 'mn-id-cds' 'The <a href="https://sites.google.com/site/commonoperationaldataset/other-country-specific/cds">Coordinated Data Scramble</a> is described by OCHA Field Services in the Common Operational Dataset site.' %}  MapAction had its own process for assembling data quickly, though may of its sources could not be shared as publicly due to licensing restrictions. And the Red Cross Movement developed its own data checklist as part of the Surge Information Management System (SIMS)
{% sidenote 'mn-id-rcrcsims' 'The <a href="http://rcrcsims.org/toolkit/">SIMS Toolkit</a> is on the SIMS web site.' %}

### NetHope Data Scramble

For NGOs under NetHope's umbrella, a similar data scramble is needed around interventions that focus on communications and information as aid. The following elements are derived from other data scramble templates and modified based on interviews around the ICT use case of NetHope.

In the early stages of a response operation, the NetHope network needs to ascertain the following pieces of information to understand the scale and scope of the emergency and plan its operations:

#### Magnitude
There are various scales employed in order to assess the magnitude of different kinds of natural hazards, for example Richter scale for earthquake, or the Saffir-Simpson wind scale for hurricanes. These measures take on more meaning in the humanitarian context when combined with elements of human exposure and risk.

#### Extent
What is the overall area impacted by an event? In the case of a natural hazard, the initial focus is on areas of human settlement where damage and casualities have been sustained. But the area of impact may also include shipping or flight routes that are affected. Displacement within or outside of a country may also result from a large scale natural hazard, and more commonly from conflict or civil unrest.

#### Affected Population
How many people are likely to have been affected, how vulnerable are these people are to the natural hazard, where they are likely to have moved to and from?

#### Secondary Events
What is the probability of additional hazards, including tsunamis resulting from an earthquake, flooding due to storm surges, or mudslides due to prolonged rain?

#### Status of Critical Infrastructure
What is the status of airports, seaports, rail stations and lines, and roads? Are key government or other service facilities open and operating?

#### Power and Communications
What is the status of power and communications, where are the outages, and how many people are affected?

#### 3W (Who is doing What, Where?)
Which organizations are already working in the country, which are deploying staff to the country, what are they doing, and what they intend to do?

#### List of Data Sets:
NetHope Crisis Informatics will commonly develop and/or utilize the following datasets in this phase of the information management cycle:


**Hydrography**
Identify bodies of water and their potential impacts on response efforts

*Sample datasets*: National flood hazard or flood zones, Historic flood boundaries, Levee/barrier locations, Tide charts, River levels (current & forecasted), Current flooding extents, Levee/barrier breaches

**Weather**
Identify event related conditions that may influence response
Sample datasets: NOAA NWS forecasts, River/stream gauges, Atmospheric conditions (wind direction, etc.)

**Utilities**
Identify infrastructure that could be damaged or hazardous.
Sample datasets: Utility pipelines, power lines, power plants, cell towers, radio communication, main Internet hubs/lines, telephone (land line) facilities & lines, power outages, phone (land line) outages, cell phone outages

**Transportation**
Identify access routes to the incident and other related transportation reference points.  
Sample datasets: Roads, evacuation routes (including contra-flow routing), bridges and tunnels, railway lines and stations, subway lines and stations, ferry lines and terminals, navigable waterways, boat ramps, maritime infrastructure (vessel mooring areas, marinas, boat ramps, ports, docks), airports, helicopter landing zones, road closures, airport closures, rail & subway stoppages, bridge closures, ferry stoppages, port closures, active evacuation routes (including contra-flow routing)

**Population**
Identify impacted and at-risk populations.
Sample datasets: Population density, socio-economic data (income, gender, age etc.), nighttime population vs. daytime population, seasonal population, businesses, at-need population (schools, day care, nursing homes, assisted care facilities, universities, hospitals/clinics, urgent care, mental health and correctional facilities, etc.)

**Public Safety**
Identify public safety and incident command facilities
Sample datasets: Fire stations, police stations EOCs (local, State, national), Public Safety Answering Points (PSAPs)/911 Call Centers, shelters, evacuation zones

**Humanitarian Portals and Information Resources**
Scan information resources and threads for information regarding who is deploying, where, and with what teams; as well as how the situation is unfolding on the ground.
<table class="booktabs">
<tr><td class="l">Virtual OSSOCM</td><td class="l">link</td></tr>
<tr><td class="l">ACAPS</td><td class="l">link</td></tr>
<tr><td class="l">SIMS/RC</td><td class="l">link</td></tr>
<tr><td class="l">Cluster links</td><td class="l">link</td></tr>
</table>

### Continuous Data Scramble

Data tends to be shared over the course of the first 3-5 weeks of the response, with the first couple of weeks being relatively low in sharing:

{% maincolumn "assets/img/ocha_datascrambling.png" "Curve of dataset submissions to HDX over time for Hurricanes Irma and Maria in 2017." %}

In large part, this lack of sharing to HDX is due to the intensity of operational tempo and the lack of bandwidth from the field. Other dynamics (including competition for grants and the advantage that data can give to these proposals) contributes to the lack of sharing. It is therefore imperative to have data sharing arrangements in place before a disaster.
