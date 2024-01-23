# nfk_timing
The dataset for the paper "The influence of time-of-day on estimates of taxonomic versus functional diversity in avian communities" [published](https://doi.org/10.1080/00063657.2023.2298661) in Bird Study.

The dataset contains the following columns:

Date : date, m/d/yyyy

Time : local time in Norfolk, VA, namely, EST (UTC−05:00) between the first Sunday of November at UTC 06:00 and the second Sunday of March at UTC 06:00 or EDT (UTC−04:00) otherwise

T : local solar time, as if 0.00 was sunrise, 0.50 was noon, and 1.00 was sunset

Per : period of day, where m = morning (0.00 < T < 0.25), n = noon (0.25 < T < 0.50), a = afternoon (0.50 < T < 0.75), and e = evening (0.75 < T < 1.00)

Dec : decade (10-days period), where 3/1/2021...3/10/2021 is the 1st decade

Point : location point code

W : wind strength, from 0 (still) to 10 (storm)

Cloud : cloud cover, from 0 to 1 (x 100 %)

all following columns correspond to the project taxa codes as in doi.org/10.5281/zenodo.7884472
