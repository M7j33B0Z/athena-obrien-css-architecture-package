# CSS Architecture Package
CSS and HTML for Module 2: Deliverable: CSS Architecture Package

# Refactoring evidence
I reduced duplication by creating a single rule for all of the cards on my resume page and all of the figures on my work page. I replaced repeated values such as color and font-family, and spacing sizes with variables. I clarified naming by giving my color variables names that represent what they are. For example, I named one of my colors "green-accent" so that I know it is both a shade of green and a secondary or tertiary color.

# Architecture notes
I chose to use the most common layer order strategy: base, layout, components, utilities, overrides, and print. I chose this order because it goes from broad to more specific, and also follows a simple organizational pattern. I chose tokens that are likely to be reused again and again throughout the design process, such as one consistent border-radius, and all of my colors. I also created some tokens for my fonts so that I do not have to remember the specific sizes intended for each layer of text. My naming approach was based in what currently makes sense for me. I named everything what it is. For example, the figures on the work page, are housed in a class called work-grid, and the cards on the resume page are housed in a class called card-grid. I may need to generate more specific names if I add more elements to my pages. I used my browser checks to make sure that each CSS rule applied correctly. I also used validation tools to make sure that there were no syntax or semantic issues.

# AI Disclosure
I used AI to check for missing states, only after all of my work was complete.

AI disclosure: if used, document purpose, output considered, verification, and what changed.