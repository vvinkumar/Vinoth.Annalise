# Vinoth.Annalise
⦁	How and when would you run these tests?

Navigate to below github repository and download the project.

 After opening the"tagged-image-manager-challenge-main"  project in your IDE ,Look for the VinothTest.py file under "scripts" folder to run the test cases. I have used "requests" library to automate the scripts. Please make sure to have this library added into your interpreter before executing.

Whenever there is a new change in the functionality the below added test scripts can be triggered as part of smoke/sanity testing.

1.  Adding a new Tag addTag(Tagname)
2.  Looking for the exsting tag with Tag name  checkForTag(Tagname)
3.  Listing Tags  listTags()


⦁	What was missed in this implementation?

Upload Image was missed  due to AWS access key and token values .Using below provided values application throws invalid credential error.

export AWS_SECRET_ACCESS_KEY="testing"
export AWS_SECURITY_TOKEN="testing"

⦁	What would you have liked to have added?

Current version of test suite does not included with BDD approach which I would strongly recommend to have it added in order to simplify the test execution and make it understandable even for the people from non programming background in the software ecosystem. Considering the python we have a librarry called "Behave" for BDD.
