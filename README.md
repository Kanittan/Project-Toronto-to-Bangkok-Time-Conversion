# Project-Toronto-to-Bangkok-Time-Conversion
### Program Description:
Use C Programming Language to create a program that takes in Date and Time in Toronto from User Input and converts to Date and Time in Bangkok. This program takes into account of 2 different timezone: EST and EDT and make the conversion based upon the inputted timezone.

Used Logic, Algorithm, Array, Pointers, string and character-wise manipulation to construct the program.

### Complexity:
- Takes in a Single "String" of Input of format: HH:MM for Time and DD/MM/YYYY for Date
- Performed Character-wise Manipulation from string to acquire individual information
- The Output of Day(DD), Month(MM), and Year(YYYY) in Bangkok may be changed according to the inputted Date and Time in Toronto.
    -  #### Example#1: Shifted Day
    -  INPUT: Toronto's Time is 14:59 (HH:MM) AND Toronto's Date is 30/10/2022 (DD/MM/YYYY)
    -  OUTPUT (In EDT): Bangkok's Time will be 1:59 (HH:MM) AND Toronto's Date is 31/12/2022 (DD/MM/YYYY)

    -  #### Example#2: Shifted Day + Month
    -  INPUT: Toronto's Time is 14:59 (HH:MM) AND Toronto's Date is 31/10/2022 (DD/MM/YYYY)
    -  OUTPUT (In EDT): Bangkok's Time will be 1:59 (HH:MM) AND Toronto's Date is 01/11/2022 (DD/MM/YYYY)


    -  #### Example#3: Shifted Day + Month + Year
    -  INPUT: Toronto's Time is 14:59 (HH:MM) AND Toronto's Date is 31/12/2022 (DD/MM/YYYY)
    -  OUTPUT (In EDT): Bangkok's Time will be 1:59 (HH:MM) AND Toronto's Date is 01/01/2023 (DD/MM/YYYY)

-  Displaying the Result in the SAME Formate of HH:MM for Time AND DD/MM/YYYY for Date

#### To Test Code:
1. Go to: https://www.programiz.com/c-programming/online-compiler/
2. Copy the code and paste it into the above online C Compiler
