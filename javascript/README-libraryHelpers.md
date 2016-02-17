# These are suggestions on how to approach each helper function in library.js

## You do not have to write your solutions like this, just suggestions an the approach.


* [] p.formatDate - takes in a string value representing the date and formats it to mm/dd/yyyy

      ```
        p.formatDate = function(date){
          split the date by the dashes
          create a variable and store the value that represents month
          create a variable and store the value that represents day
          reassign the date to the index of the month
          reassign the month to the index of the date
          turn the elements in the array back to a string
          return the string
        };

      ```