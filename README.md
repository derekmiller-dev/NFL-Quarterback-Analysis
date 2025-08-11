# Evolution & Archetypes of NFL Quarterbacks – A Data Science Approach

## Overview
This project analyzes the **evolution of the quarterback position in the NFL** using historical passing and rushing data from 1932 to 2022. The NFL is deeply embedded in American culture, and the quarterback is widely recognized as the most critical position on the field—directing the offense, reading defenses, and making game-changing decisions.

By examining career statistics, we uncover trends in quarterback play across eras, identify different QB archetypes, and provide insights into what makes a quarterback successful in various contexts.

## Objectives
1. **Understand Historical Trends** – Explore how quarterback performance metrics have changed over decades.
2. **Identify QB Archetypes** – Use unsupervised machine learning to cluster quarterbacks into distinct playstyle categories. (IN PROGRESS)
3. **Support Strategic Insights** – Provide actionable takeaways for player evaluation, drafting, and coaching strategies.

## Data Sources
- **Pro Football Reference** – Comprehensive passing and rushing data for NFL quarterbacks from 1932–2022.
- **Key Metrics Analyzed**:
  - Passing yards, touchdowns, completion %, efficiency ratings
  - Interception rates, sacks, clutch performance (4th quarter comebacks, game-winning drives)
  - Rushing yards and rushing touchdowns

## Steps
### 1. Data Collection & Processing
- Scraped and cleaned historical QB statistics from Pro Football Reference.
- Normalized data for consistency across eras.
- Selected relevant features, excluding non-performance or redundant fields.

### 2. Exploratory Analysis
- Created visualizations to observe changes in QB play over time (e.g., pass attempts per season, rushing trends).
- Compared statistical distributions across decades.

### 3. Machine Learning – QB Archetypes (IN PROGRESS)

## Tools & Libraries
- **Python**
- **Pandas**, **NumPy** – Data handling and preprocessing
- **Matplotlib**, **Seaborn** – Visualization
- **Scikit-Learn** – PCA, K-Means clustering, model evaluation
- **BeautifulSoup**, **Requests** – Web scraping
