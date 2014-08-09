Stock-Caster
============
by Rupak Chakraborty

A diverse and multi-system stock predictor using reinforcement learning

General View of the System Requirements at an Abstract Level:
-------------------------------------------------------------
1. No pre-training of the system is needed, it will be a self-learning,incremental system.
2. It must be able to auto-correct itself, by matching its predictions with the actual outcomes.
3. Here in lies the concept of Reinforcement Learning.
4. Never ending learning, which means that the system should be online 24 x 7, crawl the web, make predictions and auto-correct itself.
5. With time the knowledge base increases as well as the prediction accuracy (a desirable property)
6. The output should be accompanied by a confidence score which denotes how confident the system is about its own prediction.
7. An extended set of features should be incorporated to make the system more affable these include, stock tracking,price monitoring and user specific portfolio analysis. 

Now comes in the diversity part, the whole system will consist of the following modules:
----------------------------------------------------------------------------------------
1. NLP (Natural Language Processing) based Stock prediction module, which will crawl news sites, blogs, financial sites and other relevant sites and make its prediction solely based on the news/ratings about the company/stock
2. Image based Content Retrieval Module : This is something which has often been neglected and I think most systems do not include this feature. This means extracting the context and meaning of a given image. Sounds pretty interesting huh yes it indeed it.  :) :) . Analyse relevant images related to the stocks/company prospects and make predictions solely based on this. This will be the most difficult module to deal with.
3. Social Media Monitoring Module : Monitoring the social media is of utmost importance today, especially when news about a company's prices, stocks go viral immediately over the social networking sites, hence real time monitoring of the social media sites like Twitter, Facebook etc is required. This will need the help of the above two mentioned modules as well.
4.World and Current affairs Monitoring module: The performance of a company alone doesn't influence the stock prices is it, political atmosphere, financial leanings and the general mood of the nation and the world as a whole affect the prices. This will need the help of all the modules stated above. 

Thus as you can we have a nested hierarchy of modules here, only the NLP and image based content retrieval module are independent of the rest as well as each other. 

5. Game Theoretic and Social Network analysis Module : This will be our flagship module, mechanism design and prediction alloying the opposite ends of game theory and social network analysis to make a seasoned and well informed prediction. We look at things called company and stock graphs multi-agent systems in game theoretic perspective.

Finally the independent predictions made by each module will be coalesced into a single module which will make predictions based on individual modules.. Again this will be a tough nut to crack finding the right combination is as much of an art as science. 


Phases:
-------
 Background studies:
    current: Initial Reading
 Modules
    Web Crawler (Text & Images) : Text is completed / Image left
    Stock data (Yahoo, Google Finance)
    Financial Condition (SEC Filings)
    Analyzing Mood (sentiments) of the companies with reading articles of major financial news provider  
 Social Media
    Facebook
        optimized so that we get accurate stock or company related status or tweets
    Twitter
    Financial Social Network
Image Analysis
    on hold
Game Theory: Mechanism Design
    on hold     

Technologies:
------------
Web Crawler : Scrapy, Selenium
ML : SciPy, NumPy, Pandas
NLP: nltk
Sentiment Analysis : Orange Python

Time Line: Basic Model ( Till October End)
------------------------------------------
It should crawl all the articles, stocks and predict it. Then it should be able to correct itself and test accuracy and efficiency.
left : Web API and Interface
  
