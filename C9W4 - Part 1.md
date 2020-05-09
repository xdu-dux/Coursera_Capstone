# Peer-graded Assignment: Capstone Project - The Battle of Neighborhoods (Week 1)

## Project Title *
## Central business district comparison between Frankfurt and London

Clearly define a problem or an idea of your choice, where you would need to leverage the Foursquare location data to solve or 
execute. Remember that data science problems always target an audience and are meant to help a group of stakeholders solve a 
problem, so make sure that you explicitly describe your audience and why they would care about your problem.

This submission will eventually become your __Introduction/Business Problem__ section in your final report. So I recommend that 
you push the report (having your Introduction/Business Problem section only for now) to your Github repository and submit a 
link to it.

### Part 1. Introduction/Business Problem

#### How different between Frankfurt and London in Central business district?

Before start the introduction, I'd like to explain some background of my topic. The UK stopped being a member of the European Union (EU) at 23:00 GMT on 31 January 2020. It's called also __Brexit__ - British exit - refers to the UK leaving the EU. The UK will leave the single market and customs union at the end of the transition. The capital city London, which is today one of the main financial centres of the United Kingdom and even the EU, contains many of corporations and agencies, which are also their european headquarter. Due to Brexit maybe they want to relocate to EU and transfer some staffs and departments for the business within EU. 

Definition: a __central business district__ designates an area in the city centre where many banks, insurance companies, and other financial institutions are located. In London, __City of London__ (a city and local government district) and __Canary Wharf__ are the primary and secondary CBD. In Frankfurt is the __Bankenviertel__ (_meaning: banking quarter_)

My purpose is to make a quantitative analysis about consumption habits between different CBDs. The opportunity is with venues which scattered in CBD area. An obvious problem is, nether we could describe strict borders of a CBD nor give an official coordinate. For example Bankenviertel is commonly defined as the western part of the Innenstadt, the southern part of the Westend and the eastern part of the Bahnhofsviertel. 

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/9f/Bankenviertel_%28Banking_District%29_in_Frankfurt.png/330px-Bankenviertel_%28Banking_District%29_in_Frankfurt.png" alt="The commonly defined Bankenviertel" width="40%">

[_Red area is the commonly defined Bankenviertel_]

Fortunately we find out, that skyscraper is a significant label of CBD. We can search the tallest buildings' list in the two cities. With adress we calculate the coordinates. after that with the coordinates we can get the venues around them in a planed  radius. So the analysis is appear to realize. 

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/f/ff/Frankfurt_Skyline_Pano.S%C3%BCdwest.20130618.jpg/1200px-Frankfurt_Skyline_Pano.S%C3%BCdwest.20130618.jpg" width="75%">

[_Panorama view of Bankenviertel from the southeast_]

My analysis will discover the daily consumption habits of businessman between Frankfurt and London. There are some oversupply with location service. All nearby around venues will be provided. First of all we extract, clean and filter data set in order to be more suitable for requirements. For example let the report be more tageted, we analyze deeply in six main sections. 

1. Catering Services:
    - Food court/Restaurant
    - Bakery 
    - Bar/Pub 
    - Bistro/Lounge
    - Cafe 
    - etc.
2. Free time:
    - Art gallery
    - Shop/Store 
    - Museum
    - Theater/Opera house/Music venue
    - Nightclub/Club 
    - etc.
3. Sport:
    - Aquarium
    - Stadium/Arena
    - Gym 
    - Fitness studio 
    - etc.
4. Medical care:
    - Health Service 
    - Hospital 
    - Pharmacy 
    - Medical center 
    - etc.
5. Lodging:
    - Hostel 
    - Hotel 
    - Motel 
    - etc.
6. Public Service:
    - Court 
    - Post office 
    - Train station 
    - Metro station 
    - Bus 
    - etc.

Now we will compare the data set between Frankfurt and London. Let's see how different beween them. 

<ins>Thank you for reading</ins>

