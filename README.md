# Lifestyle Sustainability Dataset

This repository contains a dataset focused on the sustainability habits and lifestyle choices of 499 participants. The data covers various aspects of daily life and environmental impact.

## Dataset Overview

- **Total Entries:** 499
- **Total Features:** 20

### Features

1. **ParticipantID** - Unique identifier for each participant
2. **Age** - Participant's age
3. **Location** - Urban, Suburban, or Rural
4. **DietType** - Dietary preferences (e.g., Plant-Based, Balanced)
5. **LocalFoodFrequency** - How often local food is consumed
6. **TransportationMode** - Primary mode of transportation
7. **EnergySource** - Type of household energy (Renewable, Mixed, Non-Renewable)
8. **HomeType** - Type of residence (Apartment, House)
9. **HomeSize** - Size of the home in square feet
10. **ClothingFrequency** - Frequency of buying new clothes
11. **SustainableBrands** - Whether participants support sustainable brands
12. **EnvironmentalAwareness** - Self-rated awareness level (scale of 1-5)
13. **CommunityInvolvement** - Level of community engagement (Low, Moderate, High)
14. **MonthlyElectricityConsumption** - Electricity usage in kWh
15. **MonthlyWaterConsumption** - Water usage in liters
16. **Gender** - Participant's gender
17. **UsingPlasticProducts** - Frequency of plastic product usage
18. **DisposalMethods** - Waste disposal habits (Recycling, Composting, Landfill)
19. **PhysicalActivities** - Level of physical activity (Low, Moderate, High)
20. **Rating** - Overall sustainability rating (scale of 1-5)

## Usage

This dataset can be used for analysis and research on:
- Sustainable lifestyle patterns
- Environmental impact of daily choices
- Correlation between awareness and habits

## How to Access

Clone this repository and load the CSV file in your preferred data analysis tool:

```python
import pandas as pd

# Load the dataset
df = pd.read_csv('lifestyle_sustainability_data.csv')

# Display the first few rows
df.head()
```

## Contributing

Contributions are welcome! Feel free to submit issues or pull requests.

## License

This project is licensed under the MIT License.

