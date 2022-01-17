In this notebook I try and scrape the wikipedia for movies by a particular production company.
The code is written such that just by changing the link to different production company 
movie list wikipedia page we willbe able to scrape those also.

![image](https://user-images.githubusercontent.com/37789394/149747952-e0845281-e3f7-461f-9add-9542b828e220.png)

Once the movie list is scrapped we save it into an excel file.
While scrapping this list we store the links to the wikipedia page of the movies and then scrape 
the information about the movies into a json file.

![image](https://user-images.githubusercontent.com/37789394/149748043-b782dbe1-e358-4af1-b8ca-4be80c3d2de9.png)

The file movielist_WB_1.xlsx is the excel file generated after running the notebook and the json for the first movie in it is The_Book_of_Eli.json
If we remove the _**break**_ statement from the _**downloadJsonFile**_ function then it should generate a json file for every movie in the list.
