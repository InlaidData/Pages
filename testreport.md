<h1>Test Report</h1>

This page will describe how our team went about testing our system.

<h3>Component Testing</h3>

The majority of our testing throughout the semester was conducted through component testing.
When we planned on implementing a new feature into Everblade, we first made a new scene (separate
from the rest of the system) and then added the required GameObjects/Componenets into the new scene until 
that feature worked correctly. 

Specifically, we created a new scene called "Main" and in which we would first
add/or create the required assets (textures, dependent libraries etc...). From here, we would write and/or add
scripts that were required to get the functionality working as intended. The testing for each new feature 
added to this experiemental scene was iterative in nature. 

We would attempt a small peice of the feature (ie.press space bar to see if the sword would actually swing) before 
fixing it if it wasn't working properly. Once the subset of the entire feature was working propery, we would move 
onto the next subset (continuing from the last example, we would then move onto making sure that the hitbox was 
accurate for the sword, and damage was correctly deducted). This exact method was used for every single feature that
was added into everblade, so I will spare you a book writing about every single one (propably around 100 of them).

The tools that we used was just simply the in-engine playtest button. This gave us a really good idea of how the features
would function once the entire game is actually built and ready for deployment. Furthermore, Unity has a built in 
compiler which would give us error messages with line numbers if any of our written scripts didn't compile. This was
very helpful in making sure the code writing went smoothly.

The tests that we chose centered around both our gut (Does this feel like the right amount of damage?...etc.) and the 
user stories that we wrote in the beginning of the semester. For example, one of the userstories was that a combat system 
must be implemented, so, a large portion of our tests centered around can we do damage, are there weapons, can enemies follow you,
etc... This was the same for all of the other tests as well. We beleive that our test choices were good, because they
center around what is required for the end product (user stories) as well as the fact that we are all gamers, and we know
what about feels right in a game.

<h3>System Testing</h3>

As I had described in the previous section, the majority of our testing came from componenet testing. The only overall
system testing that was conducted was at the end when all of the features are grafted together. This testing was specifically
to ensure that all peices fit together seemlessly. For example, once all of the levels have been built, we will walk manually
to each of them and fight the enemies put in them. This will allow us to test all of the implemented features at once, (combat,
walking mechanics, magic, exploration, music, heath, etc...) and also to see if they fit together without any unforseen consequences.
So far, this testing is going well. Also, the testing tools for this were once again just the built-in unity play button.

<h3>Acceptance Testing</h3>

The system testing that we did that validated if features were considered accepted by the user was to see if each feature matched exactly what
was stated in the user story. The user stories were the sole driver in our acceptance testing. As mentioned before,
component testing was the primary type of testing conducted by our group, and it was completely driven by user stories.
Therefore, its easy to see why we are confident that our system, acceptance criteria, and requirements all match.

Here is a list of all requirements, accompanied by completion status, by User Story Title:
<h4>1 RPG Elements</h3> COMPLETED
<h4>1.1 Questing</h3> INCOMPLETE
<h4>1.2Character Customization</h4> COMPLETE
<h4>2 Combat System</h4> COMPLETE
<h4>2.1 Challenging Enemies</h4> COMPLETE
<h4>2.2 Combat Prefrences</h4> COMPLETE
<h4>3 Looting System</h4> COMPLETE
<h4>4 Inventory System</h4> COMPLETE
<h4>4.1 Inventory Hot Bar</h4> COMPLETE
<h4>5 Story Progression</h4> COMPLETE
<h4>5.1 Post Storyline</h4> COMPLETE
<h4>6 Level Design</h4> COMPLETE