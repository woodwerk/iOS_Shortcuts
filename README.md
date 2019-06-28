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

[Link to Shortcut](https://www.icloud.com/shortcuts/e209c366524d4939a383c4cc7059b75e)

Follow the prompts for loan amount, interest rate (%) and number of payments and the periodic payment amount is computed.

***

## ![icon](https://github.com/woodwerk/iOS_Shortcuts/blob/master/on_my_way_icon.png?raw=true) On My Way

[Link to Shortcut](https://www.icloud.com/shortcuts/d85a89ee5ac74a1bb999dfe87f71d4cc)

Send your friends/family a text with your estimated arrival time. In this shared version of the short cut, the destination and recipient are blank. Fill-in the destination with your home address and add your SO as the recipient to tell them you're on your way home and estimated arrival time.

![shortcut](https://github.com/woodwerk/iOS_Shortcuts/blob/master/on_my_way.jpg?raw=true)

***

## ![icon](https://github.com/woodwerk/iOS_Shortcuts/blob/master/pack_icon.png?raw=true) Packing List (Item Select)
[Link to Shortcut](https://www.icloud.com/shortcuts/2de1363e92af455f9675b0b182015760)

This Shortcut will create a packing list as a new project in [OmniFocus](https://apps.apple.com/us/app/omnifocus-3/id1346190318). The list template are text files contained in a dedicated folder on your iCloud drive as shown in this screenshot. 

![icon](https://github.com/woodwerk/iOS_Shortcuts/blob/master/pack_folder.png?raw=true)

The Shortcut will create project tasks for each selected list and sub-tasks for items in that list. You can select with lists to include. For example, some trips may not required business attire, so de-select the BUSINESS CLOTHES list. Also, individual list items can be deselected. Items with the battery icon appended will appear in a special 'Charge' list reminding you to charge those items before departure. Here is my TECH list:

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

As an example, below is a screen shot for a packing list 'project' where I've only selected the BUSINESS CLOTHES and TECH lists, where I've opted to not pack the MacBookPro.

![example](https://github.com/woodwerk/iOS_Shortcuts/blob/master/pack_example.png?raw=true)

***

## ![icon](https://github.com/woodwerk/iOS_Shortcuts/blob/master/timestamp_icon.png?raw=true) Timestamp to Clipboard
[Link to Shortcut](https://www.icloud.com/shortcuts/2107435b7bd9412ea1b3e14defe5f51b)

A very simple but helpful Shortcut that copies the current date and time to the clipboard. Helpful for timestamping notes and other annotations. The default format is ISO 8601 without the 'T': "yyyymmdd HHMMSS".

***

## ![icon](https://github.com/woodwerk/iOS_Shortcuts/blob/master/tip_calc_icon.png?raw=true) Tip Calculator
[Link to Shortcut](https://www.icloud.com/shortcuts/9e48a5e49cf84659b2172d1a2f2dcec6)

Quickly compute the tip on a meal. Enter tab for the mean and select from several tip percentages. 

![example](https://github.com/woodwerk/iOS_Shortcuts/blob/master/tip_example.jpeg?raw=true)

***

## ![icon](https://github.com/woodwerk/iOS_Shortcuts/blob/master/today_icon.png?raw=true) Today
[Link to Shortcut](https://www.icloud.com/shortcuts/065d04f3e55f4937a79ba4b884d7d510)

Get a summary of:
* Events on your calendar for today and tomorrow, 
* Open reminders, 
* Current conditions your location, 
* Sunset and sunrise today and
* Weather forecast for today and tomorrow 

![example](https://github.com/woodwerk/iOS_Shortcuts/blob/master/today_example.jpeg?raw=true)


***

## ![icon](https://github.com/woodwerk/iOS_Shortcuts/blob/master/vcard_icon.png?raw=true) VCARD QR
[Link to Shortcut](https://www.icloud.com/shortcuts/55588d72613345a6bd23aff4d23e772b)

Easily provide user-controlled contact information to acquaintences, colleagues and friends. This Shortcut displays one of three QR-based v-cards:
* Professional: containing work email, phone and address
* Personal (basic): just phone number and email
* Personal (full): basic plus home address

The comment block at the top of the Shortcut contains the plain-text vcard template for you to modify as needed. 

Select one of the three options 

![example](https://github.com/woodwerk/iOS_Shortcuts/blob/master/vcard_menu.jpeg?raw=true)

and have your acquaintence/friend point their camera at the resulting QR code and then save the contact.

![example](https://github.com/woodwerk/iOS_Shortcuts/blob/master/vcard_example.jpeg?raw=true)


***

## ![icon](https://github.com/woodwerk/iOS_Shortcuts/blob/master/wifi_icon.png?raw=true) Wifi QR
[Link to Shortcut](https://www.icloud.com/shortcuts/a2fb577e25a04a57b106e9d1d024c70c)

Invite friends and guests to your WiFi network without compromising security. You can maintain strong WiFi passwords but your visitors do not have to type lengthy gibberish. You don't even reveal the actual password in human-readable form as the infomation is conveyed via QR code. This Shortcut is configured with work and home (two) options but the menu could be easily expanded to include a guest log-ins and more. Select the appropriate option and have your visitor point their camera at the resulting QR code. The can then join the network.

![example](https://github.com/woodwerk/iOS_Shortcuts/blob/master/wifi_example.jpeg?raw=true)


***
