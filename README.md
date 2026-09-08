<div align="center">
  <img width="100%" max-width="900" alt="Project Banner" src="https://github.com/user-attachments/assets/33af4e8a-c1cf-4d03-8673-f66a5588b1d1" />
  <h1>NYC Air Quality and Public Health: Exploratory Data Analysis</h1>
  <p><em>An exploratory data analysis project completed for DAT-510: Foundations of Data (2026). This scenario-based analysis simulates an official commission by the New York City Department of Health and Mental Hygiene to evaluate environmental pollutants and public health outcomes.</em></p>
</div>

<hr>

<h2>Project Overview</h2>
<p>Commissioned to evaluate environmental health burdens across New York City, this project follows the complete data analytics lifecycle, from raw data cleaning and preparation to exploratory modeling and visualization, to address critical municipal health questions.</p>

<h3>Key Areas of Investigation:</h3>
<ul>
  <li><strong>Environmental Health Burdens:</strong> Identifying specific neighborhoods experiencing the highest health burdens.</li>
  <li><strong>Disease Correlations:</strong> Analyzing how air quality metrics correlate with disease prevalence and healthcare utilization.</li>
  <li><strong>Seasonal & Temporal Trends:</strong> Evaluating seasonal variables and policy influences driving spikes in health incidents.</li>
</ul>

<hr>

<h2>Tech Stack</h2>
<ul>
  <li><strong>Language:</strong> Python, SQL</li>
  <li><strong>Libraries:</strong> 
    <ul>
      <li><code>pandas</code>, <code>numpy</code> (Data cleaning & manipulation)</li>
      <li><code>matplotlib</code>, <code>seaborn</code> (Visualizations, heatmaps, and trend plots)</li>
      <li><code>scipy</code>, <code>scikit-learn</code> (Statistical analysis)</li>
    </ul>
  </li>
  <li><strong>Version Control:</strong> GitHub</li>
</ul>

<hr>

<h2>Key Findings and Conclusions</h2>

<h3>1. Neighborhood Environmental Burdens</h3>
<ul>
  <li><strong>Top Impacted Areas:</strong> Analysis of health burden scores identified the top neighborhoods facing the highest impact: led by East Harlem (41.04), Central Harlem – Morningside Heights (38.35), High Bridge – Morrisania (38.11), Hunts Point – Mott Haven (36.74), and Crotona – Tremont (36.19).</li>
</ul>

<h3>2. Air Quality and Disease Correlations</h3>
<ul>
  <li><strong>Weak Direct Correlations:</strong> Unexpectedly, most environmental factors showed only weak or negative statistical correlations with health issues. Excluding ozone-related metrics, the strongest observed relationship was between cardiovascular hospitalizations and ozone levels at a modest 0.29.</li>
  <li><strong>Socioeconomic Confounders:</strong> Wealthier high-pollution areas (such as Midtown, which recorded the highest PM2.5 levels at 12.8 mcg/m³) showed fewer emergency visits than poorer areas with lower pollution, likely due to better access to healthcare.</li>
</ul>

<h3>3. Seasonal Patterns</h3>
<ul>
  <li><strong>Data Limitations & Trends:</strong> Due to limited seasonal variables in the available dataset, analysis focused primarily on available winter versus summer comparisons for Nitrogen Dioxide (NO₂), PM₂.₅, and Ozone levels.</li>
</ul>

<hr>

<h2>Repository Structure</h2>
<pre><code>
├── data/                  # Raw dataset
├── notebooks/             # Jupyter notebooks for discovery, cleaning, and EDA
├── visualizations/        # Generated heatmaps, bar charts, and seasonal trends
└── README.md              # Project documentation
</code></pre>

<hr>
