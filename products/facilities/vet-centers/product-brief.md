# _Vet Center Product Brief_

This document will focus on Vet Center detail page enhancement 

## Table of Contents

[User Journey](https://github.com/department-of-veterans-affairs/va.gov-team/blob/master/products/facilities/vet-centers/product-brief.md#user-journey)

[User Stories](https://github.com/department-of-veterans-affairs/va.gov-team/blob/master/products/facilities/vet-centers/product-brief.md#user-stories--use-cases)

[Project Rationale](https://github.com/department-of-veterans-affairs/va.gov-team/blob/master/products/facilities/vet-centers/product-brief.md#project-rationale)

[Project Scope and Scale](https://github.com/department-of-veterans-affairs/va.gov-team/blob/master/products/facilities/vet-centers/product-brief.md#project-scope-and-scale)

[Not in Scope](https://github.com/department-of-veterans-affairs/va.gov-team/blob/master/products/facilities/vet-centers/product-brief.md#not-in-scope)

[Decisions](https://github.com/department-of-veterans-affairs/va.gov-team/blob/master/products/facilities/vet-centers/product-brief.md#decisions)

[Measuring Success](https://github.com/department-of-veterans-affairs/va.gov-team/blob/master/products/facilities/vet-centers/product-brief.md#measuring-success)

[Dependencies](https://github.com/department-of-veterans-affairs/va.gov-team/blob/master/products/facilities/vet-centers/product-brief.md#dependencies)

[Risk factors](https://github.com/department-of-veterans-affairs/va.gov-team/blob/master/products/facilities/vet-centers/product-brief.md#risk-factors)

[Definition of Done](https://github.com/department-of-veterans-affairs/va.gov-team/blob/master/products/facilities/vet-centers/product-brief.md#definition-of-done)

[Key Links](https://github.com/department-of-veterans-affairs/va.gov-team/blob/master/products/facilities/vet-centers/product-brief.md#key-links)

### User Journey
- Vet Centers are community-based counseling centers which provide a wide range of counseling, outreach, and referral services to eligible Veterans, active duty service members and their families. 
- Vet Centers guide Veterans and their families through many of the major adjustments in lifestyle that often occur after a Veteran returns from combat. 
- Vet Center benefits never expire so Veterans can be engaged in services off/on or continuously throughout the journey. 

### User Stories / Use Cases
*What two or three core use cases do we believe should cover ~80% of users?*
- As a Veteran, I need to search for services so that I can successfully transition from military to civilian life or find assistance after a traumatic event.
- As a family member of an active duty service member, I need to find supportive services for issues related to my loved one's military experience. 

### Project Rationale
_Why should this project be a priority?_ 
- In addition to 300 stand-alone (not integrated into VAMC health care systems) Vet Centers, the VHA runs 
  - ~ 18 outstations (small physical locations, like Vet Centers)
  - ~ 1000 community access points (donated space at community partners
  - 83 Mobile Vet Centers (MVC) which are used for outreach and community disasters
- Vet Centers are under-utilized and under-promoted benefit/service for Veterans, even through they are often the first touchpoint an active service member and/or family has with the VA.
- Currently, Vet Centers do not have an online presence beyond the minimal information found on the Facility Detail pages within Facility Locator. They need to leverage the social media accounts (etc) of community partners or Public Affairs Officers at VA Medical Centers to promote activities
- Outreach coordinators at each Vet Center are tasked with creating awareness/promotion about the services in their community and digital presence will help with this, especially during this time of limited face-to-face. 

**Business drivers**
- Jessica Schiefer (VHA Vet Center Communications Officer) and selected team of representative Outreach Specialists 
  - Bryan Doe (Springfield, MA)
  - Elizabeth Jackson (Orlando, FL)
  - Ken Milam (Escanaba, MI)
  - Austin Wilmarth (Colorado Springs)
  - Troy Stormoen (Reno, NV)
- Aptive (vendor: asssting with data collection and organization from the technical side)

### Project Scope and Scale
_What's in and what's out?_

**3Q 2020**
- By establishing Veteran facing taxonomy for services offered at Vet Centers during 3Q 2020, we can support our long term goal of enhancing the online presence for Vet Centers

**4Q 2020**
- By establishing the content model for Vet Centers during 4Q 2020, we can be prepared to execute on that model in Q1 2021 and support our long-term goal of 10 pilot vet centers built in Q4 2021

**MVP**

Primary problems to solve: 
- Locations
- Services Provided

Will include the following:
- Vet Center intro
- Link to "What is a Vet Center" content (to be built) (Call to action?)
- Call to action "Call us"
- Prepare for your visit (new veterans)
- Vet Center service taxonomy (national, integrated with VA Service Taxonomy)
- Vet Center services local content for each vet center location
- Convey how these services are not "cold" and are of a different flavor than a VA Clinic/VAMC
- Relationship to Oustation, as applicable, and Outstation information (hours, location) (note: unsure about services)
- Relationship to Community Access Point (CAP), as applicable, and CAP information (hours, location) (note: unsure about services but likely out-of-scope)
- Definition/Delineation between national content and locally-maintained (field) content

MVP will be rolled out to 10 sites. The initial 5 locations provided geographic distrobution by representing the 5 regions. These Outreach specialists assisted with our primary Vet Center discovery and informed the initial prototypes, and definition of MVP. 
  
### MVP Participants

Five additional locations were chosen with the intent of filling any gaps in representative characterstics, based on the following criteria: 
  - Vet Center with outstation(s) and CAP(s)
  - Vet Center with no outstations or CAP(s)
  - Vet Center with (perceived) low service volume but high numbers of Veteran residents in the area (This could be challenging to give time/attention rather than productivity
  - Vet Center close proximity to VAMC
  - Center far away from VAMC
  - Vet Center close proximity to Clinic
  - Vet Center with joint VBA presence? Can we explore a Vet Center that shares space or offers swing space to a community partner?
  - Large Distance from other VA resources (e.g. Guam?)
  - Vet Center with nearby military installation
  - Vet Center with another Vet Center in close proximity (area with location options/small catchment area)
  - Vet Center with Large catchment area
  - Newest Vet Center
  - University Access Point  
  - Active mobile vet center
  
 | Date | Location | Outreach specialist | Criteria fulfilled | 
 | ---------- | ---------- |  ---------- | ---------- |
 | Original 5 | Orlando, FL | Elizabeth.jackson3@va.gov | Geographic distribution, no CAPS during COVID, close to VAMC, near military installations, another Vet Center close by |
 | Original 5 | Springfield, MA | Bryan.doe@va.gov |  Geographic distribution, no CAPs |
  | Original 5 | Escanaba, MI | Kenneth.milam@va.gov|  Geographic distribution, 6 CAPS (3 permanently manned), 58 miles from VAMC, 16,000+ sq mile catchment area
 | Original 5, replaced Federal Way Vet Center  | Reno, NV | Troy.stormoen@va.gov | Geographic distribution, Contract for fee, close to VAMC |
  | Original 5 | Colorado Springs, CO | Austin.wilmarth@va.gov | Geographic distribution, 3 active CAPS, 64 miles from VAMC, close to 4 military installations plus USAFA, 15,000+ square mile catchment area |
 | Added Jan 2021 | Rochester, NY | Shawn.Crandall1@va.gov |  |
 | Added Jan 2021 | Nashville, TN | Witt.Cook@va.gov |  Outstation seeking approval to become a Vet Center |
 | Added Jan 2021 | Cincinnati, OH | Erika.Reynolds@va.gov|   |
 | Added Jan 2021 | Great Falls, MT | Richard.Ferry@va.gov |  |
 | Added Jan 2021 | Sacramento, CA | Joseph.Moglia@va.gov |   |

### Not in scope

A separate, but adjacent, effort will be needed to replace vetcenters.va.gov.
- Campaign landing page was evalauated as an option for this replacement but rejected. 
- Resource center will also be evaluated. (Decision TBD)

### Decisions 

[Link to decision log](https://github.com/department-of-veterans-affairs/va.gov-team/blob/master/products/facilities/vet-centers/decision-log.md)


## Measuring success

**Options for measuring success**
- SEO optimization, search results rankings
- Increased phone calls of Vet Centers (call to action?)
- Decreased conflation of Vet Center = VA Clinic (possibly through phone calls?)
- Increased utilization of Vet Center services (?)
- Increased understanding of Vet Center services (scroll depth, expansion)
- Rank in Google search
- **Verified contacts/month (currently exists Vet Center) -> considered most valuable by Ouotreach Specialists** 
   - (in-bound) Referral source is tracked nationally (how did you hear of us?) (NSS)
   - Not all Vet Centers capture call data (can be standardized)

### Dependencies
_Are other features dependent on this one? What do we need from partners? What do we need outside of engineering?_
- Availability of Jessica Schiefer and team to support our discovery process. 
- Coordination with CMS 
   - The CMS team will need to add taxonomy to Drupal for single source of truth
   - A handful of Vet Centers exist in TeamSite as part of the VHA Meidcal Center websites. 
- Detail pages with entries in Lighthouse API
- Pages within the Legacy Finder will need to be sunset. 
- Aptiv: This vendor will be asssting with data collection and organization from the technical side
  
### Risk factors

### Definition of Done
- Vet Center Facility Detail pages include a comprehensive, accurate list of services in Veteran facing language.
- Veterans/active service members/families can search for services using standard taxonomy. 
- Vet Center services are aligned with existing health service taxonomy. 

### Key Links
_Links to requirements documentation, wireframes/mock-ups, research, etc._

[Veteran Journey Map](https://github.com/department-of-veterans-affairs/va.gov-team/blob/master/platform/design/va-product-journey-maps/Veteran%20Journey%20Map.pdf)

[Initial Design files](https://github.com/department-of-veterans-affairs/va.gov-team/tree/master/products/facilities/vet-centers/design)

[Brand Analysis Report, March 2020](https://github.com/department-of-veterans-affairs/va.gov-team/blob/master/products/facilities/vet-centers/VetCenters_BrandAnalysisReport_03272020.pdf)

[Discovery](https://github.com/department-of-veterans-affairs/va.gov-team/tree/master/products/facilities/vet-centers/discovery)

[Findings from Outreach specialist stakeholder interviews, September 2020](https://github.com/department-of-veterans-affairs/va.gov-team/blob/master/products/facilities/vet-centers/discovery/outreach-specialist-interviews/Vet%20Centers%20Discovery%20-%20Research%20Findings%20.pdf)

[Findings from Vet Center Client Research, September 2020](https://github.com/department-of-veterans-affairs/va.gov-team/blob/master/products/facilities/vet-centers/discovery/veteran-interviews/Vet-Centers-Client-Research-Findings.pdf)

[Findings from Research Findings: Vet Center - non-client, Veteran, December 2020](https://github.com/department-of-veterans-affairs/va.gov-team/blob/master/products/facilities/vet-centers/discovery/veteran-usability-tests/research-findings.md)

