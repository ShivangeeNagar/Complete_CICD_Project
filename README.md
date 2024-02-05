This is a Complete CICD Devops project where I have successfully deployed SpringBoot Java application,  used Jenkins for to design the continous integration pipeline and argo CD for the CD pipline

Components of my project-

Source Code - GitHub

CI Pipeline - using Jenkins ( via Declarative JenkinsFile )

Pipeline triggers using Webhooks - my git repo

Jenkins is running on my AWS EC2 instance

Simple SpringBoot Java application build using maven

SonarQube - for static code analysis - integrated with jenkins using tokens and credentials

Final Docker Image of the application pushed to the Docker Hub (https://hub.docker.com/repository/docker/shivangeenagar/ultimate-cicd/tags?page=1&ordering=last_updated)

Jenkinsfile has the scripts that updates docker images inside deployment.yml files inside the springBoot manifest repo

Application is deployed via the updated final image on kubernetes cluster using argo CD

Project Structure :

![Screenshot 2024-02-05 at 12 22 52 AM](https://github.com/ShivangeeNagar/Complete_CICD_Project/assets/90488975/c39ed0ad-d4a2-45c1-8137-fe6357e70c78)

Snapshots during different stages of my project : 

<img width="1132" alt="Screenshot 2024-02-04 at 11 13 28 PM" src="https://github.com/ShivangeeNagar/Complete_CICD_Project/assets/90488975/4802c466-9deb-41f4-89e3-f7c0571dfb5e">

<img width="721" alt="Screenshot 2024-02-04 at 11 13 06 PM" src="https://github.com/ShivangeeNagar/Complete_CICD_Project/assets/90488975/0fc04412-9445-44d4-8f45-36e28bf135da">

<img width="751" alt="Screenshot 2024-02-04 at 11 13 00 PM" src="https://github.com/ShivangeeNagar/Complete_CICD_Project/assets/90488975/1ddeb07d-91c6-47cf-88f9-075dd3004076">

<img width="729" alt="Screenshot 2024-02-04 at 11 12 51 PM" src="https://github.com/ShivangeeNagar/Complete_CICD_Project/assets/90488975/780cb454-c717-4b10-918a-eafb0f0bc330">

<img width="1407" alt="Screenshot 2024-02-04 at 11 12 35 PM" src="https://github.com/ShivangeeNagar/Complete_CICD_Project/assets/90488975/708ec0ed-5f11-4f2f-8bdf-367572495018">

<img width="1387" alt="Screenshot 2024-02-04 at 11 12 26 PM" src="https://github.com/ShivangeeNagar/Complete_CICD_Project/assets/90488975/daf08dca-74e5-40d6-825f-2b6b4daf97b6">

<img width="776" alt="Screenshot 2024-02-04 at 11 12 14 PM" src="https://github.com/ShivangeeNagar/Complete_CICD_Project/assets/90488975/48ee6b58-3137-47e5-be47-f0fd4d8d6947">














