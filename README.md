# Player_price_prediction
### The Project aims at predicting value of the given football players
The original dataset contains 461 rows and 17 columns.
### Dependent variable:
• market_value
### Independent variables:
• name: Name of the player
• club: Club of the player
• age: Age of the player
• position: The usual position on the pitch
• position_cat: 1 for attackers, 2 for midfielders, 3 for defenders, 4 for goalkeepers
• page_views: Average daily Wikipedia page views from September 1, 2016 to May 1,
2017
• fpl_value: Value in Fantasy Premier League as on July 20th, 2017
• fpl_sel: % of FPL players who have selected that player in their team
• fpl_points: FPL points accumulated over the previous season
• region: 1 for England, 2 for EU, 3 for Americas, 4 for Rest of World
• nationality: nationality of the player
• new_foreign: Whether a new signing from a different league, for 2017/18 (till 20th
July)
• age_cat
• club_id: the unique id given to the club
• big_club: Whether one of the Top 6 clubs
• new_signing: Whether a new signing for 2017/18 (till 20th July)

### Model building:
Total five models are used namely,
• Linear Regression
• Decision Tree
• Random Forest Regression
• Lasso Regression
• Support Vector Machines

## Random Forest Model has given the most optimal results after performing Hyper parameter tuning.
