In this app, we created a Color Toggle Button.
1.) We set up our boilerplate.
2.) We created a type script that connected
the HTML to the JS.
3.) We added in the html, such as the button tag.
4.) We added logic to our JS that consisted of a var button,
a var isPurple, and an .addEventListener
5.) Inside the logic we used an if else statment.
If it is purple, we changed the background white and created
a new var isPurple equal to false.
Else change the background purple and create a new var
isPurple equal to true.
6.) Instead of using WET code, we placed the isPurple at the very end of our function.  
Summary:  This allows for the user to click the button
repeatedly without having to reload the page.  Therefore it is dynamic/interactive.

7.) Made the code DRYer by using the .classList.toggle method.  Had to add a style in the header with the class purple in order for it to work.

We can name our var isColor but as long as we make sure that we keep the color we want consistent with the actual naming convention then it will still be valid.  In this case, we wanted Purple.