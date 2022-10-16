# API-Gateway-to-S3

We have created a cloud formation script. In this cloud formation we have exposed the parametres which will take the s3 bucket name and stack name of the cloud formation.
After uploading the #yaml script to the cloud formation, we have to fill the stack name and the s3 bucket name.
After filling the bucket name, we stack template will be created. after creating the stack template all the resources should be automatically created.

After template creation, a url is generated on the API stages, we can copy it and paste the url in the postman.
Postman is used to process HTTP request for GET, PUT, UPDATE and DELETE. We have insert the endpoints to the URL for the object creation in s3 bucket
In the body of the postman we pasted the json file .
When we send the request, the json object is directly created on the s3 bucket.


