# telecom-churn
## Problem statement
seIn the telecom industry, customers are able to choose from multiple service providers and actively switch from one operator to another. In this highly competitive market, the telecommunications industry experiences an average of 15-25% annual churn rate. Given the fact that it costs 5-10 times more to acquire a new customer than to retain an existing one, customer retention has now become even more important than customer acquisition.
For many incumbent operators, retaining high profitable customers is the number one business goal.

To reduce customer churn, telecom companies need to predict which customers are at high risk of churn.

In this project, we analysed customer-level data of a leading telecom firm, build predictive models to identify customers at high risk of churn and identify the main indicators of churn.

You can also access the Live web-app here.
![image](https://user-images.githubusercontent.com/78062656/228442244-9217c656-f4bf-4f9d-91a7-6beece9afaf1.png)

Running the Dockerized App
Ensure you have Docker Installed and Setup in your OS (Windows/Mac/Linux). For detailed Instructions, please refer this.
Navigate to the folder where you have cloned this repository ( where the Dockerfile is present ).
Build the Docker Image (don't forget the dot!! 😄 ):
docker build --tag telecom_churn_app .
Run the docker:
docker run --publish 8000:8080 --detach --name bb telecom_churn_app
This will launch the dockerized app. Navigate to localhost:8000 in your browser to have a look at your application. You can check the status of your all available running dockers by:

docker ps
