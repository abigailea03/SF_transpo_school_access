# UP 221 Winter 2025: San Francisco Transportation Group 
This is the group repository for the SF Transportation group project in UP 221. The group members include: Abigail Adams, Jasmine Law, Ronald Tien Giang, and Caleb Huang. 

# Status Update
## **PROJECT TITLE:** Accessibilty of SF Public Highschools by MUNI
## **GROUP MEMBERS:** Abigail Adams, Jasmine Law, Ronald Tien Giang, and Caleb Huang

### **TASKS:**
#### 1. Ronald 
* Bus lines directions and schools
* School locations within .25 mile  due to 3.0mph walk speed, 5 min walk
* Bus locations and directions

#### 2. Abigail: Demographics/Socioeconomic
* Role: data exploration of income + socioeconomic data, map and/or chart in SF using census tracts
* Poverty level, family poverty levels -> Census age group: 5-17, or 18-24 (filter for only 18)
* Housing characteristics with Jasmine 
* Responsible for 1 chart OR 1 static map 

#### 3. Caleb 
* Race
* Equity Priority Communities
* Tree Canopy/Bus Shelters near schools and bus stops 


#### 4. Jasmine
* Muni ridership data for school-based lines 
* Housing characteristics with Abigail

###  **CONCERNS:** 
#### Major:
* Merge non-spatial data frame with spatial data frame 
#### Minor: 
* How to filter out tree canopy data to only include trees on sidewalks near bus stops
* Find dataset on SF high school locations 
* having too many moving parts in the project / managing scope

### VISUALIZATIONS: 
* 2 Maps 
  - Census tracts of rent burden-ness in SF
* 2 Charts
  - Demographics/Socioeconomic: at least one chart from this topic
  - possibly comparing demographic information of school vs. voting district

### **Status Update:** 
We have been working individually on the demographics and transportation profile of San Francisco. We are busy and tired but hopeful and working well together. We are still getting comfortable with python but are improving slowly. 

### **Data update:**
Census tract data in SF will be used to:  
* Filter for amount of rent burdened individuals, also by tract
* Look at census tracts with high poverty levels and high levels of school enrollment (individuation of students in area) 
* Look at housing characterics in area: vacancy rates (renter vs homeowner), etc
* https://data.census.gov/table/ACSSDP1YCD1192023.DP04?q=DP04:%20Selected%20Housing%20Characteristics

San Francisco Street Tree Data
* will be used to find the amount of tree canopy available near schools and bus stops. 
* https://data.sfgov.org/City-Infrastructure/Street-Tree-List/tkzw-k3nq/data

Ridership data will be used to: 
* compare which lines support the most high school students (based on ridership activity from September - May)
* Can be either displayed as a bar chart, or maybe incorporated onto an interactive map (for example, displaying average weekday ridership when hovering over the line with a mouse)
