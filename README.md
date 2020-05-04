# jfdayplanner
    Index.html:
       
       - lines 25 to 38 is the code that was made for testing before making the jquery.
       - Line 47 creates a variable to call on moment api
       - Line 50 assigns a var for the current time which should display month date day of week year hour minute and second
       - Line 54 appends currentTime to currentDay div
       - the var hours creates an array containing objects to be able to access the military time and the am/pm time
       - Line 69 Loops through hours array
       - Lines 70 to 86 creates a div containing the hour shown in timestring, the text area, and the submit button.
       - Lines 90 to 93 get the text entered by the user from local storage
       - line 114 gets current hour
       - line 115 gets military hour number from 1 - 24
       - Lines 120 to 129 compare current hour with hour of row. if the hour has passed, grey it out. If it is the current hour, red background. If the hour is in the future, make it green