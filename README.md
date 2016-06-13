# Coderbyte-Challenge-Simple-Adding
Have the function SimpleAdding(num) add up all the numbers from 1 to num. For the test cases, the parameter num will be any number from 1 to 1000. 


    function SimpleAdding(num) { 
    var counter = 0;
    // if 1 is less than num, then do whatever is inside for loop, if 2 is less than num, " " etc.
    for(var i = 1; i <= num; i++){
    // add 1 to the counter variable
    // counter which is now 1, will now have to add 2
    // 1 = 1 + 2
      counter += i;
    // 
    }
    return counter;
    }
   
