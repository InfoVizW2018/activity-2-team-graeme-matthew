
<h1>SENG 480D - Activity 2</h1>

<h3>Team Members:</h3>
Graeme Turney, Matthew Hodgson

<h3>Design:</h3>

![alt text](https://i.imgur.com/bDOMhca.jpg)

<p/>
<h3>Design Description</h3>
<p>This design mimics that of a class schedule, in that each of the days of the week are at the top and the time of day is displayed along the left side of the schedule. For each day, the 7 ferries are shown and their locations for a given time period are shown in the corresponding color representing a specific location. For example, a ferry CS is shown that it is in Surrey (Red) from 8:00am to 8:30am. The horizontal black line represents the current time of day.</p> 
<p>The black lines from a ferry's current location to it's destination represent the travel time for that route. The number of berths a port can support is encoded into the design, such that a scheduler may not allow for more than the number of berths available at a port to be occupied at a given time. For example, if Nanaimo only supported up to 3 ferries to be docked at a time, then the scheduler would not allow any changes that would result in 4 ferries in Nanaimo at once.</p>
<p>The following day would have all 7 ferries listed, each with the color coding representing where their final destination was the previous day. Schedulers could input the routes that they would like for the day and any conflicts could be accounted for with relative ease.</p>

<h3>Assumptions:</h3>

<ul>
  <li>Code exists the behind the scenes of the visualization that knows how many berths exist at each location.</li>
  <li>The system has functionality to know the length of time it takes to get to each location from another, and set the length of time of the route accordingly.</li>
  <li>The time it takes for the ferry to move from one location is fixed per route.</li>
</ul>

<h3>What-Why-How:</h3>

<p><b>What</b></p>
<p>The current data is a set of tables. The attributes of the tables are the arrival and departure times from a pair of locations. The tables are itemized by the ferry name.</p>
<p><b>Why</b></p>
<p>Why does this visualization need to exist? So that it can present to the user the time schedules of multiple ferries on multiple routes. Users also wish to query the current schedule, to compare routes to one another.</p>
<p><b>How</b></p>
<p>The data is encoded through an ordered arrangement of different colours to signify a ferry's place in time, and the location it is travelling to and from. This data would be able to be manipulated through drag and drop functionality. It would allow you to adjust the arrangment by selecting a ferry and moving it the correct time. Clicking on it would also allow you to change the start and end location.</p>

<h3>Design Study Methodology:</h3>

<p>Due to the expedited nature of this activity, most of the 9 steps of the design were sped through or even skipped. Most time was spent on the design process after quickly learning about the problem at hand.</p>
<p>If given a larger amount of time to work on this problem, more steps of the process could be performed. Discussions with the users of this system would need to occur in the learning stage, to help alleviate the assumptions made above. From there the process could continue along the defined steps.</p>

<h3>Pitfalls:</h3>

<p>Some of the pitfalls that may occur when designing this visualizations could be as follows:</p>

<p><b>PF-9: No need for change: existing tools are good enough.</b> There is an abundance of scheduling applications that currently exist. It is possible that a scheduling application could be adapted to fit the use case of Seaspan.</p>
