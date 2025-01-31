# UFC Fighter Elo Rating System

Here is my attempt to adapt the Elo rating system to UFC fights.

## How It Works
- Fighters start with a baseline rating of 1500.
- Ratings update after each fight using the Elo formula, with a k-value multiplier for different victory methods.
- A Random Forest Classifier identifies which k-value settings yield the highest fight outcome prediction accuracy.

