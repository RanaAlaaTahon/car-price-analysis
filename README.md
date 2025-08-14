# Project XYZ

**Project XYZ** is a comprehensive data analysis tool designed to streamline data exploration, analysis, and visualisation. The tool supports multiple data formats and provides an intuitive interface for both novice and expert data scientists.

# ![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

## Dataset Content

- The dataset, sourced from Kaggle: Car Price Prediction, contains specifications of different car models along with their prices.
  It includes 26 features such as:

- Identification & specifications: make (brand), fuel type, aspiration, number of doors, body style, drive wheel, engine location, wheelbase, length, width, height, curb weight.

- Engine details: engine type, number of cylinders, engine size, fuel system, bore ratio, stroke, compression ratio, horsepower, peak RPM.

- Performance & economy: city MPG, highway MPG.

- Target variable: price (USD).

- Size: 205 rows × 26 columns.

## Business Requirements

- Identify the strongest features influencing car prices in the U.S. market.

## Hypothesis and how to validate?

- Hypothesis: Cars with lower fuel efficiency (MPG) are more expensive.

  Validation: Correlation analysis of MPG vs price.

- Hypothesis: Certain brands (e.g., BMW, Jaguar) have higher average prices regardless of technical specs.

  Validation: Grouped average price per brand.

- Hypothesis: Engine size, curb weight, and number of cylinders are positively correlated with price.

  Validation: Correlation analysis for each feature with the price.

## Project Plan

- Data collection: Download dataset from Kaggle.

- Data cleaning: Handle missing values, convert categorical data to usable formats, check for outliers.

- Generate visualizations to explore relationships between features and price.

- Summarize insights for business decision-making.

## The rationale to map the business requirements to the Data Visualisations

- Identify top predictors.
- Understand the pricing dynamics of a new market.

## Analysis techniques used

- Descriptive statistics, grouped aggregations, histograms, correlation analysis.

## Ethical considerations

- Dataset contains no personal information, no privacy risk.

## Unfixed Bugs

- None

## Development Roadmap

- Challenges:

  Limited prior experience using Pandas for advanced data manipulation and visualization libraries (Matplotlib, Seaborn, Plotly) for producing insightful and aesthetically clear charts.

- Strategies to Overcome Challenges:

  Studied targeted tutorials and Kaggle notebooks to improve proficiency with Pandas groupby operations, merges, and feature engineering.

  Practiced creating different types of plots (bar, box, scatter, heatmap) and iteratively refined them to improve clarity and storytelling.

- Next Skills/Tools to Learn:

  Advanced Pandas techniques (window functions, pivot tables, custom aggregations).

  Interactive dashboard creation with Power BI or Tableau.

  SQL for complex data queries.

## Main Data Analysis Libraries

- pandas – data cleaning, aggregation.

- numpy – numerical operations.

- matplotlib / seaborn / plotly – visualizations.

## Credits

- Content: Dataset from Kaggle.

- Media: Visualizations generated in Python using Matplotlib, Seaborn, and Plotly.

### Content

- The text for the Home page was taken from Wikipedia Article A
- Instructions on how to implement form validation on the Sign-Up page was taken from [Specific YouTube Tutorial](https://www.youtube.com/)
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)

### Media

- The photos used on the home and sign-up page are from This Open-Source site
- The images used for the gallery page were taken from this other open-source site

## Acknowledgements

- Thanks to Vasi, for guidance and support throughout the project.
