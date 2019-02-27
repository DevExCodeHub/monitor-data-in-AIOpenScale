# monitor-data-in-AIOpenScale
Notebook to monitor synthetic data for AI OpenScale with German Credit data

## Pre-requisites

* **IBM Cloud account:**  An account must exist to use the platform.
* **Watson Studio service instance:** A service instance must exist to be able to upload jupyter notebook.
* **Watson Machine Learning:** IBM Watson Machine Learning (WML) Service enables you to create, train, and deploy self-learning models using an automated, collaborative workflow.
* **IBM Watson Open Scale:** Watson OpenScale provides your business with visibility, control and the ability to improve AI deployments, helps explain AI outcomes, and scales AI usage with automated neural network design and deployment.

## Steps
### Create an IBM cloud account
If you do not have an IBM Cloud account, create an account [here](ibm.biz/ai-openscale-cloud)

> Note : PLEASE MAKE ALL SERVICES UNDER ONE LOCATION. FOR EXAMPLE: Dallas

### Create Object Storage Service
1. Select Catalog found at the top right of the page.
2. Click on Storage from the menu on the left.
4. Choose **Object Storage** instance

### Create Watson Machine Learning Service
1. Select Catalog found at the top right of the page.
2. Click on Watson from the menu on the left.
4. Choose **Machine Learning** instance

### Create a Watson Studio service instance
If you don't have a **watson Studio** instance, do the following:

1. Select Catalog found at the top right of the page.
2. Click on Watson from the menu on the left, which you can find under Platform services.
3. Select Browse Services under **Watson Services**.
4. Choose **watson Studio** instance
<p align="center"><img width="947" alt="untitled" src="https://user-images.githubusercontent.com/20974667/48708706-50914980-ec14-11e8-8768-23092ab0b330.png"> 
 
* Once the main page of the service appears, click on Get Started. This will redirect your browser to the Watson Studio platform. It might ask to confirm IBM Cloud organization and space information.

### Create a Standard Project in Watson Studio
From the Get Started page, select **Creat a Project**

![](https://user-images.githubusercontent.com/20974667/48708691-4a9b6880-ec14-11e8-8936-64d0ec4f6b8b.png)

Then Choose a **Standard plan**

![](https://user-images.githubusercontent.com/20974667/48708692-4a9b6880-ec14-11e8-88a6-928cc5646f13.png)

* Make sure a cloud storage instance exists, or add a new **IBM Cloud Object Storage** instance by clicking on Add under Select storage service.

![](https://user-images.githubusercontent.com/20974667/48709557-da421680-ec16-11e8-8c07-c90b29db12e2.png)

5. **Add Jupyter Notebook asset**
6. Upload file, then attach this file into it.
7. Make the Enviroment Spark Python 3.5 XS
![](https://user-images.githubusercontent.com/37486654/53483449-9753d280-3a92-11e9-8270-376b55d1ae4f.png)

The notebooke is done by Eric Martens @emartensibm and can be found [here](https://github.com/emartensibm/german-credit)
