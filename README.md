	POC-dn6 
//****************/n
poc-dn6 is a solution package which contains a sample API and testing the api requests using the TestContainers.

Folder Structure:

poc-dn6
->docs
->pipeline
->src
	->webapi (Rest api contains uploadfile, upload multiple files, download a file and delete a file)
		->Container
		->Controllers
		->Properties
		->Service
		-appsetting.Development.json
		-appsetting.json
		-Program.cs
		-webapi.csproj
		-webapi.sln
->TestApi (Specflow sample test project for Api testing of 4 api calls, upload, upload files,download,delete from blobs.)
->Tests
	->IntegrationTest
		-AzureBlobStrorageTests.cs (Integration test for Add a file to Blob Storage, Add multiple files to BlobStorage, Delete a file from BlobStorage)
	-test.json (sample test file to upload)
	-Tests.csproj
	-Usings.cs

