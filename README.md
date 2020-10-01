# GradientClock
Gradient Clock is an open source project by Sam Roth, the current production version can be seen at https://gradientclock.com.

This page shows a gradient which acts as a clock without numbers or hands.

Four colors are declared, currently as the variables hourLow, hourHigh, minuteLow, and minuteHigh.

Based on how many seconds in the day have passed, the color on the left side of the gradient is set along an equivalent point in the spectrum between the hourLow and hourHigh color. Then, based on how many seconds in the current hour have passed, the color on the right side of the gradient is set.

Note that the "high" color is actually show halfway through the day or the hour so that there is a smooth transition up to the "high" color and back down to the "low" color each day and each hour, rather than having a hard reset at the top of each day/hour.

Gladient Clock utilizes https://github.com/EastDesire/jscolor as the color picker on the overlay.
