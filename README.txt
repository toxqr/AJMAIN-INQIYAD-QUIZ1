Name: Ajmain Inqiyad

Tools used: ChatGPT, Colab, Browser

Q1:

- Key finding (2-4 sentences):
The scatter plot shows a strong positive relationship between study hours and exam score. As study hours increase, exam scores consistently increase. The trendline slope confirms this positive correlation. Sleep hours show a weaker and less direct relationship with exam performance.

- Outlier:
Student C appears to be an outlier because the exam score is relatively high despite lower study hours compared to other high-performing students.

Q2:

- What was broken:
The hero section was not stacking properly on mobile and the grid layout was not changing columns at smaller breakpoints.

- What I changed:
I implemented media queries at 900px and 600px. I added flex-direction: column for the hero on mobile and updated grid-template-columns to change from 4 columns to 2 columns on tablet and 1 column on mobile.

Q3:

Prompt 1 (plan, no code):

Give me a step-by-step plan (no code) to implement responsive breakpoints for a 4-column grid that becomes 2 columns on tablet and 1 column on mobile. Also explain how to make a hero section stack vertically using flexbox.

Response snippet:

Use CSS media queries to define breakpoints. Change grid-template-columns inside breakpoints. Use flexbox for the hero layout and change flex-direction to column for smaller screens.

Accepted:
- Using media queries for breakpoints
- Changing flex-direction for hero layout

Rejected:
- Suggestion to use Bootstrap (not allowed by assignment)

Prompt 2 (debug):

I have this CSS but the hero section is not stacking on mobile:
.hero {
  display: flex;
  justify-content: space-between;
}

Response snippet:

Add a media query for smaller screens and set flex-direction: column for the hero class.

What I verified:

- viewport sizes tested:
375px, 768px, 1200px

- what I checked visually:
Header alignment, navigation stacking, hero stacking behavior, grid column responsiveness, and no horizontal scrolling.

Q4:

- Chart caption:
This chart shows a clear positive relationship between study hours and exam score. Students who study more tend to achieve higher scores.

- Decision based on chart:
Based on this trend, increasing structured study time would likely improve overall academic performance.
