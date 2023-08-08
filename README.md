# Data Analysis and Visualization Report: International Students in Australia
## Introduction
International students play a crucial role in Australia's higher education sector, attracted by its quality education, culture, and diverse fields of study. Their presence has contributed significantly to the country's economy while also presenting challenges related to accommodation, employment, health, and integration. Recent policy changes and the impact of the Covid-19 pandemic have further shaped the landscape for international students. This report analyzes and visualizes data from credible sources to uncover patterns and trends that inform policymakers and stakeholders in the international education industry.

## Aim
This data analysis and visualization report aims to provide insights into the demographic profile of international students in Australia, including enrollment trends, preferred fields of study, choice of state, and home countries. By understanding these variables, we can address challenges faced by overseas students and benefit both the students and the Australian government.

## Methods
### Data Source & Scope
The analysis utilizes two datasets: studentPublic.csv and nationalitySummary.csv obtained from the Australian Government's Department of Education website. The data cleaning process reveals no null values, misspellings, or duplicated entries. <ins>Python's libraries, such as Pandas, Matplotlib, Plotly, Seaborn, and Squarify</ins>, are employed for data analysis and visualization.

### Methodology
The project is implemented in a Jupyter Notebook, leveraging Python for its flexibility and rich visualization capabilities. The code and visualizations can be accessed on the GitHub repository.

## Results
### International Students Based on Nationalities
A choropleth map using Plotly demonstrates the distribution of international students based on their home countries. The analysis highlights significant variations in student numbers across different countries, with some countries sending a much higher number of students to Australia.<br>
<img width="310" alt="image" src="https://github.com/hanifahaputri/cosc3000/assets/77476862/43139e84-f737-4a98-8b0d-9ed572f28cae">
<img width="304" alt="image" src="https://github.com/hanifahaputri/cosc3000/assets/77476862/11d9ff5a-c38e-4463-9d4a-11a5978a3a1b">

### Students in Each State (2011-2021)
A strip plot illustrates the growth of international students in Australian states from 2011 to 2021. New South Wales emerges as the state with the highest number of international students, with Victoria following closely behind.<br>
<img width="281" alt="image" src="https://github.com/hanifahaputri/cosc3000/assets/77476862/c4e30cf9-117c-4274-8637-e381fd1e0f5c">
<img width="308" alt="image" src="https://github.com/hanifahaputri/cosc3000/assets/77476862/30e0e59b-9886-4bc5-bd39-b6f0c3f5b31a">

### Broad Field of Education & Sector
A treemap visualization reveals the popularity of different broad fields of education among international students. The results show that society and culture and mixed-field programs are the most pursued areas of study.<br>
<img width="505" alt="image" src="https://github.com/hanifahaputri/cosc3000/assets/77476862/d7685c1a-432d-413d-89ca-b015e5b0c071">

A stacked bar chart is employed to depict the distribution of students across different sectors. Higher education emerges as the preferred sector among international students.<br>
<img width="542" alt="image" src="https://github.com/hanifahaputri/cosc3000/assets/77476862/321f4825-4398-45fb-b82a-bf607591dea9">

A sunburst chart combines sector and broad field of education data to provide a hierarchical overview. This visualization reveals insights into the distribution of students within sectors and fields of study.<br>
<img width="339" alt="image" src="https://github.com/hanifahaputri/cosc3000/assets/77476862/cb3a27ba-5fc4-48fe-9b8c-44f53b860ee3">

## Conclusion
This data visualization project offers valuable insights into the landscape of international students in Australia. It uncovers trends, patterns, and preferences by analyzing data from diverse sources and employing various visualization techniques. The project highlights Australia's popularity as an international education destination and provides insights into enrollment trends, sectors, and fields of study.

## Reflections & Limitations
The project provided hands-on experience in Python-based data visualization. Challenges included selecting appropriate variables for each visualization and choosing suitable visualization types. A limitation was the lack of customization options in Plotly for certain visualizations. However, the project successfully demonstrated the significance of data visualization in conveying complex information and guiding policy decisions.
