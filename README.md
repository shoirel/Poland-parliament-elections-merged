# elections
merged 2019 and 2023 Poland parliament elections database 
// 
scalona baza wyborcza z 2019 i 2023 roku, wybory parlamentarne. wybory 2023 i 2019 do sejmu i senatu

final file  - 6 excess 2023 venues determined to have existed in 2019; the error is likely a consequence of the imperfect string fit (fixed for all 2019 venues). sejm and senat separated; columns such as votes via post were not included, a few variables only available for 2019/2023 were also omitted. 

correspondence_determination - venue correspondence determined, dupplicates not deleted. Two key problems: 
1. non-exact matches. the same venue may be described using e.g., a school's patreon's name in 2023 and lack that detail in 2019; in one year, a long pause is used and in the other, "-"; in 2023, an abbreviation "nr" may be used while in 2019, "numer" is used. Many such little discrepancies, hence the column "verdict" in the 2023 sheet, where the venue equivalence between years had to be determined non-automatically.
2. dupplicates (uneven numbers in 2023 and 2019, e.g., same venue name with different vote numbers repeated 6 times in 2019 and 4 times in 2023, and such).
