CAPP 30370: Final Project README File

Website's Purpose and Goals:
	 I created this website as an effort to showcase the research that I have completed this semester under the direction of Professor James Delaney and with Co-Researcher Joseph Germino. I aimed to make it a site that could be shown at the College of Science Joint Annual Meeting Undergraduate Research Fair that took place on Friday, May 1. The goal was to have individual pages showing our abstract, data collection methods, final logistic regression model, results, references and an about us section. 
	 Our research dealt with creating a regression model with the ability to predict the best pitch to be thrown in certain situations. To do this we used batter and pitcher profiles as well as the count to get a wholistic view of the situation at hand. The data used was from the 2014 Major League Baseball Season. 
	 The website was very successful at attracting people to come and explore our research during the fair, so in that respects this website, and our research was a success.
	 
Locations of document elements
	1. The picture element was used on the picture of my research advisor, James Delaney, on the About Us page. The image stays the same but crops in as the browser gets smaller and zooms out when the browser gets larger. 
	2. I used five break points in my project
		a. 515px
		b. 700px
		c. 1070px
		d. 1240px
		e. 1350px
		Most of the changes done by these break points are just increasing/decreasing the font. However, at the 515 break point the website title on all pages moves from below the header image to overlaying it. At the 700 break point the result matrices on the results tab float into a two colum design instead of the one column layout, the javascript animation on the abstract page becomes visible, and the css animation on the bottom of the model page becomes visible. Additionally the about us page goes into a two column design for the researchhers's bio's and centers the advisor bio. The 1070 break point only deals with text sizing. The 1240 break point puts the about us page into a three column design with each of the researchers bio's taking up a third and the advisor bio taking up the last third. Finally, the 1350px break point makes the javascript animation on the abstract page invisble again.
	3. The three column layout is on the about us page when the browser width is greater than 1240px. The two researchers and the adivisor's bio take up one-third of the screen each making a three column layout. 
	4. The CSS animaition is on the bottom of the model page. When the browser width is greater than 700 a baseball will roll across the bottom of the screen starting from the left, going to the right and then back again. 
	5. Flexbox was used on the main navigation bar of the page in an effort to make every tab equally spaced along the page
	6. A background image was used to fill all of the footer's on the website. It is a  blue photo with some patterns
	7. The javascript animation is located on the abstract page of the website. It depects a pitcher and catcher and when the button is pushed the ball is "thrown" from the pitcher to catcher and a reset button appears which resets the animation if pushed. The animation appears only when the browser is greater than 700 px wide and less than 1350 px wide.
	8. The toggling of an elements visual(css) style happens on the reference page. On the bottom there is a javascript "calculator" to calcuate home run rate, strikeout rate and walk rate. Once the computation is finished, if the computed rate falls within realistic MLB averages the text next to the output box appears green, if it falls outside of realistic MLB averages, the text next to the output turns red.  
	9. The toggling of an elements visible style happens on the reference page. Theere is a depiction of the strike zone on that page with a right handed batter image(on load). When the left handed batter button is pressed the left handed batter photo appears and the right handed batter photo vanishes. When the right handed batter button is pressed, the right handed batter appears and the left handed batter vanishes
	 
