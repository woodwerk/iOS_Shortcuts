# iOS Shortcuts
A collection of Shortcuts I routinely use. Note that to add a Shortcut to your own library you need to open the link (below the its title) on an iOS device.

## ![icon](https://github.com/woodwerk/iOS_Shortcuts/blob/master/availability_icon.png?raw=true) Availability 
[Link to Shortcut](https://www.icloud.com/shortcuts/16e5d93aba074dfe93f894b7bd3aa76f)

Choose a starting date and number of days to consider and this Shortcut will assemble a list of available times in your calendar. That is, it will create a list of the times not already occupied by events or meetings. It ignores all-day events and gets only events on my personal or work calendars. Also, there is the option to add travel time around events that have a designated location. The output is provided three ways:

1. Quickview display
2. Added to a new Draft (Drafts app: [Mac version](https://apps.apple.com/us/app/drafts/id1435957248?mt=12), [iOS version](https://apps.apple.com/us/app/drafts/id1236254471))
3. Copied to the clipboard

#### Example
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

***

## ![icon](https://github.com/woodwerk/iOS_Shortcuts/blob/master/current_loc_icon.png?raw=true) Current Lat/Long

[Link to Shortcut](https://www.icloud.com/shortcuts/f2b18528f8ca4e73968fd3d7a246d890)

Captures your current location and saves to your clipboard. It's helpful for geo-tagging notes, recording positions of events, etc

***

## ![icon](https://github.com/woodwerk/iOS_Shortcuts/blob/master/flight_notice_icon.png?raw=true) Flight Notice

[Link to Shortcut](https://www.icloud.com/shortcuts/b81d4a5145ff4a368bc531703b7a72dd)

If you have airline flights in your calendar formatted with the event title consisting of airline code followed by colon and then flight numbers (e.g., **SWA: 555**), this Shortcut will allow to to select your current flight, construct a FlightAware URL and text it to your family and friends. You can preload usual recipients to streamline the process even more.

#### Example
Select from today's events, one of which is a two-leg flight in the expected format.

![event](https://github.com/woodwerk/iOS_Shortcuts/blob/master/flight_notice_example_1.png?raw=true)

Choose the appropriate flight

![flight](https://github.com/woodwerk/iOS_Shortcuts/blob/master/flight_notice_example_2.png?raw=true)

The Shortcut formats the FlightAware URL and preloads a text message. The receipting gets and information-rich text message containing all flight information and can tap the message to get up-to-date info about the flight, arrival time and such.

![text_msg](https://github.com/woodwerk/iOS_Shortcuts/blob/master/flight_notice_example_3.png?raw=true)

***

## ![icon](https://github.com/woodwerk/iOS_Shortcuts/blob/master/loan_icon.png?raw=true) Loan Calculator

[link to Shortcut](https://www.icloud.com/shortcuts/e209c366524d4939a383c4cc7059b75e)

Follow the prompts for loan amount, interest rate (%) and number of payments and the periodic payment amount is computed.

***

## ![icon](https://github.com/woodwerk/iOS_Shortcuts/blob/master/on_my_way_icon.png?raw=true) On My Way

[Link to Shortcut](https://www.icloud.com/shortcuts/d85a89ee5ac74a1bb999dfe87f71d4cc)

Send your friends/family a text with your estimated arrival time. In this shared version of the short cut, the destination and recipient are blank. Fill-in the destination with your home address and add your SO as the recipient to tell them you're on your way home and estimated arrival time.

![shortcut](https://github.com/woodwerk/iOS_Shortcuts/blob/master/on_my_way.jpg?raw=true)

***
## ![icon](https://github.com/woodwerk/iOS_Shortcuts/blob/master/on_my_way_icon.png?raw=true) Packing List (Item Select)
[Link to Shortcut](https://www.icloud.com/shortcuts/2de1363e92af455f9675b0b182015760)

This short cut will create a packing list as a new project in OmniFocus. The list template are text files contained in a dedicated folder on your iCloud drive. The shortcut will create project tasks for each selected list and sub-tasks for items in that list. Items with the battery icon appended will appear in a special 'Charge' list reminding you to charge those items before departure. Here is my TECH list:

```
iPad 🔋
MacBookPro 🔋
Bose QC35 🔋
Battery back-up 🔋
Laptop charger
4-port USB charger
Lightning cables
micro-USB cable
Lightning-HDMI adapter
Hot-spot
```

As an example, below is a screen shot for a packing list 'project' where I've only selected the BUSINESS CLOTHES and TECH lists. 

***

## Timestamp to Clipboard
***

## Tip Calculator
***

## Today
***

## VCARD QR
***

## Wifi QR Share
***
