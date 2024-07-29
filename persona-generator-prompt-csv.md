# Synthetic Persona Generator Prompt Template (CSV-Ready)

Generate [X] number of detailed synthetic personas for each of the following age ranges. Ensure diversity within each age range. Output the results in a CSV-compatible format.

## Input Parameters:
Number of Personas per Age Range: [Input number, e.g., 5]

Age Ranges:
- 18-24
- 25-34
- 35-44
- 45-54
- 55-64
- 65+

## Additional Parameters (if available):
Geographic Location Focus: [Input location or "Diverse"]
Specific Demographic Focus: [Input any specific demographic requirements or "Diverse"]

## Output Format:
Generate a CSV-compatible output with the following headers:

ID,Age,Sex,Race/Ethnicity,Education,Income,Location,Job,Marital_Status,Children,Openness,Conscientiousness,Extraversion,Agreeableness,Neuroticism,Communication_Style,Reading_Level,Decision_Style,Political_Leaning,Core_Values,Hobbies,Language_Style,Survey_Engagement,Persona_Narrative,Simulation_Guidelines

## Persona Generation Guidelines:
For each persona, provide realistic and diverse characteristics:

1. Ensure a balanced distribution of sexes, races/ethnicities, and education levels within each age range.
2. Generate plausible income levels, jobs, and marital statuses based on age and education.
3. Create OCEAN scores (0-100) that form a coherent personality.
4. Develop consistent communication styles, reading levels, and decision-making patterns.
5. Assign varied political leanings, core values, and hobbies that align with the persona's background.
6. Create a brief (50-word max) persona narrative that encapsulates the individual's key characteristics.
7. Provide concise (25-word max) simulation guidelines for AI response modulation.

## Example Output Row:
001,28,Female,Asian,Bachelor's,75000,Seattle,Software Engineer,Single,0,72,85,43,68,39,Formal/Concise,College,Analytical,Moderate,Innovation,Hiking,Technical jargon,High on tech,Ambitious techie balancing career growth with wellness. Values efficiency in communication and decision-making. Skeptical of marketing claims.,Use technical terms. Be concise and logical. Show mild skepticism toward emotional appeals.

Generate [X] such rows for each age range, ensuring diversity and internal consistency in each persona.

