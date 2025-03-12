# belly-button-challenge
### Objective of the Visualization
- This project creates an interactive dashboard to explore Belly Button Biodiversity data.
- It visualizes bacteria culture samples collected from different test subjects.

### How to Use the Interactive Features
**- Select a Subject ID:** Use the dropdown menu to choose a test subject.
**- View Demographic Info:** Displays metadata about the selected subject.
**- Analyze Bacteria Cultures:**
- Bar Chart: Shows the top 10 most common bacteria found.
- Bubble Chart: Displays the distribution of bacterial species per sample.

### Key Technologies and Libraries
**- D3.js:** Used to fetch and manipulate JSON data dynamically.
**- Plotly.js:** Creates bar and bubble charts for data visualization.
**- Bootstrap:** Provides styling and responsive design.
**- API Data Source:** Data is retrieved from an Amazon S3-hosted JSON file

### Insights from the Analysis
- Bacteria distribution varies across different individuals.
- Some OTUs (Operational Taxonomic Units) are consistently present in multiple subjects.
- Larger sample values indicate a higher concentration of bacteria in certain test subjects.
- The dashboard allows quick comparison between subjects and their bacterial compositions.
