# Gradvis : Gradute School Visualization
The project visualizes TOP 1 - 50, Computer Engineering schools in detail. \
The project objective is to visualize gradute school information in a compact form.

# Features
Stacked Bar Chart : Visualizes summary of all attributes \
Bar Chart : Visualizes a single attribute \
Map Chart : Visualizes school locations via map \
Spider Chart : Visualizes two schools with seven attributes for comparison

# Attributes
Data is based on U.S News Rankings site except for latitudes and longtidues. \
https://www.usnews.com/best-graduate-schools/top-engineering-schools/computer-engineering-rankings \
latitudes and longtitudes are based on google map data. \
\
Name : Name of Graduate School \
Rank : U.S News Rankings in Computer Engineering \
TOEFL : TOEFL test cutoffs \
GRE : GRE test cutoffs \
Students : Number of enrolled students \
U.S News Score : Score given by U.S News Rankings \
Tuition : Tuition based on 1 year basis \
Student/Faculty Ratio : Student numbers per 1 Faculty member \
Master Acceptance : Master students acceptance rate \
Master Applicants : Number of Master Applicants \
Phd Acceptance : Phd students acceptance rate \
Phd Applicants : Number of Phd Applicants \
Student Score : Students normalized to 0 - 100 \
Tuition Score : Tuition normalized to 0 - 100 \
Student/Faculty Ratio Score : Student/Faculty Ratio normalized to 0 - 100 \
Master Acceptance Score : Master Acceptance normalized to 0 - 100 \
Master Applicants Score : Master Applicants normalized to 0 - 100 \
Phd Acceptance : Phd Acceptance normalized to 0 - 100 \
Phd Applicants : Phd Applicants normalized to 0 - 100 \
Latitudes : Latitudes of graduate school locations \
Longitudes : Longitudes of graduate school locations

# Quick Start
Current project requires python3 as installation. \
Follow the prompt after installation of python3. 
```
git clone https://github.com/Vivienne88/Gradvis.git gradvis
cd gradvis
pip install httpserver
python -m http.server
```
After seting up the web server go to localhost:8000/proj.html
