# assignmen1sem3
Host a static website using awss3 and cloudfront

Sign-in to your aws account, then search for S3 in the search box, click on s3 and click on create bucket as you can see in the images below, input your bucket name, note that your bucket name has to be unique, then leave every other settings as the default, scroll down and click on CREATE bucket.
![web1](https://github.com/Adeexy/Laravel-Project/assets/151438215/66c439f5-e22e-4c81-9adc-c5fe7cf2afb2)

![createbucket1](https://github.com/Adeexy/Laravel-Project/assets/151438215/44cb79e4-b787-4113-8b58-0e9ad76e93e3)

![createbucket2](https://github.com/Adeexy/Laravel-Project/assets/151438215/5aae7487-39d1-46ab-ac39-ad5e11920f4c)

We would now upload objects into our just created bucket, we would click on the bucket and open it, then click on upload, then we click on upload, it will give us option to upload files and upload folder

![bucketupload](https://github.com/Adeexy/Laravel-Project/assets/151438215/bd09ef91-3c79-428e-98bf-9d901bbb9e9e)

![bucketfileuploadsuccess](https://github.com/Adeexy/Laravel-Project/assets/151438215/0e9e5478-b629-463a-b017-079cd6e6fd8d)

We would be moving the content of the file inside of our folder to the bucket root directory, so we would click on the folder, after it is open, we would select all the objects, then click on action and click on move, then it will open a page, then under the destination tab click on browse s3, it will open another page, just click on the name of your bucket, then click on choose destination, it will open another page, scroll down, then click on move, you have now successfully moved all the objects in to the bucket root directory.

![moveobjectstorootdire](https://github.com/Adeexy/Laravel-Project/assets/151438215/c3beed71-abe5-4dd0-bfa5-afbe88bb6d88)

![moveobjectstorootdire5](https://github.com/Adeexy/Laravel-Project/assets/151438215/c571f0a8-9ecc-4d9b-ad5b-2f3b219fbfa1)

Next step is to create our cloudfront, so you will go to your search box and type cloudfront, click on it, then once it is opened click on create distribution.

![createcloudfront](https://github.com/Adeexy/Laravel-Project/assets/151438215/e21b7e40-2905-4572-a5b1-a963d6aafe2a)

![createcloudfront1](https://github.com/Adeexy/Laravel-Project/assets/151438215/1f0c6163-e809-4a87-895a-c77008d729ba)

![createoaccloudfront](https://github.com/Adeexy/Laravel-Project/assets/151438215/5041103d-5c59-4bc4-9590-9df234107d29)

![createcloudfront2](https://github.com/Adeexy/Laravel-Project/assets/151438215/1a209cb6-1555-4998-a434-1b063f791f21)

![cloudfrontcreatedsuccesfully](https://github.com/Adeexy/Laravel-Project/assets/151438215/5b7e48b7-9cc2-482f-b694-6aba6f5a1ae4)
