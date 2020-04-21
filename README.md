
### Professional Self-Assessment


The e-portfolio assignment was interesting to complete because it gives a good feel of what I feel comfortable completing and new areas for me to explore. I used GitHub for two out of three of these projects and made the METAR project open source for other to explore and riff off of. The biggest data structure and algorithms ones was also the METAR web app but purely because of the information that you receive and how you work with that information. I think the fantasy football will end up being the more complex of the three as time goes on and I continue to improve on the application from the initial database that I started with. I also went outside of my MSSQL/.NET/Web Components safety and will be implement Mongo, Express, Graph QL, and React with that application. There isn’t a ton of security in any of these projects and the only one that will end up with some type of security will be the fantasy football app so that users can login and view their leagues info. 

My first item is my personal portfolio that I will be continuing to develop. It showcases a little bit of my quirkiness with some personal information and coloring. The second item is the METAR web app that receives data from a third source, and you can search on and view live METAR data as the stations report in. This one will be fun later I think because I want to get some designer help on this, and have the website change according to the flight data that you are looking at. The last is the easiest and not as fun to look at which is the Mongo DB. All these projects were deployed to my personal server and spun up as websites to access if possible. 

### Code Review 

{% include video.html %}

### Enhancement One
Work: [Link](https://stevenfowler.dev)

Code: [Link](https://github.com/stevenfowler16/Portfolio)

Narrative:

This article is my personal portfolio that I started making about 5 months ago or so. I wanted a central landing page for my projects, and this is the start of that site.  This article was selected as it was a product that I wanted to finish and one that should start the expansion of my other artifacts display. I selected this one to display a few of the things I do but it is a simple site overall which is something I try and stick with in all my designs, keeping things simple. I finished up the back of the card specifically, the wording on the back, the logos, and the flip button. The card back is a bit of a nuisance and I think will need to be redesigned to make it more accessible. I covered both my objectives which were CS-499-02 and CS-499-04. I also got everything done that I wanted while keeping in mind that I will need to now iterate again and make some pretty big changes on version 2. My focus for my next iterations will be mobile design, accessibility, and simplifying things. 


### Enhancement Two 
Work: [Link](https://metar.stevenfowler.dev)

Code: [Link](https://github.com/stevenfowler16/Metar-webapp)

Narrative:

Enhancement two is a web project that I had to create for a job interview in February. This project shows the recent METAR data from NOAA and you can search based on site. I selected this article because it uses an array to store all the data objects. These data objects are the backing information for all the cards that you see on the page. I went ahead and made the design a lot better, reworked the structure of the page, and got it published to the web. I still would like to do some databinding with this project to help with the efficiency of the project, it currently still wipes everything. I didn’t learn a ton and my biggest challenges so far has been making sure my publish method to my server is clean up which I think I ended up doing. 

### Enhancement Three
Work: 
![Database Image](/images/enhancement3.png)

Narrative: 

This is the database dump for the Fantasy Football league containing a bare minimum to get users and the teams from each season. Each of these data sets from each season were gather from espn’s api using a custom python script and then written into json files. These json files were then imported into mongodb. There currently isn’t a lot that this artifact can show or do but it is the start of a database for a fantasy football data exploration app. I’m working on the connectors with node js now to get an API up and running with graphQL. That may or may not be included in my portfolio. I did everything that I wanted to do so far besides gathering more and more data. I’m not sure how I’m going to make this look pretty or if its possible but my only objectively was to really create everything and get it ready for an application. 

The whole process was fun though. Instead of a SQL database I went with mongo and got that setup from scratch on my server. Then scraping the data and getting that imported was also interesting to me. The hardest part for me now is figuring out how to create the connecting pieces correctly. 
