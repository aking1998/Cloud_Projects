Fake News Detection Using Data Warehouse (AWS Redshift)

Steps to execute the project:

1) Log in to AWS Account with the following credentials-
   Username - aniket.kinage@ucdconnect.ie
   Password - Aniketbhai@20

2) Search for Amazon Redshift in the AWS Management Console and open the service.

3) You can see a redshift cluster named "redshift-cluster-1" created and in the pause state. To resume the 
   cluster, select the cluster and under actions tab you will have an option to resume. After resuming, wait till the 
   cluster comes in Available state.

4) To check the SQL queries for connection between Amazon S3 and Redshift, go to the query editor v2 present at the 
   left side of the screen. Click on the cluster name and it will be connected with the dataset and you will be able to 
   see the query execution.

5) Next we have to connect to AWS Quicksight. Search for Quicksight on the AWS Management Console and open the service. 
   Ensure that the Quicksight and your redshift cluster are present in the same region (EU London). you can change the 
   region under the username tab present at the right corner.

6) Once you are logged in successfully, under the analysis tab on the left hand side, you will see a dashboard named 
   "Fake_News_dashboard". Open the dashboard to see the visuals. 