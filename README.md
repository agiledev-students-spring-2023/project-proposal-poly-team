
### PLEASE NOTE I ORIGINALLY SUBMITTED THIS BEFORE the deadline, however, I later found out that I placed the info in a pre-existing team in which I did not inted to be a member of. the place where I originally submitted this file can be found here: https://github.com/agiledev-students-spring-2023/project-proposal-poly-team/.  NOTE I HAVE ALREADY DELETED MY WORK FROM THAT TEAM REP.

Assignment #01 - Project Proposal
Due Date: 01-30-23

# MakeIt.hm (Make It Home)

## Proposer(s): 
David Acevedo, daa467

#
### What and why?

What software system would you like to build this semester, and why? Include a description of what problem the system would solve and why this is important. product's value proposition.

I would like to create a web application which shows users a time table of when a bus and/or train departs from a station/terminal. This application would then allow the user to determine what is the absolute latest said user can depart from either their current or defined location and still make it to that bus/train. This software would be useful for those take a bus or train which does not run with high frequency and don't want to spend a lenghty period of time stuck inside (or even outside in the cold!) a terminal or for those trying to find at what time the last bus/train departs and subsequently the abst.

Currently, transit apps like Google Maps, NJ Transit, MYmta, etc. only tell you when a bus/train leaves and/or determine your route based on your desired time of departure or arrival. Furthermore, in all of these apps, especially, the case of the NJ Transit app the way departures are shown are somewhat unorganzied. 
For a good amount of commuters, they usually tend to have more than one bus route or train line that can take them to their destination. However, how departures are shown by either plastering the user with a list of ALL the bus routes / train lines departing from the station OR it just shows the departure times for ONE route/line. Moreover, the current apps in the market often  don't show the complete timetable for said route and instead only output the live view of when the next buses/trains are departing. In the cases where the applications due show a complete time-table, it is often hidden behind inconspicous menus and even then it only shows the time-tables for one specific route/line. 

My app would allow the user to filter the list of departures to the routes/lines which they need and from there, the app would show a combined timetable of the routes selected. Additionally, the app could also show important alerts for a line or route, such as if said a line/route has been suspended or if a scheduled departure has been cancelled. This would aler the user to current transit issues, to which they can then adapt to.


### For whom?

As a commuter student, I've ocassionally had to stay on campus late into the night working. During these late night stays in the city, I would often worry about when the last possible bus would leave the station, and if I would even make it in time. The way the current apps are designed is that there is no way to see a combined time-table for multiple lines/routes so I would often have to download, open, and analyze a multitude of different time-tables to figure when the last bus leaves. Additionally, even after finding this information, I then have to go into Google Maps or CityMapper, input my destination (the station/terminal) and the time I want to arrive there by (when the last bus is scheduled to leave) in order to get info as to what is the latest I can stay in the city.

Thus, this software is designed for the majority of commuters -- like myself -- who already know what line/route they need to take home and who occasionally, or often times need to stay in the City (or wherever they are) late into the night or for those who rely on a line/route which does not run with high frequency. This app would allow these users to worry less if they are going to make their bus and also help them save time from having to spend time at a station/terminal -- This is especially useful for those who utilize a station that is outside.

### How?

From an end-user's perspective, when they enter the website they will be presented with either a input box or with a list wherein they can specify what station they are looking for. Once the user has provided a valid input, the app would then ask the user to specify the routes/lines they'd like to be shown (it can be all routes, multiple routes, or one route). After that, the app would show a combined timetable for those routes/lines. As an option, the user can specify a time window they are looking for via a slider.
Within the shown time-table,the user can then select the departure time that best suits them and ask the app to determine what would be the best time to depart from their current or a specified location in order to make it to the station. In this step, the user can also specify how close do they want to arrive at the station by. So if the bus/train leaves at 11:55pm, the user can specify the app to determine a route that will get them to the station by 11:43pm. This will be done via a drop down menu wherein the user can select 0 minutes( with a warning label), 2 minutes, 5 minutes, etc. By default it would be set at 5 minutes. This route calculation would be done by using some sort of routes/map API, like that provided by Google, Microsoft, or CityMapper.

One other possible feature that could be implemented is that when the time-table is shown, the app could show on the far right side the time at which they will reach their final/ultimate stop (the stop at which the user gets off at). This can be determined by also analyzing the injested time-tables from the transit operators.

IF time permits, we could also implement several other features that would also be extremely useful to users.
One such feature could be to cache a user's previously generated time-table. Another useful feature that could also be implemented if we feel our progress is faster than expected would be to show the timetables for multiple different stations/terminals, from which the user can toggle on/off. This is useful as often-times, commuters in addition to having more than one route they can take from a single station, they can also (if need be) take a route/line from a different station. In my case, and that of others, I have the ability to take several busses from either Port Authority or GWB Bus Terminal.

### Scope

I think since most of us don't have any actual  prior app development skills, this could easily take a couple months. For one, we would have to build an intuitive application from the ground up that adapts to all of the user's input to show any relevant information. This in itself would require us to learn how to build a dynamic webpage. Additionally, because we would need to intake information from the transit providers and from Google/Microsoft/CityMapper (for route selection), we would also need to learn how to utilize API's and how to organize the info we get from it. As the development cycle progresses, if we feel that we are outpacing our expected road map, we could implement the optional features I spoke about in my last paragraph of  the "How?" section.
