### Task 1
* Hooray, my first error was related to `'no such table: AspNetUsers'.` Run the migrations with `dotnet ef database update --project Todo` after installing the restore tool via `dotnet tool restore``
* Got another error related to redirect after login but not sure if it was supposed to be here. Revisiting the homepage showed me as logged in, so adding a note and moving on.
* Pseudo-reporting the quirks in the auth forms (labels are displayed below the input, is this the expected behaviour UX guys ?)