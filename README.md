# Friends Network Visualization

**Link**: https://ep393.github.io/info4310-hw2/

## Project Overview
This project focuses on visualizing the script data from the TV show "FRIENDS", providing insights into the linguistic and social dynamics of the characters across various episodes and seasons. The dataset includes columns for "Text" (dialogue), "Speaker", "Episode", "Season", and "Show".

## Specific Insights/Use Cases
- **Character Interaction Analysis**: Visualizing character interactions to understand social dynamics.
- **Dialogue Trends and Character Development**: Analyzing dialogue word counts across seasons to observe character evolution.
- **Linguistic Signatures**: Exploring catchphrases and speech patterns unique to characters using frequency analysis.

## Storyboards for Interactive Visualization
### Network Diagram of Character Interactions
- **Interaction**: Users can manipulate the network structure by dragging nodes.
- **Purpose**: Allows intuitive exploration of the relationships in "FRIENDS".

### Most Frequently Used Words
- **Interaction**: Interactive tables update to show the most used words by selected characters.
- **Purpose**: Facilitates linguistic analysis to reveal distinctive character traits and themes.

### Distinguishing Words
- **Interaction**: Display of words uniquely associated with characters based on TF-IDF analysis.
- **Purpose**: Highlights unique speech patterns, offering insights into personalities and roles.

### Line Charts for Dialogue Trends
- **Interaction**: Displays trends in dialogue word counts across seasons for selected characters.
- **Purpose**: Visualizes character development, showing changes in prominence and personality.

## Final Interactive Visualization
The web-based tool delves into the network of interactions among "FRIENDS" characters:
- **Key Features**: Dynamic network graph with nodes representing characters and edges indicating interaction frequency.
- **User Engagement**: Clicking on a character node triggers detailed visualizations specific to that character, including interaction frequencies, frequently used words, and dialogue trends.

## Development Challenges
- **Network Complexity**: Managed by limiting displayed characters to the most pivotal ones based on appearance frequency.
- **Data Preprocessing**: Addressed issues with stopwords and word forms through lemmatization using Python libraries (nltk and sklearn).

## Conclusion
This visualization tool combines interactive elements with detailed analytics to deepen the understanding of character dynamics and linguistic patterns in "FRIENDS". While focusing on functionality due to time constraints, future enhancements could include improving visual aesthetics and dynamic effects.
