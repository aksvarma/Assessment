********************************************************Road Status Concole App*********************************************************************


Run the Output:
----------------

Please unzip the file RoadStatus.Zip to a folder

Open DeveloperKey.txt and enter the app_id and app_key value after semicolon

Run Powershell or Command prompt and go to unzipped folder (Example: C:\..\RoadStatus\)

Execute Command: RoadStatus.exe <<RoadId>> (example: RoadStatus.exe A2)

Output will follow in next line


Run the Code:
----------------

Please unzip the file RoadStatusCode.Zip to a folder.

Go to unzipped folder and then select RoadStatus folder to find RoadStatus.sln file.

Open the solution and update the developerkey.txt file with app_id and app_key.

Update the application argument for the RoadStatus project to desired road id to debug the code.


Run the Test:
---------------

Test project will load on loading the solution. 

Right click on the test project and run the tests. Please check the output for each test in test explorer


Assumptions:
---------------

TFl Road API does not have any security to accept app_id and app_key. But added them to request based on sample provided in developer document.
We could add the keys to header as well if they change the API security to accept keys from header.

Test was written to test the scenario in the requirement. We could add Unit test by mocking external methods in bigger real time projects.








****************************************************************************************************************************************************
