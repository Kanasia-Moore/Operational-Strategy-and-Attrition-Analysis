## Project 04: Theme Classification & Root Cause Analysis

### Overview
This phase of the project focused on identifying and refining recurring themes within employee voice data using a combination of AI-assisted analysis, operational questioning, and Python-based categorization.

Building on previous sentiment analysis work, this stage moved beyond measuring sentiment alone and focused more directly on uncovering patterns connected to attrition, employee experience, and operational support systems.

### Objective
To identify recurring operational and workplace themes within employee feedback, classify those themes across reviews, compare sentiment patterns by theme, and explore the root causes behind burnout, physical strain, and turnover.

### What Was Done
- Used AI tools to identify recurring themes within employee voice data
- Refined and validated AI-generated themes using analytical questioning and previous findings
- Used Python to create a theme classification column within the dataset
- Tagged reviews according to the identified themes: Benefits, Burnout, Infrastructure, and Management
- Conducted sentiment analysis across categorized themes
- Created visualizations to compare positive and negative sentiment patterns between themes
- Explored burnout and turnover more deeply through root cause analysis
- Used Claude AI to create a root cause tree visualization mapping contributing factors and downstream impact

### Tools Used
- Python
- Pandas
- TextBlob
- AI-assisted thematic analysis
- Claude AI (root cause visualization)

### Key Questions Explored
- What recurring themes consistently appear across employee reviews?
- What did sentiment analysis reveal about the identified themes?
- How did root cause analysis change the direction of the project?
- What role does management appear to play in employee experience?

### Key Insights
AI-assisted analysis helped accelerate the process of identifying recurring themes, but the refinement process still required contextual understanding and analytical judgment.

After categorizing reviews into themes and analyzing associated sentiment, clear patterns began to emerge between employee experience and operational support structures.

Benefits showed the strongest positive sentiment overall, while burnout, infrastructure, and management reflected more operational strain and support-related concerns.

Exploring burnout and turnover more deeply through root cause analysis revealed how productivity pressure, management strain, and limited employee support can interact to influence burnout, disengagement, and attrition.

### Deliverables
- Theme-classified employee voice dataset (see `/data`)
- Python scripts for theme tagging and sentiment analysis (see `/python`)
- Theme sentiment visualizations (see `/visuals`)
- Root cause tree analysis (see `/analysis`)
- Key questions and operational thinking (see `/analysis/key_questions.md`)

### Connection to Previous Work
Previous phases focused on operational structure, employee sentiment, text cleaning, and sentiment scoring.

This phase builds on those findings by organizing employee feedback into operational themes and exploring how management structure, operational pressure, and support systems influence employee experience and attrition.

### Next Step
The next stage will focus on synthesizing findings across all phases into a cohesive attrition case study centered on operational structure, leadership support, workforce sustainability, and employee experience.
