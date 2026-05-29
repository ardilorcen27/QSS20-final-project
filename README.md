# QSS20-final-project
This project examines the relationship between electricity access and industrial 
employment across 129 low and middle-income countries from 2000 to 2022.

## Data
The raw data were downloaded from the World Bank World Development Indicators (WDI):
- Electricity Access: https://data.worldbank.org/indicator/EG.ELC.ACCS.ZS
- Industrial Employment: https://data.worldbank.org/indicator/SL.IND.EMPL.ZS 
- Manufacturing Value Added: https://data.worldbank.org/indicator/NV.IND.MANF.ZS
- GDP per Capita: https://data.worldbank.org/indicator/NY.GDP.PCAP.KD

The clean merged panel is available here: 

## Code
- `code/01_clean.py` — loads and merges the four WDI indicator files into a clean panel dataset
- `code/02_analyze.py` — generates visualizations from the clean panel

## Output
- `output/fig1_region_trends.png` — mean electricity access by region, 2000–2022
- `output/fig2_scatter.png` — electricity access vs industrial employment scatter plot
