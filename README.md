# TDL_Jmeter

In this repository there are non functional tests using Jmeter including spike, stress and load tests. These have been written to cover the API 
I put together for my Todo List project where there is CRUD functionaility on two entities: Task & Task Items. 
I have tested this CRUD functionality

You will find: 

- Jmx files for the specified tests
- The html test reports generated from the CLI: Running a test: (used for load tests) (append the location to store results to write to a csv file created by the append) jmeter -n -t your_script.jmx -l "location to store results" -e -o "output folder"
- Images of the tests conducted

Each Test is segregated using logic (simple) controllers for readability and good practice. I used assertions for JSON to ensure correct data is returned, and response assertions for tests where no actual data would be returned e.g. delete.
