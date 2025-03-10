## Dataset Description

The file `data/energy_dataset_18_22.csv` contains energy consumption data for various countries from 2018 to 2022. This dataset is the foundation of all analyses presented in this project.

### Data Structure

| Column | Description | Unit |
|--------|-------------|------|
| country | Name of the country | - |
| year | Year of observation | - |
| coal | Coal energy consumption | TWh |
| gas | Natural gas consumption | TWh |
| oil | Oil consumption | TWh |
| nuclear | Nuclear energy consumption | TWh |
| hydro | Hydroelectric energy consumption | TWh |
| solar | Solar energy consumption | TWh |
| wind | Wind energy consumption | TWh |
| biofuel | Biofuel consumption | TWh |
| gdp | Gross Domestic Product | Billion $ |
| population | Country population | Million |
| total_energy | Total energy consumption | TWh |
| renewable_energy | Total renewable energy consumption | TWh |
| renewables_share_energy | Percentage of renewables in total energy | % |
| co2_emissions | Carbon dioxide emissions | Mt (Million tonnes) |
| co2_per_capita | CO₂ emissions per person | t (tonnes) |
| co2_per_gdp | CO₂ emissions per unit of GDP | kg per $ |
| energy_with_unit | Total energy with unit | TWh |
| emissions_with_unit | Total emissions with unit | Mt |

### Notes on the Dataset

- The dataset covers 35 countries across all continents
- All energy values are measured in terawatt-hours (TWh)
- Renewable energy includes hydro, solar, wind, and biofuel
- The dataset allows for analysis of correlations between economic indicators (GDP), energy consumption patterns, and environmental impact (CO₂ emissions)
- Some values may appear as raw text in GitHub's preview, but the CSV file works correctly when downloaded and opened in spreadsheet software

### Sample Data

The first few rows of the dataset look like this (simplified view):

| country | year | coal | gas | oil | nuclear | hydro | solar | wind | biofuel | ... |
|---------|------|------|-----|-----|---------|-------|-------|------|---------|-----|
| China | 2018 | 2800.0 | 240.0 | 600.0 | 70.0 | 270.0 | 170.0 | 360.0 | 90.0 | ... |
| India | 2018 | 990.0 | 75.0 | 245.0 | 40.0 | 130.0 | 30.0 | 60.0 | 45.0 | ... |
| Japan | 2018 | 310.0 | 145.0 | 190.0 | 65.0 | 85.0 | 55.0 | 15.0 | 25.0 | ... |
| ... | ... | ... | ... | ... | ... | ... | ... | ... | ... | ... |
