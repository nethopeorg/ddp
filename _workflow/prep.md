---
title: Data Preparedness
layout: workflow
wf_order: 1
---
# Workflow for NGO Information Managers
## Data Preparedness
{%- include workflow_nav.html -%}

Building a repository of useful data requires a network of individuals working together to specify which data sets are necessary to support decisions around the identified use cases. This grant was designed around this process: over the course of 2018, NetHope has interviewed partner companies, member NGOs, and UN agencies and clusters to which NetHope contributes during emergencies. In general, any data preparedness project proceeds by identifying use cases, then identifying the data sets that are required to meeting these use cases. This work proceeds to obtaining and aggregating these data, cleaning them and preparing them for release on some kind of shared resource; this is often a data portal. The case of DDP followed this process.

### Use Case for DDP

Successful data preparedness projects start with a **use case**: a way of scoping an activity so that the data collected during the preparedness phase meets the needs of specific users for a known scenario or challenge. The mantra at the Open Data for Resilience Initiative at the Global Facility for Disaster Reduction and Recovery is to identify the use case before any work starts on data collection. {% sidenote 'mn-id-opendrifg' 'The <a href="https://www.gfdrr.org/en/publication/open-data-resilience-initiative-field-guide">OpenDRI Field Guide</a> is available at the GFDRR web site. See Chapter on Scoping.' %} Similarly, the work at OCHA's Centre for Humanitarian Data focuses on building baseline datasets to prepare humanitarian information managers during emergencies.

This DDP project focuses on the use case of humanitarian NGOs that are planning interventions that rely on telecommunications and electrical networks&mdash;a set of activities that include NGO operations, digital cash programming, as well as the use of information as aid. Data preparedness in this context extends into private sector datasets that may have limited distribution or non-disclosure agreements around them; such data include cellular network coverage areas, the density of mobile network subscribers and their movements over time (in aggregate with privacy controls), and social media data, which provide another lens on similar activities of consumers and businesses. The regional focus on this work further limits the use case to the Caribbean region. This area tends to be hit by hurricanes, landslides, and earthquakes.  

Use cases broke into three personas:

#### NetHope Field Team
NetHope has its own Field Operations team which deploys communications and networking equipment to disaster response operations. The team requires specific information so that they can mobilize a team to install equipment at specific sites, usually hosted by NetHope members or local NGOs. These datasets include road maps, maps of mobile data coverage, maps of internet/telecommunications grids, key contacts in telecommunications and member organizations, and a method of tracking what equipment gets installed where for whom.

#### NetHope Member Field Officer
NetHope members may either already be working in the host nation or be authorized to work there (usually with an agreement or license from the government to operate). These members are critical to the NetHope Field Team, as they often serve as sponsors for NetHope interventions as well as visa sponsors for NetHope staff and technical partner personnel. NetHope members tend to require data that identify the magnitude and extent of the natural hazard, who was affected, what aid might be needed, and what other organizations are planning for their interventions.

#### Technical Partner
Companies frequently deploy with NetHope Field Teams and provide analytical support to the NetHope Informatics Team. These entities generally require data to scope their operations, brief their management on the mission, and assess the personal safety and security of personnel headed to a country where many normal services are destroyed or degraded. They require assessments of the need, proposed locations for interventions, assets or equipment required, and details on the logistics of the operation (transportation, lodging, food, security, evacuation, etc.).


### Data Identification
To support the NetHope use case, several types of data sets were deemed important:

**Existing Humanitarian Data** (baseline): datasets that are already hosted at sites such as HDX, World Bank, GIS portals, and government open data portals.

**Links to Dynamic Data** (dynamic): data whose freshness is the key factor around its use, including weather forecasts, earthquake shake maps, flood or tsunami extent polygons, and the like.

**Licensed Private Sector Data** (licensed): data that must be obtained from telecommunications and social media companies (among others) and used under license or other restrictions around its publication and/or distribution, reuse, and combination with other data.

**Bespoke Data** (bespoke): data that need to be collected for specific purpose, which would include needs assessments as well as data that need to built from many sources into a new dataset (such the frequencies of VHF/HF radio systems in use by UN agencies and host nation civil protection teams in various countries)

The specific data sets necessary include:

<table class="booktabs">
<thead><th>Data</th><th>Type</th><th>Description</th></thead>
<tr><td>Roads</td><td class="c">Existing</td><td class="l">purpose</td></tr>
<tr><td>dataset</td><td class="c">type</td><td class="l">purpose</td></tr>
<tr><td>dataset</td><td class="c">type</td><td class="l">purpose</td></tr>
<tr><td>dataset</td><td class="c">type</td><td class="l">purpose</td></tr>
</table>

### Data Collection
Aggregating the identified datasets

#### Baseline
Baseline datasets are collected by many organizations who perform international development, climate action, humanitarian action, and other modes of development. Through intensive efforts at building open data systems, many of these baseline datasets are available through data portals and data sharing programs. **There is no need for NetHope to replicate the work of others**. Doing so would obligate NetHope to take on the challenge of keeping its own versions up to date. The best advice is to link to these datasets where they exist from a website which includes explanations of what the data includes, its provenance (how it is collected and curated), and how to use the data. This site has taken the approach of linking to external baseline datasets that are relevant to each country in the Caribbean and deemed important for the use cases outlined above. There are more baselines datasets available.

#### Dynamic
Some datasets must be accessed at the time when they are needed. There are two ways to go about this task: referencing the external link and explaining how to use the data, or creating a web service to overlay a constant stream from that data sources into a visualization. In this way, it is possible to view recent earthquakes, current and forecasted weather, mid-term climate forecasts, and similar dynamic data sets.

#### Licensed
The private sector collects data about consumer and business activities as well as governmental contracts to create smart cities and programs to use the Internet of Things. Some of these data can be licensed for use or made available under data philanthropy programs. The original version of this grant sought to create legally-binding agreements with the private sector to releases these datasets when a triggering event occurs (such as an earthquake above 7.5M with 50km of a given city). The Cambridge Analytica scandal and similar data breaches in 2018 changed the calculus on this approach. Corporate counsel are currently briefing their senior executives how to handle parliamentary inquiries into why external parties had any access to customer data; adding a program that compels a company to release data to external parties is not currently a likely possibility. NetHope therefore pursued data releases done on a voluntary basis through data sharing agreements. These took four forms:

*Data Philanthropy*. Corporate social responsibility programs have increasingly made data available alongside other corporate resources. Facebook Disaster Maps is one such program, which makes it possible for humanitarian organizations to access demographic information based on Facebook subscriber data (in aggregated with strong privacy controls).

*Center for Digital NonProfit Agreements*. As part of the agreement for a company to join NetHope's Center for the Digital Nonprofit, several companies have signed an agreement to share data with NetHope in the event of an emergency. These include (list)......

*Discount Licensing*. NetHope has negotiated a reduction of licensing costs by significant fraction and/or agreement to use a one-time purchase to cover the needs of NetHope members in the event of an emergency. The Budde Reports provide one such licensing agreement, which provide proprietary analyses about the telecommunications networks of countries around the world.

*Operational Data from NetHope's Partnerships*. As part of NetHope deployments, the networks collect data about the populations we serve. These data must be carefully anonymized and aggregated to show the impact of our work. 

#### Bespoke
Some data necessary for meeting the use cases above did not exist at the time of the signing of this grant. Instead, they must be collected through primary and secondary research. Bespoke data for response operations occur both before the event and during the response.

**Preparedness**: For NetHope, this has meant seeking out data about elements of Caribbean telecommunications infrastructure, including HF, VHF frequencies; exploring how to build maps of electrical and telecommunication grids; creating mechanisms to analyze satellite imagery for telecommunications towers.

**Response**. Surveys are a core element of response operations. Asking what is needed by whom, where, and when helps to plan interventions, track progress, and measure success.

### Data Cleansing
Data rarely in a form that we would like. They are inconsistently formatted, use taxonomies or locations that do not match our needs, have missing bits or incorrent/transposed values, and may have been collected in ways that make us curious or even skeptical about their accuracy or ethics. The job of cleansing data means putting them into a format that can be made useful. They need to be made fit for purpose.

The effort necessary to clean data is rarely sexy. It is pure grunt work of going through data sets, often with scripts to accelerate changes. Some tools exist to make this work easier: Humanitarian Exchange Language is a protocol to tag data and then transform it from one structure to another.

When we are able to obtain data that capture these dynamics, they often need to updated. They almost always need to be put into more standard form, especially data that have been collected in ways which allow for wide variation in the text structures in a field or where geographic information is put into a long narrative paragraph instead of discrete fields that capture the data structure necessary to plot a place on a map.

### Data portals
Several data portals already exist to host humanitarian data. The largest is the Humanitarian Data Exchange (HDX), which contains data sets about most countries in the world. This portal provides both public and private spaces for NGOs and UN agencies to share in data preparedness and operational analysis. The World Bank and GFDRR have created myriad GeoNodes with national governments, primarily to host data about natural hazards and the people and infrastructure exposed to those hazards.

While NetHope could choose to host its own data portal in the future, the needs for its current operation are well met by HDX. Data from this DDP project will be hosted on public and private sites on HDX, except for certain private sector data which must be hosted under terms of the agreement with the corporation.
