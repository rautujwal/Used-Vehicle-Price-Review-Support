# Used Vehicle Price Review Support (Python)

## Business Context
Manual inspection of large volumes of used-vehicle listings makes it difficult to consistently identify mispriced vehicles.  
This project builds a web-based analytical dashboard that helps operations teams quickly identify listings that warrant price review.

## Dataset
Used-vehicle listing data containing attributes such as vehicle brand, model, age, mileage, fuel type, and listing price.

## Data Preparation
- Cleaned raw listing data and handled missing values
- Standardised formats and validated realistic value ranges
- Examined distribution characteristics to detect skewed data behaviour

## Analytical Approach
- Estimated expected price ranges using key vehicle attributes
- Compared actual listing prices against expected ranges
- Applied additional validation checks to reduce extreme or unrealistic outputs

## Review Prioritisation Logic
- Identified listings with significant deviation from expected price ranges
- Categorised listings requiring manual review
- Summarised findings into a clear operational report

## Dashboard
A web-based dashboard was developed to:
- Monitor listing price distributions
- Highlight listings requiring review
- Provide a clear summary of flagged cases for operational decision-making

## Outcome
The workflow helps pricing and operations teams focus their review effort on listings most likely to be mispriced, reducing manual inspection workload.
