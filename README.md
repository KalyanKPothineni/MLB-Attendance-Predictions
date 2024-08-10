# MLB Attendance Predictions

## Project Overview

This project aims to analyze and improve game attendance for the Los Angeles Dodgers by identifying factors that influence attendance. The analysis involves data exploration, cleaning, and statistical analysis to provide actionable recommendations for enhancing fan engagement and increasing attendance at games.

## Dataset

The dataset (`dodgers-2022.csv`) includes the following variables:

- **Date**: Month and day of the game
- **Attendance**: Number of attendees
- **Day of the Week**: Day of the week the game was held
- **Opponent**: The opposing team
- **Temperature**: Temperature on the game day
- **Sky Conditions**: Weather conditions (Clear, Cloudy, etc.)
- **Day/Night**: Whether the game was held during the day or night
- **Promotions**: Presence of promotional items (Caps, Shirts, Fireworks, Bobbleheads)

## Assumptions

The analysis is based on the following assumptions:

1. Attendance is influenced by variables such as day of the week, opponent, temperature, sky conditions, and promotions.
2. Promotional items like caps, shirts, and bobbleheads significantly impact attendance.
3. Weather conditions affect attendee comfort and, subsequently, attendance.
4. Game timing (day vs. night) and the day of the week may affect attendance due to work schedules.
5. The popularity of the opponent could also impact attendance.

## Analysis Steps

1. **Data Loading and Cleaning**: Load the dataset and clean any missing or incorrect data.
2. **Exploratory Data Analysis (EDA)**: Analyze the dataset to understand the distribution of attendance and identify any trends or patterns.
3. **Feature Engineering**: Create new features, such as temperature categories, to enhance the analysis.
4. **Statistical Analysis**: Perform statistical tests to identify significant variables that influence attendance.
5. **Recommendations**: Provide actionable strategies to improve attendance based on the analysis.

## Key Findings

- **Weather Impact**: Games held in moderate temperatures (60°F - 75°F) attract the highest average attendance.
- **Promotions**: Bobblehead promotions have a statistically significant positive impact on attendance.
- **Game Timing**: Weekend games (Saturdays and Sundays) generally have higher attendance.
- **Opponents**: Games against well-known teams draw more fans.

## Recommendations

Based on the analysis, the following strategies are recommended:

1. Schedule more games on weekends to maximize attendance.
2. Promote games against popular opponents to attract more fans.
3. Host more games during moderate weather months (May, June, July).
4. Implement promotional events like bobblehead giveaways to boost attendance.

## Conclusion

By understanding the factors that influence game attendance, the Los Angeles Dodgers can strategically plan their game schedules, promotions, and marketing efforts to enhance the fan experience and increase ticket sales.
