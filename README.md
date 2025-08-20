Step1: Unzip the Folder (Due to security reasons I'm unable to Push the files directly from the IDE )

Step2: Update the Respective Database Configuration Details

Step3: For Authentication(in the Swagger UI) use Username : testtrader  and  Password : P@ssword123
Step4: Run the  below in Terminal post successful solution build 

dotnet ef migrations add AddInitialDBRun

dotnet ef database update

Step5: Use the below to test  LSEStockAPI Testing Solution

dotnet Test
