# MyCryptoDash
Senior Capstone Project.

# Group Members
1. Ashton Hess
2. Chase Morgan
3. Devynne Miller

# Documentation 1

## Team Information:
### Team Name: Web Sockets
### Mission Statement: The Web Sockets strive to provide a customizable cryptocurrency viewer that outputs live data charts to engage and inform it’s users.
## Members:
### Devynne Miller
Devynne is a Senior Computer Science major. She has experience working with websites and data visualization through projects in and out of school. During an internship with Tradebot over the summer she has learned much about the stock market as a whole and gained experience working with data manipulation, creation of data visualizations, and building web applications in Svelte.

### Ashton Hess
Ashton is a senior in Computer Science. Over the past two years, he has held internships at both Cerner and Tradebot. Ashton is experienced in web development, data science, network programming, web server deployment, data charting, and full stack development. Proficient in Python, C++, Java, HTML/CSS, Javascript, and Svelte framework.

### Chase Morgan
Chase is a senior in computer science. Who has experience working in IOS app development. With experience in both front-end using swiftui and back-end development using javascript. Chase also has worked with firebase for user login, authentication and storage. 


### Mentor:
Damian Vu
Damian is a software engineer at Tradebot, a high frequency trading company that utilizes algorithms and applied statistics to inform their trading strategies. He works closely with many aspects of the company’s data visualizations, live data graphs, website, and data collection, as well as many other areas of experience. Both Ashton and Devynne were able to work with Damian over the summer during their internship with Tradebot. Damian is a very knowledgeable programmer and a great teacher who is full of expertise in the area of how programming and stocks intersect. For these reasons, Damian Vu has been chosen as our mentor.

## Introduction: 
The Web Sockets were created with the common passion of stocks and the dream of having a crypto dashboard that was customizable to the symbols each user cares about. When a new user creates an account, they will be able to set their viewing dashboard to the crypto symbols that they wish to monitor. Through the use of live data, the user will be able to experience the ups and downs of the crypto market through real-time graphing of the current trades for the symbols selected. When the user logs back into their account, their symbols will be ready for them, displaying the current live data for their selected symbols. The user will also be able to explore historical data for cryptocurrencies and look at graphs of past trends.

## Problem Definition: 
There is not a widely used, customizable cryptocurrency dashboard that utilizes live data for heavily detailed chart viewing.
## Problem Resolution: 
The Web Sockets will resolve this problem by creating a customizable cryptocurrency viewer that allows the user to pick which symbols they would like to watch on their dashboard and displays live trading data on those symbols, as well as providing graphs and views for historical data.

## Requirements:
### Hardware Requirements: 
Storage space for daily historical data from exchange
Server
Firebase
### Functional Requirements:
Website
Login page for each user with authentication using Firebase
New user creation for first time users
User name at top right of page when logged in
Settings gear next to username which when clicked will lead to choosing of number of graphs, crypto symbols to view, and the timeframe the user wants to view for each symbols is set
Settings should pull up a view with examples of layout for number of graphs the user has to choose from (ex: 1 graph layout, 4 graph layout, etc)
Once number of graphs are picked for layout the user should be able to pick symbols and timeframes of the graph for each symbol that will be displayed on the dashboard
These settings should then be stored to the user state so that each time the user logs in their dashboard will be set to their previous selections
Default dashboard for new users (first time login) with default cryptos set
Persistence of customized crypto symbols and time windows set for each user dashboard
Live data graphing for selected symbols
Easy selection of crypto symbols through settings
Zoom-in view on charts to change “step” between points for more granular view 
iOS App
Login page for each user with authentication using Firebase
New user creation for first time users
User name at top right of page when logged in
Settings gear next to username which when clicked will lead to choosing of number of graphs, crypto symbols to view, and the timeframe the user wants to view for each symbols is set
Default dashboard for new users (first time login) with default cryptos set
Persistence of customized crypto symbols set for each user dashboard
Live data graphing for selected symbols
Easy selection of crypto symbols through settings
List or scroll view of selected crypto symbols with small live data graph
Timestamps for trades on graph 
Coin data in dynamic objects 
Watchlist view over user selected charts with smaller daily charts inside
Historical data views from yearly, monthly, weekly, daily, hourly, live
Detailed view of symbol when clicked on in list/scroll view
Back button from detailed view of symbol to get back to list/scroll view of all selected symbols

### Non-functional Requirements:
The charts should load within a few seconds of the user logging into their dashboard
Live data should be cleaned and sent to the frontend from exchange in a timely manner so there is little lag for live charts
Usability, the platform should be intuitive for the user
Authorization through Firebase should be secure
