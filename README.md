# Option-Strategies-Payoffs
My Script will provide the user with possible option strategies and their payoffs, based on the user's view of the market aka bullish,bearish or neutral

<b><u>NIFTY OPTIONS ONLY FOR NOW</b></u>

List of strategies and their respective payoffs that I want to add:

Bullish Strategies 

1. Bull Call Spread 2. Bull Put Spread 3. Call Ratio Back Spread 4. Bear Call Ladder 5. Call Butterfly 6. Synthetic Call 7. Straps 
 
Bearish Spreads 

1. Bear Call Spread 2. Bear Put Spread 3. Bull Put Ladder 4. Put Ratio Back spread 5. Strip 6. Synthetic Put 
 
Neutral Strategies 

1. Long & Short Straddles 2. Long & Short Strangles 3. Long & Short Iron Condor 4. Long & Short Butterfly 5. Box 


<b>Status of the code:</b>

Very early stages, I am still trying to figure out how to accept user input, check if the input is correct and if it is pass the input to another function where the calculations will happen.

20-02-2018:

Today I added a way to get user input Target and calculated a Bull Spread by going long in approximate ATM Call and going short in Target Call option. This Spread will give highest returns when the Spot Price of Nifty is equal to or higher than the user's target. Right now my code only returns a Dataframe, Later I will find a way to present the same to the user.
