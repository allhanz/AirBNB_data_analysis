# AirBNB_data_analysis

## some business topic before analaysing the actual data
  imaging you are a host who will decide to put some houses into the tokyo AirBNB market. i’d better to understand how the market situation. for example, which location, which area, what kind of rom etc will be the popular to the local customers and for Foreign customers. with these kinds of questions, to check is there any answer information included in this tokyo AirBNB dataset via data analysis.
1) how many host or listings(houses) are avaliable in the tokyo airBNB market japan?
2) is there any relationship between price and the datetime?
3) which area have the most review count number and may be the most popular for customers?
4) which area have the most listings(rooms) ?
5) how the price for different room type?
6) how many hosts are available in the AirBNB tokyo market and how many listings(rooms) for each host?

## package used in this project
pandas  \
numpy \
plotly \
datatable \
matlibplot

## dataset used in this project
Tokyo AirBNB data is used for data analysis and it’s also available in the following [link] (http://insideairbnb.com/get-the-data.html).
the screen capture is also attached here. including some listings, calendar and reviews data.
![alt text](/readme_images/dataset_screenshot.png "mess-labels")

## how to build the development env
1) download the dataset and save into the following folder
 ./Airbnb_open_data/01_tokyo
2) execute the ipynb file "data_analysis.ipynb".
3) if just want to check how the project runned, the details also can be checkable in the HTML file "data_analysis.html". 

## some plot gigure for data analysis 
1) how many host or listings(houses) are avaliable in the tokyo airBNB market japan?
![alt text](/readme_images/available_days.png "mess-labels")
2) is there any relationship between price and the datetime?
![alt text](/readme_images/price_per_day.png "mess-labels")
3) which area have the most review count number and may be the most popular for customers?
![alt text](/readme_images/review_per_area.png "mess-labels")
4) which area have the most listings(rooms) ?
![alt text](/readme_images/count_per_area.png "mess-labels")
5) how the price for different room type?
![alt text](/readme_images/average_price_per_room_type.png "mess-labels")
6) how many hosts are available in the AirBNB tokyo market and how many listings(rooms) for each host?
![alt text](/readme_images/host_detailed_info.png "mess-labels")
