# EMBER: World Nuclear Energy Generation 

**Corresponding file:** `world_nuclear_energy_generation.csv`

**Source:** [Ember Climate](https://ember-climate.org/topics/nuclear/)

### Column Descriptions
| Column Name | Description |
| --- | --- |
| `Entity` | The name of the country, region, or grouping. |
| `Year` | The year for which the electricity data is provided. |
| `electricity_from_nuclear_twh` | The amount of electricity generated from nuclear power sources, measured in terawatt-hours (TWh). |
| `share_of_electricity_pct` | The percentage of total electricity generation that comes from nuclear power sources for the given entity and year. This data is only available from 1985 onward for most entities.  |

Additional notes:
- Data availability varies by entity, with some countries having data spanning the entire range from 1965 to 2023, while others have more limited data.
- Some entities, such as regional groupings like Africa and Asia, have multiple entries with slightly different names (e.g., "Africa", "Africa (EI)", "Africa (Ember)"). These may represent data from different sources or with different methodologies.
- Blank cells in the `share_of_electricity_pct` column likely indicate that either no nuclear electricity was generated or the total electricity generation data was unavailable for that entity and year.