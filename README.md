#### Notebooks for the workshop at : "Build, Train, and Deploy Machine Learning for the Enterprise with Amazon SageMaker"



### Setup instructions

* Login to the AWS Console: https://console.aws.amazon.com.
* Select the US West (Oregon) region in the top right corner.
* Add the promotional code to your account
    * Open the Credits page of the Billing and Cost Management console: https://console.aws.amazon.com/billing/home?#/credits
    * "Promo Code" box: type the promotional code.
    * "Please type the characters as shown above" box: type the code.
    * Click on "Redeem".
* Move to the SageMaker console: https://us-west-2.console.aws.amazon.com/sagemaker/home?region=us-west-2#/dashboard
* Go to "Notebook / Notebook instances".
* Click on "Create notebook instance".
    * "Notebook instance name": type a name for your instance, e.g "ent321".
    * "Notebook instance type": select _ml.t3.xlarge_. No need for anything bigger :)
    * "IAM role": select "Create a new role"
         * Select "Any S3 bucket".
         * Click on "Create role".
* In the "Git repositories" section:
    * Select "Clone a public Git repository" from the dropdown list.
    * In the "Git repository" box, enter: https://gitlab.com/juliensimon/ent321
* Leave all other boxes as is and click on "Create notebook instance". A few minutes later, the instance is listed as "In Service".
* Click on "Open Jupyter".
* Click on the "ENT321.ipynb" notebook and get to work :)

