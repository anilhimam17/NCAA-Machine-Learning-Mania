# NCAA-Machine-Learning-Mania

**Understanding the Dataset**
--
> ### Abstract:  
> - The dataset contains all the data of national championship basketball matches during men's and women's tournaments
from `Mid March - Early April`.
> - The dataset isnt limited and contains significant amount historical data for both men's and women's tournaments within the same season.

### Legend
- `Prefix - M`: Indicates files containing relating to mens tournaments.
- `Prefix - W`: Indicates files containing relating to womens tournaments.
- **Cities / Conferences**: Files contain information pertaining to both mens and womens tournaments.

<hr>

### Basics
> Files to keep track MTeams.csv and WTeams.csv

- TeamID: 4 digit uniq id assigned to each team that doesn't change across seasons.
- TeamName: Compact team name for each uni.
- FirstD1Season and LastD1Season: First season in Division - I and Last season in Division - I mentioned in year. `Present only in Mens data`

**Important**
- For any current competing team the LastD1Season will be the current season in year.
- For each season identified we provide the year for when that particular season end instead of the start.

> Files to keep track MSeasons.csv and WSeasons.csv

- Season: Indicative of the year that the season was played.
- DayZero: Indicative of the start date of the games played for the respective season.
- Region W and X: W -> Always East since alpha first followed by its oppenent in the semifinal as -> X
- Region Y and Z: Y -> Always alpha first amongst the remaining regions -> Y and remaining -> Z.

> Files to keep track MNCAATourneySeeds.csv and WNCAATourneySeeds.csv

- Seed: Contain 3 chars (4 for playoff teams). First char - W/M for identity. Sec - Third char seed between (01 - 16) within their region. Last char (a / b) indicative of playoff opponent.

