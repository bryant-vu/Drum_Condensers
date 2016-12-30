# Drum_Condensers
SAM Reporting
Drum_Condensers.exe is intended for use during LTR's Title V SAM reporting.

Pressure data captured in 1 minute intervals; stored in a csv file.

Every 6 months, user is required to identify periods lasting 1hr or longer when pressure is <19.5 inches H2O.

Print out descriptive statistics of periods found in 2).




The following provides background information:

1) Only condensers with condition D12.5 are included in program.

2) A deviation period is assumed to last 60min or longer. Deviation events spanning shorter than 60mins will not appear in the output.

3) The program will output an Excel file titled "YYYY-MM-DD to YYYY-MM-DD Drum Condensers" at the location of the TGXXXX files. (For example, if the TGXXXX files are located in a folder titled “Data”; the program will create "YYYY-MM-DD to YYYY-MM-DD Drum Condensers" in the “Data” folder).

4) The program requires all 3 TGXXXX files to be fed in at the same time, with their specific names, in the original DCS format -- otherwise the script might not execute properly.

5) Tip: Start Index and Stop Index in the output file refer to the row number in the raw Excel file where the data point is found.
