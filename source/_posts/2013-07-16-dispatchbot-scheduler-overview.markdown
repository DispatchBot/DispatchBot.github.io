---
layout: post
title: "DispatchBot Scheduler Overview"
date: 2013-07-16 20:45
comments: false
categories: Scheduler
---

## Scheduler navigation
The scheduler board is where Dispatchers will spend the majority of their time. This view shows the dispatcher an overview of all the scheduled trips, unscheduled trips and driver schedules.

{% img /images/overview/board_nav.png 'Scheduler board navigation overview' %}

1. *Dispatcher Tab* This is used by dispatchers when they are marking trips as driver on route, picked up delivered, canceled or no show.
2. *Scheduler Tab* Used to see heat map colors on the trip tickets when scheduling trips.
3. *New Trip* Click this button to enter a new trip.
4. *Import Trips* Use this button to import trips from brokers that you have set up.
5. *Print* Use this button to print the every trip that is Scheduled, Driver on Route, Picked Up and Delivered.
6. Vehicle name or number.
7. Contact information for the driver.
8. Name of the first driver for this tour.

## Scheduler queue

{% img /images/overview/board_queue.png 'Scheduler board queue' %}

1. *Current board's date*. Select this to view future or past days.
2. *Trip Search*. Type in the name of a client, city, or address to search trips for this day.
3. *Drop-down Filter*. Use this filter to narrow your search to Any Status, Unscheduled, Scheduled, Driver on Route, Picked Up, Delivered, Canceled or No Showed.
4. *Trip Queue*. This will show you any trip for the current day depending on the filter setting for #3. By default it will show Unscheduled trips.Each Leg of a client’s trip will have its own ticket in the trip queue. In the image above we see two tickets in the box labeled #4.
5. *Client name*. When you hover over the name with the mouse it will tell you the mobility aids this client uses.
6. *Options menu*. Whenever you see this icon you can click it for extra options.
7. *Requested Drop Off or Pick Up Time*. This is the time the client requested that they be picked up.
8. *Origin Address and Destination Address*. These are the requested pick up and drop off addresses.
9. *Status indicator*. This is a quick way to see the status of the ticket. The color will correspond to the status on the schedule board.
10. This will tell you how many trips are visible in the queue.

## Scheduler board

{% img /images/overview/board_schedule.png 'The scheduler board' %}

1. *Scheduled Trip Count*. This tells you how many trips are on the board for the day.
2. *Trip Status Toggles*. These will break down how many trips are in each status. These will also allow you to show or hide all trips in each status. If the box is checked the trips are shown. If it is not checked the trips are hidden.
3. *Tour*. Everything inside this box is a single tour. One vehicle is normally assigned to each tour.
4. *Time axis labels*.
5. *Driver Tour*. The driver’s tour is placed on the tour for the vehicle. You can have more than one driver tour on a vehicle tour.
6. Trip ticked marked as Delivered (Green).
7. Trip ticked marked as Picked Up (Yellow).
8. Trip ticked marked as Driver on Route (Orange).
9. Trip ticked marked as Canceled or No Showed (Grey).
10. Trip ticked marked as Scheduled (Red).
11. *Extended Trip Information Box*. When you hover the mouse over a trip on the scheduler an extended trip information box will appear.

## Trip tooltips

{% img /images/overview/tooltips.png 'Trip tooltip' %}

1. *Scheduled Time on Board*. This is the time you have this trips scheduled on the schedule board.
2. *Requested Pick Up or Drop Off Time*. This is the time the client has requested to be picked up or dropped off.
3. *Account Name*. This is the name of the account that the client is assigned to.
4. *Passenger Name*.
5. *Mobility Aids*. This will show any and all mobility aids this client needs or uses.
6. *Origin Address*. Where the passenger is being picked up.
7. *Destination Address*. Where the passenger is being dropped off.
8. *View Details*. This will open up the details screen for this trip. You would use this screen to get to the parent trip to edit subscriptions.
9. *Edit Trip*. Use this if you need to make a change to this ticket only.
10. *View Route*. This will open a Google map showing the route from the pickup address to the destination address. This map will also show you the mileage and approximate driving time.
11. *Trip Status Indicator*. This is where you will change the ticket from scheduled to driver on route to picked up etc.
12. *Unscheduled*. This will take the trip off your schedule board.
13. *Scheduled*. This is the default status when you place a trip on the schedule board.
14. *Driver on Route*. This will mark the ticket as driver on the way to pick up client.
15. *Picked Up* This will mark the ticket as client picked up and on board the vehicle.
16. *Delivered*. This will mark the ticket as passenger delivered.
17. *Canceled*. This will mark the ticket as canceled.
18. *No Show*. This will mark the ticket as a no show.