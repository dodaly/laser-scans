# laser-scans
takes data from a robots laser scan and converts it into significant landmarks
i remember having a specific bug with this project where not nearly enough landmarks were appearing, and corners were not appearing at all
It turned out that there was a mistake in one of the methods that was completely throwing off all of the calculations down the line,
so even though i thought the error was in processing corners/lines it was actually just that one number that was off (really frustrating)
