# Flight Delay Prediction on Houston Airports (2011)

## Overview
This project develops and evaluates two machine learning classification models which are
Logistic Regression and Random Forest to predict whether a flight departing 
from Houston, Texas will arrive 15 or more minutes late, using only information 
available before the flight departs.

## Findings
When you fly matters more than who operates the flight. Schedule timing features 
such as time of day and day of week account for approximately 62% of the Random 
Forest model's predictive power, while no individual carrier feature contributes 
more than 3%.

## Dataset
- **Source:** hflights R package — Houston domestic departures, 2011
- **Records:** 223,874 flights after cleaning
- **Airports:** IAH (George Bush Intercontinental) and HOU (William P. Hobby)

## Models
| Model | Accuracy | Precision | Recall | F1 Score |
|---|---|---|---|---|
| Logistic Regression | 53.8% | 26.5% | 68.8% | 38.3% |
| Random Forest | 59.0% | 28.2% | 62.8% | 38.9% |

## Features Used
- Time of day (RedEye, Morning, Afternoon, Evening)
- Day of week
- Operating carrier
- Distance band (Short, Medium, Long, UltraLong)
- Departure airport (IAH or HOU)

## Files
- `flight_delay_prediction.ipynb` — Full Jupyter notebook with code and analysis
- `flight_delay_prediction.html` — HTML version of the notebook
- `hflights.csv` — Dataset used
- `flight_delay_paper.pdf` — Full research paper

## Research Paper
The full journal paper is published on Zenodo.
DOI: *[]*

## How to Run
1. Clone the repository
2. Open `flight_delay_prediction.ipynb` in Jupyter or Google Colab
3. Run all cells in order

## Author
**Harris Tekenah**
MScFE Candidate, WorldQuant University

## License
MIT License — © 2026 Harris Tekenah
