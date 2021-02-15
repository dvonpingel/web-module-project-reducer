# Understanding Questions:
1. What are the steps of execution from the pressing of the 1 button to the rendering of our updated value? List what part of the code excutes for each step.
* The user presses the 1 button.
* Onclick event is triggered.
* The dispatch calls the addOne function into the reducer
* The addOne function returns the ADD_ONE variable as a case.
* case ADD_ONE is returned with the total being adjusted up by 1
* state is updated
* TotalDisplay shows the total plus 1.
