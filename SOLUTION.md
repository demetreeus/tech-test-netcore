### Task 1
* Hooray, my first error was related to `'no such table: AspNetUsers'.` Run the migrations with `dotnet ef database update --project Todo` after installing the restore tool via `dotnet tool restore``
* Got another error related to redirect after login but not sure if it was supposed to be here. Revisiting the homepage showed me as logged in, so adding a note and moving on.
* Pseudo-reporting the quirks in the auth forms (labels are displayed below the input, is this the expected behaviour UX guys ?)

### Task 2
* I assumed enums are treated as integers internally, happy to confirm.

### Task 3


### Task 4
* Seemed too easy to change the label in 2 view files, went with data annotation in the form models. To avoid repeating I also tried to add to the entity, it didn't work at first, decided to move on with other tasks.

### Task 5
* Decided to go with a simple js approach, which saves us server resources. Note to myself to get familiar with the SSR candies though.

### Task 6
* Impressed with the .Any and the fact that I don't need to pass the userId into the closure

