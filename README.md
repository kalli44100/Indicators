# Indicators
Throughout my many years of trading, I have developed quite a few indicators on various platforms using their custom programming environments. It always started with a problem: "How can I better visualise this?" closely followed by: "Why has no-one done this before?" I therefore had no choice but to dive in and learn the new language (Although I would be lying if I said I didn't enjoy it:)

## Pinescript
This is one language I did not actually enjoy. Pinescript was built to be intuitive for the mostly retail level TradingView crowd. It had also undergone a few upgrades to its core language and therefore I found it anything but intuitive and when searching for examples online, you would more often than not, get obsolete Syntax. Using AI to help me with Pinescript also wasn't great and so I found myself reluctantly learning Pinescript and building what I needed. I have to add, that I initially avoided migrating to Sierra Charts because a) SierraCharts' Customer Service is somewhat elitist (They are the best and they know it... They may well be but the attitude doesn't help I'd say), b) They never do promos or discounts and c) because of the learning curve. TradingView on the other hand was up and coming, they had huge promos and a free version to hook you in. TV looked nice and promised an easy learning curve. Why I am not one to shy away from learning (I could happily study all my life!) I just did not have the time and so I went for the easy and convenient alternative i.e. TradingView. Taking the easy route has generally been a bad choice as opposed to following my intuition but it still happens sometimes unfortunately. So I ended up spending more on platform fees because I needed a higher tier to create custom charts (pairs trading) and the effort and pain it took to get along with pinescript most likely outweighed any strain I would have felt, learning Sierra (especially since Sierra Script is C++, the same AS SuperCollider which I heavily coded in during my Bachelours and Masters Degrees). In addition to being annoying, pinescript also had many limitations (on top of TradingViews many limitations: no Tick charts and no auto trading). Back then you could not import data from an external source. This has since changed to five data imports per day (probably on some premium subscription) and I'm not sure what the current status quo is. One main limitation was (and quite possibly still is) that you could only import data in string format and that each string was limited to some four thousand elements, which sounds like a lot but isn't a lot at all. I had these daily spreadsheets of darkpool, phantom- and block trades that I wanted to visualise on my TV charts because all of the providers simply used the TV widget which gave the worst possible resolution and very limited interactivity. I needed a much more granular approach but was stuck with the limit. The workaround? create a python script to clean and sort the code, create three final text files with pre-written Pinescript indicator code and insert the data into each file, broken up into blocks string arrays to keep below the limits, then convert the comma separated numbers out of the strings into floating point numbers and aggregrate them into a new array. I did all these things manually in Excel prior to having that python app and it would often crash OpenOffice halfway through the cleaning process. Here is a picture of the final indicator showing Darkpool, Phantom- and Blocktrades in different colours using the width of the chart as the total range for the percentage adjusted values (Creating the range from the largest value in each category).
--inser screenshot of indicator
-> Flow indicator with waves, what was it called?
-> broken highs and lows
-> TickGap
-> check TV for what other indicators i made

### NinjaScript
-> replicate broke highs and lows indicator
-> tickgap
### MQL4 and 5
risk management
-> output to excel logging
-> trade entry helper
-> what else? do i still have access?
-> MT4 vs MT5, had to learn both

