# iOS Shortcuts
A collection of Shortcuts I routinely use. Note that to make use of the links to add a Shortcut to your own library you need to open that link on an iOS device.

## Availability 
[link to Shortcut](https://www.icloud.com/shortcuts/bb2a6f83ebeb4bd1b73ef11a7991aeff)

Choose a starting date and number of days to consider and this Shortcut will assemble a list of available times in your calendar. That is, it will create a list of the times not already occupied by events or meetings. It ignores all-day events and gets only events on my personal or work calendars. Also, there is the option to add travel time around events that have a designated location. The output is provided three ways:

1. Quickview display
2. Added to a new Draft (Drafts app: [Mac version](https://apps.apple.com/us/app/drafts/id1435957248?mt=12), [iOS version](https://apps.apple.com/us/app/drafts/id1236254471))
3. Copied to the clipboard

### Example
Below is a screenshot of an example calendar with a few test events for demonstrating the Shortcut. The red items are on my personal calendar and the blue items are work meetings. 

![calendar](https://github.com/woodwerk/iOS_Shortcuts/blob/master/availability_calendar.jpg?raw=true)

In the Shortcut, I selected the July 2nd as the starting date with 3 days to check. I also adjust the travel time from the default of 30 min to 15 min. Set travel time to zero (or leave empty) to not invoke this feature. 

The resulting availability summary is:

```
My available times are...

Tue, 02 Jul 2019
Start of day - 9:45 AM
11:15 AM - 1:00 PM
2:00 PM - End of day

Wed, 03 Jul 2019
Start of day - 8:30 AM
10:00 AM - 11:45 AM
1:15 PM - End of day

Thu, 04 Jul 2019
I am free all day
```

Note that the all-day and family event were ignored. Also, the events with location (7/2 @ 10 and 7/3 @ noon) have 15 min added on either side for travel - but not the event with a phone number in the location field.
