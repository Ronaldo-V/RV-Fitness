## TESTING

### Responsiveness test

### Browser compatibility test

### Bugs test

### Lighthouse test

### Code validation test (HTML)

### Code validation test (CSS)

### User stroies test
| As a website user: | Action | Result |
| I want to press on the logo in the header and be taken to the home page | I pressed on the logo in the header section at the top of the website | I was directed to the home page - Success |
| I want to press home and be taken to the home page | I pressed on the home button at the top of the website | I was taken to the home page of the website |
| I want to press workout info and be taken to the the workout info page | I pressed on workout info at the top of the website | I was taken to the workout info page - Success |



| As a person new to fitness: | Action | Result |
| I want to learn new information about workouts | I press on 'workout info' at the top of the website. I then scroll down through the page reading the information on workouts | I was taken to the 'workout info' page. I was then able to scroll down and easily read the workout information provided - Success |
| I want to learn about food to help me understand what I should be eating | I pressed on 'nutrtion' at the top of the website. I then scrolled down through the page reading the information provided on nutrition | I was taken to the 'nutrition' page. I was then able to scroll down and easily read the nutrition info which helped me understand what I should be eating - Success |




- I want to press nutrition and be taken to the nurtrition page
- I want to press enquire now in the header and be taken to the enquire page
- I want to press the instagram icon and be taken to the businesses instagram account
- I want to press the facebook icon and be taken to the businesses facebook account
- I want to press enquire now in the footer and be taken to the enquire page
- I want to press Eatwell Guide and be redirected to the NHS website referncing this
- I want to press the download or print link in the nutritions page and have a printable/downloadable doc
- I want to press submit in the form and my form be submitted

- I want to trust the information provided by seeing reviews/testimonials about the business

As a person wanting a PT:
- I want to learn about the Personal Trainer and see if they know their stuff and can bring me value if I decide to train with them
- I want to see if I can envision doing private sessions with the trainer by gettin to know them/the business better  
- I need to see testimonials as I need to know how other people have found their training experinces with the PT

As an existing client:  
- I need a place where I can track workouts/food intake to see how much I am progressing  
- I need a support center with others going through the same process as me to help me stay on track when I feel like giving up  

### Features test

| Feature | Expect | Action | Result |
| --- | --- | --- | --- |
| Home Navbar Button | When clicked, the home page will open | Clicked Home on the Navbar | Home page opened when clicked - Success |
| All other nav elements | When I click on 'Workout Info' 'Nutrition' or 'Enquire Now' on the Navbar, the relevant page will open | Clicked 'Workout Info' 'Nutrition' or 'Enquire Now' on the Navbar | The relevant page opened - Success |
| Facebook link | When clicked, I will be redirected to the businesses Facebook account | Clicked Facebook icon in the footer section | Was redirected to the facebook page - Success |
| Instagram link | When clicked, I will be redirected to the businesses Instagram account | Clicked Instagram icon in the footer section | Was redirected to the Instagram page - Success |
| Eatwell Guide link | Press NHS Eatwell Guide and be taken to the NHS website regarding this | Pressed on the NHS Eatwell Guide link | Was taken to the Eatwell Guide section on the NHS website - Success |
| Daily food planner link | Press download or print in nutritiongs page and be taken to the printable doc regarding this | Pressed on the download or print link in the nutritions page above the Eatwell Guide | Was taken to the food planner document - Success |
| Form Submit Button | The form submits when submit button is clicked | Clicked submit button on the form | The form submitted when the submit button was clicked - Success |
| Content responsiveness for various viewports | Text, images and all other related content should shrink when the device screen width gets smaller | I pressed inspect on my website, selected the device toolbar, changed the device to a smaller screen width | Images and text shrink while layout changes slightly. Relevant photo [here](#content-responsiveness) |
| Website responsiveness for various viewports | My website should not be able to scroll horizontally | I pressed inspect on my website, selected the device toolbar, changed the device to a smaller screen width | I see a thin white trim down the right side of the device likely caused by padding. This does not effect the functionality of the website, but it does not look appealing to users. Relevant photo [here](#website-viewport-for-ipad-and-iphone)|
| Nav responsiveness for various viewports | When I shrink my tab or load the website on a different device, The text, images and display will change slightly to suit the device I am on | I pressed inspect on my website, selected the device toolbar, changed the device to ipad, iphone and other devices | For devices 576px screen width+ there was no issues. But for devices 575px screen width or less, the Navbar disappeared. Relevant photo [here](#nav-viewport-for-iphone)|

### Content responsiveness:  
- ![ipad responsiveness view](testing-screenshots/viewport-test-1.png)

### Website viewport for ipad and iphone:  
- ![mobile responsiveness view](testing-screenshots/viewport-test-2.png)

### Nav viewport for iphone:  
- ![nav responsiveness on mobile](testing-screenshots/viewport-test-3.png)

### Testing of HTML:  
- ![index.html no.1](testing-screenshots/index.html-1-validator-test.png)
- ![index.html no.2](testing-screenshots/index.html-2-validator-test.png)
- ![index.html no.3](testing-screenshots/index.html-3-validator-test.png)
- ![workout.html](testing-screenshots/workout.html-1-validator-test.png)
- ![nutrition.html](testing-screenshots/nutrition.html-1-validator-test.png)
- ![enquire.html](testing-screenshots/enquire.html-1-validator-test.png)

### Testing of CSS:  
- ![css test no.1](testing-screenshots/css-validator-test-1.png)
- ![css test no.2](testing-screenshots/css-validator-test-2.png)
- ![css test no.3](testing-screenshots/css-validator-test-3.png)

### Lighthouse testing for performance, accessibility and best practices:
- ![Lighthouse test for the home page on a desktop view](testing-screenshots/lighthouse-desktop-test-home.png)
- ![Lighthouse test for the home page on a mobile view](testing-screenshots/lighthouse-mobile-test-home.png)
- ![Lighthouse test for the workout page on a desktop view](testing-screenshots/lighthouse-desktop-test-workout.png)
- ![Lighthouse test for the workout page on a mobile view](testing-screenshots/lighthouse-mobile-test-workout.png)

## UNFIXED BUGS
- Website Viewport issue where there is a thin white trim down the right side of some devices. It becomes more noticeable the smaller the device gets. Although no content is hidden, this needs to be fixed. Need to 'inspect' my website and find the issue.
- Nav Viewport issue for devices 575px screen width or less. The Navbar disappears and users cannot navigate through the page. Can be fixed with a dropdown menu for smaller devices. This needs to be fixed ASAP. Have not had enough time to resolve the issue. Image shows the issue to be resolved.
![nav dropdown issue](testing-screenshots/nav-dropdown-toggler-issue.png) 