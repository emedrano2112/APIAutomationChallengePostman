# APIAutomationChallengePostman

Following challenge was used with some help from the Postman documentation.

The approach for the testing procedure used was Functional Testing (Acceptance Testing).
- Given that I ran out of time I did not implement any negative test cases or edge cases.

To make this work, make sure to import the .json file/collection.
- It includes the environment variables needed.
- Added an environment variable "host" for the host/environment tested, to simuilate multuple environments being considered.
- Added an environment variable "GeorgeID", which was the ID extracted from the first user from a previous call (first index of the array) and set it as an environment variable from the same test, to be used on the second one.
- Requests names are self explanatory.
