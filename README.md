# Spacex-capstone

*NOTE: All notebook files documenting this project can be found under the 'Notebooks' folder.*

*NOTE: Interactive folium maps do not display properly on Github*

This is the final capstone project for the [IBM Data Science and Machine Learning](https://www.coursera.org/professional-certificates/ibm-data-science) course on [Coursera](https://www.coursera.org/). Completion of this project earns me a certificate in machine learning issued by IBM and Coursera. 

Data used and collected in this project can be found here:

* [SpaceX REST API](https://api.spacexdata.com/v4/rockets/)
* [SpaceX Wikipedia page on Falcon 9 launches](https://en.wikipedia.org/wiki/List_of_Falcon_9_and_Falcon_Heavy_launches?utm_medium=Exinfluencer&utm_source=Exinfluencer&utm_content=000026UJ&utm_term=10006555&utm_id=NA-SkillsNetwork-Channel-SkillsNetworkCoursesIBMDS0321ENSkillsNetwork26802033-2022-01-01)

A presentation slideshow in the form of a PDF detailing the entirety of the project can be found in this repository as well. 

In this project we will be using a range of techniques to predict if the first stage of a Falcon 9 rocket will land successfully. SpaceX advertises Falcon 9 rocket launches on its website with a cost of 62 million dollars; other providers cost upward of 165 million dollars each, much of the savings is because SpaceX can reuse the first stage. Therefore if we can determine if the first stage will land, we can determine the cost of a launch. We will need to:

* Collect data (In this case we use the SpaceX API and webscrape further data from the Wikipedia page.)
* Clean, transform, and wrangle the data.
* Use SQL to explore the data in detail.
* Visualize data with pandas and interactive maps.
* Build an interactive dashboard with Plotly to further visualize data.
* Use a range of machine learning classification models to predict the likelyhood of a successful landing.
