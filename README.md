This is an interactive Mapped Profile Info of Philippine Presidential Candidates and Presidents. 
The dataset used is from Abe Caesar Perez of Kaggle.com <https://www.kaggle.com/datasets/abeperez/ph-presidential-elections>

I have only extracted Presidential Candidates with complete information. I have not included 42 candidates from the dataset because of essential missing information such as city, province and others. 
I have also added two additional columns for the dataset, lat and lng to map city locations. 

I have used dplyr to clean the dataset and used leaflet and htmltools packages in creating this interactive map. I have created this project to aid History students in their lessons and History teachers to have a more interactive tool in teaching History to their students. This can be useful as the Philippine Midterm Elections is upcoming this May 2025.

I have chosen to use the OpenStreetMap.Mapnik as against any other tile providers because of its simpler design that allows faster loading. 
Anyone can use the code and make changes as long as this original repository is referenced. 

The interactive mapped profile info can be found here: <https://rpubs.com/rnx2024/philippine-presidential-candidates-and-presidents-mapped-profiles>

Edits Have been made to the code:
Changes were made to the code to handle some lat and lng locations for some Presidents and Candidates, like Manila. 
All 17 Presidents are now displayed with green markers, 3 of which are located in Manila. 


