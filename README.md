# FireRisk
## Summary
FireRisk AI is an intelligent tool that analyzes 911 and emergency response data to forecast the risk of structure fires or wildfires at specific addresses, helping agencies prioritize prevention and allocate resources more effectively.
BuildingAI course project

## Background
Problem: Structure and wildfires cause loss of life and property. Early identification of high-risk locations can enable targeted inspections, education, and mitigation.
### How common/frequent: 
In North America alone, tens of thousands of structure fires and hundreds of wildfires threaten communities each year.
### Motivation: 
With a background in public safety and firefighting, I’ve seen how preventable many fire incidents can be. I also know that there are informal correlations between medical calls to emergency services and situations/lifestyles/behaviors that result in structure fires. 

My specific motivation is a conversation I overheard between two paramedic/firefighters. They had just responded to a medical call: patient they were called to treat had both physical and psychological challenges including living in a 'hoarder'  home. Homes with an excess of clutter, including papers or other flammable material, are very prone to fire. And so, as they got out of the ambulance at the fire station, one said rather sadly to the other, "Well, I know one structure fire we're going to be called to this summer."

That paramedic/firefighters informal, experienced-based predictive analysis is something I would like to be able to instantiate at scale.  Predictive analytics can save lives and resources.
### Importance: 
Fire prevention is often more cost-effective than response. Real-world impact could be immense—especially as climate change increases fire risks.
## Data and AI Techniques
### Data sources: 
911 call logs, fire department incident reports, hazmat and medical alerts, weather and vegetation data, building codes, address histories.
### Availability: 
Many departments already collect this data, but integration and cleaning would be required.
## Techniques:
* Data cleaning and integration
* Feature engineering (recent calls, nearby fires, weather, property characteristics)
* Classification and regression (logistic regression, random forests, gradient boosting, or neural nets)
* Geospatial analysis
* Possibly time-series or sequence models if using patterns of incidents
## Demo: 
Could use open incident datasets (like those from US cities) to predict fire likelihood for a test set of addresses.
## How is it used
* Users: Fire departments, emergency managers, insurance companies, city planners.
* Context: Used to inform inspection schedules, outreach, and resource deployment. May be integrated into emergency response dashboards.
* Affected parties: Residents, business owners, first responders, insurance companies.
## Challenges
* Does not solve: Root causes of fire (poverty, human error, etc.), nor replace professional judgment. May be limited by data quality, reporting biases, and false positives/negatives.
* Data privacy: Sensitive address data must be handled carefully.
* Interpretability: “Black box” predictions may need explanation for trust.
## What next
* Expand to include broader disaster risk (flood, wind, etc.).
* Integrate with real-time weather and satellite data.
* Collaborate with insurance and municipal agencies for impact studies.
* Add explainable AI components to support transparency and trust.
