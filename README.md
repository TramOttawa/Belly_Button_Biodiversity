# Belly_Button_Biodiversity
JavaScript, Plotly, JSON

## Overview
Roza has a partially completed dashboard that she needs to finish. She has a completed panel for demographic information and now needs to visualize the bacterial data for each volunteer. Specifically, her volunteers should be able to identify the top 10 bacterial species in their belly buttons. That way, if Improbable Beef identifies a species as a candidate to manufacture synthetic beef, Roza's volunteers will be able to identify whether that species is found in their navel.

## Website Dashboad Image

![Screenshot01](https://user-images.githubusercontent.com/100484606/175824954-d44354dc-05c7-4961-b02e-6c3fa264a0f5.JPG)
![Screenshot02](https://user-images.githubusercontent.com/100484606/175824962-a231e34e-5fc9-4274-aa9c-f50a91d63128.JPG)

* Dropdown menu on the left is for selecting the Test Subject ID number.
* Bar Chart display the top 10 bacterial species (OTUs) when an individual's ID is selcted. X-axis = ID, Y-axis = sample values
* Bubble Chart display the following when individual's ID is selcted:
    - The otu_ids as the x-axis values
    - The sample_values as the y-axis values
    - The sample_values as the marker size
    - The otu_ids as the marker colors
    - The otu_labels as the hover-text values
* Gauge Chart displays the weekly washing frequency value, 0-19 on the progress round arch
