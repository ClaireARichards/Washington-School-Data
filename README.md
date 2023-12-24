# Washington-School-Data
Compiled data for Washington School Enrollments (Comprehensive Education Data and Research Systems, CEDARS). District county data is cross-walked with American Community Survey data using data from Washington State (https://geo.wa.gov/datasets/k12wa::washington-school-districts/about) to provide detail on ages of the population on the county level. Only primary county for school districts are used. American Community Survey Data is 5 year data (e.g., 2018-2022). 

"CoDis" school district code            
"SchoolCode"  school code     
"district" school district name, lower case 
"school" school name, hopefully standardized so there is only one unique name per school code, lower case
"grade" grade level, numeric 0 for Kindergarten    
"total" number of enrolled students     
"white" number of white students          
"nonwhite" number of nonwhite students        
"female"  female per school district. Don't look at me. The state apparently is still confused about the difference between sex and not gender, folks.
"male" male per school district.        
"genderX" gender x
"lowincome" - identified low income
"nonlowincome" -not identified low income
"ELL" -identified English language learner
"nonELL"  - identified non-English language learner        
"nonmobile"  -identified non mobile    
"mobile"     -identified mobile students      
"section504"   -identified Section 504    
"disability" - identified disability     
"nondisability"   -identified nondisability
"highcap" -identified as highly capable
"nonhighcap" - not identified yet as highly capable
"homeless" - identified as being unhoused
"nonhomeless" -not identified as unhoused
"migrant"      -identified migrant   
"year" - school year (2022 is for year 2022-23)
"closed_indicator" - words closed present in the school name; not consistently applied so varies across years.
"LEAName" - full district name
"ShortName" - district name without the "school district". Retains capital letters.
"county"  - primary county        
"Counties" - all counties for district
"Region" - only available for Washington State
"East_West"- only available for Washington State
"Grade" - grade in character format
"Grades"  - high school versus K-8
"age_detail": <5 years, 5-14, 15-17, 18 to 24, 25 to 34, 45 to 64, and over 65
"time_period": 5 year census data used
"K12_Population": 5-17 years of age
