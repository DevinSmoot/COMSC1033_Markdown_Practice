# Project Name
This is where my project description would go

## Introduction
This is where my problem is stated and what I believe will happen.

## Code
```java
//Project:		Average speed in kilometers
//Date:			2015-09-10
//Author:		Devin Smoot
//Class:		COMSC1033
public class COMSC1033_HW_1_12 {
	public static void main(String[] args) {
		//This program is to show an average speed in kilometers
		//Declare variables
		//Convert miles to kilos
		double milesRan 		= 24;
		double kilometersRan	= milesRan * 1.6 ;
		//Declare times
		double timeInHours		= 1;
		double timeInMin		= 40;
		double timeInSec		= 35;
		//Convert time
		double totalTime		=
				timeInHours		+
				(timeInMin/60)	+
				( (timeInSec/60) / 60);
		//Work the problem
		double averageSpeed = kilometersRan /totalTime;
		//Display results
		System.out.print ("The average speed of a runner in km");
		System.out.print (" who ran " + milesRan + "mi in " +
					timeInHours + "h "+ timeInMin + "m "
					+ timeInSec + "s is " + averageSpeed + "km/h");
	}

}
```

## Console Output
```
The average speed of a runner in km who ran 24.0mi in 1.0h 40.0m 35.0s is 22.906379453189732km/h
```

## Summary
This is where I summarize the problem and discuss my code. Included in the code discussion is any unique problems I encountered and how I resolved those problems.
