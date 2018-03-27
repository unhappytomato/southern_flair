# southern_flair
Southern Flair Website
for Code Louisville Front End Class- Spring 2018

This site is for a friend who did really well on some Gordon Ramsay cooking show and started her own catering business. Though 
this is just a start, we are hoping to actually use the website once there is more information to put on the site and
also, once i learn to make things prettier.

I used custom html, css, and javascript to get it to this stage.


Custom CSS Classes

There are many, but three particular custom classes I used are as follows:

1. .main
   this class focuses on the styling of the main flex container that makes the layout so clean (for me, anyway). it is flex, the 
   direction is set to column, both the justify-content and aligment are set to center, and it has a black background.
   
2. .contact
   this class focuses on the styling of the contact form. it makes it flex, sets the direction to column, is centered,
   and has a width of 500px. to further, i also created specific classes to effect the input and textarea's height, margin, width, 
   border, and padding.
   
3. .magic-button
   this class is geared toward the javascript utilized. it is the styling for the pretty button you click in order for it to work.
   it sets the width at 33%, the height at 40px, the background red, and the text white.


Custom JavaScript Functions

The javascript function I created is:

1. $(".magic-button").click(function() {
        $(".contact").show();
        $(".magic-button").hide();
    });
  
  this function shows an email form when the "Do It!" button near the bottom of the page is clicked. when the button is clicked,
  the email form populates the area and the "Do It!" button hides.
  
  
  This has been awesome! Thanks for the opportunity!

