# cloud-googleappengine
Web interface to upload files to Google bucket and measure the time taken to upload

##TECHNICAL SPECIFICATIONS
    Platform: MAC OSX Yosemite (32 bit)
    Scripting Language: PHP
    Web Technology: HTML
    Deployed to: Google App Engine

##STEPS TO PERFORM TO TEST THE APPLICATION
    1) Enter the above URL in the browser and click on the registration link.
    2) Enter valid details in the registration page and register.
    3) Navigate to the login page and enter a valid username and password created during
       registration.
    4) Upload a text file, an image file and a CSV file to the Google Bucket and verify the times taken
       to upload.
    5) Repeat the above steps with larger files.
    6) Click on the Show Result button and verify the results.

##RESULTS
    Files of increasing sizes, ranging from small to large were uploaded to the Google Bucket. Performance was measured to       send, retrieve, store and query data on Google. It was concluded that the times for different file sizes are not             symmetric as the database being used here was an SQL database. If the file sizes were all the same, the times would have     been symmetric.
