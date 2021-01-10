# ETL-project

Karen Warburton
My focus on this project was on the different and most popular cheeses from France. I used three sources.

Source 1: Opendatasoft
List of French Cheese
Downloaded .csv file
https://public.opendatasoft.com/explore/dataset/frenchcheese/table/?disjunctive.cheese

Source 2: Eurostat
List of dairy products obtained per country in 2019
Downloaded .csv file
http://appsso.eurostat.ec.europa.eu/nui/show.do?query=BOOKMARK_DS-052400_QID_4D106E05_UID_-3F171EB0&layout=DAIRYPROD,B,X,0;GEO,L,Y,0;TIME,C,Z,0;MILKITEM,L,Z,1;INDICATORS,C,Z,2;&zSelection=DS-052400TIME,2017;DS-052400MILKITEM,PRO;DS-052400INDICATORS,OBS_FLAG;&rankName1=INDICATORS_1_2_-1_2&rankName2=MILKITEM_1_2_-1_2&rankName3=TIME_1_0_0_0&rankName4=DAIRYPROD_1_2_0_0&rankName5=GEO_1_2_0_1&rStp=&cStp=&rDCh=&cDCh=&rDM=true&cDM=true&footnes=false&empty=false&wai=false&time_mode=ROLLING&time_most_recent=true&lang=EN&cfo=%23%23%23%2C%23%23%23.%23%23%23

Created .csv file containing the three most popular milk sources available for cheese making:
I manually inserted three sources of data and then provided a primary key number for each one and named the file milk_source.csv.

I did some clean-up and removal of extraneous information on the downloaded files using Excel, but then realized that a number of columns needed to be deleted or renamed, which I conducted in Jupyter Notebook. Each file was saved for importing into Postgres for a quick query.

I completed a query that indicated the quantities of cheese exported throughout European countries by milk source type.
