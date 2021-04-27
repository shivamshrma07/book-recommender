# Book Recommender System
This project is an execution of a book recommender system made by using Collaborative Filtering Algorithm and creating a web application for it.<br/>
This project is an official submission for the **Software Engineering Project (CSD-327)** at *Department of Computer Science & Engineering, NIT Hamirpur(H.P).*<br/>
##### Submitted By : 
* Shivam Sharma - 185004
* Vikrant Bhardwaj - 185007
* Chandan Paul - 185042
* Atul Thakur - 185050
### Web Application Link : [Link](https://book-recommender.anvil.app/)
### Google Colaboratory Link : [Click Here](https://colab.research.google.com/drive/1h9trROB9xrIhfS5zmlB-gHJWQRcNX3im?usp=sharing)
### Link at anvil.works to create the copy of web application : [Clone Here](https://anvil.works/build#clone:FXX7AGOTRWYZASHR=PNLGIWXEI4JYNMS2EAZNYOFY)
### Data Set : 
Fetched from http://www2.informatik.uni-freiburg.de/~cziegler/BX/ <br/>
There are three datasets that we have, we pre-processed them to feed to network, all steps are mentioned in the google colaboratory.
### Steps for using the Project :
1. User Interface of web application is : 
![Screenshot (151)](https://user-images.githubusercontent.com/45414198/116284034-3fb46d00-a7aa-11eb-815b-a7a89141624d.png)
2. Enter a valid user id and we can find : 
  * Top 10 Recommended books.
  * Books that user has already reviewed.
3. If user id is not valid, it will show, user id doesn't exist.
### Steps for Cloning this project :
1. Download Data.zip file mentioned, extract all three datasets and addd them to your drive in a folder named as Data.
2. Clone the web application by the above given link and generate uplink key for application from Anvil and use it in google colab where we imported anvil sever library.
3. Run step by step all cells of the google colab for smooth execution of project.
4. All the information related to execution of each cell is provided in google colab.
5. Use "anvil.server.wait_forever()" cell for constantly connecting web application with google colab.
