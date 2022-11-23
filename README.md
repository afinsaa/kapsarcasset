# kapsarcasset
Kapsarc Assesment


1 - First run Python app to scrape the link provided with required filteration and save it in excel file (csv downloaded file of the results), run the following command:

python3 pyscrape.py

it will loop through the saved sheet and read the required data to be inserted to local sqlite database "Exportsdb.db", also it will save it in json file to presented through the Angular app under the directory "dashboardApp"

2 - Enter the directory "dashboardApp":

cd dashboardApp

3 - run npm of the Angular App

npm install

4 - run Angular App

ng serve --open  
