# [Explore-Weather-Trends-Project](https://alfred-kctang.github.io/Explore-Weather-Trends-Project/)

## Table of Contents

* [Introduction](#intro)
* [Exploration](#exploration)
* [Conclusion](#conclusion)
* [Tools Used](#toolsUsed)
* [License](#license)

## Introduction

In this project, I will analyze local and global temperature data and compare the temperature trend of my city, Hong Kong, with the global counterpart.

## Exploration

This data analysis is divided into two main parts: data wrangling and data visualization. In data wrangling, I gathered the data by using SQL queries to extract the data from Udacity's database, and assessed and cleaned the data by using Pandas. In the data visualization, I created line charts by using Matplotlib and calculating the moving averages in 5-year and 10-year windows to make the temperature trends more observable. Given the moving averages calculated from two time period windows, I can choose which one could make the trends more observable in the visualization. Apart from making trends more observable, I tried to plot both the temperature trends in the world and Hong Kong in the same chart in order to make a direct comparison between them, but the visual fails to help me make a comparison given the huge difference between the global and local mean temperatures as well as different initial years of record, so I decided to plot the difference in temperatures in both the globe and Hong Kong.

## Conclusion

On the basis of the data visualization, the following findings are discovered:

(1) the temperatures in both Hong Kong and the globe increase in the overall trend;

(2) the global and local temperatures increase much faster than the expected increasing trend, i.e. the world and Hong Kong are getting hotter than what has been expected from previous data;

(3) Hong Kong is cooler on average compared to the global average, and this is obviously brought by the greater increase in global temperature;

(4) the temperature in Hong Kong has increased steadily overall while the temperature in the globe has increased suddenly since 1970;

(5) the world temperature has increased much faster than Hong Kong temperature, i.e. the globe is getter hotter much faster than Hong Kong.

## Tools Used

- SQL
- Python
- Pandas
- Matplotlib

## License

This repository is covered under the [MIT License](https://choosealicense.com/licenses/mit/).
