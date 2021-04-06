# Round 3 /  100 Days Of Code - Log
For this Round I decided to start my own log instead of forking the 100 day of code repository. The reason is I didn't really need to get updates to the master which happens when you have forked a repository.
I wanted to use this repo to track my progress my registering my work as a commit.



**Link to work:**
1. [Link](https://simonramsay.net)

### Day 143 2021 April 6, Tuesday

**Today's Progress**

*Vue.js - simonramsay.net to prepare for new version*
1. Fixed the layout shift, first by adding wrappers to all the sections but worked out it was the mode out-in on the transition.

**Thoughts:**
* Nice to working on this again. 

**Link to work:**
1. [Simon Ramsay](https://simonramsay.net)

### Day 142 2021 April 5, Monday

**Today's Progress**

*niseko snow template fixes*
1. Finish up the gradient, fix size on mobile as it was set at 428px and gradient wasn't showing unless set to 40% width.
2. Fix minor centering issues for ads. by introducing flex to the codebase. 

**Link to work:**
1. [Niseko Snow Weather](https://nisekosnow.net/)

### Day 141 2021 April 4, Sunday

**Today's Progress**

*Weather Feed on niseko snow homepage*
1. Add gradient to weather module, was a little trouble-some. 

**Thoughts:**
* After trying to bend main template I added the gradient overlay to the iframe source. Working with old float templates and multiple media queires is not worth it. 

**Todo**
* Admin/ inputs for mobile
* Ad Sense new animated ads on mobile are positioned down and under the header. 

**Link to work:**
1. [Niseko Snow Weather](https://nisekosnow.net/)

### Day 140 2021 April 3, Saturday

**Today's Progress**

*Weather Feed on niseko snow homepage*
1. Copy page and refactor for iframe
2. tweak mobile layout for the whole site and review layout
3. Add new iframe to site, adjust size, test 

**Thoughts:**
* Need to look at refactoring the code to use OO design.
* Mobile iframe vertical height is different from the desktop

**Link to work:**
1. [Niseko Snow Weather](https://nisekosnow.net/)

### Day 139 2021 April 2, Friday

**Today's Progress**

*Weather Feed on niseko snow table head Day/ Date Month*
1. Code colspan value equation with static values, test. 
2. Work on 0 -1 -2 values and next day, code out b

**Thoughts:**
* 

**Link to work:**
1. [Niseko Snow Weather](https://nisekosnow.net/niseko-weather-snowfall)

### Day 138 2021 April 1, Thursday

**Today's Progress**

*React Project*
1. Fire up old React project just for giggles, bit of git branch checkouts, bit of JSX. 

*Vue.js Shop App / Testing for UI design*
1. Added some values to the previous order array as per prototype drawings.
2. Add the App meta for homescreen and status bar style in header.

*Weather Feed on niseko snow*
1. Comment code and review and write Psuedocode for the table head Day/ Date Month, work out colspan value equation.

**Thoughts:**
* 1 day of small tasks across a few projects is good to finish up stuff or plan bigger tasks.

**Link to work:**


### Day 137 2021 March 31, Wednesday

**Today's Progress**

*Reveal Hide JavaScript Image Viewer*
1. Tidy up a few minor things.
   * Mobile usage message. 
   * @media 4 queries for hover refactored, made hover box-shadow wider since hover and touch are cancelling each other.
2. Strip out comments and format for Codepen
3. Add to Codepen and fix a few small display problems, like leaving out * { box-sizing rule which effected mobile display }

**Thoughts:**
* Good to put this to rest, but now want to refactor with different set up for Touch due to touch and hover conflict.

**Link to work:**

1. [Hide Reveal Image Display ](https://codepen.io/simonramsay/full/mdROdEo)

### Day 136 2021 March 30, Tuesday

**Today's Progress**

*Weather Feed on niseko snow*
1. Write (Pseudo) code to hide the table columns for previous timeframes. Only leave one old timeframe.
2. Test code and push to all rows. Add CSS to hide columns and then remove until next step is worked out.
3. Pseudo code to fix table day/date header, e.g. Mon 29 Mar need to be hidden if before 9 and also colspan needs to be adjusted.
4. Write and test code for day/date header and prep. Pseudocode in dev note book.

**Thoughts:**
* Edge case where fetch at 9:00AM fails will cause this solution to fail. Maybe write a test/ function to record this event. 
* The display as such won't fail as data is cached, the switch statement will just reset to the previous day. 

**Link to work:**

1.

**Today's Progress**

*Weather Feed on niseko snow*
1. Write (Pseudo) code to hide the table columns for previous timeframes. Only leave one old timeframe.
2. Test code and push to all rows. Add CSS to hide columns and then remove until next step is worked out.
3. Pseudo code to fix table day/date header, e.g. Mon 29 Mar need to be hidden if before 9 and also colspan needs to be adjusted.
4. Write and test code for day/date header and prep. Pseudocode in dev note book.  

**Thoughts:**
* Edge case where fetch ar 9:00AM fails will case this solution to fail. Maybe write a test/ function to record this event.

**Link to work:**

1.

### Day 135 2021 March 29, Monday

**Today's Progress**

*Weather Feed on niseko snow*
1. Continue Pseudocode to check current time and then calculate the $currentTimeModifier
2. Write if statement for current time and made modifier. 
3. Convert to Switch statement
4. Work out if a next day calculation is needed for times after 00 JST / since each period is 24hours date doesn't matter*

**Thoughts:**
* Edge case where fetch ar 9:00AM fails will case this solution to fail. 
* Need to now write some Pseudo code to remove or hide the table columns for previous timeframes. Only leave one old timeframe. 

**Link to work:**

1.

### Day 134 2021 March 28, Sunday

**Today's Progress**

*Weather Feed on niseko snow*
1. Add CSS to Grey Out, image filter, color, and opacity
2. Continue Tidy up code, spacing etc. Add code from 2 on all rows on the table.
2. Make fixed integer a variable. $currentTimeModifier.
3. Start Pseudocode to check current time and then calculate the $currentTimeModifier

**Thoughts:**

**Link to work:**

1.

### Day 133 2021 March 27, Saturday

**Today's Progress**

*Weather Feed on niseko snow*
1. Finish Pseudo code for how to make some quick temporary display fixes.
2. Code: Make it so that a class is added to "Grey Out" timeframes passed with a fixed integer. 
3. Tidy up code, spacing etc.

**Thoughts:**

**Link to work:**

1.

### Day 131 2021 March 26, Friday

**Today's Progress**

*Weather Feed on niseko snow*
1. Reviewed and comment Weather code setup
2. Adjusted and tested code for output. i.e the code does work, but the input (fetched API data) has changed at some stage so tested it.
3. Started on Pseudo code for how to make some quick temporary display fixes.  

**Thoughts:**

**Link to work:**

1.

### Day 130 2021 March 25, Thursday

**Today's Progress**

*New Branch for Code Pen*
1. Look at Level Four Media queries
2. Make "hacky" temporary double tap solution for mobile 

**Thoughts:**

**Link to work:**

1.

### Day 129 2021 March 24, Wednesday

**Today's Progress**

1. New Branch for Code Pen and strip out all un-needed code
2. Add mobile tap message and test

**Thoughts:**  

**Link to work:**

1.

### Day 128 2021 March 23, Tuesday

**Today's Progress**

1. Prepare Upload Hide and Show Testing on Safari with develop and web inspector Cleaning up Touch code.
2. Working between desktop and Laptop with Mega Sync testing, this worked and allows for only using Laptop as the git remote repo to commit changes.
3. Testing the Touch hover pseudo class, need to maybe go with the solution as is and then clone to a new repo.  

**Thoughts:** Good to have a project like this, you just keeping on "hitting walls" which needs research, CSS level 4 Media queries for detecting hover interesting.

**Link to work:**

1.

### Day 127 2021 March 22, Monday

**Today's Progress**

1. Prepare Upload Hide and Show trying to work on how to get touchmove to work / testing on Safari with develop and web
   inspector

**Thoughts:** Touch is way more complex than meet the eye. Why does the function keep running multiple times between
each touch console.log

**Link to work:**

1.

### Day 126 2021 March 21, Sunday

**Today's Progress**

1. Prepare Upload Hide and Show continue/ touch swipe. working with touchmove touchstart / trying to work on how to get
   touchmove to work stopping mobile context menus

**Thoughts:**

**Link to work:**

1.

### Day 125 2021 March 20, Saturday

**Today's Progress**

1. Prepare Upload Hide and Show continue/ touch swipe. refactor the functions

**Thoughts:**

**Link to work:**

1. local

### Day 124 2021 March 19, Friday

**Today's Progress**

1. Prepare Upload Hide and Show / touch swipe. refactor the functions

**Thoughts:**

**Link to work:**

1. local

### Day 123 2021 March 18, Thursday

**Today's Progress**

1. 3D Perspective examples Added +translateZ to illustrate disappearing elements Gradients for clouds

**Thoughts:**

**Link to work:**

1. local

### Day 122 2021 March 17, Wednesday

**Today's Progress**

Couple of smaller things today

1. Layer SVG graphs test - works but unsure of how performant is would be.
2. Vue.js Transitions - Add a second transition to route, the transition doesn't work on the header logo. Need to think
   about this for when you want the header to animate on the header.
3. Looked at Drupal module development and Symfony CLI, just research

**Thoughts:**

**Link to work:**

1.

### Day 121 2021 March 16, Tuesday

**Today's Progress**

1. shape-outside:
2. text gradient with background-clip & -text-fill

**Thoughts:**

**Link to work:**

1. css-shape-outside

### Day 120 2021 March 15, Monday

**Today's Progress**

1. Tidy up the JS 3D tool / Refined UI sizing labeling for Mobile
2. Add -webkit-appearance: none on buttons for Mobile

**Thoughts:**

**Link to work:**

1. 3d-cube-js-global-variable-Git

### Day 119 2021 March 14, Sunday

**Today's Progress**:

1. Tidy up the JS 3D tool

### Day 118 2021 March 13, Saturday

**Today's Progress**:

1. Tidy up the JS 3D tool

**Thoughts:**

**Link to work:**

1. 3d-cube-js-global-variable-Git

### Day 117 2021 March 12, Friday

**Today's Progress**:

1. Basic Positioning code samples made for site. All code written from memory.
2. Review the Basic boilerplate while do the above.

**Thoughts:** Whilst today was based around fundamentals it is good to do this. In particular flexbox used for code
samples still.

**Link to work:**

1.

### Day 116 2021 March 11, Thursday

**Today's Progress**:

1. 3D Cube / basic / created 3 cubes for A Deeper Look
2. 3D Cube / Double Face & Cube / Worked on classes so they are more re-usable.

**Thoughts:** The height and position height maybe need to be created for each individual element. The limitation of CSS

**Link to work:**

1.

### Day 115 2021 March 10, Wednesday

**Today's Progress**:

1. 3D Cube / Double Face & Cube / Crosshair, bring it to front

**Thoughts:**

**Link to work:**

1.

### Day 114 2021 March 9, Tuesday

**Today's Progress**:

1. Git / set up SSH keys on laptop
2. 3D Cube / Double Face / set up 3 cubes, one cube, one square with variable height, one with variable height and depth

**Thoughts:** Want to work on class name to relate to type of cube, and then have setting based on a controlling unique
class.

**Link to work:**

1.

### Day 113 2021 March 8, Monday

**Today's Progress**:

1. 3D Cube / Double Face / Continue Working on depth and transform-origin / work on the algorithm for height & depth /
   refactor

**Thoughts:** Still go some transform right and left, could work it for consistency all left or all right

**Link to work:**

1.

### Day 112 2021 March 7, Sunday

**Today's Progress**:

1. 3D Cube / Double Face / Working out depth and transform
2. Git Init this Log /

**Thoughts:** Transform Order is so important for work in CSS

**Link to work:**

1.

### Day 111 2021 March 6, Saturday

**Today's Progress**:

1. 3D Cube / Double Face / Tidy up class name
2. 3D Cube / Double Face / Start on Working out depth and transform
3. Prepare this Log for Git & Init

**Thoughts:**

**Link to work:**

1. [100 Days of Code R3](https://github.com/siramsay/100-days-of-code-R3)

### Day 110 2021 March 5, Friday

**Today's Progress**:

1. Set up 3D Cube for Part 2 / Double Face / new set up not needing translateZ - rectangular cube worked out algorithm
2. Set up 3D Cube for Part 2 / 3d-cube/3d-cube-steps.html / set up -var

**Thoughts:**

**Link to work:**

1.

### Day 109 2021 March 4, Thursday

**Today's Progress**:

1. Set up 3D Cube for Part 2 / New cube set up not needing translateZ

**Thoughts:**

**Link to work:**

1.

### Day 108 2021 March 3, Wednesday

**Today's Progress**:

1. Set up 3D Cube for Part 2 / 3d-cube/3d-cube-steps.html

**Thoughts:**

**Link to work:**

1.

### Day 107 2021 March 2, Tuesday

**Today's Progress**:

1. Axios post with basic
2. JS resize on Image show for mobile width to desktop handle
3. Mobile detect width in px to mouse point position to stop overflow of handle

**Thoughts:**

**Link to work:**

1.

### Day 106 2021 March 1, Monday

**Today's Progress**:

1. Vue.js / Frontend Masters course work. 

**Thoughts:**

**Link to work:**

1.

### Day 105 2021 February 28, Sunday

**Today's Progress**:

*Some final tweak*
1. Stop the handle being able to go more that 100% width of screen
2. Add a hover cursor

**Thoughts:**

**Link to work:**

1.

### Day 104 2021 February 27, Saturday

**Today's Progress**:

1. Image Reveal with handle / rearrange layers so that image is in a div so it can be responsive.

**Thoughts:**

**Link to work:**

1.

### Day 103 2021 February 26, Friday

**Today's Progress**:

1. Image Reveal with handle / Git branch responsive.

**Thoughts:**

**Link to work:**

1.

### Day 102 2021 February 25, Thursday

**Today's Progress**:

1. Image Reveal with handle / window mouse up detection added

**Thoughts:**

**Link to work:**

1.

### Day 101 2021 February 24, Wednesday

**Today's Progress**:

1. Image Reveal with handle

**Thoughts:**

**Link to work:**

1.
