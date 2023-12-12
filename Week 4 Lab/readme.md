For week 4 lab, I was asked to debug a web app that was provided.  The web app only calculated the tip amount that the user had to pay for their meal. It did not calculate the total. The web app also had various syntax errors as well as logic errors. 
Here are the errors I encountered when debugging the web app.
In site.css within the css folder: 
Line 13: Syntax error, required width instead of “width”.

In TipCalcualtor.cs within the models folder:
Line 8: Changed range value from 0.00 to 0.01 so user cannot input 0.
Ine 15: Error calculation, changed / to * to receive correct calculation.

In HomeControllers.cs within the controllers folder:
Line 15: Return method was missing.

I did have a slight issue in HomeControllers.cs line 14, I kept receiving error "The name 'ViewBag' does not exist in the current context" I retyped the line and somehow fixed the issue that I had. Unless I corrected the syntax subconsciously.

