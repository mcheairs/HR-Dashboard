[HR_Analytics (1).csv](https://github.com/user-attachments/files/17334888/HR_Analytics.1.csv)HR Attrition Analysis (Interactive Dashboard using Power Bi)

Dashboard Overview
The stakeholders of Superstore wanted to get a more detailed snapshot of how the store was performing. 

Dataset used 

[UplEmpID,Age,AgeGroup,Attrition,BusinessTravel,DailyRate,Department,DistanceFromHome,Education,EducationField,EmployeeCount,EmployeeNumber,EnvironmentSatisfaction,Gender,HourlyRate,JobInvolvement,JobLevel,JobRole,JobSatisfaction,MaritalStatus,MonthlyIncome,SalarySlab,MonthlyRate,NumCompaniesWorked,Over18,OverTime,PercentSalaryHike,PerformanceRating,RelationshipSatisfaction,StandardHours,StockOptionLevel,TotalWorkingYears,TrainingTimesLastYear,WorkLifeBalance,YearsAtCompany,YearsInCurrentRole,YearsSinceLastPromotion,YearsWithCurrManager
RM297,18,18-25,Yes,Travel_Rarely,230,Research & Development,3,3,Life Sciences,1,405,3,Male,54,3,1,Laboratory Technician,3,Single,1420,Upto 5k,25233,1,Y,No,13,3,3,80,0,0,2,3,0,0,0,0
RM302,18,18-25,No,Travel_Rarely,812,Sales,10,3,Medical,1,411,4,Female,69,2,1,Sales Representative,3,Single,1200,Upto 5k,9724,1,Y,No,12,3,1,80,0,0,2,3,0,0,0,0
RM458,18,18-25,Yes,Travel_Frequently,1306,Sales,5,3,Marketing,1,614,2,Male,69,3,1,Sales Representative,2,Single,1878,Upto 5k,8059,1,Y,Yes,14,3,4,80,0,0,3,3,0,0,0,0
RM728,18,18-25,No,Non-Travel,287,Research & Development,5,2,Life Sciences,1,1012,2,Male,73,3,1,Research Scientist,4,Single,1051,Upto 5k,13493,1,Y,No,15,3,4,80,0,0,2,3,0,0,0,0
RM829,18,18-25,Yes,Non-Travel,247,Research & Development,8,1,Medical,1,1156,3,Male,80,3,1,Laboratory Technician,3,Single,1904,Upto 5k,13556,1,Y,No,12,3,4,80,0,0,0,3,0,0,0,0
RM973,18,18-25,No,Non-Travel,1124,Research & Development,1,3,Life Sciences,1,1368,4,Female,97,3,1,Laboratory Technician,4,Single,1611,Upto 5k,19305,1,Y,No,15,3,3,80,0,0,5,4,0,0,0,0
RM1154,18,18-25,Yes,Travel_Frequently,544,Sales,3,2,Medical,1,1624,2,Female,70,3,1,Sales Representative,4,Single,1569,Upto 5k,18420,1,Y,Yes,12,3,3,80,0,0,2,4,0,0,0,0
RM1312,18,18-25,No,Non-Travel,1431,Research & Development,14,3,Medical,1,1839,2,Female,33,3,1,Research Scientist,3,Single,1514,Upto 5k,8018,1,Y,No,16,3,3,80,0,0,4,1,0,0,0,0
RM128,19,18-25,Yes,Travel_Rarely,528,Sales,22,1,Marketing,1,167,4,Male,50,3,1,Sales Representative,3,Single,1675,Upto 5k,26820,1,Y,Yes,19,3,4,80,0,0,2,2,0,0,0,0
RM150,19,18-25,No,Travel_Rarely,1181,Research & Development,3,1,Medical,1,201,2,Female,79,3,1,Laboratory Technician,2,Single,1483,Upto 5k,16102,1,Y,No,14,3,4,80,0,1,3,3,1,0,0,0
RM172,19,18-25,Yes,Travel_Frequently,602,Sales,1,1,Technical Degree,1,235,3,Female,100,1,1,Sales Representative,1,Single,2325,Upto 5k,20989,0,Y,No,21,4,1,80,0,1,5,4,0,0,0,0
RM178,19,18-25,Yes,Travel_Rarely,303,Research & Development,2,3,Life Sciences,1,243,2,Male,47,2,1,Laboratory Technician,4,Single,1102,Upto 5k,9241,1,Y,No,22,4,3,80,0,1,3,2,1,0,1,0
RM423,19,18-25,Yes,Travel_Rarely,489,Human Resources,2,2,Technical Degree,1,566,1,Male,52,2,1,Human Resources,4,Single,2564,Upto 5k,18437,1,Y,No,12,3,3,80,0,1,3,4,1,0,0,0
RM689,19,18-25,Yes,Travel_Rarely,419,Sales,21,3,Other,1,959,4,Male,37,2,1,Sales Representative,2,Single,2121,Upto 5k,9947,1,Y,Yes,13,3,2,80,0,1,3,4,1,0,0,0
RM854,19,18-25,No,Travel_Rarely,645,Research & Development,9,2,Life Sciences,1,1193,3,Male,54,3,1,Research Scientist,1,Single,2552,Upto 5k,7172,1,Y,No,25,4,3,80,0,1,4,3,1,1,0,0
RM893,19,18-25,Yes,Non-Travel,504,Research & Development,10,3,Medical,1,1248,1,Female,96,2,1,Research Scientist,2,Single,1859,Upto 5k,6148,1,Y,Yes,25,4,2,80,0,1,2,4,1,1,0,0
RM910,19,18-25,No,Travel_Rarely,265,Research & Development,25,3,Life Sciences,1,1269,2,Female,57,4,1,Research Scientist,4,Single,2994,Upto 5k,21221,1,Y,Yes,12,3,4,80,0,1,2,3,1,0,0,1
RM103,20,18-25,Yes,Travel_Frequently,871,Research & Development,6,3,Life Sciences,1,137,4,Female,66,2,1,Laboratory Technician,4,Single,2926,Upto 5k,19783,1,Y,Yes,18,3,2,80,0,1,5,3,1,0,1,0
RM488,20,18-25,No,Travel_Rarely,959,Research & Development,1,3,Life Sciences,1,657,4,Female,83,2,1,Research Scientist,2,Single,2836,Upto 5k,11757,1,Y,No,13,3,4,80,0,1,0,4,1,0,0,0
RM514,20,18-25,Yes,Travel_Rarely,1362,Research & Development,10,1,Medical,1,701,4,Male,32,3,1,Research Scientist,3,Single,1009,Upto 5k,26999,1,Y,Yes,11,3,4,80,0,1,5,3,1,0,1,1
RM663,20,18-25,Yes,Travel_Rarely,500,Sales,2,3,Medical,1,922,3,Female,49,2,1,Sales Representative,3,Single,2044,Upto 5k,22052,1,Y,No,13,3,4,80,0,2,3,2,2,2,0,2
RM690,20,18-25,Yes,Travel_Rarely,129,Research & Development,4,3,Technical Degree,1,960,1,Male,84,3,1,Laboratory Technician,1,Single,2973,Upto 5k,13008,1,Y,No,19,3,2,80,0,1,2,3,1,0,0,0
RM732,20,18-25,Yes,Travel_Rarely,1097,Research & Development,11,3,Medical,1,1016,4,Female,98,2,1,Research Scientist,1,Single,2600,Upto 5k,18275,1,Y,Yes,15,3,1,80,0,1,2,3,1,0,0,0
RM777,20,18-25,Yes,Travel_Frequently,769,Sales,9,3,Marketing,1,1077,4,Female,54,3,1,Sales Representative,4,Single,2323,Upto 5k,17205,1,Y,Yes,14,3,2,80,0,2,3,3,2,2,0,2
RM857,20,18-25,No,Travel_Rarely,805,Research & Development,3,3,Life Sciences,1,1198,1,Male,87,2,1,Laboratory Technician,3,Single,3033,Upto 5k,12828,1,Y,No,12,3,1,80,0,2,2,2,2,2,1,2
RM877,20,18-25,No,Travel_Rarely,654,Sales,21,3,Marketing,1,1226,3,Male,43,4,1,Sales Representative,4,Single,2678,Upto 5k,5050,1,Y,No,17,3,4,80,0,2,2,3,2,1,2,2
RM1179,20,18-25,No,Travel_Rarely,1141,Sales,2,3,Medical,1,1657,3,Female,31,3,1,Sales Representative,3,Single,2783,Upto 5k,13251,1,Y,No,19,3,1,80,0,2,3,3,2,2,2,2
RM1198,20,18-25,No,Travel_Rarely,727,Sales,9,1,Life Sciences,1,1680,4,Male,54,3,1,Sales Representative,1,Single,2728,Upto 5k,21082,1,Y,No,11,3,1,80,0,2,3,3,2,2,0,2
RM024,21,18-25,No,Travel_Rarely,391,Research & Development,15,2,Life Sciences,1,30,3,Male,96,3,1,Research Scientist,4,Single,1232,Upto 5k,19281,1,Y,No,14,3,4,80,0,0,6,3,0,0,0,
RM275,21,18-25,No,Travel_Rarely,996,Research & Development,3,2,Medical,1,379,4,Male,100,2,1,Research Scientist,3,Single,3230,Upto 5k,10531,1,Y,No,17,3,1,80,0,3,4,4,3,2,1,0
RM358,21,18-25,Yes,Travel_Frequently,756,Sales,1,1,Technical Degree,1,478,1,Female,99,2,1,Sales Representative,2,Single,2174,Upto 5k,9150,1,Y,Yes,11,3,3,80,0,3,3,3,3,2,1,2
RM363,21,18-25,No,Non-Travel,895,Sales,9,2,Medical,1,484,1,Male,39,3,1,Sales Representative,4,Single,2610,Upto 5k,2851,1,Y,No,24,4,3,80,0,3,3,2,3,2,2,
RM371,21,18-25,Yes,Travel_Rarely,156,Sales,12,3,Life Sciences,1,494,3,Female,90,4,1,Sales Representative,2,Single,2716,Upto 5k,25422,1,Y,No,15,3,4,80,0,1,0,3,1,0,0,0
RM497,21,18-25,No,Travel_Rarely,1343,Sales,22,1,Technical Degree,1,669,3,Male,49,3,1,Sales Representative,3,Single,3447,Upto 5k,24444,1,Y,No,11,3,3,80,0,3,2,3,3,2,1,2
RM664,21,18-25,Yes,Travel_Rarely,1427,Research & Development,18,1,Other,1,923,4,Female,65,3,1,Research Scientist,4,Single,2693,Upto 5k,8870,1,Y,No,19,3,1,80,0,1,3,2,1,0,0,0
RM778,21,18-25,Yes,Travel_Rarely,1334,Research & Development,10,3,Life Sciences,1,1079,3,Female,36,2,1,Laboratory Technician,1,Single,1416,Upto 5k,17258,1,Y,No,13,3,1,80,0,1,6,2,1,0,1,0
RM816,21,18-25,No,Travel_Rarely,984,Research & Development,1,1,Technical Degree,1,1131,4,Female,70,2,1,Research Scientist,2,Single,2070,Upto 5k,25326,1,Y,Yes,11,3,3,80,0,2,6,4,2,2,2,2
RM916,21,18-25,Yes,Travel_Frequently,251,Research & Development,10,2,Life Sciences,1,1279,1,Female,45,2,1,Laboratory Technician,3,Single,2625,Upto 5k,25308,1,Y,No,20,4,3,80,0,2,2,1,2,2,2,2
RM1153,21,18-25,No,Travel_Rarely,546,Research & Development,5,1,Medical,1,1623,3,Male,97,3,1,Research Scientist,4,Single,3117,Upto 5k,26009,1,Y,No,18,3,3,80,0,3,2,3,2,2,2,2
RM1272,21,18-25,Yes,Travel_Rarely,337,Sales,7,1,Marketing,1,1780,2,Male,31,3,1,Sales Representative,2,Single,2679,Upto 5k,4567,1,Y,No,13,3,2,80,0,1,3,3,1,0,1,0
RM1437,21,18-25,No,Travel_Rarely,501,Sales,5,1,Medical,1,2021,3,Male,58,3,1,Sales Representative,1,Single,2380,Upto 5k,25479,1,Y,Yes,11,3,4,80,0,2,6,3,2,2,1,2
RM018,22,18-25,No,Non-Travel,1123,Research & Development,16,2,Medical,1,22,4,Male,96,4,1,Laboratory Technician,4,Divorced,2935,Upto 5k,7324,1,Y,Yes,13,3,2,80,2,1,2,2,1,0,0,0
RM110,22,18-25,No,Travel_Rarely,534,Research & Development,15,3,Medical,1,144,2,Female,59,3,1,Laboratory Technician,4,Single,2871,Upto 5k,23785,1,Y,No,15,3,3,80,0,1,5,3,0,0,0,0
RM129,22,18-25,No,Travel_Rarely,594,Research & Development,2,1,Technical Degree,1,169,3,Male,100,3,1,Laboratory Technician,4,Married,2523,Upto 5k,19299,0,Y,No,14,3,3,80,1,3,2,3,2,1,2,1
RM161,22,18-25,No,Travel_Rarely,1256,Research & Development,19,1,Medical,1,217,3,Male,80,3,1,Research Scientist,4,Married,2323,Upto 5k,11992,1,Y,No,24,4,1,80,2,2,6,3,2,2,2,2
RM207,22,18-25,No,Travel_Rarely,1136,Research & Development,5,3,Life Sciences,1,284,4,Male,60,4,1,Research Scientist,2,Divorced,2328,Upto 5k,12392,1,Y,Yes,16,3,1,80,1,4,2,2,4,2,2,
RM384,22,18-25,No,Travel_Rarely,253,Research & Development,11,3,Medical,1,511,1,Female,43,3,1,Research Scientist,2,Married,2244,Upto 5k,24440,1,Y,No,13,3,4,80,1,2,1,3,2,1,1,2
RM444,22,18-25,Yes,Travel_Frequently,1368,Research & Development,4,1,Technical Degree,1,593,3,Male,99,2,1,Laboratory Technician,3,Single,3894,Upto 5k,9129,5,Y,No,16,3,3,80,0,4,3,3,2,2,1,2
RM499,22,18-25,No,Travel_Rarely,604,Research & Development,6,1,Medical,1,675,1,Male,69,3,1,Research Scientist,3,Married,2773,Upto 5k,12145,0,Y,No,20,4,4,80,0,3,3,3,2,2,2,2
RM631,22,18-25,No,Travel_Rarely,1230,Research & Development,1,2,Life Sciences,1,872,4,Male,33,2,2,Manufacturing Director,4,Married,4775,Upto 5k,19146,6,Y,No,22,4,1,80,2,4,2,1,2,2,2,2
RM667,22,18-25,Yes,Travel_Rarely,617,Research & Development,3,1,Life Sciences,1,926,2,Female,34,3,2,Manufacturing Director,3,Married,4171,Upto 5k,10022,0,Y,Yes,19,3,1,80,1,4,3,4,3,2,0,2
RM735,22,18-25,No,Travel_Rarely,217,Research & Development,8,1,Life Sciences,1,1019,2,Male,94,1,1,Laboratory Technician,1,Married,2451,Upto 5k,6881,1,Y,No,15,3,1,80,1,4,3,2,4,3,1,1
RM861,22,18-25,Yes,Travel_Frequently,1256,Research & Development,3,4,Life Sciences,1,1203,3,Male,48,2,1,Research Scientist,4,Married,2853,Upto 5k,4223,0,Y,Yes,11,3,2,80,1,1,5,3,0,0,0,0
RM1138,22,18-25,No,Non-Travel,457,Research & Development,26,2,Other,1,1605,2,Female,85,2,1,Research Scientist,3,Married,2814,Upto 5k,10293,1,Y,Yes,14,3,2,80,0,4,2,2,4,2,1,3
RM1274,22,18-25,Yes,Travel_Rarely,1294,Research & Development,8,1,Medical,1,1783,3,Female,79,3,1,Laboratory Technician,1,Married,2398,Upto 5k,15999,1,Y,Yes,17,3,3,80,0,1,6,3,1,0,0,0
RM1340,22,18-25,Yes,Travel_Rarely,391,Research & Development,7,1,Life Sciences,1,1878,4,Male,75,3,1,Research Scientist,2,Single,2472,Upto 5k,26092,1,Y,Yes,23,4,1,80,0,1,2,3,1,0,0,0
RM1424,22,18-25,No,Travel_Rarely,581,Research & Development,1,2,Life Sciences,1,2007,4,Male,63,3,1,Research Scientist,3,Single,3375,Upto 5k,17624,0,Y,No,12,3,4,80,0,4,2,4,3,2,1,2
RM087,23,18-25,No,Travel_Rarely,541,Sales,2,1,Technical Degree,1,113,3,Male,62,3,1,Sales Representative,1,Divorced,2322,Upto 5k,9518,3,Y,No,13,3,3,80,1,3,3,3,0,0,0,0
RM346,23,18-25,No,Travel_Rarely,1309,Research & Development,26,1,Life Sciences,1,465,3,Male,83,3,1,Research Scientist,4,Divorced,2904,Upto 5k,16092,1,Y,No,12,3,3,80,2,4,2,2,4,2,0,2
RM517,23,18-25,No,Travel_Rarely,885,Research & Development,4,3,Medical,1,705,1,Male,58,4,1,Research Scientist,1,Married,2819,Upto 5k,8544,2,Y,No,16,3,1,80,1,5,3,4,3,2,0,2
RM551,23,18-25,No,Travel_Rarely,650,Research & Development,9,1,Medical,1,758,2,Male,37,3,1,Laboratory Technician,1,Married,2500,Upto 5k,4344,1,Y,No,14,3,4,80,1,5,2,4,4,3,0,2
RM566,23,18-25,No,Travel_Rarely,310,Research & Development,10,1,Medical,1,784,1,Male,79,4,1,Research Scientist,3,Single,3505,Upto 5k,19630,1,Y,No,18,3,4,80,0,2,3,3,2,2,0,2
RM586,23,18-25,Yes,Travel_Rarely,1243,Research & Development,6,3,Life Sciences,1,811,3,Male,63,4,1,Laboratory Technician,1,Married,1601,Upto 5k,3445,1,Y,Yes,21,4,3,80,2,1,2,3,0,0,0,0
RM911,23,18-25,No,Travel_Rarely,373,Research & Development,1,2,Life Sciences,1,1270,4,Male,47,3,1,Research Scientist,3,Married,1223,Upto 5k,16901,1,Y,No,22,4,4,80,1,1,2,3,1,0,0,1
RM1083,23,18-25,No,Travel_Rarely,507,Research & Development,20,1,Life Sciences,1,1533,1,Male,97,3,2,Laboratory Technician,3,Single,2272,Upto 5k,24812,0,Y,No,14,3,2,80,0,5,2,3,4,3,1,2
RM1128,23,18-25,No,Travel_Rarely,977,Research & Development,10,3,Technical Degree,1,1592,4,Male,45,4,1,Research Scientist,3,Married,2073,Upto 5k,12826,2,Y,No,16,3,4,80,1,4,2,3,2,2,2,2
RM1202,23,18-25,Yes,Travel_Rarely,1320,Research & Development,8,1,Medical,1,1684,4,Male,93,2,1,Laboratory Technician,3,Single,3989,Upto 5k,20586,1,Y,Yes,11,3,1,80,0,5,2,3,5,4,1,2
RM1214,23,18-25,Yes,Travel_Rarely,427,Sales,7,3,Life Sciences,1,1702,3,Male,99,3,1,Sales Representative,4,Divorced,2275,Upto 5k,25103,1,Y,Yes,21,4,2,80,1,3,2,3,3,2,0,2
RM1239,23,18-25,No,Travel_Rarely,160,Research & Development,4,1,Medical,1,1735,3,Female,51,3,1,Laboratory Technician,2,Single,3295,Upto 5k,12862,1,Y,No,13,3,3,80,0,3,3,1,3,2,1,2
RM1409,23,18-25,No,Travel_Rarely,571,Research & Development,12,2,Other,1,1982,4,Male,78,3,1,Laboratory Technician,4,Single,2647,Upto 5k,13672,1,Y,No,13,3,3,80,0,5,6,4,5,2,1,4
RM1439,23,18-25,Yes,Travel_Frequently,638,Sales,9,3,Marketing,1,2023,4,Male,33,3,1,Sales Representative,1,Married,1790,Upto 5k,26956,1,Y,No,19,3,1,80,1,1,3,2,1,0,1,0
RM021,24,18-25,No,Non-Travel,673,Research & Development,11,2,Other,1,26,1,Female,96,4,2,Manufacturing Director,3,Divorced,4011,Upto 5k,8232,0,Y,No,18,3,4,80,1,5,5,2,4,2,1,3
RM035,24,18-25,Yes,Travel_Rarely,813,Research & Development,1,3,Medical,1,45,2,Male,61,3,1,Research Scientist,4,Married,2293,Upto 5k,3020,2,Y,Yes,16,3,1,80,1,6,2,2,2,0,2,0
RM097,24,18-25,No,Travel_Rarely,1353,Sales,3,2,Other,1,128,1,Female,33,3,2,Sales Executive,3,Married,4999,Upto 5k,17519,0,Y,No,21,4,1,80,1,4,2,2,3,2,0,2
RM114,24,18-25,No,Travel_Rarely,1127,Research & Development,18,1,Life Sciences,1,150,2,Male,52,3,1,Laboratory Technician,3,Married,2774,Upto 5k,13257,0,Y,No,12,3,3,80,1,6,2,3,5,3,1,2
RM381,24,18-25,No,Travel_Rarely,1371,Sales,10,4,Marketing,1,507,4,Female,77,3,2,Sales Executive,3,Divorced,4260,Upto 5k,5915,1,Y,Yes,12,3,4,80,1,5,2,4,5,2,0,3
RM415,24,18-25,Yes,Travel_Rarely,1448,Sales,1,1,Technical Degree,1,554,1,Female,62,3,1,Sales Representative,2,Single,3202,Upto 5k,21972,1,Y,Yes,16,3,2,80,0,6,4,3,5,3,1,4
RM471,24,18-25,No,Travel_Frequently,535,Sales,24,3,Medical,1,632,4,Male,38,3,1,Sales Representative,4,Married,2400,Upto 5k,5530,0,Y,No,13,3,3,80,2,3,3,3,2,2,2,1
RM475,24,18-25,No,Travel_Rarely,691,Research & Development,23,3,Medical,1,639,2,Male,89,4,1,Research Scientist,4,Married,2725,Upto 5k,21630,1,Y,Yes,11,3,2,80,2,6,3,3,6,5,1,4
RM477,24,18-25,No,Travel_Rarely,823,Research & Development,17,2,Other,1,643,4,Male,94,2,1,Laboratory Technician,2,Married,2127,Upto 5k,9100,1,Y,No,21,4,4,80,1,1,2,3,1,0,0,0
RM480,24,18-25,Yes,Travel_Frequently,1287,Research & Development,7,3,Life Sciences,1,647,1,Female,55,3,1,Laboratory Technician,3,Married,2886,Upto 5k,14168,1,Y,Yes,16,3,4,80,1,6,4,3,6,3,1,2
RM526,24,18-25,Yes,Travel_Rarely,693,Sales,3,2,Life Sciences,1,720,1,Female,65,3,2,Sales Executive,3,Single,4577,Upto 5k,24785,9,Y,No,14,3,1,80,0,4,3,3,2,2,2,0
RM587,24,18-25,No,Non-Travel,1092,Research & Development,9,3,Life Sciences,1,812,3,Male,60,2,1,Laboratory Technician,2,Divorced,2694,Upto 5k,26551,1,Y,No,11,3,3,80,3,1,4,3,1,0,0,0
RM641,24,18-25,No,Non-Travel,1269,Research & Development,4,1,Life Sciences,1,888,1,Male,46,2,1,Laboratory Technician,4,Married,3162,Upto 5k,10778,0,Y,No,17,3,4,80,0,6,2,2,5,2,3,4
RM725,24,18-25,No,Travel_Rarely,1206,Research & Development,17,1,Medical,1,1009,4,Female,41,2,2,Manufacturing Director,3,Divorced,4377,Upto 5k,24117,1,Y,No,15,3,2,80,2,5,6,3,4,2,3,2
RM842,24,18-25,No,Travel_Rarely,477,Research & Development,24,3,Medical,1,1173,4,Male,49,3,1,Laboratory Technician,2,Single,3597,Upto 5k,6409,8,Y,No,22,4,4,80,0,6,2,3,4,3,1,2
RM872,24,18-25,Yes,Travel_Rarely,984,Research & Development,17,2,Life Sciences,1,1219,4,Female,97,3,1,Laboratory Technician,2,Married,2210,Upto 5k,3372,1,Y,No,13,3,1,80,1,1,3,1,1,0,0,0
RM1026,24,18-25,No,Travel_Rarely,1476,Sales,4,1,Medical,1,1445,4,Female,42,3,2,Sales Executive,3,Married,4162,Upto 5k,15211,1,Y,Yes,12,3,3,80,2,5,3,3,5,4,0,3
RM1061,24,18-25,Yes,Travel_Frequently,381,Research & Development,9,3,Medical,1,1494,2,Male,89,3,1,Laboratory Technician,1,Single,3172,Upto 5k,16998,2,Y,Yes,11,3,3,80,0,4,2,2,0,0,0,0
RM1062,24,18-25,No,Non-Travel,830,Sales,13,2,Life Sciences,1,1495,4,Female,78,3,1,Sales Representative,2,Married,2033,Upto 5k,7103,1,Y,No,13,3,3,80,1,1,2,3,1,0,0,0
RM1098,24,18-25,No,Travel_Rarely,350,Research & Development,21,2,Technical Degree,1,1551,3,Male,57,2,1,Laboratory Technician,1,Divorced,2296,Upto 5k,10036,0,Y,No,14,3,2,80,3,2,3,3,1,1,0,0
RM1169,24,18-25,No,Travel_Frequently,567,Research & Development,2,1,Technical Degree,1,1646,1,Female,32,3,1,Research Scientist,4,Single,3760,Upto 5k,17218,1,Y,Yes,13,3,3,80,0,6,2,3,6,3,1,3
RM1218,24,18-25,No,Travel_Rarely,581,Research & Development,9,3,Medical,1,1707,3,Male,62,4,1,Research Scientist,3,Married,4401,Upto 5k,17616,1,Y,No,16,3,4,80,1,5,1,3,5,3,0,4
RM1223,24,18-25,Yes,Travel_Rarely,240,Human Resources,22,1,Human Resources,1,1714,4,Male,58,1,1,Human Resources,3,Married,1555,Upto 5k,11585,1,Y,No,11,3,3,80,1,1,2,3,1,0,0,0
RM1231,24,18-25,No,Travel_Rarely,506,Research & Development,29,1,Medical,1,1725,2,Male,91,3,1,Laboratory Technician,1,Divorced,3907,Upto 5k,3622,1,Y,No,13,3,2,80,3,6,2,4,6,2,1,2
RM1246,24,18-25,No,Travel_Frequently,897,Human Resources,10,3,Medical,1,1746,1,Male,59,3,1,Human Resources,4,Married,2145,Upto 5k,2097,0,Y,No,14,3,4,80,1,3,2,3,2,2,2,1
RM1408,24,18-25,No,Travel_Rarely,771,Research & Development,1,2,Life Sciences,1,1981,2,Male,45,2,2,Healthcare Representative,3,Single,4617,Upto 5k,14120,1,Y,No,12,3,2,80,0,4,2,2,4,3,1,2
RM108,25,18-25,Yes,Travel_Rarely,240,Sales,5,3,Marketing,1,142,3,Male,46,2,2,Sales Executive,3,Single,5744,5k-10k,26959,1,Y,Yes,11,3,4,80,0,6,1,3,6,4,0,3
RM109,25,18-25,No,Travel_Rarely,1280,Research & Development,7,1,Medical,1,143,4,Male,64,2,1,Research Scientist,4,Married,2889,Upto 5k,26897,1,Y,No,11,3,3,80,2,2,2,3,2,2,2,1
RM139,25,18-25,No,Travel_Rarely,959,Sales,28,3,Life Sciences,1,183,1,Male,41,2,2,Sales Executive,3,Married,8639,5k-10k,24835,2,Y,No,18,3,4,80,0,6,3,3,2,2,2,
RM256,25,18-25,No,Travel_Rarely,685,Research & Development,1,3,Life Sciences,1,350,1,Female,62,3,2,Manufacturing Director,3,Married,4898,Upto 5k,7505,0,Y,No,12,3,4,80,2,5,3,3,4,2,1,
RM268,25,18-25,No,Non-Travel,675,Research & Development,5,2,Life Sciences,1,369,2,Male,85,4,2,Healthcare Representative,1,Divorced,4000,Upto 5k,18384,1,Y,No,12,3,4,80,2,6,2,3,6,3,1,5
RM398,25,18-25,No,Travel_Rarely,891,Sales,4,2,Life Sciences,1,527,2,Female,99,2,2,Sales Executive,4,Single,4487,Upto 5k,12090,1,Y,Yes,11,3,2,80,0,5,3,3,5,4,1,3
RM406,25,18-25,Yes,Travel_Rarely,688,Research & Development,3,3,Medical,1,538,1,Male,91,3,1,Laboratory Technician,1,Married,4031,Upto 5k,9396,5,Y,No,13,3,3,80,1,6,5,3,2,2,0,
RM479,25,18-25,No,Travel_Rarely,622,Sales,13,1,Medical,1,645,2,Male,40,3,1,Sales Representative,3,Married,2096,Upto 5k,26376,1,Y,No,11,3,3,80,0,7,1,3,7,4,0,6
RM518,25,18-25,No,Travel_Rarely,810,Sales,8,3,Life Sciences,1,707,4,Male,57,4,2,Sales Executive,2,Married,4851,Upto 5k,15678,0,Y,No,22,4,3,80,1,4,4,3,3,2,1,2
RM564,25,18-25,No,Travel_Rarely,883,Sales,26,1,Medical,1,781,3,Female,32,3,2,Sales Executive,4,Single,6180,5k-10k,22807,1,Y,No,23,4,2,80,0,6,5,2,6,5,1,4
RM619,25,18-25,No,Travel_Rarely,180,Research & Development,2,1,Medical,1,854,1,Male,65,4,1,Research Scientist,1,Single,3424,Upto 5k,21632,7,Y,No,13,3,3,80,0,6,3,2,4,3,0,1
RM635,25,18-25,No,Travel_Rarely,141,Sales,3,1,Other,1,879,3,Male,98,3,2,Sales Executive,1,Married,4194,Upto 5k,14363,1,Y,Yes,18,3,4,80,0,5,3,3,5,3,0,3
RM639,25,18-25,No,Travel_Rarely,583,Sales,4,1,Marketing,1,885,3,Male,87,2,2,Sales Executive,1,Married,4256,Upto 5k,18154,1,Y,No,12,3,1,80,0,5,1,4,5,2,0,3
RM684,25,18-25,Yes,Travel_Rarely,867,Sales,19,2,Marketing,1,952,3,Male,36,2,1,Sales Representative,2,Married,2413,Upto 5k,18798,1,Y,Yes,18,3,3,80,3,1,2,3,1,0,0,0
RM797,25,18-25,Yes,Travel_Rarely,1219,Research & Development,4,1,Technical Degree,1,1106,4,Male,32,3,1,Laboratory Technician,4,Married,3691,Upto 5k,4605,1,Y,Yes,15,3,2,80,1,7,3,4,7,7,5,6
RM886,25,18-25,No,Travel_Rarely,1356,Sales,10,4,Life Sciences,1,1240,3,Male,57,3,2,Sales Executive,4,Single,4950,Upto 5k,20623,0,Y,No,14,3,2,80,0,5,4,3,4,3,1,1
RM912,25,18-25,Yes,Travel_Frequently,599,Sales,24,1,Life Sciences,1,1273,3,Male,73,1,1,Sales Representative,4,Single,1118,Upto 5k,8040,1,Y,Yes,14,3,4,80,0,1,4,3,1,0,1,0
RM935,25,18-25,No,Travel_Rarely,266,Research & Development,1,3,Medical,1,1303,4,Female,40,3,1,Research Scientist,2,Single,2096,Upto 5k,18830,1,Y,No,18,3,4,80,0,2,3,2,2,2,2,1
RM966,25,18-25,No,Travel_Rarely,882,Research & Development,19,1,Medical,1,1358,4,Male,67,3,1,Laboratory Technician,4,Married,3669,Upto 5k,9075,3,Y,No,11,3,3,80,3,7,6,2,3,2,1,2
RM994,25,18-25,No,Travel_Rarely,1372,Sales,18,1,Life Sciences,1,1399,1,Male,93,4,2,Sales Executive,3,Married,6232,5k-10k,12477,2,Y,No,11,3,2,80,0,6,3,2,3,2,1,2
RM1004,25,18-25,No,Travel_Rarely,949,Research & Development,1,3,Technical Degree,1,1415,1,Male,81,3,1,Laboratory Technician,4,Married,3229,Upto 5k,4910,4,Y,No,11,3,2,80,1,7,2,2,3,2,0,2
RM1022,25,18-25,Yes,Travel_Rarely,383,Sales,9,2,Life Sciences,1,1439,1,Male,68,2,1,Sales Representative,1,Married,4400,Upto 5k,15182,3,Y,No,12,3,1,80,0,6,2,3,3,2,2,2
RM1175,25,18-25,No,Travel_Frequently,772,Research & Development,2,1,Life Sciences,1,1653,4,Male,77,4,2,Manufacturing Director,3,Divorced,5206,5k-10k,4973,1,Y,No,17,3,3,80,2,7,6,3,7,7,0,7
RM1412,25,18-25,No,Travel_Rarely,309,Human Resources,2,3,Human Resources,1,1987,3,Female,82,3,1,Human Resources,2,Married,2187,Upto 5k,19655,4,Y,No,14,3,3,80,0,6,3,3,2,0,1,2
RM1414,25,18-25,No,Travel_Rarely,977,Research & Development,2,1,Other,1,1992,4,Male,57,3,1,Laboratory Technician,3,Divorced,3977,Upto 5k,7298,6,Y,Yes,19,3,3,80,1,7,2,2,2,2,0,2
RM1434,25,18-25,No,Travel_Rarely,1382,Sales,8,2,Other,1,2018,1,Female,85,3,2,Sales Executive,3,Divorced,4907,Upto 5k,13684,0,Y,Yes,22,4,2,80,1,6,3,2,5,3,0,4
RM043,26,26-35,Yes,Travel_Rarely,1357,Research & Development,25,3,Life Sciences,1,55,1,Male,48,1,1,Laboratory Technician,3,Single,2293,Upto 5k,10558,1,Y,No,12,3,3,80,0,1,2,2,1,0,0,1
RM055,26,26-35,No,Travel_Rarely,1443,Sales,23,3,Marketing,1,72,3,Female,47,2,2,Sales Executive,4,Married,4157,Upto 5k,21436,7,Y,Yes,19,3,3,80,1,5,2,2,2,2,0,0
RM126,26,26-35,No,Travel_Rarely,841,Research & Development,6,3,Other,1,164,3,Female,46,2,1,Research Scientist,2,Married,2368,Upto 5k,23300,1,Y,No,19,3,3,80,0,5,3,2,5,4,4,3
RM135,26,26-35,No,Travel_Rarely,1355,Human Resources,25,1,Life Sciences,1,177,3,Female,61,3,1,Human Resources,3,Married,2942,Upto 5k,8916,1,Y,No,23,4,4,80,1,8,3,3,8,7,5,7
RM279,26,26-35,No,Travel_Frequently,1479,Research & Development,1,3,Life Sciences,1,384,3,Female,84,3,2,Manufacturing Director,2,Divorced,6397,5k-10k,26767,1,Y,No,20,4,1,80,1,6,6,1,6,5,1,4
RM285,26,26-35,No,Travel_Frequently,496,Research & Development,11,2,Medical,1,390,1,Male,60,3,2,Healthcare Representative,1,Married,4741,Upto 5k,22722,1,Y,Yes,13,3,3,80,1,5,3,3,5,3,3,3
RM289,26,26-35,Yes,Travel_Rarely,1449,Research & Development,16,4,Medical,1,394,1,Male,45,3,1,Laboratory Technician,2,Divorced,2373,Upto 5k,14180,2,Y,Yes,13,3,4,80,1,5,2,3,3,2,0,2
RM294,26,26-35,Yes,Travel_Rarely,950,Sales,4,4,Marketing,1,401,4,Male,48,2,2,Sales Executive,4,Single,5828,5k-10k,8450,1,Y,Yes,12,3,2,80,0,8,0,3,8,7,7,4
RM356,26,26-35,No,Travel_Rarely,933,Sales,1,3,Life Sciences,1,476,3,Male,57,3,2,Sales Executive,3,Married,5296,5k-10k,20156,1,Y,No,17,3,2,80,1,8,3,3,8,7,7,7
RM383,26,26-35,Yes,Travel_Frequently,575,Research & Development,3,1,Technical Degree,1,510,3,Male,73,3,1,Research Scientist,1,Single,3102,Upto 5k,6582,0,Y,No,22,4,3,80,0,7,2,3,6,4,0,4
RM419,26,26-35,No,Travel_Rarely,1349,Research & Development,23,3,Life Sciences,1,560,1,Female,90,3,1,Research Scientist,4,Divorced,2886,Upto 5k,3032,1,Y,No,22,4,2,80,2,3,3,1,3,2,0,2
RM454,26,26-35,Yes,Travel_Frequently,426,Human Resources,17,4,Life Sciences,1,608,2,Female,58,3,1,Human Resources,3,Divorced,2741,Upto 5k,22808,0,Y,Yes,11,3,2,80,1,8,2,2,7,7,1,0
RM461,26,26-35,No,Travel_Rarely,775,Sales,29,2,Medical,1,618,1,Male,45,3,2,Sales Executive,3,Divorced,4306,Upto 5k,4267,5,Y,No,12,3,1,80,2,8,5,3,0,0,0,0
RM464,26,26-35,Yes,Travel_Rarely,471,Research & Development,24,3,Technical Degree,1,622,3,Male,66,1,1,Laboratory Technician,4,Single,2340,Upto 5k,23213,1,Y,Yes,18,3,2,80,0,1,3,1,1,0,0,0
RM476,26,26-35,No,Travel_Rarely,703,Sales,28,2,Marketing,1,641,1,Male,66,3,2,Sales Executive,2,Married,6272,5k-10k,7428,1,Y,No,20,4,4,80,2,6,5,4,5,3,1,4
RM506,26,26-35,No,Travel_Rarely,991,Research & Development,6,3,Life Sciences,1,686,3,Female,71,3,1,Laboratory Technician,4,Married,2659,Upto 5k,17759,1,Y,Yes,13,3,3,80,1,3,2,3,3,2,0,2
RM572,26,26-35,No,Travel_Frequently,575,Research & Development,1,2,Life Sciences,1,792,1,Female,71,1,1,Laboratory Technician,4,Divorced,4364,Upto 5k,5288,3,Y,No,14,3,1,80,1,5,2,3,2,2,2,0
RM574,26,26-35,Yes,Travel_Rarely,1146,Sales,8,3,Technical Degree,1,796,4,Male,38,2,2,Sales Executive,1,Single,5326,5k-10k,3064,6,Y,No,17,3,3,80,0,6,2,2,4,3,1,2
RM615,26,26-35,Yes,Travel_Frequently,887,Research & Development,5,2,Medical,1,848,3,Female,88,2,1,Research Scientist,3,Married,2366,Upto 5k,20898,1,Y,Yes,14,3,1,80,1,8,2,3,8,7,1,7
RM686,26,26-35,No,Travel_Frequently,1283,Sales,1,3,Medical,1,956,3,Male,52,2,2,Sales Executive,1,Single,4294,Upto 5k,11148,1,Y,No,12,3,2,80,0,7,2,3,7,7,0,7
RM734,26,26-35,No,Travel_Rarely,1066,Research & Development,2,2,Medical,1,1018,4,Male,32,4,2,Manufacturing Director,4,Married,5472,5k-10k,3334,1,Y,No,12,3,2,80,0,8,2,3,8,7,1,3
RM749,26,26-35,Yes,Non-Travel,265,Sales,29,2,Medical,1,1037,2,Male,79,1,2,Sales Executive,1,Single,4969,Upto 5k,21813,8,Y,No,18,3,4,80,0,7,6,3,2,2,2,2
RM763,26,26-35,Yes,Travel_Frequently,342,Research & Development,2,3,Life Sciences,1,1053,1,Male,57,3,1,Research Scientist,1,Married,2042,Upto 5k,15346,6,Y,Yes,14,3,2,80,1,6,2,3,3,2,1,2
RM770,26,26-35,No,Travel_Frequently,921,Research & Development,1,1,Medical,1,1068,1,Female,66,2,1,Research Scientist,3,Divorced,2007,Upto 5k,25265,1,Y,No,13,3,3,80,2,5,5,3,5,3,1,3
RM782,26,26-35,No,Travel_Rarely,192,Research & Development,1,2,Medical,1,1083,1,Male,59,2,1,Laboratory Technician,1,Married,3955,Upto 5k,11141,1,Y,No,16,3,1,80,2,6,2,3,5,3,1,3
RM798,26,26-35,Yes,Travel_Rarely,1330,Research & Development,21,3,Medical,1,1107,1,Male,37,3,1,Laboratory Technician,3,Divorced,2377,Upto 5k,19373,1,Y,No,20,4,3,80,1,1,0,2,1,1,0,0
RM844,26,26-35,No,Travel_Rarely,1384,Research & Development,3,4,Medical,1,1177,1,Male,82,4,1,Laboratory Technician,4,Married,4420,Upto 5k,13421,1,Y,No,22,4,2,80,1,8,2,3,8,7,0,7
RM913,26,26-35,No,Travel_Rarely,583,Research & Development,4,2,Life Sciences,1,1275,3,Male,53,3,1,Research Scientist,4,Single,2875,Upto 5k,9973,1,Y,Yes,20,4,2,80,0,8,2,2,8,5,2,2
RM999,26,26-35,No,Travel_Rarely,683,Research & Development,2,1,Medical,1,1407,1,Male,36,2,1,Research Scientist,4,Single,3904,Upto 5k,4050,0,Y,No,12,3,4,80,0,5,2,3,4,3,1,1
RM1005,26,26-35,No,Travel_Rarely,652,Research & Development,7,3,Other,1,1417,3,Male,100,4,1,Laboratory Technician,1,Single,3578,Upto 5k,23577,0,Y,No,12,3,4,80,0,8,2,3,7,7,0,7
RM1119,26,26-35,No,Travel_Rarely,474,Research & Development,3,3,Life Sciences,1,1581,1,Female,89,3,1,Research Scientist,4,Married,2061,Upto 5k,11133,1,Y,No,21,4,1,80,0,1,5,3,1,0,0,0
RM1207,26,26-35,No,Non-Travel,786,Research & Development,7,3,Medical,1,1693,4,Male,76,3,1,Laboratory Technician,4,Single,2570,Upto 5k,11925,1,Y,No,20,4,3,80,0,7,5,3,7,7,5,7
RM1225,26,26-35,No,Travel_Rarely,390,Research & Development,17,4,Medical,1,1718,4,Male,62,1,1,Laboratory Technician,3,Married,2305,Upto 5k,6217,1,Y,No,15,3,3,80,3,3,3,4,3,2,0,2
RM1298,26,26-35,Yes,Travel_Rarely,920,Human Resources,20,2,Medical,1,1818,4,Female,69,3,1,Human Resources,2,Married,2148,Upto 5k,6889,0,Y,Yes,11,3,3,80,0,6,3,3,5,1,1,4
RM1310,26,26-35,No,Travel_Rarely,572,Sales,10,3,Medical,1,1836,3,Male,46,3,2,Sales Executive,4,Single,4684,Upto 5k,9125,1,Y,No,13,3,1,80,0,5,4,3,5,3,1,2
RM1350,26,26-35,No,Travel_Rarely,482,Research & Development,1,2,Life Sciences,1,1893,2,Female,90,2,1,Research Scientist,3,Married,2933,Upto 5k,14908,1,Y,Yes,13,3,3,80,1,1,3,2,1,0,1,0
RM1362,26,26-35,No,Travel_Frequently,1096,Research & Development,6,3,Other,1,1918,3,Male,61,4,1,Laboratory Technician,4,Married,2544,Upto 5k,7102,0,Y,No,18,3,1,80,1,8,3,3,7,7,7,7
RM1387,26,26-35,No,Travel_Rarely,157,Research & Development,1,3,Medical,1,1952,3,Male,95,3,1,Laboratory Technician,1,Single,2867,Upto 5k,20006,0,Y,No,13,3,4,80,0,8,6,2,7,7,7,6
RM1465,26,26-35,No,Travel_Rarely,1167,Sales,5,3,Other,1,2060,4,Female,30,2,1,Sales Representative,3,Single,2966,Upto 5k,21378,0,Y,No,18,3,4,80,0,5,2,3,4,2,0,0
RM1465,26,26-35,No,Travel_Rarely,1167,Sales,5,3,Other,1,2060,4,Female,30,2,1,Sales Representative,3,Single,2966,Upto 5k,21378,0,Y,No,18,3,4,80,0,5,2,3,4,2,0,5
RM005,27,26-35,No,Travel_Rarely,591,Research & Development,2,1,Medical,1,7,1,Male,40,3,1,Laboratory Technician,2,Married,3468,Upto 5k,16632,9,Y,No,12,3,4,80,1,6,3,3,2,2,2,2
RM042,27,26-35,No,Travel_Rarely,1240,Research & Development,2,4,Life Sciences,1,54,4,Female,33,3,1,Laboratory Technician,1,Divorced,2341,Upto 5k,19715,1,Y,No,13,3,4,80,1,1,6,3,1,0,0,0
RM044,27,26-35,No,Travel_Frequently,994,Sales,8,3,Life Sciences,1,56,4,Male,37,3,3,Sales Executive,3,Single,8726,5k-10k,2975,1,Y,No,15,3,4,80,0,9,0,3,9,8,1,7
RM162,27,26-35,No,Non-Travel,691,Research & Development,9,3,Medical,1,218,4,Male,57,3,1,Research Scientist,2,Divorced,2024,Upto 5k,5970,6,Y,No,18,3,4,80,1,6,1,1,2,2,2,2
RM165,27,26-35,No,Non-Travel,1450,Research & Development,3,3,Medical,1,224,3,Male,79,2,1,Research Scientist,3,Divorced,2566,Upto 5k,25326,1,Y,Yes,15,3,4,80,1,1,2,2,1,1,0,1
RM171,27,26-35,No,Travel_Rarely,1157,Research & Development,17,3,Technical Degree,1,233,3,Male,51,3,1,Research Scientist,2,Married,3058,Upto 5k,13364,0,Y,Yes,16,3,4,80,1,6,3,2,5,2,1,1
RM192,27,26-35,No,Travel_Rarely,894,Research & Development,9,3,Medical,1,260,4,Female,99,3,1,Research Scientist,2,Single,2279,Upto 5k,11781,1,Y,No,16,3,4,80,0,7,2,2,7,7,0,3
RM201,27,26-35,No,Travel_Frequently,472,Research & Development,1,1,Technical Degree,1,274,3,Male,60,2,2,Manufacturing Director,1,Married,4298,Upto 5k,9679,5,Y,No,19,3,3,80,1,6,1,3,2,2,2,0
RM213,27,26-35,No,Travel_Frequently,1242,Sales,20,3,Life Sciences,1,293,4,Female,90,3,2,Sales Executive,3,Single,9981,5k-10k,12916,1,Y,No,14,3,4,80,0,7,2,3,7,7,0,7
RM319,27,26-35,No,Travel_Rarely,1220,Research & Development,5,3,Life Sciences,1,434,3,Female,85,3,1,Research Scientist,2,Single,2478,Upto 5k,20938,1,Y,Yes,12,3,2,80,0,4,2,2,4,3,1,2
RM321,27,26-35,No,Travel_Rarely,1377,Sales,2,3,Life Sciences,1,437,4,Male,74,3,2,Sales Executive,3,Single,4478,Upto 5k,5242,1,Y,Yes,11,3,1,80,0,5,3,3,5,4,0,4
RM332,27,26-35,No,Non-Travel,210,Sales,1,1,Marketing,1,449,3,Male,73,3,2,Sales Executive,2,Married,6349,5k-10k,22107,0,Y,Yes,13,3,4,80,1,6,0,3,5,4,1,4
RM340,27,26-35,No,Travel_Rarely,1130,Sales,8,4,Marketing,1,458,2,Female,56,3,2,Sales Executive,2,Married,6214,5k-10k,3415,1,Y,No,18,3,1,80,1,8,3,3,8,7,0,7
RM374,27,26-35,No,Travel_Rarely,1469,Research & Development,1,2,Medical,1,497,4,Male,82,3,1,Laboratory Technician,2,Divorced,3816,Upto 5k,17881,1,Y,No,11,3,2,80,1,5,2,3,5,2,0,4
RM486,27,26-35,No,Travel_Rarely,798,Research & Development,6,4,Medical,1,655,1,Female,66,2,1,Research Scientist,3,Divorced,2187,Upto 5k,5013,0,Y,No,12,3,3,80,2,6,5,2,5,3,0,3
RM496,27,26-35,Yes,Travel_Rarely,1420,Sales,2,1,Marketing,1,667,3,Male,85,3,1,Sales Representative,1,Divorced,3041,Upto 5k,16346,0,Y,No,11,3,2,80,1,5,3,3,4,3,0,2
RM513,27,26-35,No,Travel_Rarely,1115,Research & Development,3,4,Medical,1,700,1,Male,54,2,1,Research Scientist,4,Single,2045,Upto 5k,15174,0,Y,No,13,3,4,80,0,5,0,3,4,2,1,1
RM522,27,26-35,No,Travel_Frequently,1410,Sales,3,1,Medical,1,714,4,Female,71,4,2,Sales Executive,4,Divorced,4647,Upto 5k,16673,1,Y,Yes,20,4,2,80,2,6,3,3,6,5,0,4
RM531,27,26-35,No,Travel_Rarely,608,Research & Development,1,2,Life Sciences,1,725,3,Female,68,3,3,Manufacturing Director,1,Married,7412,5k-10k,6009,1,Y,No,11,3,4,80,0,9,3,3,9,7,0,7
RM538,27,26-35,No,Travel_Frequently,294,Research & Development,10,2,Life Sciences,1,733,4,Male,32,3,3,Manufacturing Director,1,Divorced,8793,5k-10k,4809,1,Y,No,21,4,3,80,2,9,4,2,9,7,1,7
RM555,27,26-35,No,Travel_Rarely,975,Research & Development,7,3,Medical,1,764,4,Female,55,2,2,Healthcare Representative,1,Single,6811,5k-10k,23398,8,Y,No,19,3,1,80,0,9,2,1,7,6,0,7
RM577,27,26-35,No,Travel_Frequently,829,Sales,8,1,Marketing,1,800,3,Male,84,3,2,Sales Executive,4,Married,4342,Upto 5k,24008,0,Y,No,19,3,2,80,1,5,3,3,4,2,1,1
RM611,27,26-35,No,Travel_Rarely,269,Research & Development,5,1,Technical Degree,1,844,3,Male,42,2,3,Research Director,4,Divorced,12808,10k-15k,8842,1,Y,Yes,16,3,2,80,1,9,3,3,9,8,0,8
RM616,27,26-35,No,Non-Travel,443,Research & Development,3,3,Medical,1,850,4,Male,50,3,1,Research Scientist,4,Married,1706,Upto 5k,16571,1,Y,No,11,3,3,80,3,0,6,2,0,0,0,0
RM671,27,26-35,No,Travel_Rarely,618,Research & Development,4,3,Life Sciences,1,933,2,Female,76,3,1,Research Scientist,3,Single,2318,Upto 5k,17808,1,Y,No,19,3,3,80,0,1,2,3,1,1,0,0
RM718,27,26-35,No,Travel_Rarely,1134,Research & Development,16,4,Technical Degree,1,1001,3,Female,37,3,1,Laboratory Technician,2,Married,2811,Upto 5k,12086,9,Y,No,14,3,2,80,1,4,2,3,2,2,2,2
RM740,27,26-35,No,Travel_Rarely,1055,Research & Development,2,4,Life Sciences,1,1027,1,Female,47,3,2,Manufacturing Director,4,Married,4227,Upto 5k,4658,0,Y,No,18,3,2,80,1,4,2,3,3,2,2,2
RM787,27,26-35,No,Non-Travel,1277,Research & Development,8,5,Life Sciences,1,1094,1,Male,87,1,1,Laboratory Technician,3,Married,4621,Upto 5k,5869,1,Y,No,19,3,4,80,3,3,4,3,3,2,1,2
RM834,27,26-35,No,Travel_Rarely,199,Research & Development,6,3,Life Sciences,1,1162,4,Male,55,2,1,Research Scientist,3,Married,2539,Upto 5k,7950,1,Y,No,13,3,3,80,1,4,0,3,4,2,2,2
RM890,27,26-35,No,Travel_Rarely,1103,Research & Development,14,3,Life Sciences,1,1244,1,Male,42,3,1,Research Scientist,1,Married,2235,Upto 5k,14377,1,Y,Yes,14,3,4,80,2,9,3,2,9,7,6,8
RM903,27,26-35,No,Travel_Rarely,1167,Research & Development,4,2,Life Sciences,1,1259,1,Male,76,3,1,Research Scientist,3,Divorced,2517,Upto 5k,3208,1,Y,No,11,3,2,80,3,5,2,3,5,3,0,3
RM971,27,26-35,No,Travel_Rarely,1291,Sales,11,3,Medical,1,1364,3,Female,98,4,1,Sales Representative,4,Married,2534,Upto 5k,6527,8,Y,No,14,3,2,80,1,5,4,3,1,0,0,0
RM975,27,26-35,No,Travel_Frequently,793,Sales,2,1,Life Sciences,1,1371,4,Male,43,1,2,Sales Executive,4,Single,5071,5k-10k,20392,3,Y,No,20,4,2,80,0,8,3,3,6,2,0,0
RM997,27,26-35,No,Travel_Rarely,205,Sales,10,3,Marketing,1,1403,4,Female,98,2,2,Sales Executive,4,Married,5769,5k-10k,7100,1,Y,Yes,11,3,4,80,0,6,3,3,6,2,4,4
RM998,27,26-35,Yes,Travel_Rarely,135,Research & Development,17,4,Life Sciences,1,1405,4,Female,51,3,1,Research Scientist,3,Single,2394,Upto 5k,25681,1,Y,Yes,13,3,4,80,0,8,2,3,8,2,7,7
RM1018,27,26-35,No,Travel_Rarely,1377,Research & Development,11,1,Life Sciences,1,1434,2,Male,91,3,1,Laboratory Technician,1,Married,2099,Upto 5k,7679,0,Y,No,14,3,2,80,0,6,3,4,5,0,1,4
RM1150,27,26-35,No,Travel_Rarely,1302,Research & Development,19,3,Other,1,1619,4,Male,67,2,1,Laboratory Technician,1,Divorced,4066,Upto 5k,16290,1,Y,No,11,3,1,80,2,7,3,3,7,7,0,7
RM1170,27,26-35,No,Travel_Rarely,486,Research & Development,8,3,Medical,1,1647,2,Female,86,4,1,Research Scientist,3,Married,3517,Upto 5k,22490,7,Y,No,17,3,1,80,0,5,0,3,3,2,0,2
RM1171,27,26-35,No,Travel_Frequently,591,Research & Development,2,3,Medical,1,1648,4,Male,87,3,1,Research Scientist,4,Single,2580,Upto 5k,6297,2,Y,No,13,3,3,80,0,6,0,2,4,2,1,2
RM1249,27,26-35,No,Travel_Rarely,1054,Research & Development,8,3,Medical,1,1751,3,Female,67,3,1,Research Scientist,4,Single,3445,Upto 5k,6152,1,Y,No,11,3,3,80,0,6,5,2,6,2,1,4
RM1318,27,26-35,No,Travel_Frequently,1297,Research & Development,5,2,Life Sciences,1,1850,4,Female,53,3,1,Laboratory Technician,4,Single,2379,Upto 5k,19826,0,Y,Yes,14,3,3,80,0,6,3,2,5,4,0,2
RM1329,27,26-35,No,Travel_Rarely,728,Sales,23,1,Medical,1,1864,2,Female,36,2,2,Sales Representative,3,Married,3540,Upto 5k,7018,1,Y,No,21,4,4,80,1,9,5,3,9,8,5,8
RM1335,27,26-35,No,Travel_Frequently,1131,Research & Development,15,3,Life Sciences,1,1870,4,Female,77,2,1,Research Scientist,1,Married,4774,Upto 5k,23844,0,Y,No,19,3,4,80,1,8,2,2,7,6,7,3
RM1351,27,26-35,No,Travel_Rarely,511,Sales,2,2,Medical,1,1898,1,Female,89,4,2,Sales Executive,3,Single,6500,5k-10k,26997,0,Y,No,14,3,2,80,0,9,5,2,8,7,0,7
RM1368,27,26-35,No,TravelRarely,1354,Research & Development,2,4,Technical Degree,1,1931,2,Male,41,3,1,Research Scientist,2,Married,2226,Upto 5k,6073,1,Y,No,11,3,3,80,1,6,3,2,5,3,1,2
RM1380,27,26-35,Yes,Travel_Frequently,1337,Human Resources,22,3,Human Resources,1,1944,1,Female,58,2,1,Human Resources,2,Married,2863,Upto 5k,19555,1,Y,No,12,3,1,80,0,1,2,3,1,0,0,0
RM1394,27,26-35,No,Travel_Rarely,954,Sales,9,3,Marketing,1,1965,4,Male,44,3,2,Sales Executive,4,Single,4105,Upto 5k,5099,1,Y,No,14,3,1,80,0,7,5,3,7,7,0,7
RM1468,27,26-35,No,Travel_Rarely,155,Research & Development,4,3,Life Sciences,1,2064,2,Male,87,4,2,Manufacturing Director,2,Married,6142,5k-10k,5174,1,Y,Yes,20,4,2,80,1,6,0,3,6,2,0,3
RM1468,27,26-35,No,Travel_Rarely,155,Research & Development,4,3,Life Sciences,1,2064,2,Male,87,4,2,Manufacturing Director,2,Married,6142,5k-10k,5174,1,Y,Yes,20,4,2,80,1,6,0,3,6,2,0,3
RM015,28,26-35,Yes,Travel_Rarely,103,Research & Development,24,3,Life Sciences,1,19,3,Male,50,2,1,Laboratory Technician,3,Single,2028,Upto 5k,12947,5,Y,Yes,14,3,2,80,0,6,4,3,4,2,0,3
RM052,28,26-35,Yes,Travel_Rarely,1434,Research & Development,5,4,Technical Degree,1,65,3,Male,50,3,1,Laboratory Technician,3,Single,3441,Upto 5k,11179,1,Y,Yes,13,3,3,80,0,2,3,2,2,2,2,2
RM098,28,26-35,No,Non-Travel,120,Sales,4,3,Medical,1,129,2,Male,43,3,2,Sales Executive,3,Married,4221,Upto 5k,8863,1,Y,No,15,3,2,80,0,5,3,4,5,4,0,4
RM163,28,26-35,No,Travel_Rarely,440,Research & Development,21,3,Medical,1,221,3,Male,42,3,1,Research Scientist,4,Married,2713,Upto 5k,6672,1,Y,No,11,3,3,80,1,5,2,1,5,2,0,2
RM265,28,26-35,Yes,Travel_Rarely,529,Research & Development,2,4,Life Sciences,1,364,1,Male,79,3,1,Laboratory Technician,3,Single,3485,Upto 5k,14935,2,Y,No,11,3,3,80,0,5,5,1,0,0,0,0
RM273,28,26-35,No,Travel_Rarely,1158,Research & Development,9,3,Medical,1,377,4,Male,94,3,1,Research Scientist,4,Married,2070,Upto 5k,2613,1,Y,No,23,4,4,80,1,5,3,2,5,2,0,4
RM290,28,26-35,No,Travel_Rarely,1117,Research & Development,8,2,Life Sciences,1,395,4,Female,66,3,1,Research Scientist,4,Single,3310,Upto 5k,4488,1,Y,No,21,4,4,80,0,5,3,3,5,3,0,2
RM303,28,26-35,No,Travel_Rarely,1476,Research & Development,16,2,Medical,1,412,2,Male,68,4,2,Healthcare Representative,1,Single,5661,5k-10k,4824,0,Y,No,19,3,3,80,0,9,2,3,8,3,0,7
RM324,28,26-35,Yes,Travel_Rarely,1157,Research & Development,2,4,Medical,1,440,1,Male,84,1,1,Research Scientist,4,Married,3464,Upto 5k,24737,5,Y,Yes,13,3,4,80,0,5,4,2,3,2,2,2
RM375,28,26-35,No,Travel_Rarely,304,Sales,9,4,Life Sciences,1,498,2,Male,92,3,2,Sales Executive,4,Single,5253,5k-10k,20750,1,Y,No,16,3,4,80,0,7,1,3,7,5,0,7
RM405,28,26-35,No,Travel_Rarely,1300,Research & Development,17,2,Medical,1,536,3,Male,79,3,2,Laboratory Technician,1,Divorced,4558,Upto 5k,13535,1,Y,No,12,3,4,80,1,10,2,3,10,0,1,
RM541,28,26-35,Yes,Travel_Rarely,654,Research & Development,1,2,Life Sciences,1,741,1,Female,67,1,1,Research Scientist,2,Single,2216,Upto 5k,3872,7,Y,Yes,13,3,4,80,0,10,4,3,7,7,3,7
RM599,28,26-35,Yes,Travel_Rarely,890,Research & Development,2,4,Medical,1,828,3,Male,46,3,1,Research Scientist,3,Single,4382,Upto 5k,16374,6,Y,No,17,3,4,80,0,5,3,2,2,2,2,1
RM613,28,26-35,No,Travel_Rarely,760,Sales,2,4,Marketing,1,846,2,Female,81,3,2,Sales Executive,2,Married,4779,Upto 5k,3698,1,Y,Yes,20,4,1,80,0,8,2,3,8,7,7,5
RM630,28,26-35,No,Travel_Rarely,1169,Human Resources,8,2,Medical,1,869,2,Male,63,2,1,Human Resources,4,Divorced,4936,Upto 5k,23965,1,Y,No,13,3,4,80,1,6,6,3,5,1,0,4
RM660,28,26-35,No,Travel_Rarely,821,Sales,5,4,Medical,1,916,1,Male,98,3,2,Sales Executive,4,Single,4908,Upto 5k,24252,1,Y,No,14,3,2,80,0,4,3,3,4,2,0,2
RM669,28,26-35,No,Travel_Rarely,995,Research & Development,9,3,Medical,1,930,3,Female,77,3,1,Research Scientist,3,Divorced,2377,Upto 5k,9834,5,Y,No,18,3,2,80,1,6,2,3,2,2,2,2
RM765,28,26-35,No,Travel_Rarely,1144,Sales,10,1,Medical,1,1056,4,Male,74,3,1,Sales Representative,2,Married,1052,Upto 5k,23384,1,Y,No,22,4,2,80,0,1,5,3,1,0,0,0
RM781,28,26-35,Yes,Non-Travel,1366,Research & Development,24,2,Technical Degree,1,1082,2,Male,72,2,3,Healthcare Representative,1,Single,8722,5k-10k,12355,1,Y,No,12,3,1,80,0,10,2,2,10,7,1,9
RM789,28,26-35,No,Travel_Rarely,857,Research & Development,10,3,Other,1,1097,3,Female,59,3,2,Research Scientist,3,Single,3660,Upto 5k,7909,3,Y,No,13,3,4,80,0,10,4,4,8,7,1,7
RM794,28,26-35,No,Travel_Rarely,895,Research & Development,15,2,Life Sciences,1,1102,1,Male,50,3,1,Laboratory Technician,3,Divorced,2207,Upto 5k,22482,1,Y,No,16,3,4,80,1,4,5,2,4,2,2,2
RM801,28,26-35,Yes,Travel_Frequently,1009,Research & Development,1,3,Medical,1,1111,1,Male,45,2,1,Laboratory Technician,2,Divorced,2596,Upto 5k,7160,1,Y,No,15,3,1,80,2,1,2,3,1,0,0,0
RM810,28,26-35,No,Travel_Rarely,950,Research & Development,3,3,Medical,1,1121,4,Female,93,3,3,Manufacturing Director,2,Divorced,7655,5k-10k,8039,0,Y,No,17,3,2,80,3,10,3,2,9,7,1,7
RM820,28,26-35,No,Travel_Rarely,1451,Research & Development,2,1,Life Sciences,1,1136,1,Male,67,2,1,Research Scientist,2,Married,3201,Upto 5k,19911,0,Y,No,17,3,1,80,0,6,2,1,5,3,0,4
RM828,28,26-35,No,Travel_Frequently,773,Research & Development,6,3,Life Sciences,1,1154,3,Male,39,2,1,Research Scientist,3,Divorced,2703,Upto 5k,22088,1,Y,Yes,14,3,4,80,1,3,2,3,3,1,0,2
RM843,28,26-35,Yes,Travel_Rarely,1485,Research & Development,12,1,Life Sciences,1,1175,3,Female,79,3,1,Laboratory Technician,4,Married,2515,Upto 5k,22955,1,Y,Yes,11,3,4,80,0,1,4,2,1,1,0,0
RM869,28,26-35,No,Travel_Rarely,1179,Research & Development,19,4,Medical,1,1216,4,Male,78,2,1,Laboratory Technician,1,Married,3196,Upto 5k,12449,1,Y,No,12,3,3,80,3,6,2,3,6,5,3,3
RM922,28,26-35,No,Travel_Frequently,791,Research & Development,1,4,Medical,1,1286,4,Male,44,3,1,Laboratory Technician,3,Single,2154,Upto 5k,6842,0,Y,Yes,11,3,3,80,0,5,2,2,4,2,0,2
RM930,28,26-35,No,Travel_Frequently,193,Research & Development,2,3,Life Sciences,1,1296,4,Male,52,2,1,Laboratory Technician,4,Married,3867,Upto 5k,14222,1,Y,Yes,12,3,2,80,1,2,2,3,2,2,2,2
RM934,28,26-35,No,Travel_Rarely,640,Research & Development,1,3,Technical Degree,1,1301,4,Male,84,3,1,Research Scientist,1,Single,2080,Upto 5k,4732,2,Y,No,11,3,2,80,0,5,2,2,3,2,1,2
RM945,28,26-35,No,Non-Travel,1476,Research & Development,1,3,Life Sciences,1,1315,3,Female,55,1,2,Laboratory Technician,4,Married,6674,5k-10k,16392,0,Y,No,11,3,1,80,3,10,6,3,9,8,7,5
RM985,28,26-35,No,Travel_Rarely,736,Sales,26,3,Life Sciences,1,1387,3,Male,48,2,2,Sales Executive,1,Married,4724,Upto 5k,24232,1,Y,No,11,3,3,80,1,5,0,3,5,3,0,4
RM1042,28,26-35,No,Travel_Rarely,866,Sales,5,3,Medical,1,1469,4,Male,84,3,2,Sales Executive,1,Single,8463,5k-10k,23490,0,Y,No,18,3,4,80,0,6,4,3,5,4,1,3
RM1057,28,26-35,Yes,Travel_Frequently,1496,Sales,1,3,Technical Degree,1,1486,1,Male,92,3,1,Sales Representative,3,Married,2909,Upto 5k,15747,3,Y,No,15,3,4,80,1,5,3,4,3,2,1,2
RM1069,28,26-35,Yes,Travel_Frequently,289,Research & Development,2,2,Medical,1,1504,3,Male,38,2,1,Laboratory Technician,1,Single,2561,Upto 5k,5355,7,Y,No,11,3,3,80,0,8,2,2,0,0,0,0
RM1070,28,26-35,No,Travel_Rarely,1423,Research & Development,1,3,Life Sciences,1,1506,1,Male,72,2,1,Research Scientist,3,Divorced,1563,Upto 5k,12530,1,Y,No,14,3,4,80,1,1,2,1,1,0,0,0
RM1071,28,26-35,No,Travel_Frequently,467,Sales,7,3,Life Sciences,1,1507,3,Male,55,3,2,Sales Executive,1,Single,4898,Upto 5k,11827,0,Y,No,14,3,4,80,0,5,5,3,4,2,1,3
RM1074,28,26-35,No,Travel_Rarely,1083,Research & Development,29,1,Life Sciences,1,1514,3,Male,96,1,2,Manufacturing Director,2,Married,6549,5k-10k,3173,1,Y,No,14,3,2,80,2,8,2,2,8,6,1,7
RM1137,28,26-35,Yes,Travel_Rarely,329,Research & Development,24,3,Medical,1,1604,3,Male,51,3,1,Laboratory Technician,2,Married,2408,Upto 5k,7324,1,Y,Yes,17,3,3,80,3,1,3,3,1,1,0,0
RM1152,28,26-35,No,Travel_Rarely,580,Research & Development,27,3,Medical,1,1622,2,Female,39,1,2,Manufacturing Director,1,Divorced,4877,Upto 5k,20460,0,Y,No,21,4,2,80,1,6,5,2,5,3,0,0
RM1284,28,26-35,No,Travel_Rarely,1181,Research & Development,1,3,Life Sciences,1,1799,3,Male,82,3,1,Research Scientist,4,Married,2044,Upto 5k,5531,1,Y,No,11,3,3,80,1,5,6,4,5,3,0,3
RM1308,28,26-35,No,Travel_Rarely,1217,Research & Development,1,3,Medical,1,1834,3,Female,67,3,1,Research Scientist,1,Married,3591,Upto 5k,12719,1,Y,No,25,4,3,80,1,3,3,3,3,2,1,2
RM1324,28,26-35,No,Non-Travel,280,Human Resources,1,2,Life Sciences,1,1858,3,Male,43,3,1,Human Resources,4,Divorced,2706,Upto 5k,10494,1,Y,No,15,3,2,80,1,3,2,3,3,2,2,2
RM1338,28,26-35,No,Travel_Rarely,1172,Sales,3,3,Medical,1,1875,2,Female,78,3,1,Sales Representative,2,Married,2856,Upto 5k,3692,1,Y,No,19,3,4,80,1,1,3,3,1,0,0,0
RM1365,28,26-35,No,Travel_Frequently,783,Sales,1,2,Life Sciences,1,1927,3,Male,42,2,2,Sales Executive,4,Married,6834,5k-10k,19255,1,Y,Yes,12,3,3,80,1,7,2,3,7,7,0,7
RM1370,28,26-35,Yes,Travel_Rarely,1475,Sales,13,2,Marketing,1,1933,4,Female,84,3,2,Sales Executive,3,Single,9854,5k-10k,23352,3,Y,Yes,11,3,4,80,0,6,0,3,2,0,2,2
RM1382,28,26-35,No,Non-Travel,1103,Research & Development,16,3,Medical,1,1947,3,Male,49,3,1,Research Scientist,3,Single,2144,Upto 5k,2122,1,Y,No,14,3,3,80,0,5,3,2,5,3,1,4
RM1391,28,26-35,Yes,Travel_Rarely,1404,Research & Development,17,3,Technical Degree,1,1960,3,Male,32,2,1,Laboratory Technician,4,Divorced,2367,Upto 5k,18779,5,Y,No,12,3,1,80,1,6,2,2,4,1,0,3
RM012,29,26-35,No,Travel_Rarely,153,Research & Development,15,2,Life Sciences,1,15,4,Female,49,2,2,Laboratory Technician,3,Single,4193,Upto 5k,12682,0,Y,Yes,12,3,4,80,0,10,3,3,9,5,0,8
RM016,29,26-35,No,Travel_Rarely,1389,Research & Development,21,4,Life Sciences,1,20,2,Female,51,4,3,Manufacturing Director,1,Divorced,9980,5k-10k,10195,1,Y,No,11,3,3,80,1,10,1,3,10,9,8,8
RM072,29,26-35,No,Travel_Rarely,1328,Research & Development,2,3,Life Sciences,1,94,3,Male,76,3,1,Research Scientist,2,Married,2703,Upto 5k,4956,0,Y,No,23,4,4,80,1,6,3,3,5,4,0,
RM156,29,26-35,No,Non-Travel,1496,Research & Development,1,1,Technical Degree,1,208,4,Male,41,3,2,Manufacturing Director,3,Married,4319,Upto 5k,26283,1,Y,No,13,3,1,80,1,10,1,3,10,7,0,9
RM206,29,26-35,Yes,Travel_Rarely,121,Sales,27,3,Marketing,1,283,2,Female,35,3,3,Sales Executive,4,Married,7639,5k-10k,24525,1,Y,No,22,4,4,80,3,10,3,2,10,4,1,
RM218,29,26-35,Yes,Travel_Rarely,992,Research & Development,1,3,Technical Degree,1,300,3,Male,85,3,1,Research Scientist,3,Single,2058,Upto 5k,19757,0,Y,No,14,3,4,80,0,7,1,2,6,2,1,5
RM228,29,26-35,No,Travel_Frequently,1413,Sales,1,1,Medical,1,312,2,Female,42,3,3,Sales Executive,4,Married,7918,5k-10k,6599,1,Y,No,14,3,4,80,1,11,5,3,11,10,4,1
RM230,29,26-35,Yes,Travel_Rarely,896,Research & Development,18,1,Medical,1,315,3,Male,86,2,1,Research Scientist,4,Single,2389,Upto 5k,14961,1,Y,Yes,13,3,3,80,0,4,3,2,4,3,0,1
RM253,29,26-35,No,Travel_Rarely,665,Research & Development,15,3,Life Sciences,1,346,3,Male,60,3,1,Research Scientist,4,Single,2340,Upto 5k,22673,1,Y,No,19,3,1,80,0,6,1,3,6,5,1,
RM255,29,26-35,No,Travel_Rarely,1247,Sales,20,2,Marketing,1,349,4,Male,45,3,2,Sales Executive,4,Divorced,6931,5k-10k,10732,2,Y,No,14,3,4,80,1,10,2,3,3,2,0,
RM266,29,26-35,No,Travel_Rarely,1210,Sales,2,3,Medical,1,366,1,Male,78,2,2,Sales Executive,2,Married,6644,5k-10k,3687,2,Y,No,19,3,2,80,2,10,2,3,0,0,0,0
RM283,29,26-35,No,Travel_Frequently,442,Sales,2,2,Life Sciences,1,388,2,Male,44,3,2,Sales Executive,4,Single,4554,Upto 5k,20260,1,Y,No,18,3,1,80,0,10,3,2,10,7,0,9
RM337,29,26-35,Yes,Travel_Rarely,318,Research & Development,8,4,Other,1,454,2,Male,77,1,1,Laboratory Technician,1,Married,2119,Upto 5k,4759,1,Y,Yes,11,3,4,80,0,7,4,2,7,7,0,7
RM338,29,26-35,No,Travel_Rarely,738,Research & Development,9,5,Other,1,455,2,Male,30,2,1,Laboratory Technician,4,Single,3983,Upto 5k,7621,0,Y,No,17,3,3,80,0,4,2,3,3,2,2,2
RM344,29,26-35,No,Travel_Rarely,144,Sales,10,1,Marketing,1,463,4,Female,39,2,2,Sales Executive,2,Divorced,8268,5k-10k,11866,1,Y,Yes,14,3,1,80,2,7,2,3,7,7,1,7
RM350,29,26-35,No,Non-Travel,746,Sales,2,3,Life Sciences,1,469,4,Male,61,3,2,Sales Executive,3,Married,4649,Upto 5k,16928,1,Y,No,14,3,1,80,1,4,3,2,4,3,0,2
RM372,29,26-35,No,Travel_Rarely,1283,Research & Development,23,3,Life Sciences,1,495,4,Male,54,3,1,Research Scientist,4,Single,2201,Upto 5k,18168,9,Y,No,16,3,4,80,0,6,4,3,3,2,1,2
RM421,29,26-35,No,Travel_Rarely,986,Research & Development,3,4,Medical,1,564,2,Male,93,2,3,Research Director,3,Married,11935,10k-15k,21526,1,Y,No,18,3,3,80,0,10,2,3,10,2,0,7
RM422,29,26-35,Yes,Travel_Rarely,408,Research & Development,25,5,Technical Degree,1,565,3,Female,71,2,1,Research Scientist,2,Married,2546,Upto 5k,18300,5,Y,No,16,3,2,80,0,6,2,4,2,2,1,1
RM455,29,26-35,No,Travel_Rarely,232,Research & Development,19,3,Technical Degree,1,611,4,Male,34,3,2,Manufacturing Director,4,Divorced,4262,Upto 5k,22645,4,Y,No,12,3,2,80,2,8,2,4,3,2,1,2
RM508,29,26-35,No,Travel_Rarely,1176,Sales,3,2,Medical,1,690,2,Female,62,3,2,Sales Executive,3,Married,5561,5k-10k,3487,1,Y,No,14,3,1,80,1,6,5,2,6,0,1,2
RM520,29,26-35,No,Travel_Frequently,806,Research & Development,1,4,Life Sciences,1,710,2,Male,76,1,1,Research Scientist,4,Divorced,2720,Upto 5k,18959,1,Y,No,18,3,4,80,1,10,5,3,10,7,2,8
RM547,29,26-35,No,Travel_Rarely,1396,Sales,10,3,Life Sciences,1,749,3,Male,99,3,1,Sales Representative,3,Single,2642,Upto 5k,2755,1,Y,No,11,3,3,80,0,1,6,3,1,0,0,0
RM556,29,26-35,No,Travel_Rarely,1090,Sales,10,3,Marketing,1,766,4,Male,83,3,1,Sales Representative,2,Divorced,2297,Upto 5k,17967,1,Y,No,14,3,4,80,2,2,2,3,2,2,2,2
RM573,29,26-35,No,Travel_Rarely,657,Research & Development,27,3,Medical,1,793,2,Female,66,3,2,Healthcare Representative,3,Married,4335,Upto 5k,25549,4,Y,No,12,3,1,80,1,11,3,2,8,7,1,1
RM590,29,26-35,Yes,Travel_Rarely,805,Research & Development,1,2,Life Sciences,1,816,2,Female,36,2,1,Laboratory Technician,1,Married,2319,Upto 5k,6689,1,Y,Yes,11,3,4,80,1,1,1,3,1,0,0,0
RM595,29,26-35,No,Travel_Rarely,1252,Research & Development,23,2,Life Sciences,1,824,3,Male,81,4,1,Research Scientist,3,Married,2700,Upto 5k,23779,1,Y,No,24,4,3,80,1,10,3,3,10,7,0,7
RM646,29,26-35,Yes,Travel_Rarely,341,Sales,1,3,Medical,1,896,2,Female,48,2,1,Sales Representative,3,Divorced,2800,Upto 5k,23522,6,Y,Yes,19,3,3,80,3,5,3,3,3,2,0,2
RM658,29,26-35,No,Travel_Rarely,1086,Research & Development,7,1,Medical,1,912,1,Female,62,2,1,Laboratory Technician,4,Divorced,2532,Upto 5k,6054,6,Y,No,14,3,3,80,3,8,5,3,4,3,0,3
RM698,29,26-35,No,Travel_Frequently,1404,Sales,20,3,Technical Degree,1,974,3,Female,84,3,1,Sales Representative,4,Married,2157,Upto 5k,18203,1,Y,No,15,3,2,80,1,3,5,3,3,1,0,2
RM712,29,26-35,Yes,Travel_Rarely,906,Research & Development,10,3,Life Sciences,1,994,4,Female,92,2,1,Research Scientist,1,Single,2404,Upto 5k,11479,6,Y,Yes,20,4,3,80,0,3,5,3,0,0,0,0
RM809,29,26-35,No,Travel_Rarely,1107,Research & Development,28,4,Life Sciences,1,1120,3,Female,93,3,1,Research Scientist,4,Divorced,2514,Upto 5k,26968,4,Y,No,22,4,1,80,1,11,1,3,7,5,1,7
RM824,29,26-35,No,Travel_Frequently,490,Research & Development,10,3,Life Sciences,1,1143,4,Female,61,3,1,Research Scientist,2,Divorced,3291,Upto 5k,17940,0,Y,No,14,3,4,80,2,8,2,2,7,5,1,1
RM826,29,26-35,No,Travel_Rarely,718,Research & Development,8,1,Medical,1,1150,2,Male,79,2,2,Manufacturing Director,4,Married,5056,5k-10k,17689,1,Y,Yes,15,3,3,80,1,10,2,2,10,7,1,2
RM837,29,26-35,Yes,Travel_Rarely,408,Sales,23,1,Life Sciences,1,1165,4,Female,45,2,3,Sales Executive,1,Married,7336,5k-10k,11162,1,Y,No,13,3,1,80,1,11,3,1,11,8,3,10
RM853,29,26-35,No,Travel_Rarely,1401,Research & Development,6,1,Medical,1,1192,2,Female,54,3,1,Laboratory Technician,4,Married,3131,Upto 5k,26342,1,Y,No,13,3,1,80,1,10,5,3,10,8,0,8
RM860,29,26-35,No,Travel_Rarely,942,Research & Development,15,1,Life Sciences,1,1202,2,Female,69,1,1,Research Scientist,4,Married,2168,Upto 5k,26933,0,Y,Yes,18,3,1,80,1,6,2,2,5,4,1,3
RM894,29,26-35,No,Travel_Rarely,1010,Research & Development,1,3,Life Sciences,1,1249,1,Female,97,3,1,Research Scientist,4,Divorced,3760,Upto 5k,5598,1,Y,No,15,3,1,80,3,3,5,3,3,2,1,2
RM904,29,26-35,No,Travel_Rarely,1329,Research & Development,7,3,Life Sciences,1,1260,3,Male,82,3,2,Healthcare Representative,4,Divorced,6623,5k-10k,4204,1,Y,Yes,11,3,2,80,2,6,2,3,6,0,1,0
RM906,29,26-35,No,Travel_Rarely,694,Research & Development,1,3,Life Sciences,1,1264,4,Female,87,2,4,Research Director,4,Divorced,16124,15k+,3423,3,Y,No,14,3,2,80,2,9,2,2,7,7,1,7
RM933,29,26-35,Yes,Travel_Rarely,806,Research & Development,7,3,Technical Degree,1,1299,2,Female,39,3,1,Laboratory Technician,3,Divorced,3339,Upto 5k,17285,3,Y,Yes,13,3,1,80,2,10,2,3,7,7,7,7
RM1006,29,26-35,No,Travel_Rarely,332,Human Resources,17,3,Other,1,1419,2,Male,51,2,3,Human Resources,1,Single,7988,5k-10k,9769,1,Y,No,13,3,1,80,0,10,3,2,10,9,0,9
RM1008,29,26-35,Yes,Travel_Frequently,337,Research & Development,14,1,Other,1,1421,3,Female,84,3,3,Healthcare Representative,4,Single,7553,5k-10k,22930,0,Y,Yes,12,3,1,80,0,9,1,3,8,7,7,7
RM1058,29,26-35,Yes,Travel_Frequently,115,Sales,13,3,Technical Degree,1,1487,1,Female,51,3,2,Sales Executive,2,Single,5765,5k-10k,17485,5,Y,No,11,3,1,80,0,7,4,1,5,3,0,0
RM1064,29,26-35,No,Travel_Rarely,1246,Sales,19,3,Life Sciences,1,1497,3,Male,77,2,2,Sales Executive,3,Divorced,8620,5k-10k,23757,1,Y,No,14,3,3,80,2,10,3,3,10,7,0,4
RM1073,29,26-35,No,Travel_Frequently,410,Research & Development,2,1,Life Sciences,1,1513,4,Female,97,3,1,Laboratory Technician,2,Married,3180,Upto 5k,4668,0,Y,No,13,3,3,80,3,4,3,3,3,2,0,2
RM1078,29,26-35,Yes,Travel_Rarely,224,Research & Development,1,4,Technical Degree,1,1522,1,Male,100,2,1,Research Scientist,1,Single,2362,Upto 5k,7568,6,Y,No,13,3,3,80,0,11,2,1,9,7,0,7
RM1091,29,26-35,No,Travel_Rarely,441,Research & Development,8,1,Other,1,1544,3,Female,39,1,2,Healthcare Representative,1,Married,9715,5k-10k,7288,3,Y,No,13,3,3,80,1,9,3,3,7,7,0,7
RM1105,29,26-35,No,Travel_Rarely,598,Research & Development,9,3,Life Sciences,1,1558,3,Male,91,4,1,Research Scientist,3,Married,2451,Upto 5k,22376,6,Y,No,18,3,1,80,2,5,2,2,1,0,0,0
RM1123,29,26-35,No,Travel_Rarely,1370,Research & Development,3,1,Medical,1,1586,2,Male,87,3,1,Laboratory Technician,1,Single,4723,Upto 5k,16213,1,Y,Yes,18,3,4,80,0,10,3,3,10,9,1,5
RM1126,29,26-35,No,Travel_Frequently,995,Research & Development,2,1,Life Sciences,1,1590,1,Male,87,3,2,Healthcare Representative,4,Divorced,8853,5k-10k,24483,1,Y,No,19,3,4,80,1,6,0,4,6,4,1,3
RM1173,29,26-35,No,Travel_Rarely,469,Sales,10,3,Medical,1,1650,3,Male,42,2,2,Sales Executive,3,Single,5869,5k-10k,23413,9,Y,No,11,3,3,80,0,8,2,3,5,2,1,4
RM1189,29,26-35,No,Travel_Rarely,991,Sales,5,3,Medical,1,1669,1,Male,43,2,2,Sales Executive,2,Divorced,4187,Upto 5k,3356,1,Y,Yes,13,3,2,80,1,10,3,2,10,0,0,9
RM1220,29,26-35,No,Travel_Rarely,1082,Research & Development,9,4,Medical,1,1709,4,Female,43,3,1,Laboratory Technician,3,Married,2974,Upto 5k,25412,9,Y,No,17,3,3,80,1,9,2,3,5,3,1,2
RM1250,29,26-35,Yes,Travel_Rarely,428,Sales,9,3,Marketing,1,1752,2,Female,52,1,1,Sales Representative,2,Single,2760,Upto 5k,14630,1,Y,No,13,3,3,80,0,2,3,3,2,2,2,2
RM1251,29,26-35,No,Travel_Frequently,461,Research & Development,1,3,Life Sciences,1,1753,4,Male,70,4,2,Healthcare Representative,3,Single,6294,5k-10k,23060,8,Y,Yes,12,3,4,80,0,10,5,4,3,2,0,2
RM1259,29,26-35,No,Travel_Rarely,590,Research & Development,4,3,Technical Degree,1,1762,4,Female,91,2,1,Research Scientist,1,Divorced,2109,Upto 5k,10007,1,Y,No,13,3,3,80,1,1,2,3,1,0,0,0
RM1314,29,26-35,Yes,Travel_Rarely,350,Human Resources,13,3,Human Resources,1,1844,1,Male,56,2,1,Human Resources,1,Divorced,2335,Upto 5k,3157,4,Y,Yes,15,3,4,80,3,4,3,3,2,2,2,0
RM1319,29,26-35,No,Travel_Frequently,574,Research & Development,20,1,Medical,1,1852,4,Male,40,3,1,Laboratory Technician,4,Married,3812,Upto 5k,7003,1,Y,No,13,3,2,80,0,11,3,4,11,8,3,10
RM1325,29,26-35,No,Travel_Rarely,726,Research & Development,29,1,Life Sciences,1,1859,4,Male,93,1,2,Healthcare Representative,3,Divorced,6384,5k-10k,21143,8,Y,No,17,3,4,80,2,11,3,3,7,0,1,6
RM1330,29,26-35,No,TravelRarely,352,Human Resources,6,1,Medical,1,1865,4,Male,87,2,1,Human Resources,2,Married,2804,Upto 5k,15434,1,Y,No,11,3,4,80,0,1,3,3,1,0,0,0
RM1333,29,26-35,Yes,Travel_Frequently,459,Research & Development,24,2,Life Sciences,1,1868,4,Male,73,2,1,Research Scientist,4,Single,2439,Upto 5k,14753,1,Y,Yes,24,4,2,80,0,1,3,2,1,0,1,0
RM1344,29,26-35,No,Travel_Rarely,592,Research & Development,7,3,Life Sciences,1,1883,4,Male,59,3,1,Laboratory Technician,1,Single,2062,Upto 5k,19384,3,Y,No,14,3,2,80,0,11,2,3,3,2,1,2
RM1366,29,26-35,Yes,Travel_Frequently,746,Sales,24,3,Technical Degree,1,1928,3,Male,45,4,1,Sales Representative,1,Single,1091,Upto 5k,10642,1,Y,No,17,3,4,80,0,1,3,3,1,0,0,0
RM1388,29,26-35,No,Travel_Rarely,136,Research & Development,1,3,Life Sciences,1,1954,1,Male,89,3,2,Healthcare Representative,1,Married,5373,5k-10k,6225,0,Y,No,12,3,1,80,1,6,5,2,5,3,0,2
RM1443,29,26-35,Yes,Travel_Rarely,1092,Research & Development,1,4,Medical,1,2027,1,Male,36,3,1,Research Scientist,4,Married,4787,Upto 5k,26124,9,Y,Yes,14,3,2,80,3,4,3,4,2,2,2,2
RM1460,29,26-35,No,Travel_Rarely,1378,Research & Development,13,2,Other,1,2053,4,Male,46,2,2,Laboratory Technician,2,Married,4025,Upto 5k,23679,4,Y,Yes,13,3,1,80,1,10,2,3,4,3,0,3
RM1461,29,26-35,No,Travel_Rarely,468,Research & Development,28,4,Medical,1,2054,4,Female,73,2,1,Research Scientist,1,Single,3785,Upto 5k,8489,1,Y,No,14,3,2,80,0,5,3,1,5,4,0,4
RM1461,29,26-35,No,Travel_Rarely,468,Research & Development,28,4,Medical,1,2054,4,Female,73,2,1,Research Scientist,1,Single,3785,Upto 5k,8489,1,Y,No,14,3,2,80,0,5,3,1,5,4,0,4
RM008,30,26-35,No,Travel_Rarely,1358,Research & Development,24,1,Life Sciences,1,11,4,Male,67,3,1,Laboratory Technician,3,Divorced,2693,Upto 5k,13335,1,Y,No,22,4,2,80,1,1,2,3,1,0,0,
RM033,30,26-35,No,Travel_Rarely,125,Research & Development,9,2,Medical,1,41,4,Male,83,2,1,Laboratory Technician,3,Single,2206,Upto 5k,16117,1,Y,No,13,3,1,80,0,10,5,3,10,0,1,8
RM045,30,26-35,No,Travel_Frequently,721,Research & Development,1,2,Medical,1,57,3,Female,58,3,2,Laboratory Technician,4,Single,4011,Upto 5k,10781,1,Y,No,23,4,4,80,0,12,2,3,12,8,3,7
RM081,30,26-35,No,Travel_Rarely,852,Research & Development,1,1,Life Sciences,1,104,4,Male,55,2,2,Laboratory Technician,4,Married,5126,5k-10k,15998,1,Y,Yes,12,3,3,80,2,10,1,2,10,8,3,0
RM089,30,26-35,No,Travel_Rarely,288,Research & Development,2,3,Life Sciences,1,117,3,Male,99,2,2,Healthcare Representative,4,Married,4152,Upto 5k,15830,1,Y,No,19,3,1,80,3,11,3,3,11,10,10,8
RM093,30,26-35,No,Travel_Rarely,1334,Sales,4,2,Medical,1,121,3,Female,63,2,2,Sales Executive,2,Divorced,5209,5k-10k,19760,1,Y,Yes,12,3,2,80,3,11,4,2,11,8,2,7
RM121,30,26-35,No,Travel_Frequently,1312,Research & Development,23,3,Life Sciences,1,159,1,Male,96,1,1,Research Scientist,3,Divorced,2613,Upto 5k,22310,1,Y,No,25,4,3,80,3,10,2,2,10,7,0,9
RM140,30,26-35,No,Travel_Rarely,1240,Human Resources,9,3,Human Resources,1,184,3,Male,48,3,2,Human Resources,4,Married,6347,5k-10k,13982,0,Y,Yes,19,3,4,80,0,12,2,1,11,9,4,
RM144,30,26-35,No,Travel_Rarely,438,Research & Development,18,3,Life Sciences,1,194,1,Female,75,3,1,Research Scientist,3,Single,2632,Upto 5k,23910,1,Y,No,14,3,3,80,0,5,4,2,5,4,0,
RM146,30,26-35,No,Travel_Rarely,201,Research & Development,5,3,Technical Degree,1,197,4,Female,84,3,1,Research Scientist,1,Divorced,3204,Upto 5k,10415,5,Y,No,14,3,4,80,1,8,3,3,3,2,2,
RM147,30,26-35,No,Travel_Rarely,1427,Research & Development,2,1,Medical,1,198,2,Male,35,2,1,Laboratory Technician,4,Single,2720,Upto 5k,11162,0,Y,No,13,3,4,80,0,6,3,3,5,3,1,
RM168,30,26-35,No,Travel_Rarely,1339,Sales,5,3,Life Sciences,1,228,2,Female,41,3,3,Sales Executive,4,Married,9419,5k-10k,8053,2,Y,No,12,3,3,80,1,12,2,3,10,9,7,4
RM174,30,26-35,No,Non-Travel,111,Research & Development,9,3,Medical,1,239,3,Male,66,3,2,Laboratory Technician,1,Divorced,3072,Upto 5k,11012,1,Y,No,11,3,3,80,2,12,4,3,12,9,6,10
RM212,30,26-35,No,Non-Travel,829,Research & Development,1,1,Life Sciences,1,292,3,Male,88,2,3,Manufacturing Director,3,Single,8474,5k-10k,20925,1,Y,No,22,4,3,80,0,12,2,3,11,8,5,8
RM215,30,26-35,Yes,Travel_Rarely,1005,Research & Development,3,3,Technical Degree,1,297,4,Female,88,3,1,Research Scientist,1,Single,2657,Upto 5k,8556,5,Y,Yes,11,3,3,80,0,8,5,3,5,2,0,4
RM217,30,26-35,Yes,Travel_Frequently,334,Sales,26,4,Marketing,1,299,3,Female,52,2,2,Sales Executive,1,Single,6696,5k-10k,22967,5,Y,No,15,3,3,80,0,9,5,2,6,3,0,1
RM325,30,26-35,No,Travel_Rarely,1275,Research & Development,28,2,Medical,1,441,4,Female,64,3,2,Research Scientist,4,Married,5775,5k-10k,11934,1,Y,No,13,3,4,80,2,11,2,3,10,8,1,9
RM339,30,26-35,No,Travel_Rarely,570,Sales,5,3,Marketing,1,456,4,Female,30,2,2,Sales Executive,3,Divorced,6118,5k-10k,5431,1,Y,No,13,3,3,80,3,10,2,3,10,9,1,2
RM355,30,26-35,No,Non-Travel,641,Sales,25,2,Technical Degree,1,475,4,Female,85,3,2,Sales Executive,3,Married,4736,Upto 5k,6069,7,Y,Yes,12,3,2,80,1,4,2,4,2,2,2,2
RM382,30,26-35,No,Travel_Rarely,202,Sales,2,1,Technical Degree,1,508,3,Male,72,3,1,Sales Representative,2,Married,2476,Upto 5k,17434,1,Y,No,18,3,1,80,1,1,3,3,1,0,0,0
RM386,30,26-35,Yes,Travel_Frequently,464,Research & Development,4,3,Technical Degree,1,514,3,Male,40,3,1,Research Scientist,4,Single,2285,Upto 5k,3427,9,Y,Yes,23,4,3,80,0,3,4,3,1,0,0,0
RM403,30,26-35,No,Travel_Rarely,1082,Sales,12,3,Technical Degree,1,533,2,Female,83,3,2,Sales Executive,3,Single,6577,5k-10k,19558,0,Y,No,11,3,2,80,0,6,6,3,5,4,4,4
RM411,30,26-35,No,Travel_Rarely,317,Research & Development,2,3,Life Sciences,1,548,3,Female,43,1,2,Manufacturing Director,4,Single,6091,5k-10k,24793,2,Y,No,20,4,3,80,0,11,2,3,5,4,0,2
RM420,30,26-35,No,Non-Travel,1400,Research & Development,3,3,Life Sciences,1,562,3,Male,53,3,1,Laboratory Technician,4,Married,2097,Upto 5k,16734,4,Y,No,15,3,3,80,1,9,3,1,5,3,1,4
RM424,30,26-35,No,Non-Travel,1398,Sales,22,4,Other,1,567,3,Female,69,3,3,Sales Executive,1,Married,8412,5k-10k,2890,0,Y,No,11,3,3,80,0,10,3,3,9,8,7,8
RM427,30,26-35,No,Non-Travel,1116,Research & Development,2,3,Medical,1,571,3,Female,49,3,1,Laboratory Technician,4,Single,2564,Upto 5k,7181,0,Y,No,14,3,3,80,0,12,2,2,11,7,6,7
RM438,30,26-35,No,Travel_Rarely,413,Sales,7,1,Marketing,1,585,4,Male,57,3,1,Sales Representative,2,Single,2983,Upto 5k,18398,0,Y,No,14,3,1,80,0,4,3,3,3,2,1,2
RM481,30,26-35,Yes,Travel_Frequently,448,Sales,12,4,Life Sciences,1,648,2,Male,74,2,1,Sales Representative,1,Married,2033,Upto 5k,14470,1,Y,No,18,3,3,80,1,1,2,4,1,0,0,0
RM502,30,26-35,No,Travel_Frequently,160,Research & Development,3,3,Medical,1,680,3,Female,71,3,1,Research Scientist,3,Divorced,2083,Upto 5k,22653,1,Y,No,20,4,3,80,1,1,2,3,1,0,0,0
RM546,30,26-35,No,Travel_Rarely,501,Sales,27,5,Marketing,1,747,3,Male,99,3,2,Sales Executive,4,Divorced,5304,5k-10k,25275,7,Y,No,23,4,4,80,1,10,2,2,8,7,7,7
RM582,30,26-35,No,Travel_Rarely,921,Research & Development,1,3,Life Sciences,1,806,4,Male,38,1,1,Laboratory Technician,3,Married,3833,Upto 5k,24375,3,Y,No,21,4,3,80,2,7,2,3,2,2,0,2
RM603,30,26-35,No,Travel_Rarely,946,Research & Development,2,3,Medical,1,833,3,Female,52,2,2,Manufacturing Director,4,Single,6877,5k-10k,20234,5,Y,Yes,24,4,2,80,0,12,4,2,0,0,0,0
RM624,30,26-35,No,Travel_Frequently,1012,Research & Development,5,4,Life Sciences,1,861,2,Male,75,2,1,Research Scientist,4,Divorced,3761,Upto 5k,2373,9,Y,No,12,3,2,80,1,10,3,2,5,4,0,3
RM703,30,26-35,No,Travel_Rarely,231,Sales,8,2,Other,1,982,3,Male,62,3,3,Sales Executive,3,Divorced,7264,5k-10k,9977,5,Y,No,11,3,1,80,1,10,2,4,8,4,7,7
RM721,30,26-35,Yes,Travel_Rarely,138,Research & Development,22,3,Life Sciences,1,1004,1,Female,48,3,1,Research Scientist,3,Married,2132,Upto 5k,11539,4,Y,Yes,11,3,2,80,0,7,2,3,5,2,0,1
RM731,30,26-35,No,Travel_Rarely,153,Research & Development,8,2,Life Sciences,1,1015,2,Female,73,4,3,Research Director,1,Married,11416,10k-15k,17802,0,Y,Yes,12,3,3,80,3,9,4,2,8,7,1,7
RM733,30,26-35,Yes,Travel_Frequently,109,Research & Development,5,3,Medical,1,1017,2,Female,60,3,1,Laboratory Technician,2,Single,2422,Upto 5k,25725,0,Y,No,17,3,1,80,0,4,3,3,3,2,1,2
RM783,30,26-35,No,Travel_Rarely,1176,Research & Development,20,3,Other,1,1084,3,Male,85,3,2,Manufacturing Director,1,Married,9957,5k-10k,9096,0,Y,No,15,3,3,80,1,7,1,2,6,2,0,2
RM845,30,26-35,No,Travel_Rarely,852,Sales,10,3,Marketing,1,1179,3,Male,72,2,2,Sales Executive,3,Married,6578,5k-10k,2706,1,Y,No,18,3,1,80,1,10,3,3,10,3,1,4
RM866,30,26-35,No,Travel_Rarely,1329,Sales,29,4,Life Sciences,1,1211,3,Male,61,3,2,Sales Executive,1,Divorced,4115,Upto 5k,13192,8,Y,No,19,3,3,80,3,8,3,3,4,3,0,3
RM875,30,26-35,No,Travel_Rarely,853,Research & Development,7,4,Life Sciences,1,1224,3,Male,49,3,2,Laboratory Technician,3,Divorced,3491,Upto 5k,11309,1,Y,No,13,3,1,80,3,10,4,2,10,7,8,9
RM887,30,26-35,No,Travel_Rarely,1465,Research & Development,1,3,Medical,1,1241,4,Male,63,3,1,Research Scientist,2,Married,3579,Upto 5k,9369,0,Y,Yes,21,4,1,80,1,12,2,3,11,9,5,7
RM932,30,26-35,No,Non-Travel,879,Research & Development,9,2,Medical,1,1298,3,Female,72,3,2,Manufacturing Director,3,Single,4695,Upto 5k,12858,7,Y,Yes,18,3,3,80,0,10,3,3,8,4,1,7
RM942,30,26-35,No,Travel_Rarely,1138,Research & Development,6,3,Technical Degree,1,1311,1,Female,48,2,2,Laboratory Technician,4,Married,4627,Upto 5k,23631,0,Y,No,12,3,1,80,1,10,6,3,9,2,6,7
RM949,30,26-35,No,Travel_Rarely,634,Research & Development,17,4,Medical,1,1321,2,Female,95,3,3,Manager,1,Married,11916,10k-15k,25927,1,Y,Yes,23,4,4,80,2,9,2,3,9,1,0,8
RM1014,30,26-35,No,Travel_Rarely,855,Sales,7,4,Marketing,1,1428,4,Female,73,3,2,Sales Executive,1,Divorced,4779,Upto 5k,12761,7,Y,No,14,3,2,80,2,8,3,3,3,2,0,2
RM1050,30,26-35,No,Travel_Rarely,1358,Sales,16,1,Life Sciences,1,1479,4,Male,96,3,2,Sales Executive,3,Married,5301,5k-10k,2939,8,Y,No,15,3,3,80,2,4,2,2,2,1,2,2
RM1053,30,26-35,No,Non-Travel,990,Research & Development,7,3,Technical Degree,1,1482,3,Male,64,3,1,Research Scientist,3,Divorced,1274,Upto 5k,7152,1,Y,No,13,3,2,80,2,1,2,2,1,0,0,0
RM1065,30,26-35,No,Travel_Rarely,330,Human Resources,1,3,Life Sciences,1,1499,3,Male,46,3,1,Human Resources,3,Divorced,2064,Upto 5k,15428,0,Y,No,21,4,1,80,1,6,3,4,5,3,1,3
RM1107,30,26-35,Yes,Travel_Rarely,740,Sales,1,3,Life Sciences,1,1562,2,Male,64,2,2,Sales Executive,1,Married,9714,5k-10k,5323,1,Y,No,11,3,4,80,1,10,4,3,10,8,6,7
RM1110,30,26-35,No,Travel_Rarely,1288,Sales,29,4,Technical Degree,1,1568,3,Male,33,3,3,Sales Executive,2,Married,9250,5k-10k,17799,3,Y,No,12,3,2,80,1,9,3,3,4,2,1,3
RM1142,30,26-35,No,Travel_Rarely,241,Research & Development,7,3,Medical,1,1609,2,Male,48,2,1,Research Scientist,2,Married,2141,Upto 5k,5348,1,Y,No,12,3,2,80,1,6,3,2,6,4,1,1
RM1234,30,26-35,No,Travel_Rarely,793,Research & Development,16,1,Life Sciences,1,1729,2,Male,33,3,1,Research Scientist,4,Married,2862,Upto 5k,3811,1,Y,No,12,3,2,80,1,10,2,2,10,0,0,8
RM1245,30,26-35,No,Travel_Frequently,1312,Research & Development,2,4,Technical Degree,1,1745,4,Female,78,2,1,Research Scientist,1,Single,4968,Upto 5k,26427,0,Y,No,16,3,4,80,0,10,2,3,9,7,0,7
RM1247,30,26-35,Yes,Travel_Frequently,600,Human Resources,8,3,Human Resources,1,1747,3,Female,66,2,1,Human Resources,4,Divorced,2180,Upto 5k,9732,6,Y,No,11,3,3,80,1,6,0,2,4,2,1,2
RM1252,30,26-35,No,Travel_Rarely,979,Sales,15,2,Marketing,1,1754,3,Male,94,2,3,Sales Executive,1,Divorced,7140,5k-10k,3088,2,Y,No,11,3,1,80,1,12,2,3,7,7,1,7
RM1260,30,26-35,No,Travel_Rarely,305,Research & Development,16,3,Life Sciences,1,1763,3,Male,58,4,2,Healthcare Representative,3,Married,5294,5k-10k,9128,3,Y,No,16,3,3,80,1,10,3,3,7,0,1,7
RM1297,30,26-35,No,Travel_Rarely,1092,Research & Development,10,3,Medical,1,1816,1,Female,64,3,3,Manufacturing Director,3,Single,9667,5k-10k,2739,9,Y,No,14,3,2,80,0,9,3,3,7,7,0,2
RM1339,30,26-35,Yes,Travel_Rarely,945,Sales,9,3,Medical,1,1876,2,Male,89,3,1,Sales Representative,4,Single,1081,Upto 5k,16019,1,Y,No,13,3,3,80,0,1,3,2,1,0,0,0
RM1413,30,26-35,No,Travel_Rarely,911,Research & Development,1,2,Medical,1,1989,4,Male,76,3,1,Laboratory Technician,2,Married,3748,Upto 5k,4077,1,Y,No,13,3,3,80,0,12,6,2,12,8,1,7
RM013,31,26-35,No,Travel_Rarely,670,Research & Development,26,1,Life Sciences,1,16,1,Male,31,3,1,Research Scientist,3,Divorced,2911,Upto 5k,15170,1,Y,No,17,3,4,80,1,5,1,2,5,2,4,3
RM059,31,26-35,No,Travel_Rarely,655,Research & Development,7,4,Life Sciences,1,76,4,Male,48,3,2,Laboratory Technician,4,Divorced,5915,5k-10k,9528,3,Y,No,22,4,4,80,1,10,3,2,7,7,1,7
RM073,31,26-35,No,Travel_Rarely,1082,Research & Development,1,4,Medical,1,95,3,Male,87,3,1,Research Scientist,2,Single,2501,Upto 5k,18775,1,Y,No,17,3,2,80,0,1,4,3,1,1,1,
RM076,31,26-35,No,Travel_Rarely,746,Research & Development,8,4,Life Sciences,1,98,3,Female,61,3,2,Manufacturing Director,4,Single,4424,Upto 5k,20682,1,Y,No,23,4,4,80,0,11,2,3,11,7,1,
RM125,31,26-35,Yes,Travel_Rarely,249,Sales,6,4,Life Sciences,1,163,2,Male,76,1,2,Sales Executive,3,Married,6172,5k-10k,20739,4,Y,Yes,18,3,2,80,0,12,3,2,7,7,7,7
RM133,31,26-35,Yes,Travel_Rarely,542,Sales,20,3,Life Sciences,1,175,2,Female,71,1,2,Sales Executive,3,Married,4559,Upto 5k,24788,3,Y,Yes,11,3,3,80,1,4,2,3,2,2,2,2
RM181,31,26-35,No,Travel_Rarely,140,Research & Development,12,1,Medical,1,246,3,Female,95,3,1,Research Scientist,4,Married,3929,Upto 5k,6984,8,Y,Yes,23,4,3,80,1,7,0,3,4,2,0,2
RM225,31,26-35,No,Non-Travel,979,Research & Development,1,4,Medical,1,308,3,Male,90,1,2,Manufacturing Director,3,Married,4345,Upto 5k,4381,0,Y,No,12,3,4,80,1,6,2,3,5,4,1,4
RM246,31,26-35,No,Travel_Frequently,1327,Research & Development,3,4,Medical,1,337,2,Male,73,3,3,Research Director,3,Divorced,13675,10k-15k,13523,9,Y,No,12,3,1,80,1,9,3,3,2,2,2,2
RM260,31,26-35,Yes,Travel_Frequently,307,Research & Development,29,2,Medical,1,355,3,Male,71,2,1,Laboratory Technician,2,Single,3479,Upto 5k,11652,0,Y,No,11,3,2,80,0,6,2,4,5,4,1,4
RM267,31,26-35,No,Travel_Rarely,1463,Research & Development,23,3,Medical,1,367,2,Male,64,2,2,Healthcare Representative,4,Married,5582,5k-10k,14408,0,Y,No,21,4,2,80,1,10,2,3,9,0,7,8
RM293,31,26-35,No,Travel_Frequently,444,Sales,5,3,Marketing,1,399,4,Female,84,3,1,Sales Representative,2,Divorced,2789,Upto 5k,3909,1,Y,No,11,3,3,80,1,2,5,2,2,2,2,2
RM304,31,26-35,No,Travel_Rarely,218,Sales,7,3,Technical Degree,1,416,2,Male,100,4,2,Sales Executive,4,Married,6929,5k-10k,12241,4,Y,No,11,3,2,80,1,10,3,2,8,7,7,7
RM310,31,26-35,No,Travel_Rarely,691,Research & Development,5,4,Technical Degree,1,423,3,Male,86,3,1,Research Scientist,4,Married,4821,Upto 5k,10077,0,Y,Yes,12,3,3,80,1,6,4,3,5,2,0,3
RM311,31,26-35,No,Travel_Rarely,106,Human Resources,2,3,Human Resources,1,424,1,Male,62,2,2,Human Resources,1,Married,6410,5k-10k,17822,3,Y,No,12,3,4,80,0,9,1,3,2,2,1,0
RM313,31,26-35,No,Travel_Rarely,192,Research & Development,2,4,Life Sciences,1,426,3,Male,32,3,1,Research Scientist,4,Divorced,2695,Upto 5k,7747,0,Y,Yes,18,3,2,80,1,3,2,1,2,2,2,2
RM322,31,26-35,No,Travel_Rarely,691,Sales,7,3,Marketing,1,438,4,Male,73,3,2,Sales Executive,4,Divorced,7547,5k-10k,7143,4,Y,No,12,3,4,80,3,13,3,3,7,7,1,7
RM326,31,26-35,No,Travel_Frequently,798,Research & Development,7,2,Life Sciences,1,442,3,Female,48,2,3,Manufacturing Director,3,Married,8943,5k-10k,14034,1,Y,No,24,4,1,80,1,10,2,3,10,9,8,9
RM343,31,26-35,No,Travel_Rarely,1232,Research & Development,7,4,Medical,1,462,3,Female,39,3,3,Manufacturing Director,4,Single,7143,5k-10k,25713,1,Y,Yes,14,3,3,80,0,11,2,2,11,9,4,10
RM370,31,26-35,No,Travel_Rarely,408,Research & Development,9,4,Life Sciences,1,493,3,Male,42,2,1,Research Scientist,2,Single,2657,Upto 5k,7551,0,Y,Yes,16,3,4,80,0,3,5,3,2,2,2,2
RM395,31,26-35,No,Travel_Rarely,480,Research & Development,7,2,Medical,1,524,2,Female,31,3,2,Manufacturing Director,1,Married,4306,Upto 5k,4156,1,Y,No,12,3,2,80,1,13,5,1,13,10,3,12
RM400,31,26-35,No,Travel_Rarely,329,Research & Development,1,2,Life Sciences,1,530,4,Male,98,2,1,Laboratory Technician,1,Married,2218,Upto 5k,16193,1,Y,No,12,3,3,80,1,4,3,3,4,2,3,2
RM435,31,26-35,No,Travel_Rarely,1274,Research & Development,9,1,Life Sciences,1,581,3,Male,33,3,3,Manufacturing Director,2,Divorced,10648,10k-15k,14394,1,Y,No,25,4,4,80,1,13,6,4,13,8,0,8
RM440,31,26-35,Yes,Travel_Frequently,534,Research & Development,20,3,Life Sciences,1,587,1,Male,66,3,3,Healthcare Representative,3,Married,9824,5k-10k,22908,3,Y,No,12,3,1,80,0,12,2,3,1,0,0,0
RM451,31,26-35,No,Travel_Rarely,828,Sales,2,1,Life Sciences,1,604,2,Male,77,3,2,Sales Executive,4,Single,6582,5k-10k,8346,4,Y,Yes,13,3,3,80,0,10,2,4,6,5,0,5
RM457,31,26-35,No,Travel_Rarely,688,Sales,7,3,Life Sciences,1,613,3,Male,44,2,3,Manager,4,Divorced,11557,10k-15k,25291,9,Y,No,21,4,3,80,1,10,3,2,5,4,0,1
RM483,31,26-35,Yes,Travel_Rarely,1365,Sales,13,4,Medical,1,650,2,Male,46,3,2,Sales Executive,1,Divorced,4233,Upto 5k,11512,2,Y,No,17,3,3,80,0,9,2,1,3,1,1,2
RM485,31,26-35,No,Travel_Rarely,525,Sales,6,4,Medical,1,653,1,Male,66,4,2,Sales Executive,4,Divorced,5460,5k-10k,6219,4,Y,No,22,4,4,80,2,13,4,4,7,7,5,7
RM645,31,26-35,No,Travel_Rarely,1222,Research & Development,11,4,Life Sciences,1,895,4,Male,48,3,1,Research Scientist,4,Married,2356,Upto 5k,14871,3,Y,Yes,19,3,2,80,1,8,2,3,6,4,0,2
RM676,31,26-35,No,Travel_Rarely,154,Sales,7,4,Life Sciences,1,941,2,Male,41,2,1,Sales Representative,3,Married,2329,Upto 5k,11737,3,Y,No,15,3,2,80,0,13,2,4,7,7,5,2
RM680,31,26-35,No,Non-Travel,1188,Sales,20,2,Marketing,1,947,4,Female,45,3,2,Sales Executive,3,Married,6932,5k-10k,24406,1,Y,No,13,3,4,80,1,9,2,2,9,8,0,0
RM691,31,26-35,No,Travel_Rarely,616,Research & Development,12,3,Medical,1,961,4,Female,41,3,2,Healthcare Representative,4,Married,5855,5k-10k,17369,0,Y,Yes,11,3,3,80,2,10,2,1,9,7,8,5
RM710,31,26-35,Yes,Non-Travel,335,Research & Development,9,2,Medical,1,991,3,Male,46,2,1,Research Scientist,1,Single,2321,Upto 5k,10322,0,Y,Yes,22,4,1,80,0,4,0,3,3,2,1,2
RM727,31,26-35,No,Travel_Frequently,853,Research & Development,1,1,Life Sciences,1,1011,3,Female,96,3,2,Manufacturing Director,1,Married,4148,Upto 5k,11275,1,Y,No,12,3,3,80,1,4,1,3,4,3,0,3
RM819,31,26-35,No,Travel_Frequently,793,Sales,20,3,Life Sciences,1,1135,3,Male,67,4,1,Sales Representative,4,Married,2791,Upto 5k,21981,0,Y,No,12,3,1,80,1,3,4,3,2,2,2,2
RM832,31,26-35,Yes,Travel_Frequently,874,Research & Development,15,3,Medical,1,1160,3,Male,72,3,1,Laboratory Technician,3,Married,2610,Upto 5k,6233,1,Y,No,12,3,3,80,1,2,5,2,2,2,2,2
RM896,31,26-35,No,Travel_Rarely,1332,Research & Development,11,2,Medical,1,1251,3,Male,80,3,2,Healthcare Representative,1,Married,6833,5k-10k,17089,1,Y,Yes,12,3,4,80,0,6,2,2,6,5,0,1
RM897,31,26-35,No,Travel_Rarely,1062,Research & Development,24,3,Medical,1,1252,3,Female,96,2,2,Healthcare Representative,1,Single,6812,5k-10k,17198,1,Y,No,19,3,2,80,0,10,2,3,10,9,1,8
RM951,31,26-35,No,Non-Travel,587,Sales,2,4,Life Sciences,1,1324,4,Female,57,3,3,Sales Executive,3,Divorced,9852,5k-10k,8935,1,Y,Yes,19,3,1,80,1,10,5,2,10,8,9,6
RM953,31,26-35,Yes,Travel_Frequently,1060,Sales,1,3,Life Sciences,1,1331,4,Female,54,3,1,Sales Representative,2,Single,2302,Upto 5k,8319,1,Y,Yes,11,3,1,80,0,3,2,4,3,2,2,2
RM981,31,26-35,Yes,Travel_Frequently,703,Sales,2,3,Life Sciences,1,1379,3,Female,90,2,1,Sales Representative,4,Single,2785,Upto 5k,11882,7,Y,No,14,3,3,80,0,3,3,4,1,0,0,0
RM986,31,26-35,Yes,Travel_Rarely,330,Research & Development,22,4,Medical,1,1389,4,Male,98,3,2,Manufacturing Director,3,Married,6179,5k-10k,21057,1,Y,Yes,15,3,4,80,2,10,3,2,10,2,6,7
RM1013,31,26-35,Yes,Travel_Frequently,667,Sales,1,4,Life Sciences,1,1427,2,Female,50,1,1,Sales Representative,3,Single,1359,Upto 5k,16154,1,Y,No,12,3,2,80,0,1,3,3,1,0,0,0
RM1015,31,26-35,No,Travel_Rarely,182,Research & Development,8,5,Life Sciences,1,1430,1,Female,93,3,4,Research Director,2,Single,16422,15k+,8847,3,Y,No,11,3,3,80,0,9,3,4,3,2,1,0
RM1017,31,26-35,Yes,Travel_Rarely,202,Research & Development,8,3,Life Sciences,1,1433,1,Female,34,2,1,Research Scientist,2,Single,1261,Upto 5k,22262,1,Y,No,12,3,3,80,0,1,3,4,1,0,0,0
RM1031,31,26-35,No,Travel_Rarely,326,Sales,8,2,Life Sciences,1,1453,1,Male,31,3,3,Sales Executive,4,Divorced,10793,10k-15k,8386,1,Y,No,18,3,1,80,1,13,5,3,13,7,9,9
RM1034,31,26-35,Yes,Travel_Frequently,1445,Research & Development,1,5,Life Sciences,1,1459,3,Female,100,4,3,Manufacturing Director,2,Single,7446,5k-10k,8931,1,Y,No,11,3,1,80,0,10,2,3,10,8,4,7
RM1036,31,26-35,No,Travel_Rarely,1398,Human Resources,8,2,Medical,1,1461,4,Female,96,4,1,Human Resources,2,Single,2109,Upto 5k,24609,9,Y,No,18,3,4,80,0,8,3,3,3,2,0,2
RM1037,31,26-35,Yes,Travel_Frequently,523,Research & Development,2,3,Life Sciences,1,1464,2,Male,94,3,1,Laboratory Technician,4,Married,3722,Upto 5k,21081,6,Y,Yes,13,3,3,80,1,7,2,1,2,2,2,2
RM1086,31,26-35,Yes,Travel_Frequently,561,Research & Development,3,3,Life Sciences,1,1537,4,Female,33,3,1,Research Scientist,3,Single,4084,Upto 5k,4156,1,Y,No,12,3,1,80,0,7,2,1,7,2,7,7
RM1145,31,26-35,No,Travel_Frequently,715,Sales,2,4,Other,1,1613,4,Male,54,3,2,Sales Executive,1,Single,5332,5k-10k,21602,7,Y,No,13,3,4,80,0,10,3,3,5,2,0,3
RM1192,31,26-35,No,Travel_Rarely,1112,Sales,5,4,Life Sciences,1,1673,1,Female,67,3,2,Sales Executive,4,Married,5476,5k-10k,22589,1,Y,No,11,3,1,80,2,10,2,3,10,0,0,2
RM1228,31,26-35,No,Travel_Rarely,741,Research & Development,2,4,Life Sciences,1,1721,2,Male,69,3,1,Laboratory Technician,3,Married,3477,Upto 5k,18103,1,Y,No,14,3,4,80,1,6,2,4,5,2,0,3
RM1240,31,26-35,No,Travel_Frequently,163,Research & Development,24,1,Technical Degree,1,1736,4,Female,30,3,2,Manufacturing Director,4,Single,5238,5k-10k,6670,2,Y,No,20,4,4,80,0,9,3,2,5,4,1,4
RM1248,31,26-35,No,Travel_Rarely,1003,Sales,5,3,Technical Degree,1,1749,1,Male,51,3,2,Sales Executive,3,Married,8346,5k-10k,20943,1,Y,No,19,3,3,80,1,6,3,3,5,2,0,2
RM1258,31,26-35,Yes,Travel_Rarely,1079,Sales,16,4,Marketing,1,1761,1,Male,70,3,3,Sales Executive,3,Married,8161,5k-10k,19002,2,Y,No,13,3,1,80,3,10,2,3,1,0,0,0
RM1275,31,26-35,No,Travel_Rarely,196,Sales,29,4,Marketing,1,1784,1,Female,91,2,2,Sales Executive,4,Married,5468,5k-10k,13402,1,Y,No,14,3,1,80,2,13,3,3,12,7,5,7
RM1307,31,26-35,No,Travel_Frequently,1125,Sales,7,4,Marketing,1,1833,1,Female,68,3,3,Sales Executive,1,Married,9637,5k-10k,8277,2,Y,No,14,3,4,80,2,9,3,3,3,2,2,2
RM1313,31,26-35,Yes,Travel_Rarely,359,Human Resources,18,5,Human Resources,1,1842,4,Male,89,4,1,Human Resources,1,Married,2956,Upto 5k,21495,0,Y,No,17,3,3,80,0,2,4,3,1,0,0,0
RM1342,31,26-35,No,Travel_Rarely,311,Research & Development,20,3,Life Sciences,1,1881,2,Male,89,3,2,Laboratory Technician,3,Divorced,4197,Upto 5k,18624,1,Y,No,11,3,1,80,1,10,2,3,10,8,0,2
RM1359,31,26-35,No,Travel_Rarely,1079,Sales,10,2,Medical,1,1912,3,Female,86,3,2,Sales Executive,4,Divorced,6583,5k-10k,20115,2,Y,Yes,11,3,4,80,1,8,2,3,5,2,1,4
RM1361,31,26-35,No,Travel_Rarely,471,Research & Development,4,3,Medical,1,1916,1,Female,62,4,1,Laboratory Technician,3,Divorced,3978,Upto 5k,16031,8,Y,No,12,3,2,80,1,4,0,2,2,2,2,2
RM1383,31,26-35,No,Non-Travel,976,Research & Development,3,2,Medical,1,1948,3,Male,48,3,1,Research Scientist,1,Divorced,3065,Upto 5k,3995,1,Y,Yes,13,3,4,80,1,4,3,4,4,2,2,3
RM1390,31,26-35,No,Travel_Frequently,1125,Research & Development,1,3,Life Sciences,1,1956,4,Male,48,1,2,Research Scientist,1,Married,5003,5k-10k,5771,1,Y,No,21,4,2,80,0,10,6,3,10,8,8,7
RM1396,31,26-35,Yes,Travel_Frequently,754,Sales,26,4,Marketing,1,1967,1,Male,63,3,2,Sales Executive,4,Married,5617,5k-10k,21075,1,Y,Yes,11,3,3,80,0,10,4,3,10,7,0,8
RM1403,31,26-35,No,Travel_Rarely,1276,Research & Development,2,1,Medical,1,1974,4,Female,59,1,1,Laboratory Technician,4,Divorced,1129,Upto 5k,17536,1,Y,Yes,11,3,3,80,3,1,4,3,1,0,0,0
RM1406,31,26-35,No,Non-Travel,697,Research & Development,10,3,Medical,1,1979,3,Female,40,3,3,Research Director,3,Married,11031,10k-15k,26862,4,Y,No,20,4,3,80,1,13,2,4,11,7,4,8
RM1418,31,26-35,No,Travel_Rarely,1154,Sales,2,2,Life Sciences,1,1996,1,Male,54,3,1,Sales Representative,3,Married,3067,Upto 5k,6393,0,Y,No,19,3,3,80,1,3,1,3,2,2,1,2
RM1464,31,26-35,No,Non-Travel,325,Research & Development,5,3,Medical,1,2057,2,Male,74,3,2,Manufacturing Director,1,Single,9936,5k-10k,3787,0,Y,No,19,3,2,80,0,10,2,3,9,4,1,7
RM1464,31,26-35,No,Non-Travel,325,Research & Development,5,3,Medical,1,2057,2,Male,74,3,2,Manufacturing Director,1,Single,9936,5k-10k,3787,0,Y,No,19,3,2,80,0,10,2,3,9,4,1,7
RM006,32,26-35,No,Travel_Frequently,1005,Research & Development,2,2,Life Sciences,1,8,4,Male,79,3,1,Laboratory Technician,4,Single,3068,Upto 5k,11864,0,Y,No,13,3,3,80,0,8,2,2,7,7,3,6
RM017,32,26-35,No,Travel_Rarely,334,Research & Development,5,2,Life Sciences,1,21,1,Male,80,4,1,Research Scientist,2,Divorced,3298,Upto 5k,15053,0,Y,Yes,12,3,4,80,2,7,5,2,6,2,0,5
RM027,32,26-35,Yes,Travel_Frequently,1125,Research & Development,16,1,Life Sciences,1,33,2,Female,72,1,1,Research Scientist,1,Single,3919,Upto 5k,4681,1,Y,Yes,22,4,2,80,0,10,5,3,10,2,6,
RM061,32,26-35,No,Travel_Rarely,427,Research & Development,1,3,Medical,1,78,1,Male,33,3,2,Manufacturing Director,4,Married,6162,5k-10k,10877,1,Y,Yes,22,4,2,80,1,9,3,3,9,8,7,8
RM074,32,26-35,No,Travel_Rarely,548,Research & Development,1,3,Life Sciences,1,96,2,Male,66,3,2,Research Scientist,2,Married,6220,5k-10k,7346,1,Y,No,17,3,2,80,2,10,3,3,10,4,0,
RM095,32,26-35,No,Travel_Rarely,1093,Sales,6,4,Medical,1,125,2,Male,87,3,2,Sales Executive,3,Single,5010,5k-10k,24301,1,Y,No,16,3,1,80,0,12,0,3,11,8,5,7
RM102,32,26-35,No,Travel_Rarely,827,Research & Development,1,1,Life Sciences,1,134,4,Male,71,3,1,Research Scientist,1,Single,2956,Upto 5k,15178,1,Y,No,13,3,4,80,0,1,2,3,1,0,0,0
RM141,32,26-35,Yes,Travel_Rarely,1033,Research & Development,9,3,Medical,1,190,1,Female,41,3,1,Laboratory Technician,1,Single,4200,Upto 5k,10224,7,Y,No,22,4,1,80,0,10,2,4,5,4,0,
RM145,32,26-35,No,Travel_Frequently,689,Sales,9,2,Medical,1,195,4,Male,35,1,2,Sales Executive,4,Divorced,4668,Upto 5k,22812,0,Y,No,17,3,4,80,3,9,2,4,8,7,0,
RM155,32,26-35,No,Travel_Frequently,967,Sales,8,3,Marketing,1,207,2,Female,43,3,3,Sales Executive,4,Single,8998,5k-10k,15589,1,Y,No,14,3,4,80,0,9,2,3,9,8,3,7
RM170,32,26-35,No,Travel_Rarely,120,Research & Development,6,5,Life Sciences,1,231,3,Male,43,3,1,Research Scientist,3,Single,3038,Upto 5k,12430,3,Y,No,20,4,1,80,0,8,2,3,5,4,1,4
RM211,32,26-35,Yes,Travel_Rarely,1045,Sales,4,4,Medical,1,291,4,Male,32,1,3,Sales Executive,4,Married,10400,10k-15k,25812,1,Y,No,11,3,3,80,0,14,2,2,14,8,9,
RM239,32,26-35,No,Travel_Rarely,1401,Sales,4,2,Life Sciences,1,330,3,Female,56,3,1,Sales Representative,2,Married,3931,Upto 5k,20990,2,Y,No,11,3,1,80,1,6,5,3,4,3,1,2
RM240,32,26-35,Yes,Travel_Rarely,515,Research & Development,1,3,Life Sciences,1,331,4,Male,62,2,1,Laboratory Technician,3,Single,3730,Upto 5k,9571,0,Y,Yes,14,3,4,80,0,4,2,1,3,2,1,2
RM242,32,26-35,No,Non-Travel,976,Sales,26,4,Marketing,1,333,3,Male,100,3,2,Sales Executive,4,Married,4465,Upto 5k,12069,0,Y,No,18,3,1,80,0,4,2,3,3,2,2,2
RM261,32,26-35,No,Travel_Frequently,1311,Research & Development,7,3,Life Sciences,1,359,2,Male,100,4,1,Laboratory Technician,2,Married,2794,Upto 5k,26062,1,Y,No,20,4,3,80,0,5,3,1,5,1,0,3
RM263,32,26-35,No,Travel_Rarely,128,Research & Development,2,1,Technical Degree,1,362,4,Male,84,2,2,Laboratory Technician,1,Single,2176,Upto 5k,19737,4,Y,No,13,3,4,80,0,9,5,3,6,2,0,4
RM307,32,26-35,No,Travel_Rarely,906,Sales,7,3,Life Sciences,1,420,4,Male,91,2,2,Sales Executive,3,Married,5484,5k-10k,16985,1,Y,No,14,3,3,80,1,13,3,2,13,8,4,8
RM320,32,26-35,No,Travel_Rarely,588,Sales,8,2,Technical Degree,1,436,3,Female,65,2,2,Sales Executive,2,Married,5228,5k-10k,24624,1,Y,Yes,11,3,4,80,0,13,2,3,13,12,11,9
RM323,32,26-35,No,Travel_Rarely,1018,Research & Development,2,4,Medical,1,439,1,Female,74,4,2,Research Scientist,4,Single,5055,5k-10k,10557,7,Y,No,16,3,3,80,0,10,0,2,7,7,0,7
RM352,32,26-35,No,Travel_Rarely,1062,Research & Development,2,3,Medical,1,471,3,Female,75,3,1,Laboratory Technician,2,Married,2370,Upto 5k,3956,1,Y,No,13,3,3,80,1,8,4,3,8,0,0,7
RM470,32,26-35,Yes,Non-Travel,1474,Sales,11,4,Other,1,631,4,Male,60,4,2,Sales Executive,3,Married,4707,Upto 5k,23914,8,Y,No,12,3,4,80,0,6,2,3,4,2,1,2
RM501,32,26-35,No,Travel_Rarely,646,Research & Development,9,4,Life Sciences,1,679,1,Female,92,3,2,Research Scientist,4,Married,6322,5k-10k,18089,1,Y,Yes,12,3,4,80,1,6,2,2,6,4,0,5
RM528,32,26-35,No,Travel_Rarely,929,Sales,10,3,Marketing,1,722,4,Male,55,3,2,Sales Executive,4,Single,5396,5k-10k,21703,1,Y,No,12,3,4,80,0,10,2,2,10,7,0,8
RM532,32,26-35,No,Travel_Rarely,1018,Research & Development,3,2,Life Sciences,1,727,3,Female,39,3,3,Research Director,4,Single,11159,10k-15k,19373,3,Y,No,15,3,4,80,0,10,6,3,7,7,7,7
RM559,32,26-35,No,Travel_Frequently,430,Research & Development,24,4,Life Sciences,1,772,1,Male,80,3,2,Laboratory Technician,4,Married,5309,5k-10k,21146,1,Y,No,15,3,4,80,2,10,2,3,10,8,4,7
RM601,32,26-35,No,Travel_Rarely,859,Research & Development,4,3,Life Sciences,1,830,3,Female,98,2,2,Manufacturing Director,3,Married,6162,5k-10k,19124,1,Y,No,12,3,3,80,1,14,3,3,14,13,6,8
RM623,32,26-35,No,Travel_Rarely,117,Sales,13,4,Life Sciences,1,859,2,Male,73,3,2,Sales Executive,4,Divorced,4403,Upto 5k,9250,2,Y,No,11,3,3,80,1,8,3,2,5,2,0,3
RM627,32,26-35,No,Travel_Rarely,638,Research & Development,8,2,Medical,1,865,3,Female,91,4,2,Research Scientist,3,Married,5175,5k-10k,22162,5,Y,No,12,3,3,80,1,9,3,2,5,3,1,3
RM638,32,26-35,No,Non-Travel,300,Research & Development,1,3,Life Sciences,1,882,4,Male,61,3,1,Laboratory Technician,4,Divorced,2314,Upto 5k,9148,0,Y,No,12,3,2,80,1,4,2,3,3,0,0,2
RM642,32,26-35,No,Travel_Frequently,379,Sales,5,2,Life Sciences,1,889,2,Male,48,3,2,Sales Executive,2,Married,6524,5k-10k,8891,1,Y,No,14,3,4,80,1,10,3,3,10,8,5,3
RM657,32,26-35,Yes,Travel_Rarely,374,Research & Development,25,4,Life Sciences,1,911,1,Male,87,3,1,Laboratory Technician,4,Single,2795,Upto 5k,18016,1,Y,Yes,24,4,3,80,0,1,2,1,1,0,0,1
RM683,32,26-35,No,Non-Travel,1184,Research & Development,1,3,Life Sciences,1,951,3,Female,70,2,1,Laboratory Technician,2,Married,2332,Upto 5k,3974,6,Y,No,20,4,3,80,0,5,3,3,3,0,0,2
RM693,32,26-35,No,Travel_Rarely,498,Research & Development,3,4,Medical,1,966,3,Female,93,3,2,Manufacturing Director,1,Married,6725,5k-10k,13554,1,Y,No,12,3,3,80,1,8,2,4,8,7,6,3
RM757,32,26-35,No,Non-Travel,1109,Research & Development,29,4,Medical,1,1046,4,Female,69,3,1,Laboratory Technician,3,Single,4025,Upto 5k,11135,9,Y,No,12,3,2,80,0,10,2,3,8,7,7,7
RM851,32,26-35,No,Non-Travel,862,Sales,2,1,Life Sciences,1,1190,3,Female,76,3,1,Sales Representative,1,Divorced,2827,Upto 5k,14947,1,Y,No,12,3,3,80,3,1,3,3,1,0,0,0
RM881,32,26-35,No,Travel_Frequently,116,Research & Development,13,3,Other,1,1234,3,Female,77,2,1,Laboratory Technician,2,Married,2743,Upto 5k,7331,1,Y,No,20,4,3,80,1,2,2,3,2,2,2,2
RM882,32,26-35,No,Travel_Frequently,1316,Research & Development,2,2,Life Sciences,1,1235,4,Female,38,3,2,Research Scientist,3,Single,4998,Upto 5k,2338,4,Y,Yes,14,3,4,80,0,10,2,3,8,7,0,7
RM936,32,26-35,No,Travel_Rarely,604,Sales,8,3,Medical,1,1304,3,Male,56,4,2,Sales Executive,4,Married,6209,5k-10k,11693,1,Y,No,15,3,3,80,2,10,4,4,10,7,0,8
RM940,32,26-35,Yes,Travel_Rarely,1089,Research & Development,7,2,Life Sciences,1,1309,4,Male,79,3,2,Laboratory Technician,3,Married,4883,Upto 5k,22845,1,Y,No,18,3,1,80,1,10,3,3,10,4,1,1
RM992,32,26-35,No,Travel_Rarely,499,Sales,2,1,Marketing,1,1396,3,Male,36,3,2,Sales Executive,2,Married,4078,Upto 5k,20497,0,Y,Yes,13,3,1,80,3,4,3,2,3,2,1,2
RM1027,32,26-35,No,Travel_Rarely,601,Sales,7,5,Marketing,1,1446,4,Male,97,3,2,Sales Executive,4,Married,9204,5k-10k,23343,4,Y,No,12,3,3,80,1,7,3,2,4,3,0,3
RM1076,32,26-35,No,Travel_Rarely,495,Research & Development,10,3,Medical,1,1516,3,Male,64,3,3,Manager,4,Single,11244,10k-15k,21072,2,Y,No,25,4,2,80,0,10,5,4,5,2,0,0
RM1102,32,26-35,No,Travel_Rarely,824,Research & Development,5,2,Life Sciences,1,1555,4,Female,67,2,2,Research Scientist,2,Married,5878,5k-10k,15624,3,Y,No,12,3,1,80,1,12,2,3,7,1,2,5
RM1114,32,26-35,No,Non-Travel,1200,Research & Development,1,4,Technical Degree,1,1574,4,Male,62,3,2,Research Scientist,1,Married,4087,Upto 5k,25174,4,Y,No,14,3,2,80,1,9,3,2,6,5,1,2
RM1140,32,26-35,No,Travel_Rarely,634,Research & Development,5,4,Other,1,1607,2,Female,35,4,1,Research Scientist,4,Married,3312,Upto 5k,18783,3,Y,No,17,3,4,80,2,6,3,3,3,2,0,2
RM1191,32,26-35,No,Travel_Rarely,977,Research & Development,2,3,Medical,1,1671,4,Male,45,3,2,Research Scientist,2,Divorced,5470,5k-10k,25518,0,Y,No,13,3,3,80,2,10,4,2,9,5,1,6
RM1206,32,26-35,Yes,Travel_Rarely,1259,Research & Development,2,4,Life Sciences,1,1692,4,Male,95,3,1,Laboratory Technician,2,Single,1393,Upto 5k,24852,1,Y,No,12,3,1,80,0,1,2,3,1,0,0,0
RM1227,32,26-35,No,Travel_Frequently,585,Research & Development,10,3,Life Sciences,1,1720,1,Male,56,3,1,Research Scientist,3,Married,3433,Upto 5k,17360,6,Y,No,13,3,1,80,1,10,3,2,5,2,1,3
RM1238,32,26-35,Yes,Travel_Rarely,964,Sales,1,2,Life Sciences,1,1734,1,Male,34,1,2,Sales Executive,2,Single,6735,5k-10k,12147,6,Y,No,15,3,2,80,0,10,2,3,0,0,0,0
RM1242,32,26-35,No,Travel_Rarely,371,Sales,19,3,Life Sciences,1,1739,4,Male,80,1,3,Sales Executive,3,Married,9610,5k-10k,3840,3,Y,No,13,3,3,80,1,10,2,1,4,3,0,2
RM1261,32,26-35,No,Non-Travel,953,Research & Development,5,4,Technical Degree,1,1764,2,Male,65,3,1,Research Scientist,2,Single,2718,Upto 5k,17674,2,Y,No,14,3,2,80,0,12,3,3,7,7,0,7
RM1320,32,26-35,No,Travel_Frequently,1318,Sales,10,4,Marketing,1,1853,4,Male,79,3,2,Sales Executive,4,Single,4648,Upto 5k,26075,8,Y,No,13,3,3,80,0,4,2,4,0,0,0,0
RM1327,32,26-35,Yes,Travel_Rarely,414,Sales,2,4,Marketing,1,1862,3,Male,82,2,2,Sales Executive,2,Single,9907,5k-10k,26186,7,Y,Yes,12,3,3,80,0,7,3,2,2,2,2,2
RM1376,32,26-35,Yes,Travel_Frequently,238,Research & Development,5,2,Life Sciences,1,1939,1,Female,47,4,1,Research Scientist,3,Single,2432,Upto 5k,15318,3,Y,Yes,14,3,1,80,0,8,2,3,4,1,0,3
RM1389,32,26-35,No,Non-Travel,1146,Research & Development,15,4,Medical,1,1955,3,Female,34,3,2,Healthcare Representative,4,Divorced,6667,5k-10k,16542,5,Y,No,18,3,2,80,1,9,6,3,5,1,1,2
RM1395,32,26-35,No,Travel_Rarely,1373,Research & Development,5,4,Life Sciences,1,1966,4,Male,56,2,2,Manufacturing Director,4,Single,9679,5k-10k,10138,8,Y,No,24,4,2,80,0,8,1,3,1,0,0,0
RM1427,32,26-35,No,Travel_Rarely,267,Research & Development,29,4,Life Sciences,1,2010,3,Female,49,2,1,Laboratory Technician,2,Single,2837,Upto 5k,15919,1,Y,No,13,3,3,80,0,6,3,3,6,2,4,1
RM1429,32,26-35,No,Travel_Rarely,234,Sales,1,4,Medical,1,2013,2,Male,68,2,1,Sales Representative,2,Married,2269,Upto 5k,18024,0,Y,No,14,3,2,80,1,3,2,3,2,2,2,2
RM1432,32,26-35,No,Travel_Rarely,801,Sales,1,4,Marketing,1,2016,3,Female,48,3,3,Sales Executive,4,Married,10422,10k-15k,24032,1,Y,No,19,3,3,80,2,14,3,3,14,10,5,7
RM1450,32,26-35,No,Travel_Rarely,529,Research & Development,2,3,Technical Degree,1,2038,4,Male,78,3,1,Research Scientist,1,Single,2439,Upto 5k,11288,1,Y,No,14,3,4,80,0,4,4,3,4,2,1,2
RM004,33,26-35,No,Travel_Frequently,1392,Research & Development,3,4,Life Sciences,1,5,4,Female,56,3,1,Research Scientist,3,Married,2909,Upto 5k,23159,1,Y,Yes,11,3,3,80,0,8,3,3,8,7,3,0
RM031,33,26-35,No,Travel_Rarely,924,Research & Development,2,3,Medical,1,39,3,Male,78,3,1,Laboratory Technician,4,Single,2496,Upto 5k,6670,4,Y,No,11,3,4,80,0,7,3,3,1,1,0,
RM040,33,26-35,No,Travel_Frequently,1141,Sales,1,3,Life Sciences,1,52,3,Female,42,4,2,Sales Executive,1,Married,5376,5k-10k,3193,2,Y,No,19,3,1,80,2,10,3,3,5,3,1,3
RM056,33,26-35,No,Travel_Frequently,515,Research & Development,1,2,Life Sciences,1,73,1,Female,98,3,3,Research Director,4,Single,13458,10k-15k,15146,1,Y,Yes,12,3,3,80,0,15,1,3,15,14,8,12
RM122,33,26-35,No,Non-Travel,750,Sales,22,2,Marketing,1,160,3,Male,95,3,2,Sales Executive,2,Married,6146,5k-10k,15480,0,Y,No,13,3,1,80,1,8,2,4,7,7,0,7
RM177,33,26-35,No,Travel_Rarely,134,Research & Development,2,3,Life Sciences,1,242,3,Male,90,3,1,Research Scientist,4,Single,2500,Upto 5k,10515,0,Y,No,14,3,1,80,0,4,2,4,3,1,0,2
RM186,33,26-35,No,Travel_Rarely,931,Research & Development,14,3,Medical,1,252,4,Female,72,3,1,Research Scientist,2,Married,2756,Upto 5k,4673,1,Y,No,13,3,4,80,1,8,5,3,8,7,1,6
RM222,33,26-35,No,Travel_Rarely,147,Research & Development,4,4,Medical,1,305,3,Female,47,2,1,Research Scientist,2,Married,2622,Upto 5k,13248,6,Y,No,21,4,4,80,0,7,3,3,3,2,1,1
RM235,33,26-35,Yes,Travel_Rarely,813,Research & Development,14,3,Medical,1,325,3,Male,58,3,1,Laboratory Technician,4,Married,2436,Upto 5k,22149,5,Y,Yes,13,3,3,80,1,8,2,1,5,4,0,4
RM237,33,26-35,Yes,Travel_Rarely,465,Research & Development,2,2,Life Sciences,1,328,1,Female,39,3,1,Laboratory Technician,1,Married,2707,Upto 5k,21509,7,Y,No,20,4,1,80,0,13,3,4,9,7,1,7
RM247,33,26-35,No,Travel_Rarely,832,Research & Development,5,4,Life Sciences,1,338,3,Female,63,2,1,Research Scientist,4,Married,2911,Upto 5k,14776,1,Y,No,13,3,3,80,1,2,2,2,2,2,0,2
RM314,33,26-35,No,Travel_Frequently,553,Research & Development,5,4,Life Sciences,1,428,4,Female,74,3,3,Manager,2,Married,11878,10k-15k,23364,6,Y,No,11,3,2,80,2,12,2,3,10,6,8,8
RM329,33,26-35,No,Travel_Frequently,508,Sales,10,3,Marketing,1,446,2,Male,46,2,2,Sales Executive,4,Single,4682,Upto 5k,4317,3,Y,No,14,3,3,80,0,9,6,2,7,7,0,1
RM364,33,26-35,Yes,Travel_Rarely,350,Sales,5,3,Marketing,1,485,4,Female,34,3,1,Sales Representative,3,Single,2851,Upto 5k,9150,1,Y,Yes,13,3,2,80,0,1,2,3,1,0,0,0
RM436,33,26-35,Yes,Travel_Rarely,1277,Research & Development,15,1,Medical,1,582,2,Male,56,3,3,Manager,3,Married,13610,10k-15k,24619,7,Y,Yes,12,3,4,80,0,15,2,4,7,6,7,7
RM437,33,26-35,Yes,Travel_Rarely,587,Research & Development,10,1,Medical,1,584,1,Male,38,1,1,Laboratory Technician,4,Divorced,3408,Upto 5k,6705,7,Y,No,13,3,1,80,3,8,2,3,4,3,1,3
RM456,33,26-35,No,Travel_Rarely,922,Research & Development,1,5,Medical,1,612,1,Female,95,4,4,Research Director,3,Divorced,16184,15k+,22578,4,Y,No,19,3,3,80,1,10,2,3,6,1,0,5
RM500,33,26-35,No,Travel_Rarely,1216,Sales,8,4,Marketing,1,677,3,Male,39,3,2,Sales Executive,3,Divorced,7104,5k-10k,20431,0,Y,No,12,3,4,80,0,6,3,3,5,0,1,2
RM510,33,26-35,No,Travel_Frequently,1296,Research & Development,6,3,Life Sciences,1,692,3,Male,30,3,2,Healthcare Representative,4,Divorced,7725,5k-10k,5335,3,Y,No,23,4,3,80,1,15,2,1,13,11,4,7
RM515,33,26-35,Yes,Travel_Frequently,1076,Research & Development,3,3,Life Sciences,1,702,1,Male,70,3,1,Research Scientist,1,Single,3348,Upto 5k,3164,1,Y,Yes,11,3,1,80,0,10,3,3,10,8,9,7
RM563,33,26-35,Yes,Travel_Rarely,527,Research & Development,1,4,Other,1,780,4,Male,63,3,1,Research Scientist,4,Single,2686,Upto 5k,5207,1,Y,Yes,13,3,3,80,0,10,2,2,10,9,7,8
RM591,33,26-35,No,Travel_Rarely,213,Research & Development,7,3,Medical,1,817,3,Male,49,3,3,Research Director,3,Married,11691,10k-15k,25995,0,Y,No,11,3,4,80,0,14,3,4,13,9,3,7
RM592,33,26-35,Yes,Travel_Rarely,118,Sales,16,3,Marketing,1,819,1,Female,69,3,2,Sales Executive,1,Single,5324,5k-10k,26507,5,Y,No,15,3,3,80,0,6,3,3,3,2,0,2
RM620,33,26-35,No,Travel_Rarely,586,Sales,1,3,Medical,1,855,1,Male,48,4,2,Sales Executive,1,Divorced,4037,Upto 5k,21816,1,Y,No,22,4,1,80,1,9,5,3,9,8,0,8
RM656,33,26-35,No,Travel_Rarely,1075,Human Resources,3,2,Human Resources,1,910,4,Male,57,3,1,Human Resources,2,Divorced,2277,Upto 5k,22650,3,Y,Yes,11,3,3,80,1,7,4,4,4,3,0,3
RM674,33,26-35,No,Travel_Rarely,1198,Research & Development,1,4,Other,1,939,3,Male,100,2,1,Research Scientist,1,Single,2799,Upto 5k,3339,3,Y,Yes,11,3,2,80,0,6,1,3,3,2,0,2
RM695,33,26-35,No,Travel_Rarely,1069,Research & Development,1,3,Life Sciences,1,969,2,Female,42,2,2,Healthcare Representative,4,Single,6949,5k-10k,12291,0,Y,No,14,3,1,80,0,6,3,3,5,0,1,4
RM711,33,26-35,No,Non-Travel,722,Sales,17,3,Life Sciences,1,992,4,Male,38,3,4,Manager,3,Single,17444,15k+,20489,1,Y,No,11,3,4,80,0,10,2,3,10,8,6,0
RM713,33,26-35,No,Travel_Rarely,461,Research & Development,13,1,Life Sciences,1,995,2,Female,53,3,1,Research Scientist,4,Single,3452,Upto 5k,17241,3,Y,No,18,3,1,80,0,5,4,3,3,2,0,2
RM716,33,26-35,No,Travel_Frequently,827,Research & Development,1,4,Other,1,998,3,Female,84,4,2,Healthcare Representative,2,Married,5488,5k-10k,20161,1,Y,Yes,13,3,1,80,1,6,2,3,6,5,1,2
RM755,33,26-35,No,Non-Travel,1038,Sales,8,1,Life Sciences,1,1044,2,Female,88,2,1,Sales Representative,4,Single,2342,Upto 5k,21437,0,Y,No,19,3,4,80,0,3,2,2,2,2,2,2
RM791,33,26-35,No,Travel_Rarely,654,Research & Development,5,3,Life Sciences,1,1099,4,Male,34,2,3,Healthcare Representative,4,Divorced,7119,5k-10k,21214,4,Y,No,15,3,3,80,1,9,2,3,3,2,1,2
RM793,33,26-35,Yes,Travel_Frequently,827,Research & Development,29,4,Medical,1,1101,1,Female,54,2,2,Research Scientist,3,Single,4508,Upto 5k,3129,1,Y,No,22,4,2,80,0,14,4,3,13,7,3,8
RM799,33,26-35,Yes,Travel_Rarely,1017,Research & Development,25,3,Medical,1,1108,1,Male,55,2,1,Research Scientist,2,Single,2313,Upto 5k,2993,4,Y,Yes,20,4,2,80,0,5,0,3,2,2,2,2
RM803,33,26-35,No,Travel_Frequently,970,Sales,7,3,Life Sciences,1,1114,4,Female,30,3,2,Sales Executive,2,Married,4302,Upto 5k,13401,0,Y,No,17,3,3,80,1,4,3,3,3,2,0,2
RM830,33,26-35,Yes,Travel_Rarely,603,Sales,9,4,Marketing,1,1157,1,Female,77,3,2,Sales Executive,1,Single,8224,5k-10k,18385,0,Y,Yes,17,3,1,80,0,6,3,3,5,2,0,3
RM864,33,26-35,No,Travel_Rarely,147,Human Resources,2,3,Human Resources,1,1207,2,Male,99,3,1,Human Resources,3,Married,3600,Upto 5k,8429,1,Y,No,13,3,4,80,1,5,2,3,5,4,1,4
RM873,33,26-35,No,Travel_Frequently,1146,Sales,25,3,Medical,1,1220,2,Female,82,3,2,Sales Executive,3,Married,4539,Upto 5k,4905,1,Y,No,12,3,1,80,1,10,3,2,10,7,0,1
RM884,33,26-35,No,Travel_Rarely,117,Research & Development,9,3,Medical,1,1238,1,Male,60,3,1,Research Scientist,4,Married,2781,Upto 5k,6311,0,Y,No,13,3,2,80,1,15,5,3,14,10,4,10
RM909,33,26-35,No,Travel_Rarely,536,Sales,10,5,Marketing,1,1268,4,Male,82,4,3,Sales Executive,3,Divorced,8380,5k-10k,21708,0,Y,Yes,14,3,4,80,2,10,3,3,9,8,0,8
RM991,33,26-35,No,Travel_Frequently,1111,Sales,5,1,Life Sciences,1,1395,2,Male,61,3,2,Sales Executive,4,Married,9998,5k-10k,19293,6,Y,No,13,3,1,80,0,8,2,4,5,4,1,2
RM1048,33,26-35,No,Travel_Frequently,430,Sales,7,3,Medical,1,1477,4,Male,54,3,2,Sales Executive,1,Married,4373,Upto 5k,17456,0,Y,No,14,3,1,80,2,5,2,3,4,3,0,3
RM1067,33,26-35,No,Travel_Rarely,1099,Research & Development,4,4,Medical,1,1502,1,Female,82,2,1,Laboratory Technician,2,Married,3838,Upto 5k,8192,8,Y,No,11,3,4,80,0,8,5,3,5,4,0,2
RM1075,33,26-35,No,Travel_Rarely,516,Research & Development,8,5,Life Sciences,1,1515,4,Male,69,3,2,Healthcare Representative,3,Single,6388,5k-10k,22049,2,Y,Yes,17,3,1,80,0,14,6,3,0,0,0,0
RM1092,33,26-35,No,Travel_Rarely,575,Research & Development,25,3,Life Sciences,1,1545,4,Male,44,2,2,Manufacturing Director,2,Single,4320,Upto 5k,24152,1,Y,No,13,3,4,80,0,5,2,3,5,3,0,2
RM1096,33,26-35,No,Travel_Rarely,589,Research & Development,28,4,Life Sciences,1,1549,2,Male,79,3,2,Laboratory Technician,3,Married,5207,5k-10k,22949,1,Y,Yes,12,3,2,80,1,15,3,3,15,14,5,7
RM1106,33,26-35,No,Travel_Rarely,1242,Sales,8,4,Life Sciences,1,1560,1,Male,46,3,2,Sales Executive,1,Married,6392,5k-10k,10589,2,Y,No,13,3,4,80,1,8,6,1,2,2,2,2
RM1190,33,26-35,No,Travel_Rarely,392,Sales,2,4,Medical,1,1670,4,Male,93,3,2,Sales Executive,4,Divorced,5505,5k-10k,3921,1,Y,No,14,3,3,80,2,6,5,3,6,2,0,4
RM1199,33,26-35,No,Non-Travel,530,Sales,16,3,Life Sciences,1,1681,3,Female,36,3,2,Sales Executive,4,Divorced,5368,5k-10k,16130,1,Y,Yes,25,4,3,80,1,7,2,3,6,5,1,2
RM1211,33,26-35,No,Travel_Rarely,267,Research & Development,21,3,Medical,1,1698,2,Male,79,4,1,Laboratory Technician,2,Married,2028,Upto 5k,13637,1,Y,No,18,3,4,80,3,14,6,3,14,11,2,13
RM1254,33,26-35,No,Non-Travel,1283,Sales,2,3,Marketing,1,1756,4,Female,62,3,2,Sales Executive,2,Single,5147,5k-10k,10697,8,Y,No,15,3,4,80,0,13,2,2,11,7,1,7
RM1256,33,26-35,Yes,Travel_Rarely,211,Sales,16,3,Life Sciences,1,1758,1,Female,74,3,3,Sales Executive,1,Single,8564,5k-10k,10092,2,Y,Yes,20,4,3,80,0,11,2,2,0,0,0,0
RM1266,33,26-35,No,Non-Travel,775,Research & Development,4,3,Technical Degree,1,1771,4,Male,90,3,2,Research Scientist,2,Divorced,3055,Upto 5k,6194,5,Y,No,15,3,4,80,2,11,2,2,9,8,1,7
RM1283,33,26-35,No,Travel_Rarely,867,Research & Development,8,4,Life Sciences,1,1798,4,Male,90,4,1,Research Scientist,1,Married,3143,Upto 5k,6076,6,Y,No,19,3,2,80,1,14,1,3,10,8,7,6
RM1364,33,26-35,No,Travel_Rarely,217,Sales,10,4,Marketing,1,1924,2,Male,43,3,2,Sales Executive,3,Single,5487,5k-10k,10410,1,Y,No,14,3,2,80,0,10,2,2,10,4,0,9
RM1399,33,26-35,No,Travel_Frequently,1303,Research & Development,7,2,Life Sciences,1,1970,4,Male,36,3,2,Healthcare Representative,3,Divorced,5968,5k-10k,18079,1,Y,No,20,4,3,80,3,9,2,3,9,7,2,8
RM1416,33,26-35,No,Non-Travel,1313,Research & Development,1,2,Medical,1,1994,2,Male,59,2,1,Laboratory Technician,3,Divorced,2008,Upto 5k,20439,1,Y,No,12,3,3,80,3,1,2,2,1,1,0,0
RM1426,33,26-35,No,Travel_Rarely,501,Research & Development,15,2,Medical,1,2009,2,Female,95,3,2,Healthcare Representative,4,Married,4878,Upto 5k,21653,0,Y,Yes,13,3,1,80,1,10,6,3,9,7,8,1
RM014,34,26-35,No,TravelRarely,1346,Research & Development,19,2,Medical,1,18,2,Male,93,3,1,Laboratory Technician,4,Divorced,2661,Upto 5k,8758,0,Y,No,11,3,3,80,1,3,2,3,2,2,1,2
RM023,34,26-35,No,TravelRarely,419,Research & Development,7,4,Life Sciences,1,28,1,Female,53,3,3,Research Director,2,Single,11994,10k-15k,21293,0,Y,No,11,3,3,80,0,13,4,3,12,6,2,
RM025,34,26-35,Yes,Travel_Rarely,699,Research & Development,6,1,Medical,1,31,2,Male,83,3,1,Research Scientist,1,Single,2960,Upto 5k,17102,2,Y,No,11,3,3,80,0,8,2,3,4,2,1,
RM047,34,26-35,No,Non-Travel,1065,Sales,23,4,Marketing,1,60,2,Male,72,3,2,Sales Executive,3,Single,4568,Upto 5k,10034,0,Y,No,20,4,3,80,0,10,2,3,9,5,8,7
RM085,34,26-35,No,Travel_Rarely,1153,Research & Development,1,2,Medical,1,110,1,Male,94,3,2,Manufacturing Director,2,Married,4325,Upto 5k,17736,1,Y,No,15,3,3,80,0,5,2,3,5,2,1,3
RM104,34,26-35,No,Travel_Rarely,665,Research & Development,6,4,Other,1,138,1,Female,41,3,2,Research Scientist,3,Single,4809,Upto 5k,12482,1,Y,No,14,3,3,80,0,16,3,3,16,13,2,10
RM112,34,26-35,Yes,Travel_Frequently,658,Research & Development,7,3,Life Sciences,1,147,1,Male,66,1,2,Laboratory Technician,3,Single,6074,5k-10k,22887,1,Y,Yes,24,4,4,80,0,9,3,3,9,7,0,6
RM115,34,26-35,No,Travel_Rarely,1031,Research & Development,6,4,Life Sciences,1,151,3,Female,45,2,2,Research Scientist,2,Divorced,4505,Upto 5k,15000,6,Y,No,15,3,3,80,1,12,3,3,1,0,0,0
RM117,34,26-35,No,Travel_Rarely,1354,Research & Development,5,3,Medical,1,153,3,Female,45,2,3,Manager,1,Single,11631,10k-15k,5615,2,Y,No,12,3,4,80,0,14,6,3,11,10,5,8
RM160,34,26-35,No,Travel_Frequently,303,Sales,2,4,Marketing,1,216,3,Female,75,3,1,Sales Representative,3,Married,2231,Upto 5k,11314,6,Y,No,18,3,4,80,1,6,3,3,4,3,1,2
RM182,34,26-35,No,Travel_Rarely,629,Research & Development,27,2,Medical,1,247,4,Female,95,3,1,Research Scientist,2,Single,2311,Upto 5k,5711,2,Y,No,15,3,4,80,0,9,3,3,3,2,1,2
RM189,34,26-35,No,Travel_Frequently,1069,Research & Development,2,1,Life Sciences,1,256,4,Male,45,2,2,Manufacturing Director,3,Married,9547,5k-10k,14074,1,Y,No,17,3,3,80,0,10,2,2,10,9,1,9
RM203,34,26-35,No,Travel_Frequently,878,Research & Development,10,4,Medical,1,277,4,Male,43,3,1,Research Scientist,3,Divorced,3815,Upto 5k,5972,1,Y,Yes,17,3,4,80,1,5,4,4,5,3,2,0
RM248,34,26-35,No,Travel_Rarely,470,Research & Development,2,4,Life Sciences,1,339,4,Male,84,2,2,Manufacturing Director,1,Married,5957,5k-10k,23687,6,Y,No,13,3,2,80,1,13,3,3,11,9,5,9
RM379,34,26-35,Yes,Non-Travel,1362,Sales,19,3,Marketing,1,502,1,Male,67,4,2,Sales Executive,4,Single,5304,5k-10k,4652,8,Y,Yes,13,3,2,80,0,9,3,2,5,2,0,4
RM394,34,26-35,No,Non-Travel,1381,Sales,4,4,Marketing,1,523,3,Female,72,3,2,Sales Executive,3,Married,6538,5k-10k,12740,9,Y,No,15,3,1,80,1,6,3,3,3,2,1,2
RM416,34,26-35,Yes,Travel_Frequently,296,Sales,6,2,Marketing,1,555,4,Female,33,1,1,Sales Representative,3,Divorced,2351,Upto 5k,12253,0,Y,No,16,3,4,80,1,3,3,2,2,2,1,0
RM433,34,26-35,No,Travel_Rarely,1303,Research & Development,2,4,Life Sciences,1,579,4,Male,62,2,1,Research Scientist,3,Divorced,2768,Upto 5k,8416,3,Y,No,12,3,3,80,1,14,3,3,7,3,5,7
RM441,34,26-35,Yes,Travel_Frequently,988,Human Resources,23,3,Human Resources,1,590,2,Female,43,3,3,Human Resources,1,Divorced,9950,5k-10k,11533,9,Y,Yes,15,3,3,80,3,11,2,3,3,2,0,2
RM463,34,26-35,No,Travel_Rarely,258,Sales,21,4,Life Sciences,1,621,4,Male,74,4,2,Sales Executive,4,Single,5337,5k-10k,19921,1,Y,No,12,3,4,80,0,10,3,3,10,7,5,7
RM482,34,26-35,No,Travel_Rarely,254,Research & Development,1,2,Life Sciences,1,649,2,Male,83,2,1,Research Scientist,4,Married,3622,Upto 5k,22794,1,Y,Yes,13,3,4,80,1,6,3,3,6,5,1,3
RM495,34,26-35,No,Travel_Rarely,204,Sales,14,3,Technical Degree,1,666,3,Female,31,3,1,Sales Representative,3,Divorced,2579,Upto 5k,2912,1,Y,Yes,18,3,4,80,2,8,3,3,8,2,0,6
RM504,34,26-35,No,Travel_Rarely,1397,Research & Development,1,5,Life Sciences,1,683,2,Male,42,3,1,Research Scientist,4,Married,2691,Upto 5k,7660,1,Y,No,12,3,4,80,1,10,4,2,10,9,8,8
RM525,34,26-35,No,Travel_Rarely,1442,Research & Development,9,3,Medical,1,717,4,Female,46,2,3,Healthcare Representative,2,Single,8621,5k-10k,17654,1,Y,No,14,3,2,80,0,9,3,4,8,7,7,7
RM550,34,26-35,No,Travel_Rarely,970,Research & Development,8,2,Medical,1,757,2,Female,96,3,2,Healthcare Representative,3,Single,6142,5k-10k,7360,3,Y,No,11,3,4,80,0,10,2,3,5,1,4,3
RM561,34,26-35,No,Travel_Rarely,167,Research & Development,8,5,Life Sciences,1,775,2,Female,32,3,2,Manufacturing Director,1,Divorced,5121,5k-10k,4187,3,Y,No,14,3,3,80,1,7,3,3,0,0,0,0
RM568,34,26-35,No,Travel_Rarely,304,Sales,2,3,Other,1,786,4,Male,60,3,2,Sales Executive,4,Single,6274,5k-10k,18686,1,Y,No,22,4,3,80,0,6,5,3,6,5,1,4
RM575,34,26-35,No,Travel_Rarely,182,Research & Development,1,4,Life Sciences,1,797,2,Female,72,4,1,Research Scientist,4,Single,3280,Upto 5k,13551,2,Y,No,16,3,3,80,0,10,2,3,4,2,1,3
RM580,34,26-35,No,Travel_Rarely,121,Research & Development,2,4,Medical,1,804,3,Female,86,2,1,Research Scientist,1,Single,4381,Upto 5k,7530,1,Y,No,11,3,3,80,0,6,3,3,6,5,1,3
RM584,34,26-35,No,Travel_Rarely,1111,Sales,8,2,Life Sciences,1,808,3,Female,93,3,2,Sales Executive,1,Married,6500,5k-10k,13305,5,Y,No,17,3,2,80,1,6,1,3,3,2,1,2
RM607,34,26-35,No,Travel_Frequently,702,Research & Development,16,4,Life Sciences,1,838,3,Female,100,2,1,Research Scientist,4,Single,2553,Upto 5k,8306,1,Y,No,16,3,3,80,0,6,3,3,5,2,1,3
RM614,34,26-35,No,Travel_Rarely,829,Human Resources,3,2,Human Resources,1,847,3,Male,88,3,1,Human Resources,4,Married,3737,Upto 5k,2243,0,Y,No,19,3,3,80,1,4,1,1,3,2,0,2
RM672,34,26-35,No,Travel_Rarely,546,Research & Development,10,3,Life Sciences,1,934,2,Male,83,3,1,Laboratory Technician,2,Divorced,2008,Upto 5k,6896,1,Y,No,14,3,2,80,2,1,3,3,1,0,1,0
RM758,34,26-35,No,Travel_Rarely,216,Sales,1,4,Marketing,1,1047,2,Male,75,4,2,Sales Executive,4,Divorced,9725,5k-10k,12278,0,Y,No,11,3,4,80,1,16,2,2,15,1,0,9
RM764,34,26-35,No,Travel_Rarely,1333,Sales,10,4,Life Sciences,1,1055,3,Female,87,3,1,Sales Representative,3,Married,2220,Upto 5k,18410,1,Y,Yes,19,3,4,80,1,1,2,3,1,1,0,0
RM795,34,26-35,No,Travel_Frequently,618,Research & Development,3,1,Life Sciences,1,1103,1,Male,45,3,2,Healthcare Representative,4,Single,7756,5k-10k,22266,0,Y,No,17,3,3,80,0,7,1,2,6,2,0,4
RM804,34,26-35,No,Non-Travel,697,Research & Development,3,4,Life Sciences,1,1115,3,Male,40,2,1,Research Scientist,4,Married,2979,Upto 5k,22478,3,Y,No,17,3,4,80,3,6,2,3,0,0,0,0
RM823,34,26-35,No,Travel_Frequently,1003,Research & Development,2,2,Life Sciences,1,1140,4,Male,95,3,2,Manufacturing Director,3,Single,4033,Upto 5k,15834,2,Y,No,11,3,4,80,0,5,3,2,3,2,0,2
RM835,34,26-35,No,Travel_Rarely,1400,Sales,9,1,Life Sciences,1,1163,2,Female,70,3,2,Sales Executive,3,Married,5714,5k-10k,5829,1,Y,No,20,4,1,80,0,6,3,2,6,5,1,3
RM848,34,26-35,No,Travel_Frequently,669,Research & Development,1,3,Medical,1,1184,4,Male,97,2,2,Healthcare Representative,1,Single,5343,5k-10k,25755,0,Y,No,20,4,3,80,0,14,3,3,13,9,4,9
RM907,34,26-35,No,Travel_Rarely,1320,Research & Development,20,3,Technical Degree,1,1265,3,Female,89,4,1,Research Scientist,3,Married,2585,Upto 5k,21643,0,Y,No,17,3,4,80,0,2,5,2,1,0,0,0
RM918,34,26-35,No,Travel_Rarely,131,Sales,2,3,Marketing,1,1281,3,Female,86,3,2,Sales Executive,1,Single,4538,Upto 5k,6039,0,Y,Yes,12,3,4,80,0,4,3,3,3,2,0,2
RM921,34,26-35,No,Travel_Frequently,135,Research & Development,19,3,Medical,1,1285,3,Female,46,3,2,Laboratory Technician,2,Divorced,4444,Upto 5k,22534,4,Y,No,13,3,3,80,2,15,2,4,11,8,5,10
RM924,34,26-35,No,Travel_Frequently,648,Human Resources,11,3,Life Sciences,1,1289,3,Male,56,2,2,Human Resources,2,Married,4490,Upto 5k,21833,4,Y,No,11,3,4,80,2,14,5,4,10,9,1,8
RM959,34,26-35,No,Travel_Rarely,943,Research & Development,9,3,Life Sciences,1,1344,4,Male,86,3,3,Healthcare Representative,4,Divorced,8500,5k-10k,5494,0,Y,No,11,3,4,80,1,10,0,2,9,7,1,6
RM965,34,26-35,No,Travel_Rarely,507,Sales,15,2,Medical,1,1356,3,Female,66,3,2,Sales Executive,1,Single,6125,5k-10k,23553,1,Y,No,12,3,4,80,0,10,6,4,10,8,9,6
RM978,34,26-35,No,Non-Travel,999,Research & Development,26,1,Technical Degree,1,1374,1,Female,92,2,1,Research Scientist,3,Divorced,2029,Upto 5k,15891,1,Y,No,20,4,3,80,3,5,2,3,5,4,0,0
RM980,34,26-35,No,Travel_Rarely,285,Research & Development,29,3,Medical,1,1377,2,Male,86,3,2,Laboratory Technician,3,Married,5429,5k-10k,17491,4,Y,No,13,3,1,80,2,10,1,3,8,7,7,7
RM984,34,26-35,No,Travel_Rarely,404,Research & Development,2,4,Technical Degree,1,1383,3,Female,98,3,2,Healthcare Representative,4,Single,6687,5k-10k,6163,1,Y,No,11,3,4,80,0,14,2,4,14,11,4,11
RM1016,34,26-35,No,Travel_Frequently,560,Research & Development,1,4,Other,1,1431,4,Male,91,3,1,Research Scientist,1,Divorced,2996,Upto 5k,20284,5,Y,No,14,3,3,80,2,10,2,3,4,3,1,3
RM1028,34,26-35,No,Travel_Rarely,401,Research & Development,1,3,Life Sciences,1,1447,4,Female,86,2,1,Laboratory Technician,2,Married,3294,Upto 5k,3708,5,Y,No,17,3,1,80,1,7,2,2,5,4,0,2
RM1040,34,26-35,Yes,Travel_Rarely,1107,Human Resources,9,4,Technical Degree,1,1467,1,Female,52,3,1,Human Resources,3,Married,2742,Upto 5k,3072,1,Y,No,15,3,4,80,0,2,0,3,2,2,2,2
RM1049,34,26-35,No,Travel_Rarely,1326,Sales,3,3,Other,1,1478,4,Male,81,1,2,Sales Executive,1,Single,4759,Upto 5k,15891,3,Y,No,18,3,4,80,0,15,2,3,13,9,3,12
RM1056,34,26-35,No,Travel_Frequently,829,Research & Development,15,3,Medical,1,1485,2,Male,71,3,4,Research Director,1,Divorced,17007,15k+,11929,7,Y,No,14,3,4,80,2,16,3,2,14,8,6,9
RM1059,34,26-35,Yes,Travel_Rarely,790,Sales,24,4,Medical,1,1489,1,Female,40,2,2,Sales Executive,2,Single,4599,Upto 5k,7815,0,Y,Yes,23,4,3,80,0,16,2,4,15,9,10,10
RM1085,34,26-35,No,Travel_Rarely,971,Sales,1,3,Technical Degree,1,1535,4,Male,64,2,3,Sales Executive,3,Married,7083,5k-10k,12288,1,Y,Yes,14,3,4,80,0,10,3,3,10,9,8,6
RM1088,34,26-35,No,Travel_Rarely,1440,Sales,7,2,Technical Degree,1,1541,2,Male,55,3,1,Sales Representative,3,Married,2308,Upto 5k,4944,0,Y,Yes,25,4,2,80,1,12,4,3,11,10,5,7
RM1116,34,26-35,No,Travel_Rarely,479,Research & Development,7,4,Medical,1,1577,1,Male,35,3,1,Research Scientist,4,Single,2972,Upto 5k,22061,1,Y,No,13,3,3,80,0,1,4,1,1,0,0,0
RM1118,34,26-35,No,Travel_Rarely,1351,Research & Development,1,4,Life Sciences,1,1580,2,Male,45,3,2,Research Scientist,4,Married,5484,5k-10k,13008,9,Y,No,17,3,2,80,1,9,3,2,2,2,2,1
RM1132,34,26-35,No,Travel_Frequently,653,Research & Development,10,4,Technical Degree,1,1597,4,Male,92,2,2,Healthcare Representative,3,Married,5063,5k-10k,15332,1,Y,No,14,3,2,80,1,8,3,2,8,2,7,7
RM1147,34,26-35,No,Travel_Frequently,426,Research & Development,10,4,Life Sciences,1,1615,3,Male,42,4,2,Manufacturing Director,4,Divorced,4724,Upto 5k,17000,1,Y,No,13,3,1,80,1,9,3,3,9,7,7,2
RM1180,34,26-35,No,Travel_Rarely,1130,Research & Development,3,3,Life Sciences,1,1658,4,Female,66,3,2,Research Scientist,2,Divorced,5433,5k-10k,19332,1,Y,No,12,3,3,80,1,11,2,3,11,8,7,9
RM1209,34,26-35,No,Travel_Rarely,1157,Research & Development,5,2,Medical,1,1696,2,Male,57,2,2,Laboratory Technician,4,Married,3986,Upto 5k,11912,1,Y,No,14,3,3,80,1,15,3,4,15,10,4,13
RM1213,34,26-35,No,Travel_Rarely,678,Research & Development,19,3,Life Sciences,1,1701,2,Female,35,2,1,Research Scientist,4,Married,2929,Upto 5k,20338,1,Y,No,12,3,2,80,0,10,3,3,10,9,8,7
RM1253,34,26-35,No,Travel_Rarely,181,Research & Development,2,4,Medical,1,1755,4,Male,97,4,1,Research Scientist,4,Married,2932,Upto 5k,5586,0,Y,Yes,14,3,1,80,3,6,3,3,5,0,1,2
RM1268,34,26-35,No,Non-Travel,1375,Sales,10,3,Life Sciences,1,1774,4,Male,87,3,2,Sales Executive,3,Divorced,4001,Upto 5k,12313,1,Y,Yes,14,3,3,80,1,15,3,3,15,14,0,7
RM1271,34,26-35,No,Travel_Rarely,511,Sales,3,2,Life Sciences,1,1779,4,Female,32,1,2,Sales Executive,4,Single,6029,5k-10k,25353,5,Y,No,12,3,1,80,0,6,3,3,2,2,2,2
RM1291,34,26-35,Yes,Travel_Frequently,234,Research & Development,9,4,Life Sciences,1,1807,4,Male,93,3,2,Laboratory Technician,1,Married,5346,5k-10k,6208,4,Y,No,17,3,3,80,1,11,3,2,7,1,0,7
RM1301,34,26-35,No,Travel_Rarely,810,Sales,8,2,Technical Degree,1,1823,2,Male,92,4,2,Sales Executive,3,Married,6799,5k-10k,22128,1,Y,No,21,4,3,80,2,10,5,3,10,8,4,8
RM1343,34,26-35,No,Travel_Rarely,1480,Sales,4,3,Life Sciences,1,1882,3,Male,64,3,3,Sales Executive,4,Married,9713,5k-10k,24444,2,Y,Yes,13,3,4,80,3,9,3,3,5,3,1,0
RM1354,34,26-35,Yes,Non-Travel,967,Research & Development,16,4,Technical Degree,1,1905,4,Male,85,1,1,Research Scientist,1,Married,2307,Upto 5k,14460,1,Y,Yes,23,4,2,80,1,5,2,3,5,2,3,0
RM1360,34,26-35,No,Travel_Rarely,735,Sales,3,1,Medical,1,1915,4,Female,75,2,2,Sales Executive,4,Married,8103,5k-10k,16495,3,Y,Yes,12,3,3,80,0,9,3,2,4,2,0,1
RM1369,34,26-35,No,Travel_Frequently,735,Research & Development,22,4,Other,1,1932,3,Male,86,2,2,Research Scientist,4,Married,5747,5k-10k,26496,1,Y,Yes,15,3,2,80,0,16,3,3,15,10,6,11
RM1385,34,26-35,No,Travel_Rarely,937,Sales,1,3,Marketing,1,1950,1,Male,32,3,3,Sales Executive,4,Single,9888,5k-10k,6770,1,Y,No,21,4,1,80,0,14,3,2,14,8,2,1
RM1386,34,26-35,No,Travel_Rarely,1239,Sales,13,4,Medical,1,1951,4,Male,39,3,3,Sales Executive,3,Divorced,8628,5k-10k,22914,1,Y,No,18,3,3,80,1,9,2,2,8,7,1,1
RM1447,34,26-35,No,Travel_Rarely,704,Sales,28,3,Marketing,1,2035,4,Female,95,2,2,Sales Executive,3,Married,6712,5k-10k,8978,1,Y,No,21,4,4,80,2,8,2,3,8,7,1,7
RM1470,34,26-35,No,TravelRarely,628,Research & Development,8,3,Medical,1,2068,2,Male,82,4,2,Laboratory Technician,3,Married,4404,Upto 5k,10228,2,Y,No,12,3,1,80,0,6,3,4,4,3,1,2
RM1470,34,26-35,No,TravelRarely,628,Research & Development,8,3,Medical,1,2068,2,Male,82,4,2,Laboratory Technician,3,Married,4404,Upto 5k,10228,2,Y,No,12,3,1,80,0,6,3,4,4,3,1,2
RM011,35,26-35,No,Travel_Rarely,809,Research & Development,16,3,Medical,1,14,1,Male,84,4,1,Laboratory Technician,2,Married,2426,Upto 5k,16479,0,Y,No,13,3,3,80,1,6,5,3,5,4,0,3
RM038,35,26-35,No,Travel_Rarely,890,Sales,2,3,Marketing,1,49,4,Female,97,3,1,Sales Representative,4,Married,2014,Upto 5k,9687,1,Y,No,13,3,1,80,0,2,3,3,2,2,2,2
RM041,35,26-35,No,Travel_Rarely,464,Research & Development,4,2,Other,1,53,3,Male,75,3,1,Laboratory Technician,4,Divorced,1951,Upto 5k,10910,1,Y,No,12,3,3,80,1,1,3,3,1,0,0,0
RM050,35,26-35,No,Travel_Rarely,1229,Research & Development,8,1,Life Sciences,1,63,4,Male,36,4,1,Laboratory Technician,4,Married,2269,Upto 5k,4892,1,Y,No,19,3,4,80,0,1,2,3,1,0,0,1
RM054,35,26-35,No,Non-Travel,1097,Research & Development,11,2,Medical,1,70,3,Male,79,2,3,Healthcare Representative,1,Married,9884,5k-10k,8302,2,Y,Yes,13,3,3,80,1,10,3,3,4,0,2,3
RM057,35,26-35,No,Travel_Frequently,853,Sales,18,5,Life Sciences,1,74,2,Male,71,3,3,Sales Executive,1,Married,9069,5k-10k,11031,1,Y,No,22,4,4,80,1,9,3,2,9,8,1,8
RM058,35,26-35,No,Travel_Rarely,1142,Research & Development,23,4,Medical,1,75,3,Female,30,3,1,Laboratory Technician,1,Married,4014,Upto 5k,16002,3,Y,Yes,15,3,3,80,1,4,3,3,2,2,2,2
RM069,35,26-35,No,Travel_Frequently,664,Research & Development,1,3,Medical,1,88,2,Male,79,3,1,Research Scientist,1,Married,2194,Upto 5k,5868,4,Y,No,13,3,4,80,1,5,2,2,3,2,1,2
RM077,35,26-35,No,Travel_Rarely,776,Sales,1,4,Marketing,1,100,3,Male,32,2,2,Sales Executive,1,Single,4312,Upto 5k,23016,0,Y,No,14,3,2,80,0,16,2,3,15,13,2,
RM082,35,26-35,No,Travel_Rarely,1214,Research & Development,1,3,Medical,1,105,2,Male,30,2,1,Research Scientist,3,Single,2859,Upto 5k,26278,1,Y,No,18,3,1,80,0,6,3,3,6,4,0,4
RM152,35,26-35,No,Travel_Rarely,662,Sales,1,5,Marketing,1,204,3,Male,94,3,3,Sales Executive,2,Married,7295,5k-10k,11439,1,Y,No,13,3,1,80,2,10,3,3,10,8,0,6
RM193,35,26-35,Yes,Travel_Rarely,556,Research & Development,23,2,Life Sciences,1,261,2,Male,50,2,2,Manufacturing Director,3,Married,5916,5k-10k,15497,3,Y,Yes,13,3,1,80,0,8,1,3,1,0,0,1
RM197,35,26-35,No,Travel_Frequently,138,Research & Development,2,3,Medical,1,269,2,Female,37,3,2,Laboratory Technician,2,Single,4425,Upto 5k,15986,5,Y,No,11,3,4,80,0,10,5,3,6,2,1,2
RM229,35,26-35,No,Travel_Frequently,944,Sales,1,3,Marketing,1,314,3,Female,92,3,3,Sales Executive,3,Single,8789,5k-10k,9096,1,Y,No,14,3,1,80,0,10,3,4,10,7,0,8
RM277,35,26-35,No,Travel_Rarely,1315,Research & Development,22,3,Life Sciences,1,381,2,Female,71,4,3,Manager,2,Divorced,11996,10k-15k,19100,7,Y,No,18,3,2,80,1,10,6,2,7,7,6,2
RM298,35,26-35,No,Travel_Rarely,1232,Sales,16,3,Marketing,1,406,3,Male,96,3,3,Sales Executive,2,Married,8020,5k-10k,5100,0,Y,No,15,3,3,80,2,12,3,2,11,9,6,9
RM345,35,26-35,No,Travel_Rarely,1296,Research & Development,5,4,Technical Degree,1,464,3,Male,62,3,3,Manufacturing Director,2,Single,8095,5k-10k,18264,0,Y,No,13,3,4,80,0,17,5,3,16,6,0,13
RM373,35,26-35,No,Travel_Rarely,755,Research & Development,9,4,Life Sciences,1,496,3,Male,97,2,2,Healthcare Representative,2,Single,6540,5k-10k,19394,9,Y,No,19,3,3,80,0,10,5,3,1,1,0,0
RM431,35,26-35,No,Travel_Rarely,144,Research & Development,22,3,Life Sciences,1,577,4,Male,46,1,1,Laboratory Technician,3,Single,4230,Upto 5k,19225,0,Y,No,15,3,3,80,0,6,2,3,5,4,4,3
RM439,35,26-35,No,Travel_Rarely,1276,Research & Development,16,3,Life Sciences,1,586,4,Male,72,3,3,Healthcare Representative,3,Married,7632,5k-10k,14295,4,Y,Yes,12,3,3,80,0,10,2,3,8,7,0,0
RM448,35,26-35,No,Travel_Rarely,619,Sales,1,3,Marketing,1,600,2,Male,85,3,2,Sales Executive,3,Married,4717,Upto 5k,18659,9,Y,No,11,3,3,80,0,15,2,3,11,9,6,9
RM462,35,26-35,No,Travel_Rarely,195,Sales,1,3,Medical,1,620,1,Female,80,3,2,Sales Executive,3,Single,4859,Upto 5k,6698,1,Y,No,16,3,4,80,0,5,3,3,5,4,0,3
RM484,35,26-35,No,Travel_Rarely,538,Research & Development,25,2,Other,1,652,1,Male,54,2,2,Laboratory Technician,4,Single,3681,Upto 5k,14004,4,Y,No,14,3,4,80,0,9,3,3,3,2,0,2
RM509,35,26-35,No,Travel_Rarely,1017,Research & Development,6,4,Life Sciences,1,691,2,Male,82,1,2,Research Scientist,4,Single,6646,5k-10k,19368,1,Y,No,13,3,2,80,0,17,3,3,17,11,11,8
RM516,35,26-35,No,Non-Travel,727,Research & Development,3,3,Life Sciences,1,704,3,Male,41,2,1,Laboratory Technician,3,Married,1281,Upto 5k,16900,1,Y,No,18,3,3,80,2,1,3,3,1,0,0,0
RM558,35,26-35,No,Non-Travel,1225,Research & Development,2,4,Life Sciences,1,771,4,Female,61,3,2,Healthcare Representative,1,Divorced,5093,5k-10k,4761,2,Y,No,11,3,1,80,1,16,2,4,1,0,0,0
RM581,35,26-35,No,Travel_Rarely,384,Sales,8,4,Life Sciences,1,805,1,Female,72,3,1,Sales Representative,4,Married,2572,Upto 5k,20317,1,Y,No,16,3,2,80,1,3,1,2,3,2,0,2
RM597,35,26-35,No,Travel_Rarely,1258,Research & Development,1,4,Life Sciences,1,826,4,Female,40,4,1,Research Scientist,3,Single,2506,Upto 5k,13301,3,Y,No,13,3,3,80,0,7,0,3,2,2,2,2
RM612,35,26-35,No,Travel_Rarely,950,Research & Development,7,3,Other,1,845,3,Male,59,3,3,Manufacturing Director,3,Single,10221,10k-15k,18869,3,Y,No,21,4,2,80,0,17,3,4,8,5,1,6
RM621,35,26-35,No,Travel_Rarely,1343,Research & Development,27,1,Medical,1,856,3,Female,53,2,1,Research Scientist,1,Single,2559,Upto 5k,17852,1,Y,No,11,3,4,80,0,6,3,2,6,5,1,1
RM636,35,26-35,No,Travel_Rarely,607,Research & Development,9,3,Life Sciences,1,880,4,Female,66,2,3,Manufacturing Director,3,Married,10685,10k-15k,23457,1,Y,Yes,20,4,2,80,1,17,2,3,17,14,5,15
RM637,35,26-35,Yes,Travel_Frequently,130,Research & Development,25,4,Life Sciences,1,881,4,Female,96,3,1,Research Scientist,2,Divorced,2022,Upto 5k,16612,1,Y,Yes,19,3,1,80,1,10,3,2,10,2,7,8
RM648,35,26-35,No,Travel_Rarely,672,Research & Development,25,3,Technical Degree,1,899,4,Male,78,2,3,Manufacturing Director,2,Married,10903,10k-15k,9129,3,Y,No,16,3,1,80,0,16,2,3,13,10,4,8
RM677,35,26-35,No,Travel_Rarely,1137,Research & Development,21,1,Life Sciences,1,942,4,Female,51,3,2,Healthcare Representative,4,Married,4014,Upto 5k,19170,1,Y,Yes,25,4,4,80,1,10,2,1,10,6,0,7
RM699,35,26-35,No,Travel_Rarely,1219,Sales,18,3,Medical,1,975,3,Female,86,3,2,Sales Executive,3,Married,4601,Upto 5k,6179,1,Y,No,16,3,2,80,0,5,3,3,5,2,1,0
RM705,35,26-35,No,Travel_Rarely,882,Sales,3,4,Life Sciences,1,984,4,Male,92,3,3,Sales Executive,4,Divorced,7823,5k-10k,6812,6,Y,No,13,3,2,80,1,12,2,3,10,9,0,8
RM726,35,26-35,Yes,Travel_Rarely,622,Research & Development,14,4,Other,1,1010,3,Male,39,2,1,Laboratory Technician,2,Divorced,3743,Upto 5k,10074,1,Y,Yes,24,4,4,80,1,5,2,1,4,2,0,2
RM730,35,26-35,No,Travel_Rarely,583,Research & Development,25,4,Medical,1,1014,3,Female,57,3,3,Healthcare Representative,3,Divorced,10388,10k-15k,6975,1,Y,Yes,11,3,3,80,1,16,3,2,16,10,10,1
RM741,35,26-35,No,Travel_Rarely,802,Research & Development,10,3,Other,1,1028,2,Male,45,3,1,Laboratory Technician,4,Divorced,3917,Upto 5k,9541,1,Y,No,20,4,1,80,1,3,4,2,3,2,1,2
RM792,35,26-35,Yes,Travel_Rarely,1204,Sales,4,3,Technical Degree,1,1100,4,Male,86,3,3,Sales Executive,1,Single,9582,5k-10k,10333,0,Y,Yes,22,4,1,80,0,9,2,3,8,7,4,7
RM821,35,26-35,No,Travel_Frequently,1182,Sales,11,2,Marketing,1,1137,4,Male,54,3,2,Sales Executive,4,Divorced,4968,Upto 5k,18500,1,Y,No,11,3,4,80,1,5,3,3,5,2,0,2
RM836,35,26-35,No,Travel_Rarely,528,Human Resources,8,4,Technical Degree,1,1164,3,Male,100,3,1,Human Resources,3,Single,4323,Upto 5k,7108,1,Y,No,17,3,2,80,0,6,2,1,5,4,1,4
RM841,35,26-35,No,Travel_Rarely,982,Research & Development,1,4,Medical,1,1172,4,Male,58,2,1,Laboratory Technician,3,Married,2258,Upto 5k,16340,6,Y,No,12,3,2,80,1,10,2,3,8,0,1,7
RM847,35,26-35,No,Travel_Rarely,819,Research & Development,2,3,Life Sciences,1,1182,3,Male,44,2,3,Manufacturing Director,2,Divorced,10274,10k-15k,19588,2,Y,No,18,3,2,80,1,15,2,4,7,7,6,4
RM849,35,26-35,No,Travel_Frequently,636,Research & Development,4,4,Other,1,1185,4,Male,47,2,1,Laboratory Technician,4,Married,2376,Upto 5k,26537,1,Y,No,13,3,2,80,1,2,2,4,2,2,2,2
RM871,35,26-35,No,Travel_Rarely,1361,Sales,17,4,Life Sciences,1,1218,3,Male,94,3,2,Sales Executive,1,Married,8966,5k-10k,21026,3,Y,Yes,15,3,4,80,3,15,2,3,7,7,1,7
RM889,35,26-35,No,Non-Travel,1212,Sales,8,2,Marketing,1,1243,3,Female,78,2,3,Sales Executive,4,Married,10377,10k-15k,13755,4,Y,Yes,11,3,2,80,1,16,6,2,13,2,4,12
RM925,35,26-35,No,Travel_Rarely,735,Research & Development,6,1,Life Sciences,1,1291,3,Male,66,3,1,Research Scientist,3,Married,3506,Upto 5k,6020,0,Y,Yes,14,3,4,80,0,4,3,3,3,2,2,2
RM962,35,26-35,No,Travel_Frequently,482,Research & Development,4,4,Life Sciences,1,1350,3,Male,87,3,2,Research Scientist,3,Single,4249,Upto 5k,2690,1,Y,Yes,11,3,2,80,0,9,3,3,9,6,1,1
RM974,35,26-35,No,Travel_Rarely,817,Research & Development,1,3,Medical,1,1369,4,Female,60,2,2,Laboratory Technician,4,Married,5363,5k-10k,10846,0,Y,No,12,3,2,80,1,10,0,3,9,7,0,0
RM982,35,26-35,Yes,Travel_Frequently,662,Sales,18,4,Marketing,1,1380,4,Female,67,3,2,Sales Executive,3,Married,4614,Upto 5k,23288,0,Y,Yes,18,3,3,80,1,5,0,2,4,2,3,2
RM1003,35,26-35,No,Travel_Frequently,200,Research & Development,18,2,Life Sciences,1,1412,3,Male,60,3,3,Manufacturing Director,4,Single,9362,5k-10k,19944,2,Y,No,11,3,3,80,0,10,2,3,2,2,2,2
RM1060,35,26-35,No,Travel_Rarely,660,Sales,7,1,Life Sciences,1,1492,4,Male,76,3,1,Sales Representative,3,Married,2404,Upto 5k,16192,1,Y,No,13,3,1,80,1,1,3,3,1,0,0,0
RM1082,35,26-35,No,Travel_Rarely,1029,Research & Development,16,3,Life Sciences,1,1529,4,Female,91,2,3,Healthcare Representative,2,Single,8606,5k-10k,21195,1,Y,No,19,3,4,80,0,11,3,1,11,8,3,3
RM1101,35,26-35,No,Travel_Rarely,1402,Sales,28,4,Life Sciences,1,1554,2,Female,98,2,1,Sales Representative,3,Married,2430,Upto 5k,26204,0,Y,No,23,4,1,80,2,6,5,3,5,3,4,2
RM1109,35,26-35,No,Travel_Rarely,992,Research & Development,1,3,Medical,1,1564,4,Male,68,2,1,Laboratory Technician,1,Single,2450,Upto 5k,21731,1,Y,No,19,3,2,80,0,3,3,3,3,0,1,2
RM1111,35,26-35,Yes,Travel_Rarely,104,Research & Development,2,3,Life Sciences,1,1569,1,Female,69,3,1,Laboratory Technician,1,Divorced,2074,Upto 5k,26619,1,Y,Yes,12,3,4,80,1,1,2,3,1,0,0,0
RM1124,35,26-35,No,Travel_Rarely,670,Research & Development,10,4,Medical,1,1587,1,Female,51,3,2,Healthcare Representative,3,Single,6142,5k-10k,4223,3,Y,Yes,16,3,3,80,0,10,4,3,5,2,0,4
RM1131,35,26-35,No,Travel_Rarely,750,Research & Development,28,3,Life Sciences,1,1596,2,Male,46,4,2,Laboratory Technician,3,Married,3407,Upto 5k,25348,1,Y,No,17,3,4,80,2,10,3,2,10,9,6,8
RM1135,35,26-35,No,Travel_Rarely,1349,Research & Development,7,2,Life Sciences,1,1601,3,Male,63,2,1,Laboratory Technician,4,Married,2690,Upto 5k,7713,1,Y,No,18,3,4,80,1,1,5,2,1,0,0,1
RM1151,35,26-35,No,Travel_Rarely,819,Research & Development,18,5,Life Sciences,1,1621,2,Male,48,4,2,Research Scientist,1,Married,5208,5k-10k,26312,1,Y,No,11,3,4,80,0,16,2,3,16,15,1,10
RM1158,35,26-35,No,Non-Travel,208,Research & Development,8,4,Life Sciences,1,1630,3,Female,52,3,2,Healthcare Representative,3,Married,4148,Upto 5k,12250,1,Y,No,12,3,4,80,1,15,5,3,14,11,2,9
RM1163,35,26-35,Yes,Travel_Rarely,737,Sales,10,3,Medical,1,1639,4,Male,55,2,3,Sales Executive,1,Married,10306,10k-15k,21530,9,Y,No,17,3,3,80,0,15,3,3,13,12,6,0
RM1168,35,26-35,Yes,Travel_Rarely,763,Sales,15,2,Medical,1,1645,1,Male,59,1,2,Sales Executive,4,Divorced,5440,5k-10k,22098,6,Y,Yes,14,3,4,80,2,7,2,2,2,2,2,2
RM1187,35,26-35,Yes,Travel_Frequently,880,Sales,12,4,Other,1,1667,4,Male,36,3,2,Sales Executive,4,Single,4581,Upto 5k,10414,3,Y,Yes,24,4,1,80,0,13,2,4,11,9,6,7
RM1216,35,26-35,No,Travel_Frequently,146,Research & Development,2,4,Medical,1,1704,1,Male,79,2,1,Research Scientist,4,Single,4930,Upto 5k,13970,0,Y,Yes,14,3,3,80,0,6,2,4,5,4,1,4
RM1233,35,26-35,No,Travel_Rarely,1370,Research & Development,27,4,Life Sciences,1,1728,4,Male,49,3,2,Manufacturing Director,3,Married,6883,5k-10k,5151,2,Y,No,16,3,2,80,1,17,3,3,7,7,0,7
RM1282,35,26-35,Yes,Travel_Rarely,303,Sales,27,3,Life Sciences,1,1797,3,Male,84,3,2,Sales Executive,4,Single,5813,5k-10k,13492,1,Y,Yes,18,3,4,80,0,10,2,3,10,7,7,7
RM1289,35,26-35,No,Non-Travel,1180,Research & Development,2,2,Medical,1,1804,2,Male,90,3,2,Manufacturing Director,4,Divorced,5762,5k-10k,24442,2,Y,No,14,3,3,80,1,15,6,3,7,7,1,7
RM1303,35,26-35,No,Travel_Rarely,185,Research & Development,23,4,Medical,1,1826,2,Male,91,1,1,Laboratory Technician,3,Married,2705,Upto 5k,9696,0,Y,No,16,3,2,80,1,6,2,4,5,4,0,3
RM1346,35,26-35,No,Travel_Rarely,219,Research & Development,16,2,Other,1,1886,4,Female,44,2,2,Manufacturing Director,2,Married,4788,Upto 5k,25388,0,Y,Yes,11,3,4,80,0,4,2,3,3,2,0,2
RM1381,35,26-35,No,Travel_Rarely,682,Sales,18,4,Medical,1,1945,2,Male,71,3,2,Sales Executive,1,Married,5561,5k-10k,15975,0,Y,No,16,3,4,80,1,6,2,1,5,3,0,4
RM1393,35,26-35,No,Travel_Rarely,1224,Sales,7,4,Life Sciences,1,1962,3,Female,55,3,2,Sales Executive,4,Married,5204,5k-10k,13586,1,Y,Yes,11,3,4,80,0,10,2,3,10,8,0,9
RM1423,35,26-35,No,TravelRarely,1490,Research & Development,11,4,Medical,1,2003,4,Male,43,3,1,Laboratory Technician,3,Married,2660,Upto 5k,20232,7,Y,Yes,11,3,3,80,1,5,3,3,2,2,2,2
RM1425,35,26-35,No,Travel_Rarely,1395,Research & Development,9,4,Medical,1,2008,2,Male,48,3,2,Research Scientist,3,Single,5098,5k-10k,18698,1,Y,No,19,3,2,80,0,10,5,3,10,7,0,8
RM1451,35,26-35,No,Travel_Rarely,1146,Human Resources,26,4,Life Sciences,1,2040,3,Female,31,3,3,Human Resources,4,Single,8837,5k-10k,16642,1,Y,Yes,16,3,3,80,0,9,2,3,9,0,1,7
RM1457,35,26-35,No,Travel_Frequently,1199,Research & Development,18,4,Life Sciences,1,2049,3,Male,80,3,2,Healthcare Representative,3,Married,5689,5k-10k,24594,1,Y,Yes,14,3,4,80,2,10,2,4,10,2,0,2
RM1459,35,26-35,No,Travel_Rarely,287,Research & Development,1,4,Life Sciences,1,2052,3,Female,62,1,1,Research Scientist,4,Married,2977,Upto 5k,8952,1,Y,No,12,3,4,80,1,4,5,3,4,3,1,1
RM010,36,36-45,No,Travel_Rarely,1299,Research & Development,27,3,Medical,1,13,3,Male,94,3,2,Healthcare Representative,3,Married,5237,5k-10k,16577,6,Y,No,13,3,2,80,2,17,3,2,7,7,7,7
RM022,36,36-45,Yes,Travel_Rarely,1218,Sales,9,4,Life Sciences,1,27,3,Male,82,2,1,Sales Representative,1,Single,3407,Upto 5k,6986,7,Y,No,23,4,2,80,0,10,4,3,5,3,0,3
RM039,36,36-45,No,Travel_Rarely,852,Research & Development,5,4,Life Sciences,1,51,2,Female,82,2,1,Research Scientist,1,Married,3419,Upto 5k,13072,9,Y,Yes,14,3,4,80,1,6,3,4,1,1,0,0
RM065,36,36-45,No,Travel_Rarely,1223,Research & Development,8,3,Technical Degree,1,83,3,Female,59,3,3,Healthcare Representative,3,Divorced,10096,10k-15k,8202,1,Y,No,13,3,2,80,3,17,2,3,17,14,12,8
RM067,36,36-45,No,Travel_Frequently,1195,Research & Development,11,3,Life Sciences,1,85,2,Male,95,2,2,Manufacturing Director,2,Single,6499,5k-10k,22656,1,Y,No,13,3,3,80,0,6,3,3,6,5,0,3
RM070,36,36-45,Yes,Travel_Rarely,318,Research & Development,9,3,Medical,1,90,4,Male,79,2,1,Research Scientist,3,Married,3388,Upto 5k,21777,0,Y,Yes,17,3,1,80,1,2,0,2,1,0,0,
RM075,36,36-45,No,Travel_Rarely,132,Research & Development,6,3,Life Sciences,1,97,2,Female,55,4,1,Laboratory Technician,4,Married,3038,Upto 5k,22002,3,Y,No,12,3,2,80,0,5,3,3,1,0,0,
RM118,36,36-45,No,Travel_Frequently,1467,Sales,11,2,Technical Degree,1,154,2,Female,92,3,3,Sales Executive,4,Married,9738,5k-10k,22952,0,Y,No,14,3,3,80,1,10,6,3,9,7,2,8
RM119,36,36-45,No,Travel_Rarely,922,Research & Development,3,2,Life Sciences,1,155,1,Female,39,3,1,Laboratory Technician,4,Divorced,2835,Upto 5k,2561,5,Y,No,22,4,1,80,1,7,2,3,1,0,0,0
RM136,36,36-45,No,Travel_Rarely,216,Research & Development,6,2,Medical,1,178,2,Male,84,3,2,Manufacturing Director,2,Divorced,4941,Upto 5k,2819,6,Y,No,20,4,4,80,2,7,0,3,3,2,0,1
RM173,36,36-45,No,Travel_Frequently,1480,Research & Development,3,2,Medical,1,238,4,Male,30,3,1,Laboratory Technician,2,Single,2088,Upto 5k,15062,4,Y,No,12,3,3,80,0,13,3,2,8,7,7,2
RM208,36,36-45,No,Travel_Frequently,635,Research & Development,18,1,Medical,1,286,2,Female,73,3,1,Laboratory Technician,4,Single,2153,Upto 5k,7703,1,Y,No,13,3,1,80,0,8,2,3,8,1,1,
RM221,36,36-45,No,Travel_Rarely,1396,Research & Development,5,2,Life Sciences,1,304,4,Male,62,3,2,Laboratory Technician,2,Single,5914,5k-10k,9945,8,Y,No,16,3,4,80,0,16,3,4,13,11,3,7
RM270,36,36-45,No,Travel_Rarely,1403,Research & Development,6,3,Life Sciences,1,373,4,Male,47,3,1,Laboratory Technician,4,Married,3210,Upto 5k,20251,0,Y,No,11,3,3,80,1,16,4,3,15,13,10,11
RM292,36,36-45,No,Travel_Rarely,506,Research & Development,3,3,Technical Degree,1,397,3,Male,30,3,2,Research Scientist,2,Single,4485,Upto 5k,26285,4,Y,No,12,3,4,80,0,10,2,3,8,0,7,7
RM299,36,36-45,No,Travel_Frequently,566,Research & Development,18,4,Life Sciences,1,407,3,Male,81,4,1,Laboratory Technician,4,Married,3688,Upto 5k,7122,4,Y,No,18,3,4,80,2,4,2,3,1,0,0,0
RM306,36,36-45,No,Non-Travel,1105,Research & Development,24,4,Life Sciences,1,419,2,Female,47,3,2,Laboratory Technician,2,Married,5674,5k-10k,6927,7,Y,No,15,3,3,80,1,11,3,3,9,8,0,8
RM359,36,36-45,No,Non-Travel,845,Sales,1,5,Medical,1,479,4,Female,45,3,2,Sales Executive,4,Single,6653,5k-10k,15276,4,Y,No,15,3,2,80,0,7,6,3,1,0,0,
RM360,36,36-45,No,Travel_Frequently,541,Sales,3,4,Medical,1,481,1,Male,48,2,3,Sales Executive,4,Married,9699,5k-10k,7246,4,Y,No,11,3,1,80,1,16,2,3,13,9,1,
RM378,36,36-45,No,Travel_Rarely,329,Research & Development,2,3,Life Sciences,1,501,4,Female,96,3,1,Research Scientist,3,Married,2543,Upto 5k,11868,4,Y,No,13,3,2,80,1,6,3,3,2,2,2,2
RM385,36,36-45,No,Travel_Rarely,164,Sales,2,2,Medical,1,513,2,Male,61,2,3,Sales Executive,3,Married,7596,5k-10k,3809,1,Y,No,13,3,2,80,2,10,2,3,10,9,9,0
RM443,36,36-45,No,Non-Travel,635,Sales,10,4,Medical,1,592,2,Male,32,3,3,Sales Executive,4,Single,9980,5k-10k,15318,1,Y,No,14,3,4,80,0,10,3,2,10,3,9,7
RM512,36,36-45,No,Travel_Rarely,913,Research & Development,9,2,Medical,1,699,2,Male,48,2,2,Manufacturing Director,2,Divorced,8847,5k-10k,13934,2,Y,Yes,11,3,3,80,1,13,2,3,3,2,0,2
RM542,36,36-45,No,Non-Travel,427,Research & Development,8,3,Life Sciences,1,742,1,Female,63,4,3,Research Director,1,Married,11713,10k-15k,20335,9,Y,No,14,3,1,80,1,10,2,3,8,7,0,5
RM570,36,36-45,No,Non-Travel,1434,Sales,8,4,Life Sciences,1,789,1,Male,76,2,3,Sales Executive,1,Single,7587,5k-10k,14229,1,Y,No,15,3,2,80,0,10,1,3,10,7,0,9
RM594,36,36-45,No,Travel_Rarely,676,Research & Development,1,3,Other,1,823,3,Female,35,3,2,Manufacturing Director,2,Married,5228,5k-10k,23361,0,Y,No,15,3,1,80,1,10,2,3,9,7,0,5
RM600,36,36-45,No,Travel_Rarely,1041,Human Resources,13,3,Human Resources,1,829,3,Male,36,3,1,Human Resources,2,Married,2143,Upto 5k,25527,4,Y,No,13,3,2,80,1,8,2,3,5,2,0,4
RM622,36,36-45,No,Travel_Rarely,928,Sales,1,2,Life Sciences,1,857,2,Male,56,3,2,Sales Executive,4,Married,6201,5k-10k,2823,1,Y,Yes,14,3,4,80,1,18,1,2,18,14,4,11
RM634,36,36-45,No,Travel_Rarely,1278,Human Resources,8,3,Life Sciences,1,878,1,Male,77,2,1,Human Resources,1,Married,2342,Upto 5k,8635,0,Y,No,21,4,3,80,0,6,3,3,5,4,0,3
RM665,36,36-45,No,Travel_Rarely,1425,Research & Development,14,1,Life Sciences,1,924,3,Male,68,3,2,Healthcare Representative,4,Married,6586,5k-10k,4821,0,Y,Yes,17,3,1,80,1,17,2,2,16,8,4,11
RM681,36,36-45,No,Travel_Rarely,188,Research & Development,7,4,Other,1,949,2,Male,65,3,1,Research Scientist,4,Single,4678,Upto 5k,23293,2,Y,No,18,3,3,80,0,8,6,3,6,2,0,1
RM688,36,36-45,No,Travel_Rarely,938,Research & Development,2,4,Medical,1,958,3,Male,79,3,1,Laboratory Technician,3,Single,2519,Upto 5k,12287,4,Y,No,21,4,3,80,0,16,6,3,11,8,3,9
RM694,36,36-45,Yes,Travel_Rarely,530,Sales,3,1,Life Sciences,1,967,3,Male,51,2,3,Sales Executive,4,Married,10325,10k-15k,5518,1,Y,Yes,11,3,1,80,1,16,6,3,16,7,3,7
RM709,36,36-45,No,Non-Travel,1229,Sales,8,4,Technical Degree,1,990,1,Male,84,3,2,Sales Executive,4,Divorced,5079,5k-10k,25952,4,Y,No,13,3,4,80,2,12,3,3,7,7,0,7
RM753,36,36-45,Yes,Travel_Rarely,885,Research & Development,16,4,Life Sciences,1,1042,3,Female,43,4,1,Laboratory Technician,1,Single,2743,Upto 5k,8269,1,Y,No,16,3,3,80,0,18,1,3,17,13,15,14
RM762,36,36-45,Yes,Travel_Rarely,660,Research & Development,15,3,Other,1,1052,1,Male,81,3,2,Laboratory Technician,3,Divorced,4834,Upto 5k,7858,7,Y,No,14,3,2,80,1,9,3,2,1,0,0,0
RM774,36,36-45,No,Travel_Rarely,796,Research & Development,12,5,Medical,1,1073,4,Female,51,2,3,Manufacturing Director,4,Single,8858,5k-10k,15669,0,Y,No,11,3,2,80,0,15,2,2,14,8,7,8
RM818,36,36-45,No,Non-Travel,217,Research & Development,18,4,Life Sciences,1,1133,1,Male,78,3,2,Manufacturing Director,4,Single,7779,5k-10k,23238,2,Y,No,20,4,1,80,0,18,0,3,11,9,0,9
RM874,36,36-45,No,Travel_Rarely,917,Research & Development,6,4,Life Sciences,1,1221,3,Male,60,1,1,Laboratory Technician,3,Divorced,2741,Upto 5k,6865,1,Y,No,14,3,3,80,1,7,4,3,7,7,1,7
RM883,36,36-45,No,Travel_Rarely,363,Research & Development,1,3,Technical Degree,1,1237,3,Female,77,1,3,Manufacturing Director,1,Divorced,10252,10k-15k,4235,2,Y,Yes,21,4,3,80,1,17,2,3,7,7,7,7
RM901,36,36-45,No,Travel_Frequently,469,Research & Development,3,3,Technical Degree,1,1257,3,Male,46,3,1,Research Scientist,2,Married,3692,Upto 5k,9256,1,Y,No,12,3,3,80,0,12,2,2,11,10,0,7
RM928,36,36-45,No,Travel_Rarely,429,Research & Development,2,4,Life Sciences,1,1294,3,Female,53,3,2,Manufacturing Director,2,Single,5410,5k-10k,2323,9,Y,Yes,11,3,4,80,0,18,2,3,16,14,5,12
RM943,36,36-45,No,Travel_Rarely,325,Research & Development,10,4,Technical Degree,1,1312,4,Female,63,3,3,Healthcare Representative,3,Married,7094,5k-10k,5747,3,Y,No,12,3,1,80,0,10,0,3,7,7,1,7
RM969,36,36-45,No,Travel_Frequently,607,Sales,7,3,Marketing,1,1362,1,Female,83,4,2,Sales Executive,1,Married,4639,Upto 5k,2261,2,Y,No,16,3,4,80,1,17,2,2,15,7,6,13
RM1012,36,36-45,No,Travel_Rarely,1174,Sales,3,4,Marketing,1,1425,1,Female,99,3,2,Sales Executive,2,Single,9278,5k-10k,20763,3,Y,Yes,16,3,4,80,0,15,3,3,5,4,0,1
RM1019,36,36-45,No,Travel_Rarely,172,Research & Development,4,4,Life Sciences,1,1435,1,Male,37,2,2,Laboratory Technician,4,Single,5810,5k-10k,22604,1,Y,No,16,3,3,80,0,10,2,2,10,4,1,8
RM1020,36,36-45,No,Travel_Rarely,329,Sales,16,4,Marketing,1,1436,3,Female,98,2,2,Sales Executive,1,Married,5647,5k-10k,13494,4,Y,No,13,3,1,80,2,11,3,2,3,2,0,2
RM1103,36,36-45,No,Travel_Rarely,1157,Sales,2,4,Life Sciences,1,1556,3,Male,70,3,1,Sales Representative,4,Single,2644,Upto 5k,17001,3,Y,Yes,21,4,4,80,0,7,3,2,3,2,1,2
RM1122,36,36-45,No,Travel_Rarely,884,Sales,1,4,Life Sciences,1,1585,2,Female,73,3,2,Sales Executive,3,Single,6815,5k-10k,21447,6,Y,No,13,3,1,80,0,15,5,3,1,0,0,0
RM1129,36,36-45,No,Travel_Frequently,1302,Research & Development,6,4,Life Sciences,1,1594,1,Male,80,4,2,Laboratory Technician,1,Married,5562,5k-10k,19711,3,Y,Yes,13,3,4,80,1,9,3,3,3,2,0,2
RM1146,36,36-45,No,Travel_Rarely,559,Research & Development,12,4,Life Sciences,1,1614,3,Female,76,3,2,Manufacturing Director,3,Married,4663,Upto 5k,12421,9,Y,Yes,12,3,2,80,2,7,2,3,3,2,1,1
RM1174,36,36-45,No,Travel_Rarely,711,Research & Development,5,4,Life Sciences,1,1651,2,Female,42,3,3,Healthcare Representative,1,Married,8008,5k-10k,22792,4,Y,No,12,3,3,80,2,9,6,3,3,2,0,2
RM1181,36,36-45,No,Travel_Rarely,311,Research & Development,7,3,Life Sciences,1,1659,1,Male,77,3,1,Laboratory Technician,2,Single,2013,Upto 5k,10950,2,Y,No,11,3,3,80,0,15,4,3,4,3,1,3
RM1183,36,36-45,No,Non-Travel,894,Research & Development,1,4,Medical,1,1662,4,Female,33,2,2,Manufacturing Director,3,Married,4374,Upto 5k,15411,0,Y,No,15,3,3,80,0,4,6,3,3,2,1,2
RM1184,36,36-45,No,Travel_Rarely,1040,Research & Development,3,2,Life Sciences,1,1664,4,Male,79,4,2,Healthcare Representative,1,Divorced,6842,5k-10k,26308,6,Y,No,20,4,1,80,1,13,3,3,5,4,0,4
RM1200,36,36-45,No,Travel_Rarely,1351,Research & Development,26,4,Life Sciences,1,1682,1,Male,80,3,2,Healthcare Representative,3,Married,5347,5k-10k,7419,6,Y,No,14,3,2,80,2,10,2,2,3,2,0,2
RM1221,36,36-45,No,Travel_Rarely,530,Sales,2,4,Life Sciences,1,1710,3,Female,51,3,2,Sales Representative,4,Single,4502,Upto 5k,7439,3,Y,No,15,3,3,80,0,17,2,2,13,7,6,7
RM1237,36,36-45,Yes,Travel_Rarely,1456,Sales,13,5,Marketing,1,1733,2,Male,96,2,2,Sales Executive,1,Divorced,6134,5k-10k,8658,5,Y,Yes,13,3,2,80,3,16,3,3,2,2,2,2
RM1279,36,36-45,No,Travel_Rarely,1383,Research & Development,10,3,Life Sciences,1,1790,4,Male,90,3,3,Healthcare Representative,1,Married,8321,5k-10k,25949,7,Y,Yes,13,3,4,80,1,15,1,3,12,8,5,7
RM1316,36,36-45,No,Travel_Rarely,430,Research & Development,2,4,Other,1,1847,4,Female,73,3,2,Research Scientist,2,Married,6962,5k-10k,19573,4,Y,Yes,22,4,4,80,1,15,2,3,1,0,0,0
RM1341,36,36-45,No,Travel_Rarely,1266,Sales,10,4,Technical Degree,1,1880,2,Female,63,2,2,Sales Executive,3,Married,5673,5k-10k,6060,1,Y,Yes,13,3,1,80,1,10,4,3,10,9,1,7
RM1348,36,36-45,No,Travel_Frequently,1213,Human Resources,2,1,Human Resources,1,1890,2,Male,94,2,2,Human Resources,4,Single,3886,Upto 5k,4223,1,Y,No,21,4,4,80,0,10,2,2,10,1,0,8
RM1356,36,36-45,No,Travel_Rarely,335,Sales,17,2,Marketing,1,1908,3,Male,33,2,2,Sales Executive,2,Married,5507,5k-10k,16822,2,Y,No,16,3,3,80,2,12,1,1,4,2,1,3
RM1384,36,36-45,No,Non-Travel,1351,Research & Development,9,4,Life Sciences,1,1949,1,Male,66,4,1,Laboratory Technician,2,Married,2810,Upto 5k,9238,1,Y,No,22,4,2,80,0,5,3,3,5,4,0,2
RM1440,36,36-45,No,Travel_Rarely,557,Sales,3,3,Medical,1,2024,1,Female,94,2,3,Sales Executive,4,Married,7644,5k-10k,12695,0,Y,No,19,3,3,80,2,10,2,3,9,7,3,4
RM1441,36,36-45,No,Travel_Frequently,688,Research & Development,4,2,Life Sciences,1,2025,4,Female,97,3,2,Manufacturing Director,2,Divorced,5131,5k-10k,9192,7,Y,No,13,3,2,80,3,18,3,3,4,2,0,2
RM1448,36,36-45,No,Non-Travel,301,Sales,15,4,Marketing,1,2036,4,Male,88,1,2,Sales Executive,4,Divorced,5406,5k-10k,10436,1,Y,No,24,4,1,80,1,15,4,2,15,12,11,11
RM1454,36,36-45,No,Travel_Rarely,1120,Sales,11,4,Marketing,1,2045,2,Female,100,2,2,Sales Executive,4,Married,6652,5k-10k,14369,4,Y,No,13,3,1,80,1,8,2,2,6,3,0,0
RM1466,36,36-45,No,Travel_Frequently,884,Research & Development,23,2,Medical,1,2061,3,Male,41,4,2,Laboratory Technician,4,Married,2571,Upto 5k,12290,4,Y,No,17,3,3,80,1,17,3,3,5,2,0,3
RM1466,36,36-45,No,Travel_Frequently,884,Research & Development,23,2,Medical,1,2061,3,Male,41,4,2,Laboratory Technician,4,Married,2571,Upto 5k,12290,4,Y,No,17,3,3,80,1,17,3,3,5,2,0,2
RM003,37,36-45,Yes,Travel_Rarely,1373,Research & Development,2,2,Other,1,4,4,Male,92,2,1,Laboratory Technician,3,Single,2090,Upto 5k,2396,6,Y,Yes,15,3,2,80,0,7,3,3,0,0,0,0
RM048,37,36-45,No,Travel_Rarely,408,Research & Development,19,2,Life Sciences,1,61,2,Male,73,3,1,Research Scientist,2,Married,3022,Upto 5k,10227,4,Y,No,21,4,1,80,0,8,1,3,1,0,0,0
RM060,37,36-45,No,Travel_Rarely,1115,Research & Development,1,4,Life Sciences,1,77,1,Male,51,2,2,Manufacturing Director,3,Divorced,5993,5k-10k,2689,1,Y,No,18,3,3,80,1,7,2,4,7,5,0,7
RM079,37,36-45,No,Travel_Rarely,397,Research & Development,7,4,Medical,1,102,1,Male,30,3,3,Research Director,3,Single,13664,10k-15k,25258,4,Y,No,13,3,1,80,0,16,3,4,5,2,0,2
RM101,37,36-45,Yes,Travel_Rarely,807,Human Resources,6,4,Human Resources,1,133,3,Male,63,3,1,Human Resources,1,Divorced,2073,Upto 5k,23648,4,Y,Yes,22,4,4,80,0,7,3,3,3,2,0,2
RM105,37,36-45,No,Non-Travel,1040,Research & Development,2,2,Life Sciences,1,139,3,Male,100,2,2,Healthcare Representative,4,Divorced,5163,5k-10k,15850,5,Y,No,14,3,4,80,1,17,2,4,1,0,0,0
RM116,37,36-45,No,Travel_Rarely,1189,Sales,3,3,Life Sciences,1,152,3,Male,87,3,3,Sales Executive,4,Single,7428,5k-10k,14506,2,Y,No,12,3,1,80,0,12,3,3,5,3,1,3
RM196,37,36-45,No,Travel_Rarely,290,Research & Development,21,3,Life Sciences,1,267,2,Male,65,4,1,Research Scientist,1,Married,3564,Upto 5k,22977,1,Y,Yes,12,3,1,80,1,8,3,2,8,7,1,7
RM223,37,36-45,No,Travel_Frequently,663,Research & Development,11,3,Other,1,306,2,Male,47,3,3,Research Director,4,Divorced,12185,10k-15k,10056,1,Y,Yes,14,3,3,80,3,10,1,3,10,8,0,7
RM227,37,36-45,No,Travel_Frequently,319,Sales,4,4,Marketing,1,311,1,Male,41,3,1,Sales Representative,4,Divorced,2793,Upto 5k,2539,4,Y,No,17,3,3,80,1,13,2,3,9,8,5,8
RM249,37,36-45,No,Travel_Rarely,1017,Research & Development,1,2,Medical,1,340,3,Female,83,2,1,Research Scientist,1,Married,3920,Upto 5k,18697,2,Y,No,14,3,1,80,1,17,2,2,3,1,0,
RM251,37,36-45,Yes,Travel_Frequently,504,Research & Development,10,3,Medical,1,342,1,Male,61,3,3,Manufacturing Director,3,Divorced,10048,10k-15k,22573,6,Y,No,11,3,2,80,2,17,5,3,1,0,0,
RM274,37,36-45,No,Travel_Rarely,228,Sales,6,4,Medical,1,378,3,Male,98,3,2,Sales Executive,4,Married,6502,5k-10k,22825,4,Y,No,14,3,2,80,1,7,5,4,5,4,0,1
RM276,37,36-45,No,Non-Travel,728,Research & Development,1,4,Medical,1,380,1,Female,80,3,3,Research Director,4,Divorced,13603,10k-15k,11677,2,Y,Yes,18,3,1,80,2,15,2,3,5,2,0,2
RM286,37,36-45,No,Travel_Rarely,1372,Research & Development,1,3,Life Sciences,1,391,4,Female,42,3,1,Research Scientist,4,Single,2115,Upto 5k,15881,1,Y,No,12,3,2,80,0,17,3,3,17,12,5,7
RM295,37,36-45,No,Travel_Frequently,889,Research & Development,9,3,Medical,1,403,2,Male,53,3,1,Research Scientist,4,Married,2326,Upto 5k,11411,1,Y,Yes,12,3,3,80,3,4,3,2,4,2,1,2
RM341,37,36-45,No,Travel_Rarely,1192,Research & Development,5,2,Medical,1,460,4,Male,61,3,2,Manufacturing Director,4,Divorced,6347,5k-10k,23177,7,Y,No,16,3,3,80,2,8,2,2,6,2,0,4
RM354,37,36-45,No,Travel_Rarely,1319,Research & Development,6,3,Medical,1,474,3,Male,51,4,2,Research Scientist,1,Divorced,5974,5k-10k,17001,4,Y,Yes,13,3,1,80,2,13,2,3,7,7,6,7
RM365,37,36-45,No,Travel_Rarely,921,Research & Development,10,3,Medical,1,486,3,Female,98,3,1,Laboratory Technician,1,Married,3452,Upto 5k,17663,6,Y,No,20,4,2,80,1,17,3,3,5,4,0,3
RM387,37,36-45,No,Travel_Rarely,1107,Research & Development,14,3,Life Sciences,1,515,4,Female,95,3,1,Laboratory Technician,1,Divorced,3034,Upto 5k,26914,1,Y,No,12,3,3,80,1,18,2,2,18,7,12,17
RM390,37,36-45,No,Travel_Rarely,1305,Research & Development,10,4,Life Sciences,1,518,3,Male,49,3,2,Manufacturing Director,2,Single,4197,Upto 5k,21123,2,Y,Yes,12,3,4,80,0,18,2,2,1,0,0,1
RM399,37,36-45,No,Non-Travel,1063,Research & Development,25,5,Medical,1,529,2,Female,72,3,2,Research Scientist,3,Married,4449,Upto 5k,23866,3,Y,Yes,15,3,1,80,2,15,2,3,13,11,10,7
RM465,37,36-45,No,Travel_Rarely,799,Research & Development,1,3,Technical Degree,1,623,2,Female,59,3,3,Manufacturing Director,4,Single,7491,5k-10k,23848,4,Y,No,17,3,4,80,0,12,3,4,6,5,1,2
RM468,37,36-45,No,Non-Travel,142,Sales,9,4,Medical,1,626,1,Male,69,3,3,Sales Executive,2,Divorced,8834,5k-10k,24666,1,Y,No,13,3,4,80,1,9,6,3,9,5,7,7
RM473,37,36-45,No,Travel_Rarely,446,Research & Development,1,4,Life Sciences,1,635,2,Female,65,3,2,Manufacturing Director,2,Married,6447,5k-10k,15701,6,Y,No,12,3,2,80,1,8,2,2,6,5,4,3
RM487,37,36-45,No,Travel_Rarely,558,Sales,2,3,Marketing,1,656,4,Male,75,3,2,Sales Executive,3,Married,9602,5k-10k,3010,4,Y,Yes,11,3,3,80,1,17,3,2,3,0,1,0
RM507,37,36-45,No,Travel_Rarely,482,Research & Development,3,3,Other,1,689,3,Male,36,3,3,Manufacturing Director,3,Married,9434,5k-10k,9606,1,Y,No,15,3,3,80,1,10,2,3,10,7,7,8
RM523,37,36-45,No,Travel_Rarely,1225,Research & Development,10,2,Life Sciences,1,715,4,Male,80,4,1,Research Scientist,4,Single,4680,Upto 5k,15232,3,Y,No,17,3,1,80,0,4,2,3,1,0,0,0
RM578,37,36-45,No,Travel_Rarely,571,Research & Development,10,1,Life Sciences,1,802,4,Female,82,3,1,Research Scientist,1,Divorced,2782,Upto 5k,19905,0,Y,Yes,13,3,2,80,2,6,3,2,5,3,4,3
RM629,37,36-45,No,Travel_Rarely,342,Sales,16,4,Marketing,1,868,4,Male,66,2,2,Sales Executive,3,Divorced,6334,5k-10k,24558,4,Y,No,19,3,4,80,2,9,2,3,1,0,0,0
RM649,37,36-45,No,Travel_Frequently,1231,Sales,21,2,Medical,1,900,3,Female,54,3,1,Sales Representative,4,Married,2973,Upto 5k,21222,5,Y,No,15,3,2,80,1,10,3,3,5,4,0,0
RM653,37,36-45,No,Non-Travel,1252,Sales,19,2,Medical,1,904,1,Male,32,3,3,Sales Executive,2,Single,7642,5k-10k,4814,1,Y,Yes,13,3,4,80,0,10,2,3,10,0,0,9
RM696,37,36-45,Yes,Travel_Rarely,625,Sales,1,4,Life Sciences,1,970,1,Male,46,2,3,Sales Executive,3,Married,10609,10k-15k,14922,5,Y,No,11,3,3,80,0,17,2,1,14,1,11,7
RM745,37,36-45,Yes,Travel_Rarely,1141,Research & Development,11,2,Medical,1,1033,1,Female,61,1,2,Healthcare Representative,2,Married,4777,Upto 5k,14382,5,Y,No,15,3,1,80,0,15,2,1,1,0,0,0
RM768,37,36-45,No,Travel_Rarely,124,Research & Development,3,3,Other,1,1062,4,Female,35,3,2,Healthcare Representative,2,Single,4107,Upto 5k,13848,3,Y,No,15,3,1,80,0,8,3,2,4,3,0,1
RM796,37,36-45,No,Travel_Rarely,309,Sales,10,4,Life Sciences,1,1105,4,Female,88,2,2,Sales Executive,4,Divorced,6694,5k-10k,24223,2,Y,Yes,14,3,3,80,3,8,5,3,1,0,0,0
RM833,37,36-45,No,Travel_Rarely,367,Research & Development,25,2,Medical,1,1161,3,Female,52,2,2,Healthcare Representative,4,Divorced,5731,5k-10k,17171,7,Y,No,13,3,3,80,2,9,2,3,6,2,1,3
RM856,37,36-45,No,Travel_Rarely,977,Research & Development,1,3,Life Sciences,1,1196,4,Female,56,2,2,Manufacturing Director,4,Married,6474,5k-10k,9961,1,Y,No,13,3,2,80,1,14,2,2,14,8,3,11
RM990,37,36-45,No,Travel_Rarely,1439,Research & Development,4,1,Life Sciences,1,1394,3,Male,54,3,1,Research Scientist,3,Married,2996,Upto 5k,5182,7,Y,Yes,15,3,4,80,0,8,2,3,6,4,1,3
RM1002,37,36-45,No,Travel_Rarely,1462,Research & Development,11,3,Medical,1,1411,1,Female,94,3,1,Laboratory Technician,3,Single,3629,Upto 5k,19106,4,Y,No,18,3,1,80,0,8,6,3,3,2,0,2
RM1023,37,36-45,No,Non-Travel,1413,Research & Development,5,2,Technical Degree,1,1440,3,Male,84,4,1,Laboratory Technician,3,Single,3500,Upto 5k,25470,0,Y,No,14,3,1,80,0,7,2,1,6,5,1,3
RM1090,37,36-45,No,Travel_Rarely,674,Research & Development,13,3,Medical,1,1543,1,Male,47,3,2,Research Scientist,4,Married,4285,Upto 5k,3031,1,Y,No,17,3,1,80,0,10,2,3,10,8,3,7
RM1159,37,36-45,No,Travel_Rarely,671,Research & Development,19,3,Life Sciences,1,1631,3,Male,85,3,2,Manufacturing Director,3,Married,5768,5k-10k,26493,3,Y,No,17,3,1,80,3,9,2,2,4,3,0,2
RM1164,37,36-45,No,Travel_Rarely,1470,Research & Development,10,3,Medical,1,1640,2,Female,71,3,1,Research Scientist,2,Married,3936,Upto 5k,9953,1,Y,No,11,3,1,80,1,8,2,1,8,4,7,7
RM1212,37,36-45,No,Travel_Frequently,1278,Sales,1,4,Medical,1,1700,3,Male,31,1,2,Sales Executive,4,Divorced,9525,5k-10k,7677,1,Y,No,14,3,3,80,2,6,2,2,6,3,1,3
RM1277,37,36-45,No,Travel_Rarely,589,Sales,9,2,Marketing,1,1787,2,Male,46,2,2,Sales Executive,2,Married,4189,Upto 5k,8800,1,Y,No,14,3,1,80,2,5,2,3,5,2,0,3
RM1281,37,36-45,No,Travel_Rarely,1239,Human Resources,8,2,Other,1,1794,3,Male,89,3,2,Human Resources,2,Divorced,4071,Upto 5k,12832,2,Y,No,13,3,3,80,0,19,4,2,10,0,4,7
RM1292,37,36-45,Yes,Travel_Rarely,370,Research & Development,10,4,Medical,1,1809,4,Male,58,3,2,Manufacturing Director,1,Single,4213,Upto 5k,4992,1,Y,No,15,3,2,80,0,10,4,1,10,3,0,8
RM1345,37,36-45,No,Travel_Rarely,783,Research & Development,7,4,Medical,1,1885,4,Male,78,3,2,Research Scientist,1,Married,4284,Upto 5k,13588,5,Y,Yes,22,4,3,80,1,16,2,3,5,3,0,4
RM1433,37,36-45,No,Travel_Rarely,161,Research & Development,10,3,Life Sciences,1,2017,3,Female,42,4,3,Research Director,4,Married,13744,10k-15k,15471,1,Y,Yes,25,4,1,80,1,16,2,3,16,11,6,8
RM009,38,36-45,No,Travel_Frequently,216,Research & Development,23,3,Life Sciences,1,12,4,Male,44,2,3,Manufacturing Director,3,Single,9526,5k-10k,8787,0,Y,No,21,4,2,80,0,10,2,3,9,7,1,
RM020,38,36-45,No,Travel_Rarely,371,Research & Development,2,3,Life Sciences,1,24,4,Male,45,3,1,Research Scientist,4,Single,3944,Upto 5k,4306,5,Y,Yes,11,3,3,80,0,6,3,3,3,2,1,2
RM062,38,36-45,No,Travel_Frequently,653,Research & Development,29,5,Life Sciences,1,79,4,Female,50,3,2,Laboratory Technician,4,Single,2406,Upto 5k,5456,1,Y,No,11,3,4,80,0,10,2,3,10,3,9,9
RM084,38,36-45,No,Non-Travel,573,Research & Development,6,3,Medical,1,107,2,Female,79,1,2,Research Scientist,4,Divorced,5329,5k-10k,15717,7,Y,Yes,12,3,4,80,3,17,3,3,13,11,1,9
RM143,38,36-45,No,Travel_Rarely,364,Research & Development,3,5,Technical Degree,1,193,4,Female,32,3,2,Research Scientist,3,Single,4317,Upto 5k,2302,3,Y,Yes,20,4,2,80,0,19,2,3,3,2,2,
RM169,38,36-45,No,Travel_Rarely,702,Sales,1,4,Life Sciences,1,230,1,Female,59,2,2,Sales Executive,4,Single,8686,5k-10k,12930,4,Y,No,22,4,3,80,0,12,2,4,8,3,0,7
RM180,38,36-45,No,Travel_Rarely,1380,Research & Development,9,2,Life Sciences,1,245,3,Female,75,3,1,Laboratory Technician,4,Single,2288,Upto 5k,6319,1,Y,No,12,3,3,80,0,2,3,3,2,2,2,1
RM199,38,36-45,No,Travel_Rarely,1261,Research & Development,2,4,Life Sciences,1,271,4,Male,88,3,2,Manufacturing Director,3,Married,6553,5k-10k,7259,9,Y,No,14,3,2,80,0,14,3,3,1,0,0,0
RM200,38,36-45,No,Travel_Rarely,1084,Research & Development,29,3,Technical Degree,1,273,4,Male,54,3,2,Manufacturing Director,4,Married,6261,5k-10k,4185,3,Y,No,18,3,1,80,1,9,3,1,7,7,1,7
RM205,38,36-45,Yes,Travel_Rarely,1180,Research & Development,29,1,Medical,1,282,2,Male,70,3,2,Healthcare Representative,1,Married,6673,5k-10k,11354,7,Y,Yes,19,3,2,80,0,17,2,3,1,0,0,0
RM224,38,36-45,No,Travel_Rarely,119,Sales,3,3,Life Sciences,1,307,1,Male,76,3,3,Sales Executive,3,Divorced,10609,10k-15k,9647,0,Y,No,12,3,3,80,2,17,6,2,16,10,5,13
RM262,38,36-45,No,Non-Travel,1327,Sales,2,2,Life Sciences,1,361,4,Male,39,2,2,Sales Executive,4,Married,5249,5k-10k,19682,3,Y,No,18,3,4,80,1,13,0,3,8,7,7,5
RM278,38,36-45,No,Travel_Rarely,322,Sales,7,2,Medical,1,382,1,Female,44,4,2,Sales Executive,1,Divorced,5605,5k-10k,19191,1,Y,Yes,24,4,3,80,1,8,3,3,8,0,7,7
RM288,38,36-45,No,Travel_Rarely,688,Research & Development,23,4,Life Sciences,1,393,4,Male,82,3,2,Healthcare Representative,4,Divorced,5745,5k-10k,18899,9,Y,No,14,3,2,80,1,10,2,3,2,2,1,2
RM308,38,36-45,No,Travel_Rarely,849,Research & Development,25,2,Life Sciences,1,421,1,Female,81,2,3,Research Director,2,Married,12061,10k-15k,26707,3,Y,No,17,3,3,80,1,19,2,3,10,8,0,1
RM342,38,36-45,No,Travel_Rarely,343,Research & Development,15,2,Life Sciences,1,461,3,Male,92,2,3,Research Director,4,Divorced,11510,10k-15k,15682,0,Y,Yes,14,3,2,80,1,12,3,3,11,10,2,9
RM417,38,36-45,No,Travel_Frequently,1490,Research & Development,2,2,Life Sciences,1,556,4,Male,42,3,1,Laboratory Technician,4,Married,1702,Upto 5k,12106,1,Y,Yes,23,4,3,80,1,1,3,3,1,0,0,0
RM472,38,36-45,No,Travel_Rarely,1495,Research & Development,10,3,Medical,1,634,3,Female,76,3,2,Healthcare Representative,3,Married,9824,5k-10k,22174,3,Y,No,19,3,3,80,1,18,4,3,1,0,0,0
RM491,38,36-45,No,Travel_Rarely,362,Research & Development,1,1,Life Sciences,1,662,3,Female,43,3,1,Research Scientist,1,Single,2619,Upto 5k,14561,3,Y,No,17,3,4,80,0,8,3,2,0,0,0,0
RM519,38,36-45,No,Travel_Rarely,243,Sales,7,4,Marketing,1,709,4,Female,46,2,2,Sales Executive,4,Single,4028,Upto 5k,7791,0,Y,No,20,4,1,80,0,8,2,3,7,7,0,5
RM530,38,36-45,No,Travel_Rarely,827,Research & Development,1,4,Life Sciences,1,724,2,Female,33,4,2,Healthcare Representative,4,Single,7625,5k-10k,19383,0,Y,No,13,3,3,80,0,10,4,2,9,7,1,8
RM543,38,36-45,No,Travel_Rarely,168,Research & Development,1,3,Life Sciences,1,743,3,Female,81,3,3,Manufacturing Director,3,Single,7861,5k-10k,15397,4,Y,Yes,14,3,4,80,0,10,4,4,1,0,0,0
RM560,38,36-45,No,Travel_Rarely,268,Research & Development,2,5,Medical,1,773,4,Male,92,3,1,Research Scientist,3,Married,3057,Upto 5k,20471,6,Y,Yes,13,3,2,80,1,6,0,1,1,0,0,1
RM579,38,36-45,No,Travel_Frequently,240,Research & Development,2,4,Life Sciences,1,803,1,Female,75,4,2,Manufacturing Director,1,Single,5980,5k-10k,26085,6,Y,Yes,12,3,4,80,0,17,2,3,15,7,4,12
RM606,38,36-45,No,Travel_Frequently,471,Research & Development,12,3,Life Sciences,1,837,1,Male,45,2,2,Healthcare Representative,1,Divorced,6288,5k-10k,4284,2,Y,No,15,3,3,80,1,13,3,2,4,3,1,2
RM643,38,36-45,No,Travel_Rarely,395,Sales,9,3,Marketing,1,893,2,Male,98,2,1,Sales Representative,2,Married,2899,Upto 5k,12102,0,Y,No,19,3,4,80,1,3,3,3,2,2,1,2
RM682,38,36-45,No,Travel_Rarely,1333,Research & Development,1,3,Technical Degree,1,950,4,Female,80,3,3,Research Director,1,Married,13582,10k-15k,16292,1,Y,No,13,3,2,80,1,15,3,3,15,12,5,11
RM704,38,36-45,No,Non-Travel,152,Sales,10,3,Technical Degree,1,983,3,Female,85,3,2,Sales Executive,4,Single,5666,5k-10k,19899,1,Y,Yes,13,3,2,80,0,6,1,3,5,3,1,3
RM723,38,36-45,No,Travel_Frequently,1391,Research & Development,10,1,Medical,1,1006,3,Male,66,3,1,Research Scientist,3,Married,2684,Upto 5k,12127,0,Y,No,17,3,2,80,1,3,0,2,2,1,0,2
RM748,38,36-45,No,Travel_Rarely,1035,Sales,3,4,Life Sciences,1,1036,2,Male,42,3,2,Sales Executive,4,Single,6861,5k-10k,4981,8,Y,Yes,12,3,3,80,0,19,1,3,1,0,0,0
RM766,38,36-45,No,Travel_Frequently,1186,Research & Development,3,4,Other,1,1060,3,Male,44,3,1,Research Scientist,3,Married,2821,Upto 5k,2997,3,Y,No,16,3,1,80,1,8,2,3,2,2,2,2
RM785,38,36-45,No,Travel_Rarely,330,Research & Development,17,1,Life Sciences,1,1088,3,Female,65,2,3,Healthcare Representative,3,Married,8823,5k-10k,24608,0,Y,No,18,3,1,80,1,20,4,2,19,9,1,9
RM808,38,36-45,No,Travel_Rarely,770,Sales,10,4,Marketing,1,1119,3,Male,73,2,3,Sales Executive,3,Divorced,8740,5k-10k,5569,0,Y,Yes,14,3,2,80,2,9,2,3,8,7,2,7
RM812,38,36-45,No,Travel_Rarely,130,Sales,2,2,Marketing,1,1125,4,Male,32,3,3,Sales Executive,2,Single,7351,5k-10k,20619,7,Y,No,16,3,3,80,0,10,2,3,1,0,0,0
RM827,38,36-45,No,Travel_Rarely,433,Human Resources,1,3,Human Resources,1,1152,3,Male,37,4,1,Human Resources,3,Married,2844,Upto 5k,6004,1,Y,No,13,3,4,80,1,7,2,4,7,6,5,0
RM964,38,36-45,No,Travel_Rarely,1009,Sales,2,2,Life Sciences,1,1355,2,Female,31,3,2,Sales Executive,1,Divorced,6893,5k-10k,19461,3,Y,No,15,3,4,80,1,11,3,3,7,7,1,7
RM983,38,36-45,No,Travel_Frequently,693,Research & Development,7,3,Life Sciences,1,1382,4,Male,57,4,1,Research Scientist,3,Divorced,2610,Upto 5k,15748,1,Y,No,11,3,4,80,3,4,2,3,4,2,0,3
RM1108,38,36-45,No,Travel_Frequently,888,Human Resources,10,4,Human Resources,1,1563,3,Male,71,3,2,Human Resources,3,Married,6077,5k-10k,14814,3,Y,No,11,3,3,80,0,10,2,3,6,3,1,2
RM1113,38,36-45,Yes,Travel_Rarely,903,Research & Development,2,3,Medical,1,1573,3,Male,81,3,2,Manufacturing Director,2,Married,4855,Upto 5k,7653,4,Y,No,11,3,1,80,2,7,2,3,5,2,1,4
RM1120,38,36-45,No,Travel_Rarely,1245,Sales,14,3,Life Sciences,1,1582,3,Male,80,3,2,Sales Executive,2,Married,9924,5k-10k,12355,0,Y,No,11,3,4,80,1,10,3,3,9,8,7,7
RM1121,38,36-45,No,Travel_Rarely,437,Sales,16,3,Life Sciences,1,1583,2,Female,90,3,2,Sales Executive,2,Single,4198,Upto 5k,16379,2,Y,No,12,3,2,80,0,8,5,4,3,2,1,2
RM1162,38,36-45,No,Travel_Rarely,397,Research & Development,2,2,Medical,1,1638,4,Female,54,2,3,Manufacturing Director,3,Married,7756,5k-10k,14199,3,Y,Yes,19,3,4,80,1,10,6,4,5,4,0,2
RM1188,38,36-45,No,Travel_Frequently,1189,Research & Development,1,3,Life Sciences,1,1668,4,Male,90,3,2,Research Scientist,4,Married,4735,Upto 5k,9867,7,Y,No,15,3,4,80,2,19,4,4,13,11,2,9
RM1194,38,36-45,No,Travel_Frequently,148,Research & Development,2,3,Medical,1,1675,4,Female,42,2,1,Laboratory Technician,2,Single,2440,Upto 5k,23826,1,Y,No,22,4,2,80,0,4,3,3,4,3,3,3
RM1203,38,36-45,No,Travel_Rarely,1495,Research & Development,4,2,Medical,1,1687,4,Female,87,3,1,Laboratory Technician,3,Married,3306,Upto 5k,26176,7,Y,No,19,3,4,80,1,7,5,2,0,0,0,0
RM1257,38,36-45,No,Travel_Frequently,594,Research & Development,2,2,Medical,1,1760,3,Female,75,2,1,Laboratory Technician,2,Married,2468,Upto 5k,15963,4,Y,No,14,3,2,80,1,9,4,2,6,1,0,5
RM1262,38,36-45,No,Travel_Rarely,833,Research & Development,18,3,Medical,1,1766,2,Male,60,1,2,Healthcare Representative,4,Married,5811,5k-10k,24539,3,Y,Yes,16,3,3,80,1,15,2,3,1,0,1,0
RM1273,38,36-45,No,Travel_Rarely,1153,Research & Development,6,2,Other,1,1782,4,Female,40,2,1,Laboratory Technician,3,Married,3702,Upto 5k,16376,1,Y,No,11,3,2,80,1,5,3,3,5,4,0,4
RM1290,38,36-45,No,Non-Travel,1336,Human Resources,2,3,Human Resources,1,1805,1,Male,100,3,1,Human Resources,2,Divorced,2592,Upto 5k,7129,5,Y,No,13,3,4,80,3,13,3,3,11,10,3,8
RM1309,38,36-45,No,Travel_Rarely,723,Sales,2,4,Marketing,1,1835,2,Female,77,1,2,Sales Representative,4,Married,5405,5k-10k,4244,2,Y,Yes,20,4,1,80,2,20,4,2,4,2,0,3
RM1374,38,36-45,No,Travel_Frequently,1394,Research & Development,8,3,Medical,1,1937,4,Female,58,2,2,Research Scientist,2,Divorced,2133,Upto 5k,18115,1,Y,Yes,16,3,3,80,1,20,3,3,20,11,0,7
RM1377,38,36-45,No,Travel_Rarely,1206,Research & Development,9,2,Life Sciences,1,1940,2,Male,71,3,1,Research Scientist,4,Divorced,4771,Upto 5k,14293,2,Y,No,19,3,4,80,2,10,0,4,5,2,0,3
RM1392,38,36-45,No,Travel_Rarely,1404,Sales,1,3,Life Sciences,1,1961,1,Male,59,2,1,Sales Representative,1,Single,2858,Upto 5k,11473,4,Y,No,14,3,1,80,0,20,3,2,1,0,0,0
RM1401,38,36-45,No,Travel_Frequently,1444,Human Resources,1,4,Other,1,1972,4,Male,88,3,1,Human Resources,2,Married,2991,Upto 5k,5224,0,Y,Yes,11,3,2,80,1,7,2,3,6,2,1,2
RM1417,38,36-45,No,Travel_Rarely,1321,Sales,1,4,Life Sciences,1,1995,4,Male,86,3,2,Sales Executive,2,Married,4440,Upto 5k,7636,0,Y,No,15,3,1,80,2,16,3,3,15,13,5,8
RM1419,38,36-45,No,Travel_Frequently,508,Research & Development,6,4,Life Sciences,1,1997,1,Male,72,2,2,Manufacturing Director,3,Married,5321,5k-10k,14284,2,Y,No,11,3,4,80,1,10,1,3,8,3,7,7
RM1431,38,36-45,No,Travel_Rarely,201,Research & Development,10,3,Medical,1,2015,2,Female,99,1,3,Research Director,3,Married,13206,10k-15k,3376,3,Y,No,12,3,1,80,1,20,3,3,18,16,1,11
RM1452,38,36-45,No,TravelRarely,345,Sales,10,2,Life Sciences,1,2041,1,Female,100,3,2,Sales Executive,4,Married,5343,5k-10k,5982,1,Y,No,11,3,3,80,1,10,1,3,10,7,1,9
RM034,39,36-45,Yes,Travel_Rarely,895,Sales,5,3,Technical Degree,1,42,4,Male,56,3,2,Sales Representative,4,Married,2086,Upto 5k,3335,3,Y,No,14,3,3,80,1,19,6,4,1,0,0,0
RM138,39,36-45,No,Travel_Rarely,1329,Sales,4,4,Life Sciences,1,182,4,Female,47,2,2,Sales Executive,3,Married,5902,5k-10k,14590,4,Y,No,14,3,3,80,1,17,1,4,15,11,5,9
RM241,39,36-45,No,Travel_Rarely,1431,Research & Development,1,4,Medical,1,332,3,Female,96,3,1,Laboratory Technician,3,Divorced,2232,Upto 5k,15417,7,Y,No,14,3,3,80,3,7,1,3,3,2,1,2
RM252,39,36-45,No,Travel_Frequently,505,Research & Development,2,4,Technical Degree,1,343,3,Female,64,3,3,Healthcare Representative,3,Single,10938,10k-15k,6420,0,Y,No,25,4,4,80,0,20,1,3,19,6,11,
RM305,39,36-45,No,Travel_Rarely,1132,Research & Development,1,3,Medical,1,417,3,Male,48,4,3,Healthcare Representative,4,Divorced,9613,5k-10k,10942,0,Y,No,17,3,1,80,3,19,5,2,18,10,3,7
RM315,39,36-45,No,Travel_Rarely,117,Research & Development,10,1,Medical,1,429,3,Male,99,3,4,Manager,1,Married,17068,15k+,5355,1,Y,Yes,14,3,4,80,0,21,3,3,21,9,11,10
RM327,39,36-45,No,Travel_Frequently,672,Research & Development,7,2,Medical,1,444,3,Male,54,2,5,Manager,4,Married,19272,15k+,21141,1,Y,No,15,3,1,80,1,21,2,3,21,9,13,3
RM328,39,36-45,Yes,Travel_Rarely,1162,Sales,3,2,Medical,1,445,4,Female,41,3,2,Sales Executive,3,Married,5238,5k-10k,17778,4,Y,Yes,18,3,1,80,0,12,3,2,1,0,0,0
RM401,39,36-45,No,Travel_Frequently,1218,Research & Development,1,1,Life Sciences,1,531,2,Male,52,3,5,Manager,3,Divorced,19197,15k+,8213,1,Y,Yes,14,3,3,80,1,21,3,3,21,8,1,6
RM450,39,36-45,No,Travel_Frequently,443,Research & Development,8,1,Life Sciences,1,602,3,Female,48,3,1,Laboratory Technician,3,Married,3755,Upto 5k,17872,1,Y,No,11,3,1,80,1,8,3,3,8,3,0,7
RM527,39,36-45,No,Travel_Rarely,408,Research & Development,2,4,Technical Degree,1,721,4,Female,80,2,2,Healthcare Representative,3,Single,4553,Upto 5k,20978,1,Y,No,11,3,1,80,0,20,4,3,20,7,11,10
RM552,39,36-45,No,Travel_Rarely,141,Human Resources,3,3,Human Resources,1,760,3,Female,44,4,2,Human Resources,2,Married,6389,5k-10k,18767,9,Y,No,15,3,3,80,1,12,3,1,8,3,3,6
RM655,39,36-45,No,Travel_Rarely,1383,Human Resources,2,3,Life Sciences,1,909,4,Female,42,2,2,Human Resources,4,Married,5204,5k-10k,7790,8,Y,No,11,3,3,80,2,13,2,3,5,4,0,4
RM670,39,36-45,Yes,Travel_Rarely,1122,Research & Development,6,3,Medical,1,932,4,Male,70,3,1,Laboratory Technician,1,Married,2404,Upto 5k,4303,7,Y,Yes,21,4,4,80,0,8,2,1,2,2,2,2
RM706,39,36-45,No,Travel_Rarely,903,Sales,2,5,Life Sciences,1,985,1,Male,41,4,3,Sales Executive,3,Single,7880,5k-10k,2560,0,Y,No,18,3,4,80,0,9,3,3,8,7,0,7
RM739,39,36-45,No,Travel_Rarely,466,Research & Development,1,1,Life Sciences,1,1026,4,Female,65,2,4,Manufacturing Director,4,Married,12742,10k-15k,7060,1,Y,No,16,3,3,80,1,21,3,3,21,6,11,8
RM754,39,36-45,No,Travel_Frequently,945,Research & Development,22,3,Medical,1,1043,4,Female,82,3,3,Manufacturing Director,1,Single,10880,10k-15k,5083,1,Y,Yes,13,3,3,80,0,21,2,3,21,6,2,8
RM814,39,36-45,Yes,Travel_Frequently,203,Research & Development,2,3,Life Sciences,1,1127,1,Male,84,3,4,Healthcare Representative,4,Divorced,12169,10k-15k,13547,7,Y,No,11,3,4,80,3,21,4,3,18,7,11,5
RM817,39,36-45,No,Non-Travel,439,Research & Development,9,3,Life Sciences,1,1132,3,Male,70,3,2,Laboratory Technician,2,Single,6782,5k-10k,8770,9,Y,No,15,3,3,80,0,9,2,2,5,4,0,3
RM938,39,36-45,No,Travel_Rarely,412,Research & Development,13,4,Medical,1,1307,3,Female,94,2,4,Manager,2,Divorced,17123,15k+,17334,6,Y,Yes,13,3,4,80,2,21,4,3,19,9,15,2
RM941,39,36-45,Yes,Travel_Rarely,360,Research & Development,23,3,Medical,1,1310,3,Male,93,3,1,Research Scientist,1,Single,3904,Upto 5k,22154,0,Y,No,13,3,1,80,0,6,2,3,5,2,0,3
RM950,39,36-45,No,Travel_Rarely,524,Research & Development,18,2,Life Sciences,1,1322,1,Male,32,3,2,Manufacturing Director,3,Single,4534,Upto 5k,13352,0,Y,No,11,3,1,80,0,9,6,3,8,7,1,7
RM987,39,36-45,No,Travel_Rarely,1498,Sales,21,4,Life Sciences,1,1390,1,Male,44,2,2,Sales Executive,4,Married,6120,5k-10k,3567,3,Y,Yes,12,3,4,80,2,8,2,4,5,4,1,4
RM993,39,36-45,No,Non-Travel,1485,Research & Development,25,2,Life Sciences,1,1397,3,Male,71,3,3,Healthcare Representative,3,Married,10920,10k-15k,3449,3,Y,No,21,4,2,80,1,13,2,3,6,4,0,5
RM1033,39,36-45,Yes,Non-Travel,592,Research & Development,2,3,Life Sciences,1,1458,1,Female,54,2,1,Laboratory Technician,1,Single,3646,Upto 5k,17181,2,Y,Yes,23,4,2,80,0,11,2,4,1,0,0,0
RM1080,39,36-45,No,Travel_Rarely,1089,Research & Development,6,3,Life Sciences,1,1525,2,Female,32,3,3,Manufacturing Director,2,Single,8376,5k-10k,9150,4,Y,No,18,3,4,80,0,9,3,3,2,0,2,2
RM1125,39,36-45,No,Travel_Rarely,1462,Sales,6,3,Medical,1,1588,4,Male,38,4,3,Sales Executive,3,Married,8237,5k-10k,4658,2,Y,No,11,3,1,80,1,11,3,3,7,6,7,6
RM1149,39,36-45,No,Travel_Rarely,1387,Research & Development,10,5,Medical,1,1618,2,Male,76,3,2,Manufacturing Director,1,Married,5377,5k-10k,3835,2,Y,No,13,3,4,80,3,10,3,3,7,7,7,7
RM1156,39,36-45,No,Travel_Rarely,170,Research & Development,3,2,Medical,1,1627,3,Male,76,2,2,Laboratory Technician,3,Divorced,3069,Upto 5k,10302,0,Y,No,15,3,4,80,1,11,3,3,10,8,0,7
RM1160,39,36-45,No,Travel_Frequently,711,Research & Development,4,3,Medical,1,1633,1,Female,81,3,2,Manufacturing Director,3,Single,5042,5k-10k,3140,0,Y,No,13,3,4,80,0,10,2,1,9,2,3,8
RM1176,39,36-45,No,Travel_Rarely,492,Research & Development,12,3,Medical,1,1654,4,Male,66,3,2,Manufacturing Director,2,Married,5295,5k-10k,7693,4,Y,No,21,4,3,80,0,7,3,3,5,4,1,0
RM1241,39,36-45,No,Non-Travel,792,Research & Development,1,3,Life Sciences,1,1737,4,Male,77,3,2,Laboratory Technician,4,Married,6472,5k-10k,8989,1,Y,Yes,15,3,4,80,1,9,2,3,9,8,5,8
RM1285,39,36-45,No,Travel_Rarely,1253,Research & Development,10,1,Medical,1,1800,3,Male,65,3,3,Research Director,3,Single,13464,10k-15k,7914,7,Y,No,21,4,3,80,0,9,3,3,4,3,2,2
RM1293,39,36-45,No,Travel_Frequently,766,Sales,20,3,Life Sciences,1,1812,3,Male,83,3,2,Sales Executive,4,Divorced,4127,Upto 5k,19188,2,Y,No,18,3,4,80,1,7,6,3,2,1,2,2
RM1336,39,36-45,No,Travel_Rarely,835,Research & Development,19,4,Other,1,1871,4,Male,41,3,2,Research Scientist,4,Divorced,3902,Upto 5k,5141,8,Y,No,14,3,2,80,3,7,2,3,2,2,2,2
RM1367,39,36-45,No,Non-Travel,1251,Sales,21,4,Life Sciences,1,1929,1,Female,32,1,2,Sales Executive,3,Married,5736,5k-10k,3987,6,Y,No,19,3,3,80,1,10,1,3,3,2,1,2
RM1373,39,36-45,No,Travel_Rarely,867,Research & Development,9,2,Medical,1,1936,1,Male,87,3,2,Manufacturing Director,1,Married,5151,5k-10k,12315,1,Y,No,25,4,4,80,1,10,3,3,10,0,7,9
RM1404,39,36-45,No,Travel_Rarely,119,Sales,15,4,Marketing,1,1975,2,Male,77,3,4,Sales Executive,1,Single,13341,10k-15k,25098,0,Y,No,12,3,1,80,0,21,3,3,20,8,11,10
RM1430,39,36-45,No,Travel_Rarely,116,Research & Development,24,1,Life Sciences,1,2014,1,Male,52,3,2,Research Scientist,4,Single,4108,Upto 5k,5340,7,Y,No,13,3,1,80,0,18,2,3,7,7,1,7
RM1438,39,36-45,No,Non-Travel,105,Research & Development,9,3,Life Sciences,1,2022,4,Male,87,3,5,Manager,4,Single,19431,15k+,15302,2,Y,No,13,3,3,80,0,21,3,2,6,0,1,3
RM1463,39,36-45,No,Travel_Rarely,722,Sales,24,1,Marketing,1,2056,2,Female,60,2,4,Sales Executive,4,Married,12031,10k-15k,8828,0,Y,No,11,3,1,80,1,21,2,2,20,9,9,6
RM1467,39,36-45,No,Travel_Rarely,613,Research & Development,6,1,Medical,1,2062,4,Male,42,2,3,Healthcare Representative,1,Married,9991,5k-10k,21457,4,Y,No,15,3,1,80,1,9,5,3,7,7,1,7
RM1463,39,36-45,No,Travel_Rarely,722,Sales,24,1,Marketing,1,2056,2,Female,60,2,4,Sales Executive,4,Married,12031,10k-15k,8828,0,Y,No,11,3,1,80,1,21,2,2,20,9,9,6
RM1467,39,36-45,No,Travel_Rarely,613,Research & Development,6,1,Medical,1,2062,4,Male,42,2,3,Healthcare Representative,1,Married,9991,5k-10k,21457,4,Y,No,15,3,1,80,1,9,5,3,7,7,1,1
RM091,40,36-45,No,Travel_Frequently,530,Research & Development,1,4,Life Sciences,1,119,3,Male,78,2,4,Healthcare Representative,2,Married,13503,10k-15k,14115,1,Y,No,22,4,4,80,1,22,3,2,22,3,11,11
RM151,40,36-45,No,Travel_Frequently,1395,Research & Development,26,3,Medical,1,202,2,Female,54,3,2,Research Scientist,2,Divorced,5605,5k-10k,8504,1,Y,No,11,3,1,80,1,20,2,3,20,7,2,13
RM159,40,36-45,No,Travel_Rarely,630,Sales,4,4,Marketing,1,215,3,Male,67,2,3,Sales Executive,4,Married,10855,10k-15k,8552,7,Y,No,11,3,1,80,1,15,2,2,12,11,2,11
RM187,40,36-45,No,Travel_Rarely,989,Research & Development,4,1,Medical,1,253,4,Female,46,3,5,Manager,3,Married,19033,15k+,6499,1,Y,No,14,3,2,80,1,21,2,3,20,8,9,9
RM204,40,36-45,No,Travel_Rarely,905,Research & Development,19,2,Medical,1,281,3,Male,99,3,2,Laboratory Technician,4,Married,2741,Upto 5k,16523,8,Y,Yes,15,3,3,80,1,15,2,4,7,2,3,7
RM209,40,36-45,No,Non-Travel,1151,Research & Development,9,5,Life Sciences,1,287,4,Male,63,2,2,Healthcare Representative,4,Married,4876,Upto 5k,14242,9,Y,No,14,3,4,80,1,5,5,1,3,2,0,
RM244,40,36-45,No,Travel_Rarely,1300,Research & Development,24,2,Technical Degree,1,335,1,Male,62,3,2,Research Scientist,4,Divorced,3319,Upto 5k,24447,1,Y,No,17,3,1,80,2,9,3,3,9,8,4,7
RM258,40,36-45,No,Travel_Rarely,1416,Research & Development,2,2,Medical,1,352,1,Male,49,3,5,Research Director,3,Divorced,19436,15k+,5949,0,Y,No,19,3,4,80,1,22,5,3,21,7,3,
RM336,40,36-45,No,Travel_Rarely,1124,Sales,1,2,Medical,1,453,2,Male,57,1,2,Sales Executive,4,Married,7457,5k-10k,13273,2,Y,Yes,22,4,3,80,3,6,2,2,4,3,0,2
RM362,40,36-45,No,Travel_Rarely,1171,Research & Development,10,4,Life Sciences,1,483,4,Female,46,4,1,Laboratory Technician,3,Married,2213,Upto 5k,22495,3,Y,Yes,13,3,3,80,1,10,3,3,7,7,1,
RM369,40,36-45,Yes,Travel_Rarely,575,Sales,22,2,Marketing,1,492,3,Male,68,2,2,Sales Executive,3,Married,6380,5k-10k,6110,2,Y,Yes,12,3,1,80,2,8,6,3,6,4,1,0
RM388,40,36-45,No,Travel_Rarely,759,Sales,2,2,Marketing,1,516,4,Female,46,3,2,Sales Executive,2,Divorced,5715,5k-10k,22553,7,Y,No,12,3,3,80,2,8,5,3,5,4,1,3
RM392,40,36-45,No,Travel_Rarely,555,Research & Development,2,3,Medical,1,521,2,Female,78,2,2,Laboratory Technician,3,Married,3448,Upto 5k,13436,6,Y,No,22,4,2,80,1,20,3,3,1,0,0,0
RM418,40,36-45,No,Travel_Rarely,1398,Sales,2,4,Life Sciences,1,558,3,Female,79,3,5,Manager,3,Married,18041,15k+,13022,0,Y,No,14,3,4,80,0,21,2,3,20,15,1,12
RM449,40,36-45,No,Travel_Rarely,302,Research & Development,6,3,Life Sciences,1,601,2,Female,75,3,4,Manufacturing Director,3,Single,13237,10k-15k,20364,7,Y,No,15,3,3,80,0,22,3,3,20,6,5,13
RM459,40,36-45,No,Non-Travel,1094,Sales,28,3,Other,1,615,3,Male,58,1,3,Sales Executive,1,Divorced,10932,10k-15k,11373,3,Y,No,15,3,3,80,1,20,2,3,1,0,0,1
RM534,40,36-45,No,Travel_Frequently,580,Sales,5,4,Life Sciences,1,729,4,Male,48,2,3,Sales Executive,1,Married,10475,10k-15k,23772,5,Y,Yes,21,4,3,80,1,20,2,3,18,13,1,12
RM554,40,36-45,No,Travel_Rarely,804,Research & Development,2,1,Medical,1,763,4,Female,86,2,1,Research Scientist,4,Single,2342,Upto 5k,22929,0,Y,Yes,20,4,4,80,0,5,2,2,4,2,2,3
RM583,40,36-45,No,Travel_Frequently,791,Research & Development,2,2,Medical,1,807,3,Female,38,4,2,Healthcare Representative,2,Married,4244,Upto 5k,9931,1,Y,No,24,4,4,80,1,8,2,3,8,7,3,7
RM602,40,36-45,No,Travel_Frequently,720,Research & Development,16,4,Medical,1,832,1,Male,51,2,2,Laboratory Technician,3,Single,5094,5k-10k,11983,6,Y,No,14,3,4,80,0,10,6,3,1,0,0,0
RM685,40,36-45,No,Travel_Rarely,658,Sales,10,4,Marketing,1,954,1,Male,67,2,3,Sales Executive,2,Divorced,9705,5k-10k,20652,2,Y,No,12,3,2,80,1,11,2,2,1,0,0,0
RM692,40,36-45,No,Travel_Frequently,1469,Research & Development,9,4,Medical,1,964,4,Male,35,3,1,Research Scientist,2,Divorced,3617,Upto 5k,25063,8,Y,Yes,14,3,4,80,1,3,2,3,1,1,0,0
RM707,40,36-45,Yes,Non-Travel,1479,Sales,24,3,Life Sciences,1,986,2,Female,100,4,4,Sales Executive,2,Single,13194,10k-15k,17071,4,Y,Yes,16,3,4,80,0,22,2,2,1,0,0,0
RM769,40,36-45,No,Travel_Rarely,300,Sales,26,3,Marketing,1,1066,3,Male,74,3,2,Sales Executive,1,Married,8396,5k-10k,22217,1,Y,No,14,3,2,80,1,8,3,2,7,7,7,5
RM786,40,36-45,No,Travel_Rarely,1492,Research & Development,20,4,Technical Degree,1,1092,1,Male,61,3,3,Healthcare Representative,4,Married,10322,10k-15k,26542,4,Y,No,20,4,4,80,1,14,6,3,11,10,11,1
RM815,40,36-45,No,Travel_Rarely,1308,Research & Development,14,3,Medical,1,1128,3,Male,44,2,5,Research Director,3,Single,19626,15k+,17544,1,Y,No,14,3,1,80,0,21,2,4,20,7,4,9
RM838,40,36-45,No,Travel_Frequently,593,Research & Development,9,4,Medical,1,1166,2,Female,88,3,3,Research Director,3,Single,13499,10k-15k,13782,9,Y,No,17,3,3,80,0,20,3,2,18,7,2,13
RM846,40,36-45,No,Travel_Frequently,902,Research & Development,26,2,Medical,1,1180,3,Female,92,2,2,Research Scientist,4,Married,4422,Upto 5k,21203,3,Y,Yes,13,3,4,80,1,16,3,1,1,1,0,0
RM867,40,36-45,No,Travel_Frequently,1184,Sales,2,4,Medical,1,1212,2,Male,62,3,2,Sales Executive,2,Married,4327,Upto 5k,25440,5,Y,No,12,3,4,80,3,5,2,3,0,0,0,0
RM885,40,36-45,No,Travel_Rarely,107,Sales,10,3,Technical Degree,1,1239,2,Female,84,2,2,Sales Executive,2,Divorced,6852,5k-10k,11591,7,Y,No,12,3,2,80,1,7,2,4,5,1,1,3
RM947,40,36-45,Yes,Travel_Rarely,299,Sales,25,4,Marketing,1,1318,4,Male,57,2,3,Sales Executive,2,Single,9094,5k-10k,17235,2,Y,Yes,12,3,3,80,0,9,2,3,5,4,1,0
RM958,40,36-45,No,Non-Travel,458,Research & Development,16,2,Life Sciences,1,1340,3,Male,74,3,1,Research Scientist,3,Divorced,3544,Upto 5k,8532,9,Y,No,16,3,2,80,1,6,0,3,4,2,0,0
RM960,40,36-45,No,Travel_Rarely,523,Research & Development,2,3,Life Sciences,1,1346,3,Male,98,3,2,Research Scientist,4,Single,4661,Upto 5k,22455,1,Y,No,13,3,3,80,0,9,4,3,9,8,8,8
RM968,40,36-45,No,Travel_Rarely,329,Research & Development,1,4,Life Sciences,1,1361,2,Male,88,3,1,Laboratory Technician,2,Married,2387,Upto 5k,6762,3,Y,No,22,4,3,80,1,7,3,3,4,2,0,3
RM979,40,36-45,No,Travel_Rarely,1202,Research & Development,2,1,Medical,1,1375,2,Female,89,4,2,Healthcare Representative,3,Divorced,6377,5k-10k,13888,5,Y,No,20,4,2,80,3,15,0,3,12,11,11,8
RM1030,40,36-45,No,Non-Travel,663,Research & Development,9,4,Other,1,1449,3,Male,81,3,2,Laboratory Technician,3,Divorced,3975,Upto 5k,23099,3,Y,No,11,3,3,80,2,11,2,4,8,7,0,7
RM1041,40,36-45,No,Non-Travel,218,Research & Development,8,1,Medical,1,1468,4,Male,55,2,3,Research Director,2,Divorced,13757,10k-15k,25178,2,Y,No,11,3,3,80,1,16,5,3,9,8,4,8
RM1046,40,36-45,No,Travel_Rarely,896,Research & Development,2,3,Medical,1,1474,3,Male,68,3,1,Research Scientist,3,Divorced,2345,Upto 5k,8045,2,Y,No,14,3,3,80,1,8,3,4,3,1,1,2
RM1084,40,36-45,Yes,Travel_Rarely,676,Research & Development,9,4,Life Sciences,1,1534,4,Male,86,3,1,Laboratory Technician,1,Single,2018,Upto 5k,21831,3,Y,No,14,3,2,80,0,15,3,1,5,4,1,0
RM1095,40,36-45,No,Travel_Rarely,1342,Sales,9,2,Medical,1,1548,1,Male,47,3,2,Sales Executive,1,Married,5473,5k-10k,19345,0,Y,No,12,3,4,80,0,9,5,4,8,4,7,1
RM1097,40,36-45,No,Travel_Rarely,898,Human Resources,6,2,Medical,1,1550,3,Male,38,3,4,Manager,4,Single,16437,15k+,17381,1,Y,Yes,21,4,4,80,0,21,2,3,21,7,7,7
RM1099,40,36-45,No,Non-Travel,1142,Research & Development,8,2,Life Sciences,1,1552,4,Male,72,3,2,Healthcare Representative,4,Divorced,4069,Upto 5k,8841,3,Y,Yes,18,3,3,80,0,8,2,3,2,2,2,2
RM1133,40,36-45,No,Travel_Rarely,118,Sales,14,2,Life Sciences,1,1598,4,Female,84,3,2,Sales Executive,1,Married,4639,Upto 5k,11262,1,Y,No,15,3,3,80,1,5,2,3,5,4,1,2
RM1157,40,36-45,No,Travel_Rarely,884,Research & Development,15,3,Life Sciences,1,1628,1,Female,80,2,3,Manufacturing Director,3,Married,10435,10k-15k,25800,1,Y,No,13,3,4,80,2,18,2,3,18,15,14,12
RM1165,40,36-45,No,Travel_Rarely,448,Research & Development,16,3,Life Sciences,1,1641,3,Female,84,3,3,Manufacturing Director,4,Single,7945,5k-10k,19948,6,Y,Yes,15,3,4,80,0,18,2,2,4,2,3,3
RM1172,40,36-45,Yes,Travel_Rarely,1329,Research & Development,7,3,Life Sciences,1,1649,1,Male,73,3,1,Laboratory Technician,1,Single,2166,Upto 5k,3339,3,Y,Yes,14,3,2,80,0,10,3,1,4,2,0,3
RM1230,40,36-45,No,Travel_Rarely,369,Research & Development,8,2,Life Sciences,1,1724,2,Female,92,3,2,Manufacturing Director,1,Married,6516,5k-10k,5041,2,Y,Yes,16,3,2,80,1,18,3,3,1,0,0,0
RM1243,40,36-45,No,Travel_Rarely,611,Sales,7,4,Medical,1,1740,2,Male,88,3,5,Manager,2,Single,19833,15k+,4349,1,Y,No,14,3,2,80,0,21,3,2,21,8,12,8
RM1287,40,36-45,No,Travel_Rarely,616,Research & Development,2,2,Life Sciences,1,1802,3,Female,99,3,1,Laboratory Technician,1,Married,3377,Upto 5k,25605,4,Y,No,17,3,4,80,1,7,5,2,4,3,0,2
RM1300,40,36-45,No,Travel_Rarely,1194,Research & Development,1,3,Life Sciences,1,1822,3,Female,52,3,2,Healthcare Representative,4,Divorced,6513,5k-10k,9060,4,Y,No,17,3,4,80,1,12,3,3,5,3,0,3
RM1305,40,36-45,No,Travel_Rarely,750,Research & Development,12,3,Life Sciences,1,1829,2,Female,47,3,2,Healthcare Representative,1,Divorced,4448,Upto 5k,10748,2,Y,No,12,3,2,80,1,15,3,3,7,4,7,7
RM1349,40,36-45,No,Travel_Rarely,1137,Research & Development,1,4,Life Sciences,1,1892,1,Male,98,3,4,Manager,1,Divorced,16823,15k+,18991,2,Y,No,11,3,1,80,1,22,3,3,19,7,11,16
RM1410,40,36-45,No,Travel_Frequently,692,Research & Development,11,3,Technical Degree,1,1985,4,Female,73,3,2,Laboratory Technician,3,Married,6323,5k-10k,26849,1,Y,No,11,3,1,80,1,10,2,4,10,9,9,4
RM1411,40,36-45,No,Travel_Rarely,444,Sales,2,2,Marketing,1,1986,2,Female,92,3,2,Sales Executive,2,Married,5677,5k-10k,4258,3,Y,No,14,3,3,80,1,15,4,3,11,8,5,10
RM1428,40,36-45,No,Travel_Rarely,543,Research & Development,1,4,Life Sciences,1,2012,1,Male,83,3,1,Laboratory Technician,4,Married,2406,Upto 5k,4060,8,Y,No,19,3,3,80,2,8,3,2,1,0,0,0
RM1456,40,36-45,No,Travel_Rarely,1322,Research & Development,2,4,Life Sciences,1,2048,3,Male,52,2,1,Research Scientist,3,Single,2809,Upto 5k,2725,2,Y,No,14,3,4,80,0,8,2,3,2,2,2,2
RM1458,40,36-45,No,Travel_Rarely,1194,Research & Development,2,4,Medical,1,2051,3,Female,98,3,1,Research Scientist,3,Married,2001,Upto 5k,12549,2,Y,No,14,3,2,80,3,20,2,3,5,3,0,2
RM001,41,36-45,Yes,Travel_Rarely,1102,Sales,1,2,Life Sciences,1,1,2,Female,94,3,2,Sales Executive,4,Single,5993,5k-10k,19479,8,Y,Yes,11,3,1,80,0,8,0,1,6,4,0,5
RM046,41,36-45,Yes,Travel_Rarely,1360,Research & Development,12,3,Technical Degree,1,58,2,Female,49,3,5,Research Director,3,Married,19545,15k+,16280,1,Y,No,12,3,4,80,0,23,0,3,22,15,15,8
RM134,41,36-45,No,Travel_Rarely,802,Sales,9,1,Life Sciences,1,176,3,Male,96,3,3,Sales Executive,3,Divorced,8189,5k-10k,21196,3,Y,Yes,13,3,3,80,1,12,2,3,9,7,0,7
RM148,41,36-45,No,Travel_Frequently,857,Research & Development,10,3,Life Sciences,1,199,4,Male,91,2,4,Manager,1,Divorced,17181,15k+,12888,4,Y,No,13,3,2,80,1,21,2,2,7,6,7,7
RM149,41,36-45,No,Travel_Rarely,933,Research & Development,9,4,Life Sciences,1,200,3,Male,94,3,1,Laboratory Technician,1,Married,2238,Upto 5k,6961,2,Y,No,21,4,4,80,1,7,2,3,5,0,1,4
RM167,41,36-45,No,Travel_Rarely,465,Research & Development,14,3,Life Sciences,1,227,1,Male,56,3,1,Research Scientist,3,Divorced,2451,Upto 5k,4609,4,Y,No,12,3,1,80,1,13,2,3,9,8,1,8
RM183,41,36-45,Yes,Travel_Rarely,1356,Sales,20,2,Marketing,1,248,2,Female,70,3,1,Sales Representative,2,Single,3140,Upto 5k,21728,1,Y,Yes,22,4,4,80,0,4,5,2,4,3,0,2
RM216,41,36-45,No,Travel_Rarely,896,Sales,6,3,Life Sciences,1,298,4,Female,75,3,3,Manager,4,Single,13591,10k-15k,14674,3,Y,Yes,18,3,3,80,0,16,3,3,1,0,0,0
RM243,41,36-45,No,Travel_Rarely,1411,Research & Development,19,2,Life Sciences,1,334,3,Male,36,3,2,Research Scientist,1,Divorced,3072,Upto 5k,19877,2,Y,No,16,3,1,80,2,17,2,2,1,0,0,0
RM301,41,36-45,No,Travel_Rarely,334,Sales,2,4,Life Sciences,1,410,4,Male,88,3,4,Manager,2,Single,16015,15k+,15896,1,Y,No,19,3,2,80,0,22,2,3,22,10,0,4
RM347,41,36-45,No,Travel_Rarely,483,Research & Development,6,3,Medical,1,466,4,Male,95,2,2,Manufacturing Director,2,Single,6032,5k-10k,10110,6,Y,Yes,15,3,4,80,0,8,3,3,5,4,1,2
RM367,41,36-45,Yes,Travel_Frequently,143,Sales,4,3,Marketing,1,488,1,Male,56,3,2,Sales Executive,2,Single,9355,5k-10k,9558,1,Y,No,18,3,3,80,0,8,5,3,8,7,7,7
RM404,41,36-45,No,Travel_Rarely,645,Sales,1,3,Marketing,1,534,2,Male,49,4,3,Sales Executive,1,Married,8392,5k-10k,19566,1,Y,No,16,3,3,80,1,10,2,3,10,7,0,
RM447,41,36-45,No,Non-Travel,267,Sales,10,2,Life Sciences,1,599,4,Male,56,3,2,Sales Executive,4,Single,6230,5k-10k,13430,7,Y,No,14,3,4,80,0,16,3,3,14,3,1,10
RM460,41,36-45,No,Non-Travel,509,Research & Development,2,4,Other,1,616,1,Female,62,2,2,Healthcare Representative,3,Single,6811,5k-10k,2112,2,Y,Yes,17,3,1,80,0,10,3,3,8,7,0,7
RM467,41,36-45,No,Travel_Rarely,1276,Sales,2,5,Life Sciences,1,625,2,Female,91,3,4,Manager,1,Married,16595,15k+,5626,7,Y,No,16,3,2,80,1,22,2,3,18,16,11,8
RM536,41,36-45,No,Travel_Rarely,427,Human Resources,10,4,Human Resources,1,731,2,Male,73,2,5,Manager,4,Divorced,19141,15k+,8861,3,Y,No,15,3,2,80,3,23,2,2,21,6,12,6
RM539,41,36-45,No,Travel_Rarely,314,Human Resources,1,3,Human Resources,1,734,4,Male,59,2,5,Manager,3,Married,19189,15k+,19562,1,Y,No,12,3,2,80,1,22,3,3,22,7,2,10
RM668,41,36-45,Yes,Travel_Rarely,1085,Research & Development,2,4,Life Sciences,1,927,2,Female,57,1,1,Laboratory Technician,4,Divorced,2778,Upto 5k,17725,4,Y,Yes,13,3,3,80,1,10,1,2,7,7,1,0
RM687,41,36-45,No,Travel_Rarely,263,Research & Development,6,3,Medical,1,957,4,Male,59,3,1,Laboratory Technician,1,Single,4721,Upto 5k,3119,2,Y,Yes,13,3,3,80,0,20,3,3,18,13,2,17
RM717,41,36-45,No,Travel_Frequently,840,Research & Development,9,3,Medical,1,999,1,Male,64,3,5,Research Director,3,Divorced,19419,15k+,3735,2,Y,No,17,3,2,80,1,21,2,4,18,16,0,11
RM738,41,36-45,No,Travel_Rarely,549,Research & Development,7,2,Medical,1,1025,4,Female,42,3,2,Manufacturing Director,3,Single,5003,5k-10k,23371,6,Y,No,14,3,2,80,0,8,6,3,2,2,2,1
RM747,41,36-45,No,Non-Travel,247,Research & Development,7,1,Life Sciences,1,1035,2,Female,55,1,5,Research Director,3,Divorced,19973,15k+,20284,1,Y,No,22,4,2,80,2,21,3,3,21,16,5,10
RM784,41,36-45,No,Travel_Rarely,509,Research & Development,7,2,Technical Degree,1,1085,2,Female,43,4,1,Research Scientist,3,Married,3376,Upto 5k,18863,1,Y,No,13,3,3,80,0,10,3,3,10,6,0,8
RM831,41,36-45,No,Travel_Rarely,167,Research & Development,12,4,Life Sciences,1,1158,2,Male,46,3,1,Laboratory Technician,4,Married,4766,Upto 5k,9051,3,Y,Yes,11,3,1,80,1,6,4,3,1,0,0,0
RM865,41,36-45,Yes,Non-Travel,906,Research & Development,5,2,Life Sciences,1,1210,1,Male,95,2,1,Research Scientist,1,Divorced,2107,Upto 5k,20293,6,Y,No,17,3,1,80,1,5,2,1,1,0,0,0
RM952,41,36-45,No,Non-Travel,256,Sales,10,2,Medical,1,1329,3,Male,40,1,2,Sales Executive,2,Single,6151,5k-10k,22074,1,Y,No,13,3,1,80,0,19,4,3,19,2,11,9
RM961,41,36-45,No,Travel_Frequently,1018,Sales,1,3,Marketing,1,1349,3,Female,66,3,2,Sales Executive,1,Divorced,4103,Upto 5k,4297,0,Y,No,17,3,4,80,1,10,2,3,9,3,1,7
RM989,41,36-45,No,Travel_Frequently,1200,Research & Development,22,3,Life Sciences,1,1392,4,Female,75,3,2,Research Scientist,4,Divorced,5467,5k-10k,13953,3,Y,Yes,14,3,1,80,2,12,4,2,6,2,3,3
RM1029,41,36-45,No,Travel_Rarely,1283,Research & Development,5,5,Medical,1,1448,2,Male,90,4,1,Research Scientist,3,Married,2127,Upto 5k,5561,2,Y,Yes,12,3,1,80,0,7,5,2,4,2,0,3
RM1197,41,36-45,No,Travel_Rarely,1206,Sales,23,2,Life Sciences,1,1678,4,Male,80,3,3,Sales Executive,3,Single,7082,5k-10k,11591,3,Y,Yes,16,3,4,80,0,21,2,3,2,0,0,2
RM1219,41,36-45,No,Travel_Rarely,918,Sales,6,3,Marketing,1,1708,4,Male,35,3,3,Sales Executive,3,Single,9241,5k-10k,15869,1,Y,No,12,3,2,80,0,10,3,3,10,8,8,7
RM1229,41,36-45,No,Non-Travel,552,Human Resources,4,3,Human Resources,1,1722,3,Male,60,1,2,Human Resources,2,Married,6430,5k-10k,20794,6,Y,No,19,3,2,80,1,10,4,3,3,2,1,2
RM1267,41,36-45,No,Travel_Rarely,548,Research & Development,9,4,Life Sciences,1,1772,3,Male,94,3,1,Laboratory Technician,1,Divorced,2289,Upto 5k,20520,1,Y,No,20,4,2,80,2,5,2,3,5,3,0,4
RM1295,41,36-45,No,Travel_Rarely,447,Research & Development,5,3,Life Sciences,1,1814,2,Male,85,4,2,Healthcare Representative,2,Single,6870,5k-10k,15530,3,Y,No,12,3,1,80,0,11,3,1,3,2,1,2
RM1296,41,36-45,No,Travel_Rarely,796,Sales,4,1,Marketing,1,1815,3,Female,81,3,3,Sales Executive,3,Divorced,10447,10k-15k,26458,0,Y,Yes,13,3,4,80,1,23,3,4,22,14,13,5
RM1357,41,36-45,No,Travel_Rarely,337,Sales,8,3,Marketing,1,1909,3,Female,54,3,2,Sales Executive,2,Married,4393,Upto 5k,26841,5,Y,No,21,4,3,80,1,14,3,3,5,4,1,4
RM1421,41,36-45,No,Travel_Rarely,642,Research & Development,1,3,Life Sciences,1,1999,4,Male,76,3,1,Research Scientist,4,Married,2782,Upto 5k,21412,3,Y,No,22,4,1,80,1,12,3,3,5,3,1,0
RM1446,41,36-45,No,Travel_Rarely,582,Research & Development,28,4,Life Sciences,1,2034,1,Female,60,2,4,Manufacturing Director,2,Married,13570,10k-15k,5640,0,Y,No,23,4,3,80,1,21,3,3,20,7,0,10
RM1449,41,36-45,No,Travel_Rarely,930,Sales,3,3,Life Sciences,1,2037,3,Male,57,2,2,Sales Executive,2,Divorced,8938,5k-10k,12227,2,Y,No,11,3,3,80,1,14,5,3,5,4,0,4
RM028,42,36-45,No,Travel_Rarely,691,Sales,8,4,Marketing,1,35,3,Male,48,3,2,Sales Executive,2,Married,6825,5k-10k,21173,0,Y,No,11,3,4,80,1,10,2,3,9,7,4,
RM198,42,36-45,No,Non-Travel,926,Research & Development,21,2,Medical,1,270,3,Female,36,3,2,Manufacturing Director,3,Divorced,5265,5k-10k,16439,2,Y,No,16,3,2,80,1,11,5,3,5,3,0,2
RM232,42,36-45,No,Travel_Rarely,532,Research & Development,4,2,Technical Degree,1,319,3,Male,58,3,5,Manager,4,Married,19232,15k+,4933,1,Y,No,11,3,4,80,0,22,3,3,22,17,11,15
RM254,42,36-45,No,Travel_Rarely,916,Research & Development,17,2,Life Sciences,1,347,4,Female,82,4,2,Research Scientist,1,Single,6545,5k-10k,23016,3,Y,Yes,13,3,3,80,0,10,1,3,3,2,0,
RM257,42,36-45,No,Travel_Rarely,269,Research & Development,2,3,Medical,1,351,4,Female,56,2,1,Laboratory Technician,1,Divorced,2593,Upto 5k,8007,0,Y,Yes,11,3,3,80,1,10,4,3,9,6,7,
RM282,42,36-45,No,Travel_Rarely,635,Sales,1,1,Life Sciences,1,387,2,Male,99,3,2,Sales Executive,3,Married,4907,Upto 5k,24532,1,Y,No,25,4,3,80,0,20,3,3,20,16,11,6
RM296,42,36-45,No,Travel_Frequently,555,Sales,26,3,Marketing,1,404,3,Female,77,3,4,Sales Executive,2,Married,13525,10k-15k,14864,5,Y,No,14,3,4,80,1,23,2,4,20,4,4,8
RM349,42,36-45,No,Travel_Rarely,810,Research & Development,23,5,Life Sciences,1,468,1,Female,44,3,4,Research Director,4,Single,15992,15k+,15901,2,Y,No,14,3,2,80,0,16,2,3,1,0,0,0
RM351,42,36-45,No,Travel_Rarely,544,Human Resources,2,1,Technical Degree,1,470,3,Male,52,3,1,Human Resources,3,Divorced,2696,Upto 5k,24017,0,Y,Yes,11,3,3,80,1,4,5,3,3,2,1,0
RM357,42,36-45,No,Travel_Rarely,1332,Research & Development,2,4,Other,1,477,1,Male,98,2,2,Healthcare Representative,4,Single,6781,5k-10k,17078,3,Y,No,23,4,2,80,0,14,6,3,1,0,0,0
RM389,42,36-45,No,Travel_Rarely,201,Research & Development,1,4,Life Sciences,1,517,2,Female,95,3,1,Laboratory Technician,1,Divorced,2576,Upto 5k,20490,3,Y,No,16,3,2,80,1,8,5,3,5,2,1,2
RM410,42,36-45,No,Travel_Frequently,532,Research & Development,29,2,Life Sciences,1,547,1,Female,92,3,2,Research Scientist,3,Divorced,4556,Upto 5k,12932,2,Y,No,11,3,2,80,1,19,3,3,5,4,0,2
RM414,42,36-45,No,Travel_Frequently,1368,Research & Development,28,4,Technical Degree,1,551,4,Female,88,2,2,Healthcare Representative,4,Married,4523,Upto 5k,4386,0,Y,No,11,3,4,80,3,7,4,4,6,5,0,4
RM442,42,36-45,No,Travel_Frequently,1474,Research & Development,5,2,Other,1,591,2,Male,97,3,1,Laboratory Technician,3,Married,2093,Upto 5k,9260,4,Y,No,17,3,4,80,1,8,4,3,2,2,2,0
RM452,42,36-45,No,Travel_Rarely,319,Research & Development,24,3,Medical,1,605,4,Male,56,3,3,Manufacturing Director,1,Married,7406,5k-10k,6950,1,Y,Yes,21,4,4,80,1,10,5,2,10,9,5,8
RM489,42,36-45,No,Travel_Rarely,622,Research & Development,2,4,Life Sciences,1,659,3,Female,81,3,2,Healthcare Representative,4,Married,4089,Upto 5k,5718,1,Y,No,13,3,2,80,2,10,4,3,10,2,2,2
RM548,42,36-45,Yes,Travel_Frequently,933,Research & Development,19,3,Medical,1,752,3,Male,57,4,1,Research Scientist,3,Divorced,2759,Upto 5k,20366,6,Y,Yes,12,3,4,80,0,7,2,3,2,2,2,2
RM585,42,36-45,No,Travel_Frequently,570,Research & Development,8,3,Life Sciences,1,809,2,Male,66,3,5,Manager,4,Divorced,18430,15k+,16225,1,Y,No,13,3,2,80,1,24,4,2,24,7,14,9
RM598,42,36-45,No,Travel_Rarely,932,Research & Development,1,2,Life Sciences,1,827,4,Female,43,2,2,Manufacturing Director,4,Married,6062,5k-10k,4051,9,Y,Yes,13,3,4,80,1,8,4,3,4,3,0,2
RM605,42,36-45,No,Travel_Rarely,933,Research & Development,29,3,Life Sciences,1,836,2,Male,98,3,2,Manufacturing Director,2,Married,4434,Upto 5k,11806,1,Y,No,13,3,4,80,1,10,3,2,9,8,7,8
RM633,42,36-45,No,Travel_Frequently,1271,Research & Development,2,1,Medical,1,875,2,Male,35,3,1,Research Scientist,4,Single,2515,Upto 5k,9068,5,Y,Yes,14,3,4,80,0,8,2,3,2,1,2,2
RM644,42,36-45,No,Travel_Rarely,1265,Research & Development,3,3,Life Sciences,1,894,3,Female,95,4,2,Laboratory Technician,4,Married,5231,5k-10k,23726,2,Y,Yes,13,3,2,80,1,17,1,2,5,3,1,3
RM673,42,36-45,No,Travel_Rarely,462,Sales,14,2,Medical,1,936,3,Female,68,2,2,Sales Executive,3,Single,6244,5k-10k,7824,7,Y,No,17,3,1,80,0,10,6,3,5,4,0,3
RM742,42,36-45,No,Travel_Rarely,265,Sales,5,2,Marketing,1,1029,4,Male,90,3,5,Manager,3,Married,18303,15k+,7770,6,Y,No,13,3,2,80,0,21,3,4,1,0,0,0
RM800,42,36-45,No,Travel_Rarely,469,Research & Development,2,2,Medical,1,1109,4,Male,35,3,4,Manager,1,Married,17665,15k+,14399,0,Y,No,17,3,4,80,1,23,3,3,22,6,13,7
RM825,42,36-45,No,Travel_Rarely,188,Research & Development,29,3,Medical,1,1148,2,Male,56,1,2,Laboratory Technician,4,Single,4272,Upto 5k,9558,4,Y,No,19,3,1,80,0,16,3,3,1,0,0,0
RM839,42,36-45,Yes,Travel_Frequently,481,Sales,12,3,Life Sciences,1,1167,3,Male,44,3,4,Sales Executive,1,Single,13758,10k-15k,2447,0,Y,Yes,12,3,2,80,0,22,2,2,21,9,13,14
RM840,42,36-45,No,Travel_Rarely,647,Sales,4,4,Marketing,1,1171,2,Male,45,3,2,Sales Executive,1,Single,5155,5k-10k,2253,7,Y,No,13,3,4,80,0,9,3,4,6,4,1,5
RM879,42,36-45,No,Non-Travel,179,Human Resources,2,5,Medical,1,1231,4,Male,79,4,2,Human Resources,1,Married,6272,5k-10k,12858,7,Y,No,16,3,1,80,1,10,3,4,4,3,0,3
RM888,42,36-45,No,Travel_Frequently,458,Research & Development,26,5,Medical,1,1242,1,Female,60,3,3,Research Director,1,Married,13191,10k-15k,23281,3,Y,Yes,17,3,3,80,0,20,6,3,1,0,0,0
RM926,42,36-45,No,Travel_Rarely,603,Research & Development,7,4,Medical,1,1292,2,Female,78,4,2,Research Scientist,2,Married,2372,Upto 5k,5628,6,Y,Yes,16,3,4,80,0,18,2,3,1,0,0,0
RM955,42,36-45,No,Non-Travel,495,Research & Development,2,1,Life Sciences,1,1334,3,Male,37,3,4,Manager,3,Married,17861,15k+,26582,0,Y,Yes,13,3,4,80,0,21,3,2,20,8,2,10
RM1000,42,36-45,No,Travel_Rarely,1147,Human Resources,10,3,Human Resources,1,1408,3,Female,31,3,4,Manager,1,Married,16799,15k+,16616,0,Y,No,14,3,3,80,1,21,5,3,20,7,0,9
RM1051,42,36-45,No,Travel_Frequently,748,Research & Development,9,2,Medical,1,1480,1,Female,74,3,1,Laboratory Technician,4,Single,3673,Upto 5k,16458,1,Y,No,13,3,3,80,0,12,3,3,12,9,5,8
RM1089,42,36-45,No,Travel_Rarely,1210,Research & Development,2,3,Medical,1,1542,3,Male,68,2,1,Laboratory Technician,2,Married,4841,Upto 5k,24052,4,Y,No,14,3,2,80,1,4,3,3,1,0,0,0
RM1094,42,36-45,No,Travel_Frequently,288,Research & Development,2,3,Life Sciences,1,1547,4,Male,40,3,3,Healthcare Representative,4,Married,10124,10k-15k,18611,2,Y,Yes,14,3,3,80,1,24,3,1,20,8,13,9
RM1130,42,36-45,No,Travel_Rarely,1059,Research & Development,9,2,Other,1,1595,4,Male,93,2,5,Manager,4,Single,19613,15k+,26362,8,Y,No,22,4,4,80,0,24,2,3,1,0,0,1
RM1264,42,36-45,No,Travel_Rarely,855,Research & Development,12,3,Medical,1,1768,2,Male,57,3,1,Laboratory Technician,2,Divorced,2766,Upto 5k,8952,8,Y,No,22,4,2,80,3,7,6,2,5,3,0,4
RM1288,42,36-45,No,Travel_Rarely,1128,Research & Development,13,3,Medical,1,1803,2,Male,95,4,2,Healthcare Representative,1,Married,5538,5k-10k,5696,5,Y,No,18,3,3,80,2,10,2,2,0,0,0,0
RM1321,42,36-45,No,Non-Travel,355,Research & Development,10,4,Technical Degree,1,1854,3,Male,38,3,1,Research Scientist,3,Married,2936,Upto 5k,6161,3,Y,No,22,4,2,80,2,10,1,2,6,3,3,3
RM1326,42,36-45,No,Travel_Rarely,1142,Research & Development,8,3,Life Sciences,1,1860,4,Male,81,3,1,Laboratory Technician,3,Single,3968,Upto 5k,13624,4,Y,No,13,3,4,80,0,8,3,3,0,0,0,0
RM1358,42,36-45,No,Travel_Rarely,1396,Research & Development,6,3,Medical,1,1911,3,Male,83,3,3,Research Director,1,Married,13348,10k-15k,14842,9,Y,No,13,3,2,80,1,18,3,4,13,7,5,7
RM1379,42,36-45,No,Travel_Rarely,419,Sales,12,4,Marketing,1,1943,2,Male,77,3,2,Sales Executive,4,Divorced,5087,5k-10k,2900,3,Y,Yes,12,3,3,80,2,14,4,3,0,0,0,0
RM1405,42,36-45,No,Non-Travel,335,Research & Development,23,2,Life Sciences,1,1976,4,Male,37,2,2,Research Scientist,3,Single,4332,Upto 5k,14811,1,Y,No,12,3,4,80,0,20,2,3,20,9,3,7
RM1420,42,36-45,No,Travel_Rarely,557,Research & Development,18,4,Life Sciences,1,1998,4,Male,35,3,2,Research Scientist,1,Divorced,5410,5k-10k,11189,6,Y,Yes,17,3,3,80,1,9,3,2,4,3,1,2
RM1444,42,36-45,No,Travel_Rarely,300,Research & Development,2,3,Life Sciences,1,2031,1,Male,56,3,5,Manager,3,Married,18880,15k+,17312,5,Y,No,11,3,1,80,0,24,2,2,22,6,4,14
RM036,43,36-45,No,Travel_Rarely,1273,Research & Development,2,2,Medical,1,46,4,Female,72,4,1,Research Scientist,3,Divorced,2645,Upto 5k,21923,1,Y,No,12,3,4,80,2,6,3,2,5,3,1,4
RM120,43,36-45,No,Travel_Frequently,394,Sales,26,2,Life Sciences,1,158,3,Male,92,3,4,Manager,4,Married,16959,15k+,19494,1,Y,Yes,12,3,4,80,2,25,3,4,25,12,4,12
RM131,43,36-45,No,Travel_Frequently,957,Research & Development,28,3,Medical,1,171,2,Female,72,4,1,Research Scientist,3,Single,4739,Upto 5k,16090,4,Y,No,12,3,4,80,0,18,2,3,3,2,1,2
RM194,43,36-45,No,Non-Travel,1344,Research & Development,7,3,Medical,1,262,4,Male,37,4,1,Research Scientist,4,Divorced,2089,Upto 5k,5228,4,Y,No,14,3,4,80,3,7,3,4,5,4,2,2
RM236,43,36-45,No,Travel_Rarely,1034,Sales,16,3,Marketing,1,327,4,Female,80,3,4,Manager,4,Married,16064,15k+,7744,5,Y,Yes,22,4,3,80,1,22,3,3,17,13,1,9
RM316,43,36-45,No,Travel_Frequently,185,Research & Development,10,4,Life Sciences,1,430,3,Female,33,3,1,Laboratory Technician,4,Single,2455,Upto 5k,10675,0,Y,No,19,3,1,80,0,9,5,3,8,7,1,7
RM331,43,36-45,No,Travel_Frequently,559,Research & Development,10,4,Life Sciences,1,448,3,Female,82,2,2,Laboratory Technician,3,Divorced,5257,5k-10k,6227,1,Y,No,11,3,2,80,1,9,3,4,9,7,0,0
RM334,43,36-45,No,Travel_Rarely,1001,Research & Development,7,3,Life Sciences,1,451,3,Female,43,3,3,Healthcare Representative,1,Married,9985,5k-10k,9262,8,Y,No,16,3,1,80,1,10,1,2,1,0,0,0
RM391,43,36-45,No,Travel_Rarely,982,Research & Development,12,3,Life Sciences,1,520,1,Male,59,2,4,Research Director,2,Divorced,14336,10k-15k,4345,1,Y,No,11,3,3,80,1,25,3,3,25,10,3,9
RM396,43,36-45,No,Travel_Frequently,313,Research & Development,21,3,Medical,1,525,4,Male,61,3,1,Laboratory Technician,4,Married,2258,Upto 5k,15238,7,Y,No,20,4,1,80,1,8,1,3,3,2,1,2
RM397,43,36-45,No,Travel_Rarely,1473,Research & Development,8,4,Other,1,526,3,Female,74,3,2,Healthcare Representative,3,Divorced,4522,Upto 5k,2227,4,Y,Yes,14,3,4,80,0,8,3,3,5,2,0,2
RM490,43,36-45,No,Travel_Rarely,782,Research & Development,6,4,Other,1,661,2,Male,50,2,4,Research Director,4,Divorced,16627,15k+,2671,4,Y,Yes,14,3,3,80,1,21,3,2,1,0,0,0
RM492,43,36-45,No,Travel_Frequently,1001,Research & Development,9,5,Medical,1,663,4,Male,72,3,2,Laboratory Technician,3,Divorced,5679,5k-10k,19627,3,Y,Yes,13,3,2,80,1,10,3,3,8,7,4,7
RM549,43,36-45,No,Travel_Frequently,775,Sales,15,3,Life Sciences,1,754,4,Male,47,2,2,Sales Executive,4,Married,6804,5k-10k,23683,3,Y,No,18,3,3,80,1,7,5,3,2,2,2,2
RM610,43,36-45,No,Travel_Rarely,589,Research & Development,14,2,Life Sciences,1,843,2,Male,94,3,4,Research Director,1,Married,17159,15k+,5200,6,Y,No,24,4,3,80,1,22,3,3,4,1,1,0
RM651,43,36-45,No,Travel_Frequently,422,Research & Development,1,3,Life Sciences,1,902,4,Female,33,3,2,Healthcare Representative,4,Married,5562,5k-10k,21782,4,Y,No,13,3,2,80,1,12,2,2,5,2,2,2
RM662,43,36-45,No,Travel_Rarely,177,Research & Development,8,3,Life Sciences,1,920,1,Female,55,3,2,Manufacturing Director,2,Divorced,4765,Upto 5k,23814,4,Y,No,21,4,3,80,1,4,2,4,1,0,0,0
RM776,43,36-45,No,Travel_Rarely,415,Sales,25,3,Medical,1,1076,3,Male,79,2,3,Sales Executive,4,Divorced,10798,10k-15k,5268,5,Y,No,13,3,3,80,1,18,5,3,1,0,0,0
RM813,43,36-45,No,Travel_Frequently,1082,Research & Development,27,3,Life Sciences,1,1126,3,Female,83,3,3,Manufacturing Director,1,Married,10820,10k-15k,11535,8,Y,No,11,3,3,80,1,18,1,3,8,7,0,1
RM850,43,36-45,Yes,Travel_Rarely,1372,Sales,9,3,Marketing,1,1188,1,Female,85,1,2,Sales Executive,3,Single,5346,5k-10k,9489,8,Y,No,13,3,2,80,0,7,2,2,4,3,1,3
RM899,43,36-45,No,Travel_Rarely,920,Research & Development,3,3,Life Sciences,1,1255,3,Male,96,1,5,Research Director,4,Married,19740,15k+,18625,3,Y,No,14,3,2,80,1,25,2,3,8,7,0,7
RM927,43,36-45,No,Travel_Rarely,531,Sales,4,4,Marketing,1,1293,4,Female,56,2,3,Sales Executive,4,Single,10231,10k-15k,20364,3,Y,No,14,3,4,80,0,23,3,4,21,7,15,17
RM996,43,36-45,No,Travel_Rarely,930,Research & Development,6,3,Medical,1,1402,1,Female,73,2,2,Research Scientist,3,Single,4081,Upto 5k,20003,1,Y,Yes,14,3,1,80,0,20,3,1,20,7,1,8
RM1134,43,36-45,No,Travel_Rarely,990,Research & Development,27,3,Technical Degree,1,1599,4,Male,87,4,1,Laboratory Technician,2,Divorced,4876,Upto 5k,5855,5,Y,No,12,3,3,80,1,8,0,3,6,4,0,2
RM1186,43,36-45,No,Travel_Rarely,1291,Research & Development,15,2,Life Sciences,1,1666,3,Male,65,2,4,Research Director,3,Married,17603,15k+,3525,1,Y,No,24,4,1,80,1,14,3,3,14,10,6,11
RM1217,43,36-45,No,Travel_Rarely,1179,Sales,2,3,Medical,1,1706,4,Male,73,3,2,Sales Executive,4,Married,7847,5k-10k,6069,1,Y,Yes,17,3,1,80,1,10,3,3,10,9,8,8
RM1263,43,36-45,Yes,Travel_Frequently,807,Research & Development,17,3,Technical Degree,1,1767,3,Male,38,2,1,Research Scientist,3,Married,2437,Upto 5k,15587,9,Y,Yes,16,3,4,80,1,6,4,3,1,0,0,0
RM1270,43,36-45,No,Travel_Rarely,244,Human Resources,2,3,Life Sciences,1,1778,2,Male,97,3,1,Human Resources,4,Single,3539,Upto 5k,5033,0,Y,No,13,3,2,80,0,10,5,3,9,7,1,8
RM1294,43,36-45,No,Non-Travel,343,Research & Development,9,3,Life Sciences,1,1813,1,Male,52,3,1,Research Scientist,3,Single,2438,Upto 5k,24978,4,Y,No,13,3,3,80,0,7,2,2,3,2,1,2
RM1317,43,36-45,No,Travel_Frequently,1422,Sales,2,4,Life Sciences,1,1849,1,Male,92,3,2,Sales Executive,4,Married,5675,5k-10k,19246,1,Y,No,20,4,3,80,1,7,5,3,7,7,7,7
RM1331,43,36-45,No,Travel_Rarely,823,Research & Development,6,3,Medical,1,1866,1,Female,81,2,5,Manager,3,Married,19392,15k+,22539,7,Y,No,13,3,4,80,0,21,2,3,16,12,6,14
RM1400,43,36-45,No,Travel_Rarely,574,Research & Development,11,3,Life Sciences,1,1971,1,Male,30,3,3,Healthcare Representative,3,Married,7510,5k-10k,16873,1,Y,No,17,3,2,80,1,10,1,3,10,9,0,9
RM029,44,36-45,No,Travel_Rarely,477,Research & Development,7,4,Medical,1,36,1,Female,42,2,3,Healthcare Representative,4,Married,10248,10k-15k,2094,3,Y,No,14,3,4,80,1,24,4,3,22,6,5,
RM032,44,36-45,No,Travel_Rarely,1459,Research & Development,10,4,Other,1,40,4,Male,41,3,2,Healthcare Representative,4,Married,6465,5k-10k,19121,2,Y,Yes,13,3,4,80,0,9,5,4,4,2,1,3
RM053,44,36-45,No,Travel_Rarely,1488,Sales,1,5,Marketing,1,68,2,Female,75,3,2,Sales Executive,1,Divorced,5454,5k-10k,4009,5,Y,Yes,21,4,3,80,1,9,2,2,4,3,1,3
RM100,44,36-45,No,Non-Travel,489,Research & Development,23,3,Medical,1,132,2,Male,67,3,2,Laboratory Technician,2,Married,2042,Upto 5k,25043,4,Y,No,12,3,3,80,1,17,3,4,3,2,1,2
RM287,44,36-45,Yes,Travel_Frequently,920,Research & Development,24,3,Life Sciences,1,392,4,Male,43,3,1,Laboratory Technician,3,Divorced,3161,Upto 5k,19920,3,Y,Yes,22,4,4,80,1,19,0,1,1,0,0,0
RM494,44,36-45,No,Travel_Rarely,1112,Human Resources,1,4,Life Sciences,1,665,1,Female,50,2,2,Human Resources,3,Single,5985,5k-10k,26894,4,Y,No,11,3,2,80,0,10,1,4,2,2,0,2
RM498,44,36-45,No,Travel_Rarely,1315,Research & Development,3,4,Other,1,671,4,Male,35,3,5,Manager,4,Married,19513,15k+,9358,4,Y,Yes,12,3,1,80,1,26,2,4,2,2,0,1
RM544,44,36-45,No,Non-Travel,381,Research & Development,24,3,Medical,1,744,1,Male,49,1,1,Laboratory Technician,3,Single,3708,Upto 5k,2104,2,Y,No,14,3,3,80,0,9,5,3,5,2,1,4
RM618,44,36-45,No,Travel_Rarely,625,Research & Development,4,3,Medical,1,852,4,Male,50,3,2,Healthcare Representative,2,Single,5933,5k-10k,5197,9,Y,No,12,3,4,80,0,10,2,2,5,2,2,3
RM632,44,36-45,No,Travel_Rarely,986,Research & Development,8,4,Life Sciences,1,874,1,Male,62,4,1,Laboratory Technician,4,Married,2818,Upto 5k,5044,2,Y,Yes,24,4,3,80,1,10,2,2,3,2,0,2
RM659,44,36-45,No,Travel_Rarely,661,Research & Development,9,2,Life Sciences,1,913,2,Male,61,3,1,Research Scientist,1,Married,2559,Upto 5k,7508,1,Y,Yes,13,3,4,80,0,8,0,3,8,7,7,1
RM751,44,36-45,No,Travel_Rarely,1448,Sales,28,3,Medical,1,1039,4,Female,53,4,4,Sales Executive,4,Married,13320,10k-15k,11737,3,Y,Yes,18,3,3,80,1,23,2,3,12,11,11,11
RM790,44,36-45,Yes,Travel_Rarely,1376,Human Resources,1,2,Medical,1,1098,2,Male,91,2,3,Human Resources,1,Married,10482,10k-15k,2326,9,Y,No,14,3,4,80,1,24,1,3,20,6,3,6
RM858,44,36-45,Yes,Travel_Rarely,1097,Research & Development,10,4,Life Sciences,1,1200,3,Male,96,3,1,Research Scientist,3,Single,2936,Upto 5k,10826,1,Y,Yes,11,3,3,80,0,6,4,3,6,4,0,2
RM863,44,36-45,No,Non-Travel,111,Research & Development,17,3,Life Sciences,1,1206,4,Male,74,1,1,Research Scientist,3,Single,2290,Upto 5k,4279,2,Y,No,13,3,4,80,0,6,3,3,0,0,0,0
RM876,44,36-45,No,Travel_Rarely,200,Research & Development,29,4,Other,1,1225,4,Male,32,3,2,Research Scientist,4,Single,4541,Upto 5k,7744,1,Y,No,25,4,2,80,0,20,3,3,20,11,13,17
RM892,44,36-45,No,Travel_Rarely,1117,Research & Development,2,1,Life Sciences,1,1246,1,Female,72,4,1,Research Scientist,4,Married,2011,Upto 5k,19982,1,Y,No,13,3,4,80,1,10,5,3,10,5,7,7
RM908,44,36-45,No,Travel_Rarely,1099,Sales,5,3,Marketing,1,1267,2,Male,88,3,5,Manager,2,Married,18213,15k+,8751,7,Y,No,11,3,3,80,1,26,5,3,22,9,3,10
RM923,44,36-45,No,Travel_Rarely,1199,Research & Development,4,2,Life Sciences,1,1288,3,Male,92,4,5,Manager,1,Divorced,19190,15k+,17477,1,Y,No,14,3,4,80,2,26,4,2,25,9,14,13
RM929,44,36-45,Yes,Travel_Rarely,621,Research & Development,15,3,Medical,1,1295,1,Female,73,3,3,Healthcare Representative,4,Married,7978,5k-10k,14075,1,Y,No,11,3,4,80,1,10,2,3,10,7,0,5
RM954,44,36-45,Yes,Travel_Rarely,935,Research & Development,3,3,Life Sciences,1,1333,1,Male,89,3,1,Laboratory Technician,1,Married,2362,Upto 5k,14669,4,Y,No,12,3,3,80,0,10,4,4,3,2,1,2
RM1043,44,36-45,No,Non-Travel,981,Research & Development,5,3,Life Sciences,1,1471,3,Male,90,2,1,Laboratory Technician,3,Single,3162,Upto 5k,7973,3,Y,No,14,3,4,80,0,7,5,3,5,2,0,3
RM1047,44,36-45,No,Travel_Rarely,1467,Research & Development,20,3,Life Sciences,1,1475,4,Male,49,3,1,Research Scientist,2,Single,3420,Upto 5k,21158,1,Y,No,13,3,3,80,0,6,3,2,5,2,1,3
RM1052,44,36-45,No,Travel_Frequently,383,Sales,1,5,Marketing,1,1481,1,Female,79,3,2,Sales Executive,3,Married,4768,Upto 5k,9282,7,Y,No,12,3,3,80,1,11,4,2,1,0,0,0
RM1063,44,36-45,No,Travel_Frequently,1193,Research & Development,2,1,Medical,1,1496,2,Male,86,3,3,Manufacturing Director,3,Single,10209,10k-15k,19719,5,Y,Yes,18,3,2,80,0,16,2,2,2,2,2,2
RM1079,44,36-45,No,Travel_Rarely,136,Research & Development,28,3,Life Sciences,1,1523,4,Male,32,3,4,Research Director,1,Married,16328,15k+,22074,3,Y,No,13,3,3,80,1,24,1,4,20,6,14,17
RM1141,44,36-45,No,Travel_Rarely,1313,Research & Development,7,3,Medical,1,1608,2,Female,31,3,5,Research Director,4,Divorced,19049,15k+,3549,0,Y,Yes,14,3,4,80,1,23,4,2,22,7,1,10
RM1166,44,36-45,No,Travel_Frequently,602,Human Resources,1,5,Human Resources,1,1642,1,Male,37,3,2,Human Resources,4,Married,5743,5k-10k,10503,4,Y,Yes,11,3,3,80,0,14,3,3,10,7,0,2
RM1201,44,36-45,No,Travel_Rarely,528,Human Resources,1,3,Life Sciences,1,1683,3,Female,44,3,1,Human Resources,4,Divorced,3195,Upto 5k,4167,4,Y,Yes,18,3,1,80,3,8,2,3,2,2,2,2
RM1215,44,36-45,No,Travel_Rarely,921,Research & Development,2,3,Life Sciences,1,1703,3,Female,96,4,3,Healthcare Representative,4,Married,7879,5k-10k,14810,1,Y,Yes,19,3,2,80,1,9,2,3,8,7,6,7
RM1280,44,36-45,Yes,Travel_Frequently,429,Research & Development,1,2,Medical,1,1792,3,Male,99,3,1,Research Scientist,2,Divorced,2342,Upto 5k,11092,1,Y,Yes,12,3,3,80,3,6,2,2,5,3,2,3
RM1353,44,36-45,No,Travel_Rarely,170,Research & Development,1,4,Life Sciences,1,1903,2,Male,78,4,2,Healthcare Representative,1,Married,5033,5k-10k,9364,2,Y,No,15,3,4,80,1,10,5,3,2,0,2,2
RM1436,44,36-45,No,Travel_Rarely,1037,Research & Development,1,3,Medical,1,2020,2,Male,42,3,1,Research Scientist,4,Single,2436,Upto 5k,13422,6,Y,Yes,12,3,3,80,0,6,2,3,4,3,1,2
RM068,45,36-45,No,Travel_Rarely,1339,Research & Development,7,3,Life Sciences,1,86,2,Male,59,3,3,Research Scientist,1,Divorced,9724,5k-10k,18787,2,Y,No,17,3,3,80,1,25,2,3,1,0,0,0
RM078,45,36-45,No,Travel_Rarely,193,Research & Development,6,4,Other,1,101,4,Male,52,3,3,Research Director,1,Married,13245,10k-15k,15067,4,Y,Yes,14,3,2,80,0,17,3,4,0,0,0,
RM142,45,36-45,No,Travel_Rarely,1316,Research & Development,29,3,Medical,1,192,3,Male,83,3,1,Research Scientist,4,Single,3452,Upto 5k,9752,5,Y,No,13,3,2,80,0,9,2,2,6,5,0,
RM154,45,36-45,No,Travel_Rarely,194,Research & Development,9,3,Life Sciences,1,206,2,Male,60,3,2,Laboratory Technician,2,Divorced,2348,Upto 5k,10901,8,Y,No,18,3,3,80,1,20,2,1,17,9,0,15
RM175,45,36-45,No,Travel_Rarely,1268,Sales,4,2,Life Sciences,1,240,3,Female,30,3,2,Sales Executive,1,Divorced,5006,5k-10k,6319,4,Y,Yes,11,3,1,80,1,9,3,4,5,4,0,3
RM195,45,36-45,No,Non-Travel,1195,Research & Development,2,2,Medical,1,264,1,Male,65,2,4,Manager,4,Married,16792,15k+,20462,9,Y,No,23,4,4,80,1,22,1,3,20,8,11,8
RM219,45,36-45,No,Non-Travel,1052,Sales,6,3,Medical,1,302,4,Female,57,2,3,Sales Executive,4,Single,8865,5k-10k,16840,6,Y,No,12,3,4,80,0,23,2,3,19,7,12,8
RM245,45,36-45,No,Travel_Rarely,252,Research & Development,1,3,Other,1,336,3,Male,70,4,5,Manager,4,Married,19202,15k+,15970,0,Y,No,11,3,3,80,1,25,2,3,24,0,1,7
RM250,45,36-45,No,Travel_Frequently,1199,Research & Development,7,4,Life Sciences,1,341,1,Male,77,4,2,Manufacturing Director,3,Married,6434,5k-10k,5118,4,Y,No,17,3,4,80,1,9,1,3,3,2,0,
RM269,45,36-45,No,Travel_Rarely,1385,Research & Development,20,2,Medical,1,372,3,Male,79,3,4,Healthcare Representative,4,Married,13496,10k-15k,7501,0,Y,Yes,14,3,2,80,0,21,2,3,20,7,4,10
RM312,45,36-45,No,Travel_Frequently,1249,Research & Development,7,3,Life Sciences,1,425,1,Male,97,3,3,Laboratory Technician,1,Divorced,5210,5k-10k,20308,1,Y,No,18,3,1,80,1,24,2,3,24,9,9,11
RM335,45,36-45,No,Travel_Rarely,549,Research & Development,8,4,Other,1,452,4,Male,75,3,2,Research Scientist,4,Married,3697,Upto 5k,9278,9,Y,No,14,3,1,80,2,12,3,3,10,9,9,8
RM408,45,36-45,No,Travel_Rarely,192,Research & Development,10,2,Life Sciences,1,544,1,Male,69,3,1,Research Scientist,4,Married,2654,Upto 5k,9655,3,Y,No,21,4,4,80,2,8,3,2,2,2,0,
RM453,45,36-45,No,Travel_Rarely,561,Sales,2,3,Other,1,606,4,Male,61,3,2,Sales Executive,2,Married,4805,Upto 5k,16177,0,Y,No,19,3,2,80,1,9,3,4,8,7,3,7
RM505,45,36-45,Yes,Travel_Frequently,306,Sales,26,4,Life Sciences,1,684,1,Female,100,3,2,Sales Executive,1,Married,4286,Upto 5k,5630,2,Y,No,14,3,4,80,2,5,4,3,1,1,0,0
RM565,45,36-45,No,Travel_Rarely,954,Sales,2,2,Technical Degree,1,783,2,Male,46,1,2,Sales Representative,3,Single,6632,5k-10k,12388,0,Y,No,13,3,1,80,0,9,3,3,8,7,3,1
RM604,45,36-45,No,Travel_Rarely,252,Research & Development,2,3,Life Sciences,1,834,2,Female,95,2,1,Research Scientist,3,Single,2274,Upto 5k,6153,1,Y,No,14,3,4,80,0,1,3,3,1,0,0,0
RM626,45,36-45,No,Travel_Rarely,930,Sales,9,3,Marketing,1,864,4,Male,74,3,3,Sales Executive,1,Divorced,10761,10k-15k,19239,4,Y,Yes,12,3,3,80,1,18,2,3,5,4,0,2
RM697,45,36-45,No,Non-Travel,805,Research & Development,4,2,Life Sciences,1,972,3,Male,57,3,2,Laboratory Technician,2,Married,4447,Upto 5k,23163,1,Y,No,12,3,2,80,0,9,5,2,9,7,0,8
RM714,45,36-45,No,Travel_Rarely,974,Research & Development,1,4,Medical,1,996,4,Female,91,3,1,Laboratory Technician,4,Divorced,2270,Upto 5k,11005,3,Y,No,14,3,4,80,2,8,2,3,5,3,0,2
RM719,45,36-45,No,Non-Travel,248,Research & Development,23,2,Life Sciences,1,1002,4,Male,42,3,2,Laboratory Technician,1,Married,3633,Upto 5k,14039,1,Y,Yes,15,3,3,80,1,9,2,3,9,8,0,8
RM756,45,36-45,No,Travel_Rarely,1234,Sales,11,2,Life Sciences,1,1045,4,Female,90,3,4,Manager,4,Married,17650,15k+,5404,3,Y,No,13,3,2,80,1,26,4,4,9,3,1,1
RM760,45,36-45,No,Travel_Rarely,788,Human Resources,24,4,Medical,1,1049,2,Male,36,3,1,Human Resources,2,Single,2177,Upto 5k,8318,1,Y,No,16,3,1,80,0,6,3,3,6,3,0,4
RM806,45,36-45,No,Non-Travel,1050,Sales,9,4,Life Sciences,1,1117,2,Female,65,2,2,Sales Executive,3,Married,5593,5k-10k,17970,1,Y,No,13,3,4,80,1,15,2,3,15,10,4,12
RM855,45,36-45,No,Travel_Rarely,1457,Research & Development,7,3,Medical,1,1195,1,Female,83,3,1,Research Scientist,3,Married,4477,Upto 5k,20100,4,Y,Yes,19,3,3,80,1,7,2,2,3,2,0,2
RM914,45,36-45,Yes,Travel_Rarely,1449,Sales,2,3,Marketing,1,1277,1,Female,94,1,5,Manager,2,Single,18824,15k+,2493,2,Y,Yes,16,3,1,80,0,26,2,3,24,10,1,11
RM937,45,36-45,No,Travel_Frequently,364,Research & Development,25,3,Medical,1,1306,2,Female,83,3,5,Manager,2,Single,18061,15k+,13035,3,Y,No,22,4,3,80,0,22,4,3,0,0,0,0
RM1035,45,36-45,No,Travel_Rarely,1038,Research & Development,20,3,Medical,1,1460,2,Male,95,1,3,Healthcare Representative,1,Divorced,10851,10k-15k,19863,2,Y,Yes,18,3,2,80,1,24,2,3,7,7,0,7
RM1038,45,36-45,No,Travel_Rarely,1448,Research & Development,29,3,Technical Degree,1,1465,2,Male,55,3,3,Manufacturing Director,4,Married,9380,5k-10k,14720,4,Y,Yes,18,3,4,80,2,10,4,4,3,1,1,2
RM1093,45,36-45,No,Travel_Rarely,950,Research & Development,28,3,Technical Degree,1,1546,4,Male,97,3,1,Research Scientist,4,Married,2132,Upto 5k,4585,4,Y,No,20,4,4,80,1,8,3,3,5,4,0,3
RM1100,45,36-45,No,Travel_Rarely,538,Research & Development,1,4,Technical Degree,1,1553,1,Male,66,3,3,Healthcare Representative,2,Divorced,7441,5k-10k,20933,1,Y,No,12,3,1,80,3,10,4,3,10,8,7,7
RM1143,45,36-45,No,Travel_Rarely,1015,Research & Development,5,5,Medical,1,1611,3,Female,50,1,2,Laboratory Technician,1,Single,5769,5k-10k,23447,1,Y,Yes,14,3,1,80,0,10,3,3,10,7,1,4
RM1144,45,36-45,No,Non-Travel,336,Sales,26,3,Marketing,1,1612,1,Male,52,2,2,Sales Executive,1,Married,4385,Upto 5k,24162,1,Y,No,15,3,1,80,1,10,2,3,10,7,4,5
RM1161,45,36-45,No,Travel_Rarely,1329,Research & Development,2,2,Other,1,1635,4,Female,59,2,2,Manufacturing Director,4,Divorced,5770,5k-10k,5388,1,Y,No,19,3,1,80,2,10,3,3,10,7,3,9
RM1222,45,36-45,No,Non-Travel,1238,Research & Development,1,1,Life Sciences,1,1712,3,Male,74,2,3,Healthcare Representative,3,Married,10748,10k-15k,3395,3,Y,No,23,4,4,80,1,25,3,2,23,15,14,4
RM1226,45,36-45,No,Travel_Rarely,1005,Research & Development,28,2,Technical Degree,1,1719,4,Female,48,2,4,Research Director,2,Single,16704,15k+,17119,1,Y,No,11,3,3,80,0,21,2,3,21,6,8,6
RM1244,45,36-45,No,Travel_Rarely,176,Human Resources,4,3,Life Sciences,1,1744,3,Female,56,1,3,Human Resources,3,Married,9756,5k-10k,6595,4,Y,No,21,4,3,80,2,9,2,4,5,0,0,3
RM1315,45,36-45,No,Non-Travel,589,Sales,2,4,Life Sciences,1,1845,3,Female,67,3,2,Sales Executive,3,Married,5154,5k-10k,19665,4,Y,No,22,4,2,80,2,10,3,4,8,7,5,7
RM1347,45,36-45,No,Travel_Rarely,556,Research & Development,25,2,Life Sciences,1,1888,2,Female,93,2,2,Manufacturing Director,4,Married,5906,5k-10k,23888,0,Y,No,13,3,4,80,2,10,2,2,9,8,3,8
RM1363,45,36-45,No,Travel_Frequently,1297,Research & Development,1,4,Medical,1,1922,2,Male,44,3,2,Healthcare Representative,3,Single,5399,5k-10k,14511,4,Y,No,12,3,3,80,0,12,3,3,4,2,0,3
RM1455,45,36-45,No,Travel_Rarely,374,Sales,20,3,Life Sciences,1,2046,4,Female,50,3,2,Sales Executive,3,Single,4850,Upto 5k,23333,8,Y,No,15,3,3,80,0,8,3,3,5,3,0,1
RM030,46,46-55,No,Travel_Rarely,705,Sales,2,4,Marketing,1,38,2,Female,83,3,5,Manager,1,Single,18947,15k+,22822,3,Y,No,12,3,4,80,0,22,2,2,2,2,2,
RM049,46,46-55,No,Travel_Frequently,1211,Sales,5,4,Marketing,1,62,1,Male,98,3,2,Sales Executive,4,Single,5772,5k-10k,20445,4,Y,Yes,21,4,3,80,0,14,4,3,9,6,0,8
RM080,46,46-55,No,Travel_Rarely,945,Human Resources,5,2,Medical,1,103,2,Male,80,3,2,Human Resources,2,Divorced,5021,5k-10k,10425,8,Y,Yes,22,4,4,80,1,16,2,3,4,2,0,2
RM090,46,46-55,Yes,Travel_Rarely,669,Sales,9,2,Medical,1,118,3,Male,64,2,3,Sales Executive,4,Single,9619,5k-10k,13596,1,Y,No,16,3,4,80,0,9,3,3,9,8,4,7
RM094,46,46-55,No,Travel_Frequently,638,Research & Development,1,3,Medical,1,124,3,Male,40,2,3,Healthcare Representative,1,Married,10673,10k-15k,3142,2,Y,Yes,13,3,3,80,1,21,5,2,10,9,9,5
RM179,46,46-55,No,Travel_Rarely,526,Sales,1,2,Marketing,1,244,2,Female,92,3,3,Sales Executive,1,Divorced,10453,10k-15k,2137,1,Y,No,25,4,3,80,3,24,2,3,24,13,15,7
RM210,46,46-55,No,Travel_Rarely,644,Research & Development,1,4,Medical,1,288,4,Male,97,3,3,Healthcare Representative,1,Divorced,9396,5k-10k,12368,7,Y,No,16,3,3,80,1,17,3,3,4,2,0,
RM264,46,46-55,No,Travel_Rarely,488,Sales,2,3,Technical Degree,1,363,3,Female,75,1,4,Manager,2,Married,16872,15k+,14977,3,Y,Yes,12,3,2,80,1,28,2,2,7,7,7,7
RM366,46,46-55,No,Non-Travel,1144,Research & Development,7,4,Medical,1,487,3,Female,30,3,2,Manufacturing Director,3,Married,5258,5k-10k,16044,2,Y,No,14,3,3,80,0,7,2,4,1,0,0,0
RM413,46,46-55,No,Travel_Rarely,1485,Research & Development,18,3,Medical,1,550,3,Female,87,3,2,Manufacturing Director,3,Divorced,4810,Upto 5k,26314,2,Y,No,14,3,3,80,1,19,5,2,10,7,0,8
RM430,46,46-55,No,Travel_Rarely,1009,Research & Development,2,3,Life Sciences,1,575,1,Male,51,3,4,Research Director,3,Married,17861,15k+,2288,6,Y,No,13,3,3,80,0,26,2,1,3,2,0,1
RM434,46,46-55,No,Travel_Rarely,1125,Sales,10,3,Marketing,1,580,3,Female,94,2,3,Sales Executive,4,Married,9071,5k-10k,11563,2,Y,Yes,19,3,3,80,1,15,3,3,3,2,1,2
RM466,46,46-55,No,Travel_Frequently,1034,Research & Development,18,1,Medical,1,624,1,Female,86,3,3,Healthcare Representative,3,Married,10527,10k-15k,8984,5,Y,No,11,3,4,80,0,28,3,2,2,2,1,2
RM724,46,46-55,No,Travel_Rarely,566,Research & Development,7,2,Medical,1,1007,4,Male,75,3,3,Manufacturing Director,3,Divorced,10845,10k-15k,24208,6,Y,No,13,3,2,80,1,13,3,3,8,7,0,7
RM771,46,46-55,No,Travel_Rarely,430,Research & Development,1,4,Medical,1,1069,4,Male,40,3,5,Research Director,4,Divorced,19627,15k+,21445,9,Y,No,17,3,4,80,2,23,0,3,2,2,2,2
RM779,46,46-55,No,Travel_Rarely,1003,Research & Development,8,4,Life Sciences,1,1080,4,Female,74,2,2,Research Scientist,1,Divorced,4615,Upto 5k,21029,8,Y,Yes,23,4,1,80,3,19,2,3,16,13,1,7
RM811,46,46-55,No,Travel_Rarely,406,Sales,3,1,Marketing,1,1124,1,Male,52,3,4,Manager,3,Married,17465,15k+,15596,3,Y,No,12,3,4,80,1,23,3,3,12,9,4,9
RM862,46,46-55,No,Travel_Rarely,1402,Sales,2,3,Marketing,1,1204,3,Female,69,3,4,Manager,1,Married,17048,15k+,24097,8,Y,No,23,4,1,80,0,28,2,3,26,15,15,9
RM870,46,46-55,No,Travel_Rarely,1450,Research & Development,15,2,Life Sciences,1,1217,4,Male,52,3,5,Research Director,2,Married,19081,15k+,10849,5,Y,No,11,3,1,80,1,25,2,3,4,2,0,3
RM878,46,46-55,No,Travel_Rarely,150,Research & Development,2,4,Technical Degree,1,1228,4,Male,60,3,2,Manufacturing Director,4,Divorced,7379,5k-10k,17433,2,Y,No,11,3,3,80,1,12,3,2,6,3,1,4
RM917,46,46-55,No,Travel_Rarely,168,Sales,4,2,Marketing,1,1280,4,Female,33,2,5,Manager,2,Married,18789,15k+,9946,2,Y,No,14,3,3,80,1,26,2,3,11,4,0,8
RM944,46,46-55,No,Travel_Rarely,991,Human Resources,1,2,Life Sciences,1,1314,4,Female,44,3,1,Human Resources,1,Single,3423,Upto 5k,22957,6,Y,No,12,3,3,80,0,10,3,4,7,6,5,7
RM1032,46,46-55,Yes,Travel_Rarely,377,Sales,9,3,Marketing,1,1457,1,Male,52,3,3,Sales Executive,4,Divorced,10096,10k-15k,15986,4,Y,No,11,3,1,80,1,28,1,4,7,7,4,3
RM1081,46,46-55,No,Travel_Rarely,228,Sales,3,3,Life Sciences,1,1527,3,Female,51,3,4,Manager,2,Married,16606,15k+,11380,8,Y,No,12,3,4,80,1,23,2,4,13,12,5,1
RM1136,46,46-55,No,Travel_Rarely,563,Sales,1,4,Life Sciences,1,1602,4,Male,56,4,4,Manager,1,Single,17567,15k+,3156,1,Y,No,15,3,2,80,0,27,5,1,26,0,0,12
RM1232,46,46-55,No,Travel_Rarely,717,Research & Development,13,4,Life Sciences,1,1727,3,Male,34,3,2,Healthcare Representative,2,Single,5562,5k-10k,9697,6,Y,No,14,3,4,80,0,19,3,3,10,7,0,9
RM1236,46,46-55,No,Travel_Rarely,1277,Sales,2,3,Life Sciences,1,1732,3,Male,74,3,3,Sales Executive,4,Divorced,10368,10k-15k,5596,4,Y,Yes,12,3,2,80,1,13,5,2,10,6,0,3
RM1278,46,46-55,No,Travel_Rarely,734,Research & Development,2,4,Medical,1,1789,3,Male,46,3,5,Research Director,4,Divorced,19328,15k+,14218,7,Y,Yes,17,3,3,80,1,24,3,3,2,1,2,2
RM1286,46,46-55,No,Non-Travel,849,Sales,26,2,Life Sciences,1,1801,2,Male,98,2,2,Sales Executive,2,Single,7991,5k-10k,25166,8,Y,No,15,3,3,80,0,6,3,3,2,2,2,2
RM1299,46,46-55,Yes,Travel_Rarely,261,Research & Development,21,2,Medical,1,1821,4,Female,66,3,2,Healthcare Representative,2,Married,8926,5k-10k,10842,4,Y,No,22,4,4,80,1,13,2,4,9,7,3,7
RM1323,46,46-55,No,Travel_Rarely,706,Research & Development,2,2,Life Sciences,1,1857,4,Male,82,3,3,Manufacturing Director,4,Divorced,8578,5k-10k,19989,3,Y,No,14,3,3,80,1,12,4,2,9,8,4,7
RM1328,46,46-55,No,Travel_Rarely,1319,Sales,3,3,Technical Degree,1,1863,1,Female,45,4,4,Sales Executive,1,Divorced,13225,10k-15k,7739,2,Y,No,12,3,4,80,1,25,5,3,19,17,2,8
RM1334,46,46-55,Yes,Travel_Rarely,1254,Sales,10,3,Life Sciences,1,1869,3,Female,64,3,3,Sales Executive,2,Married,7314,5k-10k,14011,5,Y,No,21,4,3,80,3,14,2,3,8,7,0,7
RM272,47,46-55,Yes,Non-Travel,666,Research & Development,29,4,Life Sciences,1,376,1,Male,88,3,3,Manager,2,Married,11849,10k-15k,10268,1,Y,Yes,12,3,4,80,1,10,2,2,10,7,9,9
RM330,47,46-55,No,Travel_Rarely,1482,Research & Development,5,5,Life Sciences,1,447,4,Male,42,3,5,Research Director,3,Married,18300,15k+,16375,4,Y,No,11,3,2,80,1,21,2,3,3,2,1,1
RM348,47,46-55,No,Travel_Frequently,1309,Sales,4,1,Medical,1,467,2,Male,99,3,2,Sales Representative,3,Single,2976,Upto 5k,25751,3,Y,No,19,3,1,80,0,5,3,3,0,0,0,0
RM429,47,46-55,No,Travel_Rarely,983,Research & Development,2,2,Medical,1,574,1,Female,65,3,2,Manufacturing Director,4,Divorced,5070,5k-10k,7389,5,Y,No,13,3,3,80,3,20,2,3,5,0,0,4
RM533,47,46-55,No,Travel_Rarely,703,Sales,14,4,Marketing,1,728,4,Male,42,3,2,Sales Executive,1,Single,4960,Upto 5k,11825,2,Y,No,12,3,4,80,0,20,2,3,7,7,1,7
RM545,47,46-55,No,Travel_Frequently,217,Sales,3,3,Medical,1,746,4,Female,49,3,4,Sales Executive,3,Divorced,13770,10k-15k,10225,9,Y,Yes,12,3,4,80,2,28,2,2,22,2,11,13
RM567,47,46-55,Yes,Travel_Frequently,719,Sales,27,2,Life Sciences,1,785,2,Female,77,4,2,Sales Executive,3,Single,6397,5k-10k,10339,4,Y,Yes,12,3,4,80,0,8,2,3,5,4,1,3
RM593,47,46-55,No,Travel_Rarely,202,Research & Development,2,2,Other,1,820,3,Female,33,3,4,Manager,4,Married,16752,15k+,12982,1,Y,Yes,11,3,3,80,1,26,3,2,26,14,3,0
RM652,47,46-55,No,Travel_Rarely,249,Sales,2,2,Marketing,1,903,3,Female,35,3,2,Sales Executive,4,Married,4537,Upto 5k,17783,0,Y,Yes,22,4,1,80,1,8,2,3,7,6,7,7
RM666,47,46-55,No,Travel_Rarely,1454,Sales,2,4,Life Sciences,1,925,4,Female,65,2,1,Sales Representative,4,Single,3294,Upto 5k,13137,1,Y,Yes,18,3,1,80,0,3,3,2,3,2,1,2
RM708,47,46-55,No,Travel_Frequently,1379,Research & Development,16,4,Medical,1,987,3,Male,64,4,2,Manufacturing Director,3,Divorced,5067,5k-10k,6759,1,Y,Yes,19,3,3,80,0,20,3,4,19,10,2,7
RM720,47,46-55,No,Travel_Rarely,955,Sales,4,2,Life Sciences,1,1003,4,Female,83,3,2,Sales Executive,4,Single,4163,Upto 5k,8571,1,Y,Yes,17,3,3,80,0,9,0,3,9,0,0,7
RM1021,47,46-55,No,Travel_Rarely,465,Research & Development,1,3,Technical Degree,1,1438,1,Male,74,3,1,Research Scientist,4,Married,3420,Upto 5k,10205,7,Y,No,12,3,3,80,1,17,2,2,6,5,1,2
RM1025,47,46-55,No,Travel_Rarely,359,Research & Development,2,4,Medical,1,1443,1,Female,82,3,4,Research Director,3,Married,17169,15k+,26703,3,Y,No,19,3,2,80,2,26,2,4,20,17,5,6
RM1068,47,46-55,No,Travel_Rarely,571,Sales,14,3,Medical,1,1503,3,Female,78,3,2,Sales Executive,3,Married,4591,Upto 5k,24200,3,Y,Yes,17,3,3,80,1,11,4,2,5,4,1,2
RM1155,47,46-55,No,Travel_Rarely,1176,Human Resources,26,4,Life Sciences,1,1625,4,Female,98,3,5,Manager,3,Married,19658,15k+,5220,3,Y,No,11,3,3,80,1,27,2,3,5,2,1,0
RM1195,47,46-55,No,Travel_Rarely,1225,Sales,2,4,Life Sciences,1,1676,2,Female,47,4,4,Manager,2,Divorced,15972,15k+,21086,6,Y,No,14,3,3,80,3,29,2,3,3,2,1,2
RM1224,47,46-55,Yes,Travel_Frequently,1093,Sales,9,3,Life Sciences,1,1716,3,Male,82,1,4,Sales Executive,3,Married,12936,10k-15k,24164,7,Y,No,11,3,3,80,0,25,3,1,23,5,14,10
RM1235,47,46-55,No,Non-Travel,543,Sales,2,4,Marketing,1,1731,3,Male,87,3,2,Sales Executive,2,Married,4978,Upto 5k,3536,7,Y,No,11,3,4,80,1,4,3,1,1,0,0,0
RM1304,47,46-55,No,Travel_Rarely,1001,Research & Development,4,3,Life Sciences,1,1827,3,Female,92,2,3,Manufacturing Director,2,Divorced,10333,10k-15k,19271,8,Y,Yes,12,3,3,80,1,28,4,3,22,11,14,10
RM1322,47,46-55,No,Travel_Rarely,207,Research & Development,9,4,Life Sciences,1,1856,2,Female,64,3,1,Laboratory Technician,3,Single,2105,Upto 5k,5411,4,Y,No,12,3,3,80,0,7,2,3,2,2,2,0
RM1371,47,46-55,No,Non-Travel,1169,Research & Development,14,4,Technical Degree,1,1934,3,Male,64,3,2,Research Scientist,2,Married,5467,5k-10k,2125,8,Y,No,18,3,3,80,1,16,4,4,8,7,1,7
RM1415,47,46-55,No,Travel_Rarely,1180,Research & Development,25,3,Medical,1,1993,1,Male,84,3,3,Healthcare Representative,3,Single,8633,5k-10k,13084,2,Y,No,23,4,2,80,0,25,3,3,17,14,12,11
RM1422,47,46-55,No,Non-Travel,1162,Research & Development,1,1,Medical,1,2000,3,Female,98,3,3,Research Director,2,Married,11957,10k-15k,17231,0,Y,No,18,3,1,80,2,14,3,1,13,8,5,12
RM051,48,46-55,Yes,Travel_Rarely,626,Research & Development,1,2,Life Sciences,1,64,1,Male,98,2,3,Laboratory Technician,3,Single,5381,5k-10k,19294,9,Y,Yes,13,3,4,80,0,23,2,3,1,0,0,0
RM353,48,46-55,No,Travel_Rarely,530,Sales,29,1,Medical,1,473,1,Female,91,3,3,Manager,3,Married,12504,10k-15k,23978,3,Y,No,21,4,2,80,1,15,3,1,0,0,0,0
RM445,48,46-55,No,Travel_Rarely,163,Sales,2,5,Marketing,1,595,2,Female,37,3,2,Sales Executive,4,Married,4051,Upto 5k,19658,2,Y,No,14,3,1,80,1,14,2,3,9,7,6,7
RM493,48,46-55,No,Travel_Rarely,1236,Research & Development,1,4,Life Sciences,1,664,4,Female,40,2,4,Manager,1,Married,15402,15k+,17997,7,Y,No,11,3,1,80,1,21,3,1,3,2,0,2
RM521,48,46-55,No,Travel_Rarely,817,Sales,2,1,Marketing,1,712,2,Male,56,4,2,Sales Executive,2,Married,8120,5k-10k,18597,3,Y,No,12,3,4,80,0,12,3,3,2,2,2,2
RM679,48,46-55,No,Travel_Rarely,1469,Research & Development,20,4,Medical,1,945,4,Male,51,3,1,Research Scientist,3,Married,2259,Upto 5k,5543,4,Y,No,17,3,1,80,2,13,2,2,0,0,0,0
RM736,48,46-55,No,Travel_Rarely,277,Research & Development,6,3,Life Sciences,1,1022,1,Male,97,2,2,Healthcare Representative,3,Single,4240,Upto 5k,13119,2,Y,No,13,3,4,80,0,19,0,3,2,2,2,2
RM737,48,46-55,No,Travel_Rarely,1355,Research & Development,4,4,Life Sciences,1,1024,3,Male,78,2,3,Healthcare Representative,3,Single,10999,10k-15k,22245,7,Y,No,14,3,2,80,0,27,3,3,15,11,4,8
RM805,48,46-55,No,Non-Travel,1262,Research & Development,1,4,Medical,1,1116,1,Male,35,4,4,Manager,4,Single,16885,15k+,16154,2,Y,No,22,4,3,80,0,27,3,2,5,4,2,1
RM902,48,46-55,No,Travel_Rarely,969,Research & Development,2,2,Technical Degree,1,1258,4,Male,76,4,1,Laboratory Technician,2,Single,2559,Upto 5k,16620,5,Y,No,11,3,3,80,0,7,4,2,1,0,0,0
RM905,48,46-55,No,Travel_Rarely,715,Research & Development,1,3,Life Sciences,1,1263,4,Male,76,2,5,Research Director,4,Single,18265,15k+,8733,6,Y,No,12,3,3,80,0,25,3,4,1,0,0,0
RM970,48,46-55,No,Travel_Rarely,855,Research & Development,4,3,Life Sciences,1,1363,4,Male,54,3,3,Manufacturing Director,4,Single,7898,5k-10k,18706,1,Y,No,11,3,3,80,0,11,2,3,10,9,0,8
RM1039,48,46-55,No,Travel_Rarely,1221,Sales,7,3,Marketing,1,1466,3,Male,96,3,2,Sales Executive,1,Divorced,5486,5k-10k,24795,4,Y,No,11,3,1,80,3,15,3,3,2,2,2,2
RM1104,48,46-55,No,Travel_Rarely,492,Sales,16,4,Life Sciences,1,1557,3,Female,96,3,2,Sales Executive,3,Divorced,6439,5k-10k,13693,8,Y,No,14,3,3,80,1,18,2,3,8,7,7,7
RM1115,48,46-55,No,Travel_Rarely,1108,Research & Development,15,4,Other,1,1576,3,Female,65,3,1,Research Scientist,1,Married,2367,Upto 5k,16530,8,Y,No,12,3,4,80,1,10,3,2,8,2,7,6
RM1167,48,46-55,No,Travel_Frequently,365,Research & Development,4,5,Medical,1,1644,3,Male,89,2,4,Manager,4,Married,15202,15k+,5602,2,Y,No,25,4,2,80,1,23,3,3,2,2,2,2
RM1205,48,46-55,Yes,Travel_Frequently,708,Sales,7,2,Medical,1,1691,4,Female,95,3,1,Sales Representative,3,Married,2655,Upto 5k,11740,2,Y,Yes,11,3,3,80,2,19,3,3,9,7,7,7
RM1332,48,46-55,No,Travel_Rarely,1224,Research & Development,10,3,Life Sciences,1,1867,4,Male,91,2,5,Research Director,2,Married,19665,15k+,13583,4,Y,No,12,3,4,80,0,29,3,3,22,10,12,9
RM1352,48,46-55,No,Travel_Frequently,117,Research & Development,22,3,Medical,1,1900,4,Female,58,3,4,Manager,4,Divorced,17174,15k+,2437,3,Y,No,11,3,2,80,1,24,3,3,22,17,4,7
RM002,49,46-55,No,Travel_Frequently,279,Research & Development,8,1,Life Sciences,1,2,3,Male,61,2,2,Research Scientist,2,Married,5130,5k-10k,24907,1,Y,No,23,4,4,80,1,10,3,3,10,7,1,7
RM130,49,46-55,No,Travel_Rarely,470,Research & Development,20,4,Medical,1,170,3,Female,96,3,2,Manufacturing Director,1,Married,6567,5k-10k,5549,1,Y,No,14,3,3,80,0,16,2,2,15,11,5,11
RM202,49,46-55,No,Non-Travel,1002,Research & Development,18,4,Life Sciences,1,275,4,Male,92,3,2,Manufacturing Director,4,Divorced,6804,5k-10k,23793,1,Y,Yes,15,3,1,80,2,7,0,3,7,7,1,7
RM291,49,46-55,No,Travel_Frequently,636,Research & Development,10,4,Life Sciences,1,396,3,Female,35,3,5,Research Director,1,Single,18665,15k+,25594,9,Y,Yes,11,3,4,80,0,22,4,3,3,2,1,2
RM317,49,46-55,No,Travel_Rarely,1091,Research & Development,1,2,Technical Degree,1,431,3,Female,90,2,4,Healthcare Representative,3,Single,13964,10k-15k,17810,7,Y,Yes,12,3,4,80,0,25,2,3,7,1,0,7
RM376,49,46-55,No,Travel_Rarely,1261,Research & Development,7,3,Other,1,499,2,Male,31,2,3,Healthcare Representative,3,Single,10965,10k-15k,12066,8,Y,No,24,4,3,80,0,26,2,3,5,2,0,0
RM474,49,46-55,No,Travel_Rarely,1245,Research & Development,18,4,Life Sciences,1,638,4,Male,58,2,5,Research Director,3,Divorced,19502,15k+,2125,1,Y,Yes,17,3,3,80,1,31,5,3,31,9,0,9
RM608,49,46-55,Yes,Travel_Rarely,1184,Sales,11,3,Marketing,1,840,3,Female,43,3,3,Sales Executive,4,Married,7654,5k-10k,5860,1,Y,No,18,3,1,80,2,9,3,4,9,8,7,7
RM640,49,46-55,No,Travel_Rarely,1418,Research & Development,1,3,Technical Degree,1,887,3,Female,36,3,1,Research Scientist,1,Married,3580,Upto 5k,10554,2,Y,No,16,3,2,80,1,7,2,3,4,2,0,2
RM678,49,46-55,No,Travel_Rarely,527,Research & Development,8,2,Other,1,944,1,Female,51,3,3,Laboratory Technician,2,Married,7403,5k-10k,22477,4,Y,No,11,3,3,80,1,29,3,2,26,9,1,7
RM822,49,46-55,No,Travel_Rarely,174,Sales,8,4,Technical Degree,1,1138,4,Male,56,2,4,Sales Executive,2,Married,13120,10k-15k,11879,6,Y,No,17,3,2,80,1,22,3,3,9,8,2,3
RM900,49,46-55,No,Travel_Rarely,1098,Research & Development,4,2,Medical,1,1256,1,Male,85,2,5,Manager,3,Married,18711,15k+,12124,2,Y,No,13,3,3,80,1,23,2,4,1,0,0,0
RM1007,49,46-55,Yes,Travel_Frequently,1475,Research & Development,28,2,Life Sciences,1,1420,1,Male,97,2,2,Laboratory Technician,1,Single,4284,Upto 5k,22710,3,Y,No,20,4,1,80,0,20,2,3,4,3,1,3
RM1045,49,46-55,No,Travel_Rarely,1495,Research & Development,5,4,Technical Degree,1,1473,1,Male,96,3,2,Healthcare Representative,3,Married,6651,5k-10k,21534,2,Y,No,14,3,2,80,1,20,0,2,3,2,1,2
RM1055,49,46-55,No,Travel_Rarely,1490,Research & Development,7,4,Life Sciences,1,1484,3,Male,35,3,3,Healthcare Representative,2,Divorced,10466,10k-15k,20948,3,Y,No,14,3,2,80,2,29,3,3,8,7,0,7
RM1072,49,46-55,No,Travel_Rarely,271,Research & Development,3,2,Medical,1,1509,3,Female,43,2,2,Laboratory Technician,1,Married,4789,Upto 5k,23070,4,Y,No,25,4,1,80,1,10,3,3,3,2,1,2
RM1148,49,46-55,No,Travel_Rarely,722,Research & Development,25,4,Life Sciences,1,1617,3,Female,84,3,1,Laboratory Technician,1,Married,3211,Upto 5k,22102,1,Y,No,14,3,4,80,1,10,3,2,9,6,1,4
RM1177,49,46-55,No,Travel_Rarely,301,Research & Development,22,4,Other,1,1655,1,Female,72,3,4,Research Director,2,Married,16413,15k+,3498,3,Y,No,16,3,2,80,2,27,2,3,4,2,1,2
RM1182,49,46-55,No,Travel_Rarely,465,Research & Development,6,1,Life Sciences,1,1661,3,Female,41,2,4,Healthcare Representative,3,Married,13966,10k-15k,11652,2,Y,Yes,19,3,2,80,1,30,3,3,15,11,2,12
RM1193,49,46-55,No,Travel_Rarely,464,Research & Development,16,3,Medical,1,1674,4,Female,74,3,1,Laboratory Technician,1,Divorced,2587,Upto 5k,24941,4,Y,Yes,16,3,2,80,1,17,2,2,2,2,2,2
RM1196,49,46-55,No,Travel_Rarely,809,Research & Development,1,3,Life Sciences,1,1677,3,Male,36,3,4,Manager,3,Single,15379,15k+,22384,4,Y,No,14,3,1,80,0,23,2,3,8,7,0,0
RM1255,49,46-55,No,Travel_Rarely,1313,Sales,11,4,Marketing,1,1757,4,Female,80,3,2,Sales Executive,4,Single,4507,Upto 5k,8191,3,Y,No,12,3,3,80,0,8,1,4,5,1,0,4
RM1378,49,46-55,No,Travel_Frequently,1064,Research & Development,2,1,Life Sciences,1,1941,2,Male,42,3,5,Research Director,4,Married,19161,15k+,13738,3,Y,No,15,3,4,80,0,28,3,3,5,4,4,3
RM1469,49,46-55,No,Travel_Frequently,1023,Sales,2,3,Medical,1,2065,4,Male,63,2,2,Sales Executive,2,Married,5390,5k-10k,13243,2,Y,No,14,3,4,80,0,17,3,2,9,6,0,8
RM1469,49,46-55,No,Travel_Frequently,1023,Sales,2,3,Medical,1,2065,4,Male,63,2,2,Sales Executive,2,Married,5390,5k-10k,13243,2,Y,No,14,3,4,80,0,17,3,2,9,6,0,8
RM037,50,46-55,Yes,Travel_Rarely,869,Sales,3,2,Marketing,1,47,1,Male,86,2,1,Sales Representative,3,Married,2683,Upto 5k,3810,1,Y,Yes,14,3,3,80,0,3,2,3,3,2,0,2
RM063,50,46-55,No,Travel_Rarely,989,Research & Development,7,2,Medical,1,80,2,Female,43,2,5,Research Director,3,Divorced,18740,15k+,16701,5,Y,Yes,12,3,4,80,1,29,2,2,27,3,13,8
RM107,50,46-55,No,Travel_Frequently,1115,Research & Development,1,3,Life Sciences,1,141,1,Female,73,3,5,Research Director,2,Married,18172,15k+,9755,3,Y,Yes,19,3,1,80,0,28,1,2,8,3,0,7
RM132,50,46-55,No,Travel_Frequently,809,Sales,12,3,Marketing,1,174,3,Female,77,3,3,Sales Executive,4,Single,9208,5k-10k,6645,4,Y,No,11,3,4,80,0,16,3,3,2,2,2,1
RM166,50,46-55,No,Travel_Rarely,1452,Research & Development,11,3,Life Sciences,1,226,3,Female,53,3,5,Manager,2,Single,19926,15k+,17053,3,Y,No,15,3,2,80,0,21,5,3,5,4,4,4
RM184,50,46-55,No,Travel_Rarely,328,Research & Development,1,3,Medical,1,249,3,Male,86,2,1,Laboratory Technician,3,Married,3690,Upto 5k,3425,2,Y,No,15,3,4,80,1,5,2,2,3,2,0,2
RM234,50,46-55,No,Travel_Rarely,854,Sales,1,4,Medical,1,323,4,Female,68,3,5,Manager,4,Divorced,19517,15k+,24118,3,Y,No,11,3,3,80,1,32,3,2,7,0,0,6
RM280,50,46-55,No,Travel_Rarely,797,Research & Development,4,1,Life Sciences,1,385,1,Male,96,3,5,Research Director,2,Divorced,19144,15k+,15815,3,Y,No,14,3,1,80,2,28,4,2,10,4,1,6
RM368,50,46-55,No,Travel_Rarely,1046,Research & Development,10,3,Technical Degree,1,491,4,Male,100,2,3,Healthcare Representative,4,Single,10496,10k-15k,2755,6,Y,No,15,3,4,80,0,20,2,3,4,3,1,3
RM426,50,46-55,No,Travel_Rarely,1099,Research & Development,29,4,Life Sciences,1,569,2,Male,88,2,4,Manager,3,Married,17046,15k+,9314,0,Y,No,15,3,2,80,1,28,2,3,27,10,15,7
RM478,50,46-55,No,Travel_Frequently,1246,Human Resources,3,3,Medical,1,644,1,Male,99,3,5,Manager,2,Married,18200,15k+,7999,1,Y,No,11,3,3,80,1,32,2,3,32,5,10,7
RM524,50,46-55,No,Travel_Rarely,1207,Research & Development,28,1,Medical,1,716,4,Male,74,4,1,Laboratory Technician,3,Married,3221,Upto 5k,3297,1,Y,Yes,11,3,3,80,3,20,3,3,20,8,3,8
RM529,50,46-55,Yes,Travel_Frequently,562,Sales,8,2,Technical Degree,1,723,2,Male,50,3,2,Sales Executive,3,Married,6796,5k-10k,23452,3,Y,Yes,14,3,1,80,1,18,4,3,4,3,1,3
RM540,50,46-55,No,Travel_Rarely,316,Sales,8,4,Marketing,1,738,4,Male,54,3,1,Sales Representative,2,Married,3875,Upto 5k,9983,7,Y,No,15,3,4,80,1,4,2,3,2,2,2,2
RM589,50,46-55,No,Travel_Rarely,691,Research & Development,2,3,Medical,1,815,3,Male,64,3,4,Research Director,3,Married,17639,15k+,6881,5,Y,No,16,3,4,80,0,30,3,3,4,3,0,3
RM654,50,46-55,No,Non-Travel,881,Research & Development,2,4,Life Sciences,1,905,1,Male,98,3,4,Manager,1,Divorced,17924,15k+,4544,1,Y,No,11,3,4,80,1,31,3,3,31,6,14,7
RM715,50,46-55,No,Travel_Rarely,1126,Research & Development,1,2,Medical,1,997,4,Male,66,3,4,Research Director,4,Divorced,17399,15k+,6615,9,Y,No,22,4,3,80,1,32,1,2,5,4,1,3
RM722,50,46-55,No,Travel_Rarely,939,Research & Development,24,3,Life Sciences,1,1005,4,Male,95,3,4,Manufacturing Director,3,Married,13973,10k-15k,4161,3,Y,Yes,18,3,4,80,1,22,2,3,12,11,1,5
RM743,50,46-55,No,Travel_Rarely,804,Research & Development,9,3,Life Sciences,1,1030,1,Male,64,3,1,Laboratory Technician,4,Married,2380,Upto 5k,20165,4,Y,No,18,3,2,80,0,8,5,3,1,0,0,0
RM752,50,46-55,No,Non-Travel,145,Sales,1,3,Life Sciences,1,1040,4,Female,95,3,2,Sales Executive,3,Married,6347,5k-10k,24920,0,Y,No,12,3,1,80,1,19,3,3,18,7,0,13
RM767,50,46-55,No,Travel_Rarely,1464,Research & Development,2,4,Medical,1,1061,2,Male,62,3,5,Research Director,3,Married,19237,15k+,12853,2,Y,Yes,11,3,4,80,1,29,2,2,8,1,7,7
RM802,50,46-55,Yes,Travel_Frequently,959,Sales,1,4,Other,1,1113,4,Male,81,3,2,Sales Executive,3,Single,4728,Upto 5k,17251,3,Y,Yes,14,3,4,80,0,5,4,3,0,0,0,0
RM868,50,46-55,No,Travel_Frequently,1421,Research & Development,2,3,Medical,1,1215,4,Female,30,3,4,Manager,1,Married,17856,15k+,9490,2,Y,No,22,4,3,80,1,32,3,3,2,2,2,2
RM946,50,46-55,No,Travel_Rarely,1322,Research & Development,28,3,Life Sciences,1,1317,4,Female,43,3,4,Research Director,1,Married,16880,15k+,22422,4,Y,Yes,11,3,2,80,0,25,2,3,3,2,1,2
RM1087,50,46-55,No,Travel_Frequently,333,Research & Development,22,5,Medical,1,1539,3,Male,88,1,4,Research Director,4,Single,14411,10k-15k,24450,1,Y,Yes,13,3,4,80,0,32,2,3,32,6,13,9
RM1127,50,46-55,No,Travel_Rarely,264,Sales,9,3,Marketing,1,1591,3,Male,59,3,5,Manager,3,Married,19331,15k+,19519,4,Y,Yes,16,3,3,80,1,27,2,3,1,0,0,0
RM1139,50,46-55,No,Travel_Frequently,1234,Research & Development,20,5,Medical,1,1606,2,Male,41,3,4,Healthcare Representative,3,Married,11245,10k-15k,20689,2,Y,Yes,15,3,3,80,1,32,3,3,30,8,12,13
RM1178,50,46-55,No,Travel_Rarely,813,Research & Development,17,5,Life Sciences,1,1656,4,Female,50,2,3,Research Director,1,Divorced,13269,10k-15k,21981,5,Y,No,15,3,3,80,3,19,3,3,14,11,1,11
RM1453,50,46-55,Yes,Travel_Frequently,878,Sales,1,4,Life Sciences,1,2044,2,Male,94,3,2,Sales Executive,3,Divorced,6728,5k-10k,14255,7,Y,No,12,3,4,80,2,12,3,3,6,3,0,1
RM1462,50,46-55,Yes,Travel_Rarely,410,Sales,28,3,Marketing,1,2055,4,Male,39,2,3,Sales Executive,1,Divorced,10854,10k-15k,16586,4,Y,Yes,13,3,2,80,1,20,3,3,3,2,2,0
RM1462,50,46-55,Yes,Travel_Rarely,410,Sales,28,3,Marketing,1,2055,4,Male,39,2,3,Sales Executive,1,Divorced,10854,10k-15k,16586,4,Y,Yes,13,3,2,80,1,20,3,3,3,2,2,0
RM088,51,46-55,No,Travel_Rarely,432,Research & Development,9,4,Life Sciences,1,116,4,Male,96,3,1,Laboratory Technician,4,Married,2075,Upto 5k,18725,3,Y,No,23,4,2,80,2,10,4,3,4,2,0,3
RM092,51,46-55,No,Travel_Rarely,632,Sales,21,4,Marketing,1,120,3,Male,71,3,2,Sales Executive,4,Single,5441,5k-10k,8423,0,Y,Yes,22,4,4,80,0,11,2,1,10,7,1,0
RM111,51,46-55,No,Travel_Frequently,1456,Research & Development,1,4,Medical,1,145,1,Female,30,2,3,Healthcare Representative,1,Single,7484,5k-10k,25796,3,Y,No,20,4,3,80,0,23,1,2,13,12,12,8
RM124,51,46-55,No,Travel_Rarely,684,Research & Development,6,3,Life Sciences,1,162,1,Male,51,3,5,Research Director,3,Single,19537,15k+,6462,7,Y,No,13,3,3,80,0,23,5,3,20,18,15,15
RM137,51,46-55,Yes,Travel_Frequently,1150,Research & Development,8,4,Life Sciences,1,179,1,Male,53,1,3,Manufacturing Director,4,Single,10650,10k-15k,25150,2,Y,No,15,3,4,80,0,18,2,3,4,2,0,3
RM157,51,46-55,No,Travel_Rarely,1169,Research & Development,7,4,Medical,1,211,2,Male,34,2,2,Manufacturing Director,3,Married,6132,5k-10k,13983,2,Y,No,17,3,3,80,0,10,2,3,1,0,0,0
RM190,51,46-55,No,Travel_Rarely,313,Research & Development,3,3,Medical,1,258,4,Female,98,3,4,Healthcare Representative,2,Single,13734,10k-15k,7192,3,Y,No,18,3,3,80,0,21,6,3,7,7,1,0
RM214,51,46-55,No,Travel_Rarely,1469,Research & Development,8,4,Life Sciences,1,296,2,Male,81,2,3,Research Director,2,Married,12490,10k-15k,15736,5,Y,No,16,3,4,80,2,16,5,1,10,9,4,7
RM259,51,46-55,No,Travel_Rarely,833,Research & Development,1,3,Life Sciences,1,353,3,Male,96,3,1,Research Scientist,4,Married,2723,Upto 5k,23231,1,Y,No,11,3,2,80,0,1,0,2,1,0,0,
RM300,51,46-55,No,Travel_Rarely,1302,Research & Development,2,3,Medical,1,408,4,Male,84,1,2,Manufacturing Director,2,Divorced,5482,5k-10k,16321,5,Y,No,18,3,4,80,1,13,3,3,4,1,1,2
RM377,51,46-55,No,Travel_Rarely,1178,Sales,14,2,Life Sciences,1,500,3,Female,87,3,2,Sales Executive,4,Married,4936,Upto 5k,14862,4,Y,No,11,3,3,80,1,18,2,2,7,7,0,7
RM617,51,46-55,No,Travel_Rarely,1318,Sales,26,4,Marketing,1,851,1,Female,66,3,4,Manager,3,Married,16307,15k+,5594,2,Y,No,14,3,3,80,1,29,2,2,20,6,4,17
RM780,51,46-55,Yes,Travel_Rarely,1323,Research & Development,4,4,Life Sciences,1,1081,1,Male,34,3,1,Research Scientist,3,Married,2461,Upto 5k,10332,9,Y,Yes,12,3,3,80,3,18,2,4,10,0,2,7
RM919,51,46-55,No,Travel_Frequently,237,Sales,9,3,Life Sciences,1,1282,4,Male,83,3,5,Manager,2,Divorced,19847,15k+,19196,4,Y,Yes,24,4,1,80,1,31,5,2,29,10,11,10
RM931,51,46-55,No,Travel_Frequently,968,Research & Development,6,2,Medical,1,1297,2,Female,40,2,1,Laboratory Technician,3,Single,2838,Upto 5k,4257,0,Y,No,14,3,2,80,0,8,6,2,7,0,7,7
RM963,51,46-55,No,Travel_Rarely,770,Human Resources,5,3,Life Sciences,1,1352,3,Male,84,3,4,Manager,2,Divorced,14026,10k-15k,17588,1,Y,Yes,11,3,2,80,1,33,2,3,33,9,0,10
RM972,51,46-55,No,Travel_Rarely,1405,Research & Development,11,2,Technical Degree,1,1367,4,Female,82,2,4,Manufacturing Director,2,Single,13142,10k-15k,24439,3,Y,No,16,3,2,80,0,29,1,2,5,2,0,3
RM988,51,46-55,No,Travel_Frequently,541,Sales,2,3,Marketing,1,1391,2,Male,52,3,3,Sales Executive,2,Married,10596,10k-15k,15395,2,Y,No,11,3,2,80,0,14,5,3,4,2,3,2
RM1276,51,46-55,No,Travel_Rarely,942,Research & Development,3,3,Technical Degree,1,1786,1,Female,53,3,3,Manager,3,Married,13116,10k-15k,22984,2,Y,No,11,3,4,80,0,15,2,3,2,2,2,2
RM191,52,46-55,No,Travel_Rarely,699,Research & Development,1,4,Life Sciences,1,259,3,Male,65,2,5,Manager,3,Married,19999,15k+,5678,0,Y,No,14,3,1,80,1,34,5,3,33,18,11,9
RM231,52,46-55,No,Travel_Rarely,1323,Research & Development,2,3,Life Sciences,1,316,3,Female,89,2,1,Laboratory Technician,4,Single,3212,Upto 5k,3300,7,Y,No,15,3,2,80,0,6,3,2,2,2,2,2
RM238,52,46-55,No,Non-Travel,771,Sales,2,4,Life Sciences,1,329,1,Male,79,2,5,Manager,3,Single,19068,15k+,21030,1,Y,Yes,18,3,4,80,0,33,2,4,33,7,15,12
RM318,52,46-55,Yes,Travel_Rarely,723,Research & Development,8,4,Medical,1,433,3,Male,85,2,2,Research Scientist,2,Married,4941,Upto 5k,17747,2,Y,No,15,3,1,80,0,11,3,2,8,2,7,7
RM407,52,46-55,No,Travel_Rarely,319,Research & Development,3,3,Medical,1,543,4,Male,39,2,3,Manufacturing Director,3,Married,7969,5k-10k,19609,2,Y,Yes,14,3,3,80,0,28,4,3,5,4,0,
RM409,52,46-55,No,Travel_Rarely,1490,Research & Development,4,2,Life Sciences,1,546,4,Female,30,3,4,Manager,4,Married,16555,15k+,10310,2,Y,No,13,3,4,80,0,31,2,1,5,2,1,4
RM469,52,46-55,No,Travel_Rarely,956,Research & Development,6,2,Technical Degree,1,630,4,Male,78,3,2,Research Scientist,1,Divorced,5577,5k-10k,22087,3,Y,Yes,12,3,2,80,2,18,3,3,10,9,6,9
RM562,52,46-55,No,Travel_Rarely,621,Sales,3,4,Marketing,1,776,3,Male,31,2,4,Manager,1,Married,16856,15k+,10084,1,Y,No,11,3,1,80,0,34,3,4,34,6,1,16
RM571,52,46-55,No,Non-Travel,715,Research & Development,19,4,Medical,1,791,4,Male,41,3,1,Research Scientist,4,Married,4258,Upto 5k,26589,0,Y,No,18,3,1,80,1,5,3,3,4,3,1,2
RM588,52,46-55,No,Travel_Rarely,1325,Research & Development,11,4,Life Sciences,1,813,4,Female,82,3,2,Laboratory Technician,3,Married,3149,Upto 5k,21821,8,Y,No,20,4,2,80,1,9,3,3,5,2,1,4
RM628,52,46-55,No,Travel_Frequently,890,Research & Development,25,4,Medical,1,867,3,Female,81,2,4,Manufacturing Director,4,Married,13826,10k-15k,19028,3,Y,No,22,4,3,80,0,31,3,3,9,8,0,0
RM700,52,46-55,No,Travel_Rarely,1053,Research & Development,1,2,Life Sciences,1,976,4,Male,70,3,4,Manager,4,Married,17099,15k+,13829,2,Y,No,15,3,2,80,1,26,2,2,9,8,7,8
RM750,52,46-55,Yes,Travel_Rarely,266,Sales,2,1,Marketing,1,1038,1,Female,57,1,5,Manager,4,Married,19845,15k+,25846,1,Y,No,15,3,4,80,1,33,3,3,32,14,6,9
RM807,52,46-55,No,Travel_Rarely,994,Research & Development,7,4,Life Sciences,1,1118,2,Male,87,3,3,Healthcare Representative,2,Single,10445,10k-15k,15322,7,Y,No,19,3,4,80,0,18,4,3,8,6,4,0
RM948,52,46-55,Yes,Travel_Rarely,1030,Sales,5,3,Life Sciences,1,1319,2,Male,64,3,3,Sales Executive,2,Single,8446,5k-10k,21534,9,Y,Yes,19,3,3,80,0,10,2,2,8,7,7,7
RM995,52,46-55,No,Travel_Frequently,322,Research & Development,28,2,Medical,1,1401,4,Female,59,4,4,Manufacturing Director,3,Married,13247,10k-15k,9731,2,Y,Yes,11,3,2,80,1,24,3,2,5,3,0,2
RM1001,52,46-55,No,Travel_Rarely,258,Research & Development,8,4,Other,1,1409,3,Female,54,3,1,Laboratory Technician,1,Married,2950,Upto 5k,17363,9,Y,No,13,3,3,80,0,12,2,1,5,4,0,4
RM1435,52,46-55,No,Non-Travel,585,Sales,29,4,Life Sciences,1,2019,1,Male,40,3,1,Sales Representative,4,Divorced,3482,Upto 5k,19788,2,Y,No,15,3,2,80,2,16,3,2,9,8,0,0
RM019,53,46-55,No,Travel_Rarely,1219,Sales,2,4,Life Sciences,1,23,1,Female,78,2,4,Manager,4,Married,15427,15k+,22021,2,Y,No,16,3,3,80,0,31,3,3,25,8,3,7
RM026,53,46-55,No,Travel_Rarely,1282,Research & Development,5,3,Other,1,32,3,Female,58,3,5,Manager,3,Divorced,19094,15k+,10735,4,Y,No,11,3,4,80,1,26,3,2,14,13,4,
RM153,53,46-55,No,Travel_Rarely,1436,Sales,6,2,Marketing,1,205,2,Male,34,3,2,Sales Representative,3,Married,2306,Upto 5k,16047,2,Y,Yes,20,4,4,80,1,13,3,1,7,7,4,5
RM185,53,46-55,No,Travel_Rarely,1084,Research & Development,13,2,Medical,1,250,4,Female,57,4,2,Manufacturing Director,1,Divorced,4450,Upto 5k,26250,1,Y,No,11,3,3,80,2,5,3,3,4,2,1,3
RM281,53,46-55,No,Travel_Rarely,1070,Research & Development,3,4,Medical,1,386,3,Male,45,3,4,Research Director,3,Married,17584,15k+,21016,3,Y,Yes,16,3,4,80,3,21,5,2,5,3,1,3
RM503,53,46-55,No,Travel_Rarely,238,Sales,1,1,Medical,1,682,4,Female,34,3,2,Sales Executive,1,Single,8381,5k-10k,7507,7,Y,No,20,4,4,80,0,18,2,4,14,7,8,10
RM535,53,46-55,No,Travel_Rarely,970,Research & Development,7,3,Life Sciences,1,730,3,Male,59,4,4,Research Director,3,Married,14814,10k-15k,13514,3,Y,No,19,3,3,80,0,32,3,3,5,1,1,3
RM557,53,46-55,No,Travel_Rarely,346,Research & Development,6,3,Life Sciences,1,769,4,Male,86,3,2,Laboratory Technician,4,Single,2450,Upto 5k,10919,2,Y,No,17,3,4,80,0,19,4,3,2,2,2,2
RM625,53,46-55,No,Travel_Rarely,661,Sales,7,2,Marketing,1,862,1,Female,78,2,3,Sales Executive,4,Married,10934,10k-15k,20715,7,Y,Yes,18,3,4,80,1,35,3,3,5,2,0,4
RM647,53,46-55,No,Travel_Rarely,868,Sales,8,3,Marketing,1,897,1,Male,73,3,4,Sales Executive,4,Married,11836,10k-15k,22789,5,Y,No,14,3,3,80,1,28,3,3,2,0,2,2
RM650,53,46-55,No,Travel_Rarely,102,Research & Development,23,4,Life Sciences,1,901,4,Female,72,3,4,Research Director,4,Single,14275,10k-15k,20206,6,Y,No,18,3,3,80,0,33,0,3,12,9,3,8
RM702,53,46-55,No,Travel_Rarely,1376,Sales,2,2,Medical,1,981,3,Male,45,3,4,Manager,3,Divorced,14852,10k-15k,13938,6,Y,No,13,3,3,80,1,22,3,4,17,13,15,2
RM761,53,46-55,No,Travel_Frequently,124,Sales,2,3,Marketing,1,1050,3,Female,38,2,3,Sales Executive,2,Married,7525,5k-10k,23537,2,Y,No,12,3,1,80,1,30,2,3,15,7,6,12
RM859,53,46-55,No,Travel_Rarely,1223,Research & Development,7,2,Medical,1,1201,4,Female,50,3,5,Manager,3,Divorced,18606,15k+,18640,3,Y,No,18,3,2,80,1,26,6,3,7,7,4,7
RM1044,53,46-55,No,Travel_Rarely,447,Research & Development,2,3,Medical,1,1472,4,Male,39,4,4,Research Director,2,Single,16598,15k+,19764,4,Y,No,12,3,2,80,0,35,2,2,9,8,8,8
RM1112,53,46-55,Yes,Travel_Rarely,607,Research & Development,2,5,Technical Degree,1,1572,3,Female,78,2,3,Manufacturing Director,4,Married,10169,10k-15k,14618,0,Y,No,16,3,2,80,1,34,4,3,33,7,1,9
RM1204,53,46-55,No,Travel_Rarely,1395,Research & Development,24,4,Medical,1,1689,2,Male,48,4,3,Healthcare Representative,4,Married,7005,5k-10k,3458,3,Y,No,15,3,3,80,0,11,2,3,4,3,1,2
RM1269,53,46-55,No,Non-Travel,661,Research & Development,1,4,Medical,1,1775,1,Female,60,2,4,Manufacturing Director,3,Married,12965,10k-15k,22308,4,Y,Yes,20,4,4,80,3,27,2,2,3,2,0,2
RM1397,53,46-55,Yes,Travel_Rarely,1168,Sales,24,4,Life Sciences,1,1968,1,Male,66,3,3,Sales Executive,1,Single,10448,10k-15k,5843,6,Y,Yes,13,3,2,80,0,15,2,2,2,2,2,2
RM096,54,46-55,No,Travel_Rarely,1217,Research & Development,2,4,Technical Degree,1,126,1,Female,60,3,3,Research Director,3,Married,13549,10k-15k,24001,9,Y,No,12,3,1,80,1,16,5,1,4,3,0,3
RM113,54,46-55,No,Non-Travel,142,Human Resources,26,3,Human Resources,1,148,4,Female,30,4,4,Manager,4,Single,17328,15k+,13871,2,Y,Yes,12,3,3,80,0,23,3,3,5,3,4,4
RM220,54,46-55,No,Travel_Rarely,1147,Sales,3,3,Marketing,1,303,4,Female,52,3,2,Sales Executive,1,Married,5940,5k-10k,17011,2,Y,No,14,3,4,80,1,16,4,3,6,2,0,5
RM333,54,46-55,No,Travel_Frequently,928,Research & Development,20,4,Life Sciences,1,450,4,Female,31,3,2,Research Scientist,3,Single,4869,Upto 5k,16885,3,Y,No,12,3,4,80,0,20,4,2,4,3,0,3
RM393,54,46-55,No,Travel_Rarely,821,Research & Development,5,2,Medical,1,522,1,Male,86,3,5,Research Director,1,Married,19406,15k+,8509,4,Y,No,11,3,3,80,1,24,4,2,4,2,1,2
RM432,54,46-55,No,Travel_Rarely,548,Research & Development,8,4,Life Sciences,1,578,3,Female,42,3,2,Laboratory Technician,3,Single,3780,Upto 5k,23428,7,Y,No,11,3,3,80,0,19,3,3,1,0,0,0
RM511,54,46-55,No,Travel_Rarely,397,Human Resources,19,4,Medical,1,698,3,Male,88,3,3,Human Resources,2,Married,10725,10k-15k,6729,2,Y,No,15,3,3,80,1,16,1,4,9,7,7,1
RM576,54,46-55,No,Travel_Rarely,376,Research & Development,19,4,Medical,1,799,4,Female,95,3,2,Manufacturing Director,1,Divorced,5485,5k-10k,22670,9,Y,Yes,11,3,2,80,2,9,4,3,5,3,1,4
RM729,54,46-55,No,Travel_Rarely,1441,Research & Development,17,3,Technical Degree,1,1013,3,Female,56,3,3,Manufacturing Director,3,Married,10739,10k-15k,13943,8,Y,No,11,3,3,80,1,22,2,3,10,7,0,8
RM772,54,46-55,No,Travel_Rarely,1082,Sales,2,4,Life Sciences,1,1070,3,Female,41,2,3,Sales Executive,3,Married,10686,10k-15k,8392,6,Y,No,11,3,2,80,1,13,4,3,9,4,7,0
RM891,54,46-55,No,Travel_Frequently,966,Research & Development,1,4,Life Sciences,1,1245,4,Female,53,3,3,Manufacturing Director,3,Divorced,10502,10k-15k,9659,7,Y,No,17,3,1,80,1,33,2,1,5,4,1,4
RM895,54,46-55,No,Travel_Rarely,685,Research & Development,3,3,Life Sciences,1,1250,4,Male,85,3,4,Research Director,4,Married,17779,15k+,23474,3,Y,No,14,3,1,80,0,36,2,3,10,9,0,9
RM1009,54,46-55,No,Travel_Rarely,971,Research & Development,1,3,Medical,1,1422,4,Female,54,3,4,Research Director,4,Single,17328,15k+,5652,6,Y,No,19,3,4,80,0,29,3,2,20,7,12,7
RM1077,54,46-55,No,Travel_Frequently,1050,Research & Development,11,4,Medical,1,1520,2,Female,87,3,4,Manager,4,Divorced,16032,15k+,24456,3,Y,No,20,4,1,80,1,26,2,3,14,9,1,12
RM1185,54,46-55,No,Travel_Rarely,584,Research & Development,22,5,Medical,1,1665,2,Female,91,3,4,Manager,3,Married,17426,15k+,18685,3,Y,No,25,4,3,80,1,36,6,3,10,8,4,7
RM1306,54,46-55,No,Travel_Rarely,431,Research & Development,7,4,Medical,1,1830,4,Female,68,3,2,Research Scientist,4,Married,6854,5k-10k,15696,4,Y,No,15,3,2,80,1,14,2,2,7,1,1,7
RM1398,54,46-55,No,Travel_Rarely,155,Research & Development,9,2,Life Sciences,1,1969,1,Female,67,3,2,Research Scientist,3,Married,2897,Upto 5k,22474,3,Y,No,11,3,3,80,2,9,6,2,4,3,2,3
RM1407,54,46-55,No,Travel_Rarely,157,Research & Development,10,3,Medical,1,1980,3,Female,77,3,2,Manufacturing Director,1,Single,4440,Upto 5k,25198,6,Y,Yes,19,3,4,80,0,9,3,3,5,2,1,4
RM066,55,46-55,No,Travel_Rarely,836,Research & Development,8,3,Medical,1,84,4,Female,33,3,4,Manager,3,Divorced,14756,10k-15k,19730,2,Y,Yes,14,3,3,80,3,21,2,3,5,0,0,2
RM083,55,46-55,No,Travel_Rarely,111,Sales,1,2,Life Sciences,1,106,1,Male,70,3,3,Sales Executive,4,Married,10239,10k-15k,18092,3,Y,No,14,3,4,80,1,24,4,3,1,0,1,0
RM188,55,46-55,No,Travel_Rarely,692,Research & Development,14,4,Medical,1,254,3,Male,61,4,5,Research Director,2,Single,18722,15k+,13339,8,Y,No,11,3,4,80,0,36,3,3,24,15,2,15
RM271,55,46-55,No,Travel_Rarely,452,Research & Development,1,3,Medical,1,374,4,Male,81,3,5,Manager,1,Single,19045,15k+,18938,0,Y,Yes,14,3,3,80,0,37,2,3,36,10,4,13
RM284,55,46-55,No,Travel_Rarely,147,Research & Development,20,2,Technical Degree,1,389,2,Male,37,3,2,Laboratory Technician,4,Married,5415,5k-10k,15972,3,Y,Yes,19,3,4,80,1,12,4,3,10,7,0,8
RM380,55,46-55,No,Travel_Rarely,1311,Research & Development,2,3,Life Sciences,1,505,3,Female,97,3,4,Manager,4,Single,16659,15k+,23258,2,Y,Yes,13,3,3,80,0,30,2,3,5,4,1,2
RM446,55,46-55,No,Travel_Rarely,1117,Sales,18,5,Life Sciences,1,597,1,Female,83,3,4,Manager,2,Single,16835,15k+,9873,3,Y,No,23,4,4,80,0,37,2,3,10,9,7,7
RM569,55,46-55,Yes,Travel_Rarely,725,Research & Development,2,3,Medical,1,787,4,Male,78,3,5,Manager,1,Married,19859,15k+,21199,5,Y,Yes,13,3,4,80,1,24,2,3,5,2,1,4
RM609,55,46-55,Yes,Travel_Rarely,436,Sales,2,1,Medical,1,842,3,Male,37,3,2,Sales Executive,4,Single,5160,5k-10k,21519,4,Y,No,16,3,3,80,0,12,3,2,9,7,7,3
RM746,55,46-55,No,Travel_Frequently,135,Research & Development,18,4,Medical,1,1034,3,Male,62,3,2,Healthcare Representative,2,Married,6385,5k-10k,12992,3,Y,Yes,14,3,4,80,2,17,3,3,8,7,6,7
RM775,55,46-55,No,Non-Travel,444,Research & Development,2,1,Medical,1,1074,3,Male,40,2,4,Manager,1,Single,16756,15k+,17323,7,Y,No,15,3,2,80,0,31,3,4,9,7,6,2
RM788,55,46-55,No,Travel_Frequently,1091,Research & Development,2,1,Life Sciences,1,1096,4,Male,65,3,3,Manufacturing Director,2,Married,10976,10k-15k,15813,3,Y,No,18,3,2,80,1,23,4,3,3,2,1,2
RM915,55,46-55,No,Non-Travel,177,Research & Development,8,1,Medical,1,1278,4,Male,37,2,4,Healthcare Representative,2,Divorced,13577,10k-15k,25592,1,Y,Yes,15,3,4,80,1,34,3,3,33,9,15,0
RM956,55,46-55,No,Travel_Rarely,282,Research & Development,2,2,Medical,1,1336,4,Female,58,1,5,Manager,3,Married,19187,15k+,6992,4,Y,No,14,3,4,80,1,23,5,3,19,9,9,11
RM976,55,46-55,Yes,Travel_Rarely,267,Sales,13,4,Marketing,1,1372,1,Male,85,4,4,Sales Executive,3,Single,13695,10k-15k,9277,6,Y,Yes,17,3,3,80,0,24,2,2,19,7,3,8
RM1011,55,46-55,No,Travel_Rarely,1136,Research & Development,1,4,Medical,1,1424,2,Male,81,4,4,Research Director,4,Divorced,14732,10k-15k,12414,2,Y,No,13,3,4,80,2,31,4,4,7,7,0,0
RM1066,55,46-55,No,Travel_Rarely,1229,Research & Development,4,4,Life Sciences,1,1501,4,Male,30,3,2,Healthcare Representative,3,Married,4035,Upto 5k,16143,0,Y,Yes,16,3,2,80,0,4,2,3,3,2,1,2
RM1117,55,46-55,No,Travel_Rarely,685,Sales,26,5,Marketing,1,1578,3,Male,60,2,5,Manager,4,Married,19586,15k+,23037,1,Y,No,21,4,3,80,1,36,3,3,36,6,2,13
RM1208,55,46-55,No,Travel_Rarely,1441,Research & Development,22,3,Technical Degree,1,1694,1,Male,94,2,1,Research Scientist,2,Divorced,3537,Upto 5k,23737,5,Y,No,12,3,4,80,1,8,1,3,4,2,1,2
RM1265,55,46-55,No,Travel_Rarely,478,Research & Development,2,3,Medical,1,1770,3,Male,60,2,5,Research Director,1,Married,19038,15k+,19805,8,Y,No,12,3,2,80,3,34,2,3,1,0,0,0
RM1337,55,46-55,No,Travel_Rarely,836,Research & Development,2,4,Technical Degree,1,1873,2,Male,98,2,1,Research Scientist,4,Married,2662,Upto 5k,7975,8,Y,No,20,4,2,80,1,19,2,4,5,2,0,4
RM1402,55,46-55,No,Travel_Rarely,189,Human Resources,26,4,Human Resources,1,1973,3,Male,71,4,5,Manager,2,Married,19636,15k+,25811,4,Y,Yes,18,3,1,80,1,35,0,3,10,9,1,4
RM086,56,55+,No,Travel_Rarely,1400,Research & Development,7,3,Life Sciences,1,112,4,Male,49,1,3,Manufacturing Director,4,Single,7260,5k-10k,21698,4,Y,No,11,3,1,80,0,37,3,2,6,4,0,2
RM123,56,55+,Yes,Travel_Rarely,441,Research & Development,14,4,Life Sciences,1,161,2,Female,72,3,1,Research Scientist,2,Married,4963,Upto 5k,4510,9,Y,Yes,18,3,1,80,3,7,2,3,5,4,4,3
RM176,56,55+,No,Travel_Rarely,713,Research & Development,8,3,Life Sciences,1,241,3,Female,67,3,1,Research Scientist,1,Divorced,4257,Upto 5k,13939,4,Y,Yes,18,3,3,80,1,19,3,3,2,2,2,2
RM402,56,55+,No,Travel_Frequently,906,Sales,6,3,Life Sciences,1,532,3,Female,86,4,4,Sales Executive,1,Married,13212,10k-15k,18256,9,Y,No,11,3,4,80,3,36,0,2,7,7,7,7
RM553,56,55+,No,Travel_Rarely,832,Research & Development,9,3,Medical,1,762,3,Male,81,3,4,Healthcare Representative,4,Married,11103,10k-15k,20420,7,Y,No,11,3,3,80,0,30,1,2,10,7,1,1
RM773,56,55+,No,Travel_Frequently,1240,Research & Development,9,3,Medical,1,1071,1,Female,63,3,1,Research Scientist,3,Married,2942,Upto 5k,12154,2,Y,No,19,3,2,80,1,18,4,3,5,4,0,3
RM852,56,55+,No,Travel_Rarely,718,Research & Development,4,4,Technical Degree,1,1191,4,Female,92,3,5,Manager,1,Divorced,19943,15k+,18575,4,Y,No,13,3,4,80,1,28,2,3,5,2,4,2
RM957,56,55+,No,Travel_Rarely,206,Human Resources,8,4,Life Sciences,1,1338,4,Male,99,3,5,Manager,2,Single,19717,15k+,4022,6,Y,No,14,3,1,80,0,36,4,3,7,3,7,7
RM977,56,55+,No,Travel_Rarely,1369,Research & Development,23,3,Life Sciences,1,1373,4,Male,68,3,4,Manufacturing Director,2,Married,13402,10k-15k,18235,4,Y,Yes,12,3,1,80,1,33,0,3,19,16,15,9
RM1024,56,55+,No,Travel_Rarely,1255,Research & Development,1,2,Life Sciences,1,1441,1,Female,90,3,1,Research Scientist,1,Married,2066,Upto 5k,10494,2,Y,No,22,4,4,80,1,5,3,4,3,2,1,0
RM1355,56,55+,Yes,Travel_Rarely,1162,Research & Development,24,2,Life Sciences,1,1907,1,Male,97,3,1,Laboratory Technician,4,Single,2587,Upto 5k,10261,1,Y,No,16,3,4,80,0,5,3,3,4,2,1,0
RM1372,56,55+,No,Travel_Rarely,1443,Sales,11,5,Marketing,1,1935,4,Female,89,2,2,Sales Executive,1,Married,5380,5k-10k,20328,4,Y,No,16,3,3,80,1,6,3,3,0,0,0,0
RM1442,56,55+,No,Non-Travel,667,Research & Development,1,4,Life Sciences,1,2026,3,Male,57,3,2,Healthcare Representative,3,Divorced,6306,5k-10k,26236,1,Y,No,21,4,1,80,1,13,2,2,13,12,1,9
RM1445,56,55+,Yes,Travel_Rarely,310,Research & Development,7,2,Technical Degree,1,2032,4,Male,72,3,1,Laboratory Technician,3,Married,2339,Upto 5k,3666,8,Y,No,11,3,4,80,1,14,4,1,10,9,9,8
RM164,57,55+,No,Travel_Rarely,334,Research & Development,24,2,Life Sciences,1,223,3,Male,83,4,3,Healthcare Representative,4,Divorced,9439,5k-10k,23402,3,Y,Yes,16,3,2,80,1,12,2,1,5,3,1,4
RM361,57,55+,No,Travel_Rarely,593,Research & Development,1,4,Medical,1,482,4,Male,88,3,2,Healthcare Representative,3,Married,6755,5k-10k,2967,2,Y,No,11,3,3,80,0,15,2,3,3,2,1,
RM425,57,55+,No,Travel_Rarely,210,Sales,29,3,Marketing,1,568,1,Male,56,2,4,Manager,4,Divorced,14118,10k-15k,22102,3,Y,No,12,3,3,80,1,32,3,2,1,0,0,0
RM1054,57,55+,No,Travel_Rarely,405,Research & Development,1,2,Life Sciences,1,1483,2,Male,93,4,2,Research Scientist,3,Married,4900,Upto 5k,2721,0,Y,No,24,4,1,80,1,13,2,2,12,9,2,8
RM099,58,55+,No,Travel_Rarely,682,Sales,10,4,Medical,1,131,4,Male,37,3,4,Sales Executive,3,Single,13872,10k-15k,24409,0,Y,No,13,3,3,80,0,38,1,2,37,10,1,8
RM127,58,55+,Yes,Travel_Rarely,147,Research & Development,23,4,Medical,1,165,4,Female,94,3,3,Healthcare Representative,4,Married,10312,10k-15k,3465,1,Y,No,12,3,4,80,1,40,3,2,40,10,15,6
RM158,58,55+,No,Travel_Rarely,1145,Research & Development,9,3,Medical,1,214,2,Female,75,2,1,Research Scientist,2,Married,3346,Upto 5k,11873,4,Y,Yes,20,4,2,80,1,9,3,2,1,0,0,0
RM309,58,55+,No,Non-Travel,390,Research & Development,1,4,Life Sciences,1,422,4,Male,32,1,2,Healthcare Representative,3,Divorced,5660,5k-10k,17056,2,Y,Yes,13,3,4,80,1,12,2,3,5,3,1,2
RM596,58,55+,Yes,Travel_Rarely,286,Research & Development,2,4,Life Sciences,1,825,4,Male,31,3,5,Research Director,2,Single,19246,15k+,25761,7,Y,Yes,12,3,4,80,0,40,2,3,31,15,13,8
RM661,58,55+,Yes,Travel_Frequently,781,Research & Development,2,1,Life Sciences,1,918,4,Male,57,2,1,Laboratory Technician,4,Divorced,2380,Upto 5k,13384,9,Y,Yes,14,3,4,80,1,3,3,2,1,0,0,0
RM675,58,55+,No,Travel_Rarely,1272,Research & Development,5,3,Technical Degree,1,940,3,Female,37,2,3,Healthcare Representative,2,Divorced,10552,10k-15k,9255,2,Y,Yes,13,3,4,80,1,24,3,3,6,0,0,4
RM701,58,55+,Yes,Travel_Rarely,289,Research & Development,2,3,Technical Degree,1,977,4,Male,51,3,1,Research Scientist,3,Single,2479,Upto 5k,26227,4,Y,No,24,4,1,80,0,7,4,3,1,0,0,0
RM939,58,55+,No,Travel_Rarely,848,Research & Development,23,4,Life Sciences,1,1308,1,Male,88,3,1,Research Scientist,3,Divorced,2372,Upto 5k,26076,1,Y,No,12,3,4,80,2,2,3,3,2,2,2,2
RM967,58,55+,Yes,Travel_Rarely,601,Research & Development,7,4,Medical,1,1360,3,Female,53,2,3,Manufacturing Director,1,Married,10008,10k-15k,12023,7,Y,Yes,14,3,4,80,0,31,0,2,10,9,5,9
RM1010,58,55+,No,Travel_Rarely,1055,Research & Development,1,3,Medical,1,1423,4,Female,76,3,5,Research Director,1,Married,19701,15k+,22456,3,Y,Yes,21,4,3,80,1,32,3,3,9,8,1,5
RM1302,58,55+,No,Non-Travel,350,Sales,2,3,Medical,1,1824,2,Male,52,3,4,Manager,2,Divorced,16291,15k+,22577,4,Y,No,22,4,4,80,1,37,0,2,16,9,14,14
RM1311,58,55+,No,Travel_Frequently,1216,Research & Development,15,4,Life Sciences,1,1837,1,Male,87,3,4,Research Director,3,Married,15787,15k+,21624,2,Y,Yes,14,3,2,80,0,23,3,3,2,2,2,2
RM1375,58,55+,No,Travel_Rarely,605,Sales,21,3,Life Sciences,1,1938,4,Female,72,3,4,Manager,4,Married,17875,15k+,11761,4,Y,Yes,13,3,3,80,1,29,2,2,1,0,0,0
RM007,59,55+,No,Travel_Rarely,1324,Research & Development,3,3,Medical,1,10,3,Female,81,4,1,Laboratory Technician,1,Married,2670,Upto 5k,9964,4,Y,Yes,20,4,1,80,3,12,3,2,1,0,0,
RM064,59,55+,No,Travel_Rarely,1435,Sales,25,3,Life Sciences,1,81,1,Female,99,3,3,Sales Executive,1,Single,7637,5k-10k,2354,7,Y,No,11,3,4,80,0,28,3,2,21,16,7,9
RM071,59,55+,No,Travel_Frequently,1225,Sales,1,1,Life Sciences,1,91,1,Female,57,2,2,Sales Executive,3,Single,5473,5k-10k,24668,7,Y,No,11,3,4,80,0,20,2,2,4,3,1,
RM106,59,55+,No,Non-Travel,1420,Human Resources,2,4,Human Resources,1,140,3,Female,32,2,5,Manager,4,Married,18844,15k+,21922,9,Y,No,21,4,4,80,1,30,3,3,3,2,2,2
RM226,59,55+,No,Travel_Rarely,142,Research & Development,3,3,Life Sciences,1,309,3,Male,70,2,1,Research Scientist,4,Married,2177,Upto 5k,8456,3,Y,No,17,3,1,80,1,7,6,3,1,0,0,0
RM233,59,55+,No,Travel_Rarely,818,Human Resources,6,2,Medical,1,321,2,Male,52,3,1,Human Resources,3,Married,2267,Upto 5k,25657,8,Y,No,17,3,4,80,0,7,2,2,2,2,2,2
RM744,59,55+,No,Travel_Rarely,715,Research & Development,2,3,Life Sciences,1,1032,3,Female,69,2,4,Manufacturing Director,4,Single,13726,10k-15k,21829,3,Y,Yes,13,3,1,80,0,30,4,3,5,3,4,3
RM759,59,55+,No,Travel_Rarely,1089,Sales,1,2,Technical Degree,1,1048,2,Male,66,3,3,Manager,4,Married,11904,10k-15k,11038,3,Y,Yes,14,3,3,80,1,14,1,1,6,4,0,4
RM898,59,55+,No,Travel_Rarely,326,Sales,3,3,Life Sciences,1,1254,3,Female,48,2,2,Sales Executive,4,Single,5171,5k-10k,16490,5,Y,No,17,3,4,80,0,13,2,3,6,1,0,5
RM920,59,55+,No,Travel_Rarely,1429,Research & Development,18,4,Medical,1,1283,4,Male,67,3,3,Manufacturing Director,4,Single,10512,10k-15k,20002,6,Y,No,12,3,4,80,0,25,6,2,9,7,5,4
RM412,60,55+,No,Travel_Rarely,422,Research & Development,7,3,Life Sciences,1,549,1,Female,41,3,5,Manager,1,Married,19566,15k+,3854,5,Y,No,11,3,4,80,0,33,5,1,29,8,11,10
RM428,60,55+,No,Travel_Frequently,1499,Sales,28,3,Marketing,1,573,3,Female,80,2,3,Sales Executive,1,Married,10266,10k-15k,2845,4,Y,No,19,3,4,80,0,22,5,4,18,13,13,11
RM537,60,55+,No,Travel_Rarely,1179,Sales,16,4,Marketing,1,732,1,Male,84,3,2,Sales Executive,1,Single,5405,5k-10k,11924,8,Y,No,14,3,4,80,0,10,1,3,2,2,2,2
RM880,60,55+,No,Travel_Rarely,696,Sales,7,4,Marketing,1,1233,2,Male,52,4,2,Sales Executive,4,Divorced,5220,5k-10k,10893,0,Y,Yes,18,3,2,80,1,12,3,3,11,7,1,9
RM1210,60,55+,No,Travel_Rarely,370,Research & Development,1,4,Medical,1,1697,3,Male,92,1,3,Healthcare Representative,4,Divorced,10883,10k-15k,20467,3,Y,No,20,4,3,80,1,19,2,4,1,0,0,0
oading HR_Analytics (1).csv…]()


 Dashboard Objectives
 
•	Composition of the Workforce: Understand the composition of the workforce by department, education field, business travel frequency, gender, job role, and age group.
•	HR KPIs: Analyze employee count, average salary, average monthly salary, average age, average salary hike, average Job satisfaction score, and gender ratio.
•	Identify trends and patterns in employee data across different parameters like Education, Age group, and Department.
•	Analyze different HR KPIs for different Job roles.
•	Show the impact of Age & Department on Salary.
•	Employee Attrition Analysis: Identify the factors that influence employee turnover and retention, such as salary, age, gender, education, and employee demographics (e.g., age, marital status, work-life balance).
•	Gain insights into areas with high attrition rates to inform targeted retention strategies.
•	Analyze the attrition rate by various parameters including business travel, job satisfaction, marital status, work-life balance, monthly income, and age.
•	Compare the attrition rates in different departments such as Sales, R&D, and HR.

Process

1.	Import and clean data.
2.	Create data model and relationships.
3.	Define key performance indicators and DAX measures.
4.	Design dashboard layout and visualizations.
5.	Add interactivity and functionality to the dashboard.
6.	Draw insights from data.


Dashboard
![Screenshot 2024-10-10 173928](https://github.com/user-attachments/assets/cc4fb696-f592-4e73-b77f-c412dfdbd578)

![Screenshot 2024-10-10 174023](https://github.com/user-attachments/assets/d543da76-7464-4be5-8bec-244f369f9d15)

Project Insights
Key Metrics:
•	Total Employees: 1,233
•	Average Salary: $6.88K
•	Average Age: 38
•	Monthly Salary: $8M
•	Average Salary Hike: 15.23%
•	Average Job Satisfaction: 2.78/4
•	Gender Ratio: 68% male

Key Attrition Metrics:
•	Total Attrition Count: 237 employees
•	Attrition Rate: 16%
•	Average Age: 34
•	Average Salary: $4.83K

Education and Age Distribution:
•	Education: The majority of employees have degrees in Life Sciences (381) and Medical (316). Marketing, Technical Degrees, and HR have lower representation.
•	Age Group: The largest segment (490 employees) is in the 26-35 age range, followed by 36-45 (425 employees). The younger age group (18-25) has the least representation.

Job Role Breakdown:
•	Highest Average Salary: Manufacturing Directors ($17.2K), Research Directors ($15.9K).
•	Highest Job Satisfaction: Research Scientist (2.83/4), Sales Executive (2.8/4).
•	Overtime: Higher in jobs like Sales Representatives (79%) and Laboratory Technicians (33%).

Attrition by Department:
•	Highest Attrition Rate: Sales (21%) and Human Resources (19%)
•	Lowest Attrition Rate: Research & Development (14%)

Job Role Attrition:
•	Sales Representatives have the highest attrition (40%), followed by Sales Executives (17%), and Research Directors (14%).

Factors Influencing Attrition:
•	Job Satisfaction: Attrition decreases as job satisfaction improves. The rate drops from 23% (for satisfaction level 1) to 11% (satisfaction level 4).
•	Gender: Males (17%) have a slightly higher attrition rate than females (15%).
•	Age: The 18-25 group shows the highest attrition rate (67%), followed by 26-35 (50%).
•	Work-Life Balance: Employees with poor work-life balance show higher attrition rates.
•	Income: Attrition increases with lower income and decreases as income grows.

Business Travel Impact: Employees who travel frequently show lower attrition rates (8%) compared to non-traveling employees (20%).


Key Insights and Recommendations:
1.	Attrition in Sales: Sales roles have high attrition rates, which may be due to lower job satisfaction (2.48/4) and higher overtime (79%). Improving work conditions, providing better support, and possibly offering flexible hours or higher compensation may reduce attrition.
2.	Job Satisfaction: A clear correlation exists between higher job satisfaction and lower attrition. Offering more development opportunities and recognizing employee achievements could improve satisfaction, especially in departments like Sales and Laboratory Technicians, where satisfaction is low.
3.	Age and Work-Life Balance: Younger employees (18-25) and those with poor work-life balance are more likely to leave. Offering mentoring programs for younger employees and promoting work-life balance initiatives could help retain talent.
4.	Gender Attrition Disparity: Though male employees exhibit slightly higher attrition, the gap is small. However, HR departments may focus on retaining both genders equally by creating inclusive policies that address unique challenges.
5.	Impact of Education: The attrition rate may vary across different educational backgrounds. Companies could target specific education fields with retention programs, such as offering continuous learning opportunities or career growth for employees in high-attrition departments.

