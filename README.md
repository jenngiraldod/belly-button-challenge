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
  
![Screenshot 2025-03-17 at 10 10 24 PM](https://github.com/user-attachments/assets/81ccc248-d866-4ef3-b76b-64488d253d25)

![Screenshot 2025-03-17 at 10 10 40 PM](https://github.com/user-attachments/assets/41e9d91e-2373-4b3f-9bce-6bb3c58fe376)


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
