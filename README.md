# ml-final
Repo to track the CS 4780 Final Project

## Timeline
- Decision Tree
- Soft-Margin SVM

## Feature Space
- Country: binary feature for each possible country
- Time: feature for week (indexed), feature for day (indexed), feature for day of week, all counters (don't reset at the new year)
- Daily Hospital Occupancy: normalized
- For age ranges, we're concerned that they will no longer sum to be the total occupancy- do we want to preserve this property? Normalize differently
