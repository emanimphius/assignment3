# assignment3

link to the assignment details : https://docs.google.com/document/d/1z4Nw_zL3qYxUcz17mWgeuSn7xC3z_bEh8q9UTfHVWNU/edit?usp=sharing

1.I need to simplify my if statement to make it represent something like this:
- I am guessing I have to add a for loop as well.

I think I will need to do something similar to this:
     for(let currentStudentIndex = 0; currentStudentIndex < allStudents.length; currentStudentIndex++)
     {
         //Use this condition and the filters to only display select students
         if((allStudents[currentStudentIndex].currentSemester === num || num === 0)
          && (allStudents[currentStudentIndex].program === studentProgram || studentProgram === 'Any'))
         {
           
            console.log(allStudents[currentStudentIndex]["firstName"] + " " + allStudents[currentStudentIndex]["lastName"] + " " + allStudents[currentStudentIndex]["program"] + " " + allStudents[currentStudentIndex]["currentSemester"]);
             let currentStudentElement = allStudents[currentStudentIndex].createElement();

             resultElement.appendChild(currentStudentElement);
         }


     }


2. On initial loading of the page I need to have all resturants avalable NOT just when the checkbox is clicked and submitted.
