# Code-Refactor-assign1

# Purpose 
The purpose of this project was to take a website that had been previously created and to clean up the code while preserving the desired layout and design of the page. 

# Process
* I first gave the website a proper title, using the company's name as it serves a concise descriptive title.
* I then provided all of the images with a proper alt attributes that effectively describe the image while also helping with ESO
* Going to the CSS file, I reorganized the structure of the document so that it followed a cascading/top-down model
* From there I removed the div tags that were used to create a <header> and <footer>, instead using the proper header and footer tags
* In the header I also removed the div tags that were being used to form a list, instead using <nav> as it would be semantically correct
* Once again, I removed the div tags being used to form two seperate portions of the website, instead using <main> and <aside>. From there I removed all of the div tags from the <main> body, using the <section> tag to create individual bodies of text 
    * As there were a total of six different groups within the <main> and <aside> bodies, each was previously using its own css class even though they were all formatted the same. In order to clean up the html and css, I got rid of the classes for each section, instead using the elements <section> and <aside> to direct how the css file should format. As the classes for floating left and right were useful in being kept seperate I didn't remove those (Note: I kept the ID tags as those allowed the hyperlinks to function). 

