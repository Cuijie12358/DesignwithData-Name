# Welcome!
## This is a blog marking down what we have done by step to ge the final show :)

You can use the [editor on GitHub](https://github.com/Cuijie12358/DesignwithData.github.io/edit/master/index.md) to maintain and preview the source code for your website.

Organizers:   
- [Jie Cui](https://github.com/Cuijie12358/)
- [Bramianha Yudana](https://github.com/ianz88)

The website is based on github.io and if you have any suggerstion, you can add issue on the [github link](https://github.com/Cuijie12358/DesignwithData.github.io/edit/master/index.md) or email [me](cuijie12358@outlook.com).

Numbers:
- Bramianha Yudana
- Yixin Liu
- Xinyi Wang
- Xiaoxin Zhang
- Jie Cui


## Timetable.

|What to do|When to do|
|----|----|
|Brainstorming and research|week1-week3|
|Make prototype for the project|week4-week5|
|Build map|week6-week7|
|Build tree |week7-week8|
|Test demo |week8-week9|
|final product for the whole system|week9-week10|

### Week 1 : Friday, 25 Jan 2019 - DI Studio
We decided on three topic as the triangle for the group project:   
![triangle](pictures/triangle.jpg)

Social interaction : especially between performers and audience from different country    
Data exploration : see the insight from past festival data; visualize artists data to choose    
Performance rating : how to know which performance is great .   



### Week 2 : Friday, 1 Feb 2019 - DI Studio
Discussing about possible direction for the project and create out first kanban board. The topic is around visualizing the movement of crowd in the city center area on the festival. We are thinking of showing the location of street performance and the density of the crowds around those areas and projecting the visual information onto 3d map model of the city center.

Possible way to do that:
* Create iot device that can detect wifi activity of the crowds and sending it to server
* Access the data from the server and show it as a projection mapping
* Build 3d model of the city center of edinburgh
* Collect the location data of the street performers
* Build web page to access the visualization data

Here is our to-do list:   
![TODO](pictures/TODOlist.jpg)

### Week 3 : Friday, 8 Feb 2019 - DI Studio
In this week we are thinking of making something to show the experience of a person going to the festival.
We imagine we are going to see the street performances, what things are we going to do:   
![out_door](pictures/Find_questions_in_outdoor_performance.jpg)

During the meeting, we are suggested to think about our audience at first.
![meeting](pictures/Meeting_question.jpg)

We also make a brainstorm to think about different ideas such as: \textbf{emoji_map} and use it as the first prototype:
![emoji_map](pictures/Thoughts_of_emoji_map.jpg)

We use the \textbf{tree} idea later on:   
![tree](pictures/Tree_thought.jpg)

### Week 4 : Friday, 15 Feb 2019 - DI Studio
We focus on the \textbf{tree} idea and discuss about the detail things in the meeting.   
We have the idea of showing all the location of street performers on a map and put in the center of our installation for users to explore. We want to give information about which performers are interesting by showing its popularity through a visual cue.

The initial idea is to make a tree with hanging fruit to indicate the popularity based on the height and color of the fruits. The audience of the installation could see the image of video of the performers and vote for the performance that they like.
![tree_image1](pictures/tree_pic1.jpg)
![tree_image1](pictures/tree_pic2.jpg)

So we would have two part for the  installation:
* Data collection part to get the rating/popularity of the street performers
* Data visualization part by using the tree to show the rating/popularity
![tree_storyboard](pictures/tree_storyboard.jpg)

The detailed equipments haven't been decided:   
![detail_tree](pictures/Tree_details_and_other_thoughts.jpg)


### Week 5 : Sunday, 24 Feb 2019 - DI Studio
We have notived that the techical part of the tree idea could be unrealistic and if the tree is much taller than a person we do will have no space to make installation, so we move to a new \textbf{projection} idea.
![projection](pictures/Thoughts_of_projection.jpg)

### Week 6 : Friday, 1st March 2019
After meeting with our Teacher, Dave, we got some important question to answers:   
* The disconnected experience of the user of the installation from just showing which street performer is popular through videos/ pictures/ map, knowing that the actual street performer are very dynamic in nature.
* Why not consider other type of performance in the festivals.
* Meaningful interaction with the data from the users.

Later our group did some interview and having a pivotal discussion that changes the direction of the project in a big way. Based on the interview, most people just wander around the city if the want to see street performers not based on some review. So we try to find about how people find the shows that they want to see and one of the media of getting the information is by looking at posters.
![poster1](pictures/posters.png)

These posters overload us with huge numbers of information and make it difficult to find the one that might be interesting for each person personal interest. Moreover the number of paper waste and litter that come from these posters.

Some possible reference design regarding to poster (Advertising column and digital display)

![poster2](pictures/poster2.png)

But these solutions don’t have additional information about the rating of the shows. So we are thinking of creating some digital display for the posters that could change based on personal interest and influenced by the rating or popularity of the show.

So the main data that we are going to used in our project are:
- Poster of performance
- Review or description of the show based on respected reviewer
- Popularity of the show based on voting mechanism

The main interaction in the installation (through gesture):
- Browsing for posters based on interest (type of shows)
- Finding more detail about the show
- Vote for the show (like it/ want to see it)

The installation layout design:   
![layout](pictures/projection_installation.png)

The proposed gesture interaction module:
![gesture](pictures/interaction_process.png)
![led](pictures/projection_np.png)

The proposed visual element to differentiate between show categories:   
![building](pictures/building_structure.png)









# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/Cuijie12358/DesignwithData.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
