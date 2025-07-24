# Data Visualization

## Assignment 3: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify: 

 Power BI:
    > What software did you use to create your data visualization?
    I chose Power Bi since I am more familiarized with it

    > Who is your intended audience? 
    My main audience would be data analysts or reserchers
    
    > What information or message are you trying to convey with your visualization? 
    Comparative Insights:
    With Stratifier and Subgroup, you show how metrics differ across demographics, regions, or categories.
    For example: "Completion rate of students by age group" or "Subscription growth by geographic zone"
    Statistical Validity:
    Including LL (Lower Limit) and UL (Upper Limit) shows awareness of uncertainty and variability.
    This supports informed decision-making and highlights areas that may need further investigation.
    Benchmarking and Flags:
    The Flag and Comparison columns offer context for:
    Whether metrics meet expected thresholds
    Highlight anomalies or performance gaps
    Suggest whether certain values are statistically significant or worth deeper attention



    
    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 
    Clarity, to ensure users grasp the message without decodig complexity, and Purpose Alignment
    to match the visual to the type of question being asked (comparison, distribution, trend, etc.)
    
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
    I linked the datasets clearly within Power BI. Included metadata (source name, version, refresh date).
    I also used OneDrive to track evolution. I also used Power Query steps for data cleaning, and Set parameters for things like date ranges or filters.
    
    > How did you ensure that your data visualization is accessible?  
    I avoided renaming technical terms like "LL" or "UL" to “Lower Bound” and “Upper Bound.” As well as avoiding relying only on color to convey meaning. I used high-contrast text and background (dark on light or vice versa).Kept font sizes readable, Avoided cramming—space out visuals and used white space to guide focus.And I provided slicers for key dimensions (e.g. year, subgroup), but made them simple to use.

    > Who are the individuals and communities who might be impacted by your visualization?  
    Data Analysts and researchers as these graphs provide reproducible, statistically grounded evidence for studies or reports.They depend on accurate stratification, confidence intervals, and visual clarity to support further analysis.

    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
    I prioritized features like Indicator Name, Measure, and Subgroup because they directly support the insight I'm trying to highlight—such as trends in performance, engagement, or disparities.

    > What ‘underwater labour’ contributed to your final data visualization product?
    It was not easy that is for sure. I evaluated which fields would add analytical value and which might clutter or confuse the visuals. Before even building charts, I ran descriptive stats and quick visuals to understand trends, outliers, and patterns.This helped shape what stories the dashboard could tell and guided my chart selection. I didn’t just slap on charts—I fine-tuned colors, legends, tooltips, and layouts to improve readability and accessibility


PYTHON:
    > What software did you use to create your data visualization?
    I chose Python

    > Who is your intended audience? 
    For this visuzlization (a chart that explores the infrastructural strengths and gaps in urban dog-friendly spaces, providing a lens for decision-makers to prioritize safe and accessible public environments), my audiende could be professional and civic audiences, those making decisions or advocating for better infrastructure.
    
    > What information or message are you trying to convey with your visualization? 
   Showing which public zones are lacking security or illumination, empowering planners and officials to allocate resources, encouraging action to improve underdeveloped areas, and helping analysts and designers evaluate needs objectively.

    
    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 
    Color Choice: High-contrast colors (like dark gray for fences and bright yellow for lights) so viewers can instantly distinguish the categories.
    Scale and Axis Design: Uniform axis ranges, logical tick intervals, and labeling units (meters, square meters, etc.).
    Grouping or Clustering by Location to visually compare infrastructure across distinct zones.
    
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
    By Using Code, not manual steps. Example: df['total'] = df['fenced_perimeter'] + df['lit_area'] ensures traceability.
    Defining where my data comes from (file path, for instance),
    Adding comments explaining what each block does, especially where decisions are made (like feature selection or aggregation thresholds).

    > How did you ensure that your data visualization is accessible?  Using clean color choices, adding descriptive labels and titles, choosing legible fonts and sizes, and avoid overcomplexity
   

    > Who are the individuals and communities who might be impacted by your visualization?  
    Primary data consumers: Stakeholders and decision-makers who use visuals to guide policy, business, or resource allocation.
    General Audiences: Sharing or republishing simplified graphics might lose nuance if it's not embedded in the original.
    Marginalized or vulnerable Groups: Visualizations of socioeconomic data might reinforce stereotypes if not framed responsibly.
    Technical Communities: Fellow analysts, researchers, students learning from this work may rely on this chart to build understanding.
    

    > How did you choose which features of your chosen dataset to include or exclude from your visualization? I chose fenced_perimeter and lit_area because Both variables are numeric, allowing for direct comparison through a grouped bar chart. Besides, these features relate to infrastructure and safety, which likely aligns with this visualization’s intent (assessing security measures or public amenities by location, for instance). Choosing them together emphasizes a meaningful contrast in how different locations manage safety features. 
    There were so many other variables I did not pick such as address,hours,url,small_dog_area (),surface_material,nearby_drinking_water_source,nearby_drinking_water_source_ty. The reason why was to avoid introducing complexity that could distract from the main insigh
    
      
    > What ‘underwater labour’ contributed to your final data visualization product?
    I removed inconsistencies, normalized formats, manged nulls. Variables selection was another main piece; thoughfully filtered out less impacful features (like small dog area), keeping the story clean and focused. I also tailored content for clarity, and relevance; chosing safety-centric variables which everyone is familiarazied with. Tested differetn plot types, color palettes, anf layout structures before landing on the one i considered is the most effective.

    




- This assignment is intentionally open-ended - you are free to create static or dynamic data visualizations, maps, or whatever form of data visualization you think best communicates your information to your audience of choice! 
- Total word count should not exceed **(as a maximum) 1000 words** 
 
### Why am I doing this assignment?:  
- This ongoing assignment ensures active participation in the course, and assesses the learning outcomes: 
* Create and customize data visualizations from start to finish in Python
* Apply general design principles to create accessible and equitable data visualizations
* Use data visualization to tell a story  
- This would be a great project to include in your GitHub Portfolio – put in the effort to make it something worthy of showing prospective employers!

### Rubric:

| Component         | Scoring  | Requirement                                                                 |
|-------------------|----------|-----------------------------------------------------------------------------|
| Data Visualizations | Complete/Incomplete | - Data visualizations are distinct from each other<br>- Data visualizations are clearly identified<br>- Different sources/rationales (text with two images of data, if visualizations are labeled)<br>- High-quality visuals (high resolution and clear data)<br>- Data visualizations follow best practices of accessibility |
| Written Explanations | Complete/Incomplete | - All questions from assignment description are answered for each visualization<br>- Explanations are supported by course content or scholarly sources, where needed |
| Code              | Complete/Incomplete | - All code is included as an appendix with your final submissions<br>- Code is clearly commented and reproducible |

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 - 13/07/2025`
* The branch name for your repo should be: `assignment-3`
* What to submit for this assignment:
    * A folder/directory containing:
        * This file (assignment_3.md)
        * Two data visualizations 
        * Two markdown files for each both visualizations with their written descriptions.
        * Link to your dataset of choice.
        * Complete and commented code as an appendix (for your visualization made with Python, and for the other, if relevant) 
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-3`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
