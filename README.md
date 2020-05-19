# Code-Refactor-assign1

# Purpose 
The purpose of this project was to take a website that had been previously created and to clean up the code while preserving the desired layout and design of the page. I built this project so as to me able to apply the knowledge gained over the last week and take a website that was poorly constructed and turn it into one that I could be proud of. 

# Problem
This project when originally started was riddled with semantic issues, was lacking in alt tags, and had a disorganized css file. My goal was to take this mess and transform it into a project that not only made sense semantically, but also optimized eso and was easy for an incoming developer to follow.

# Process
* I first gave the website a proper title, using the company's name as it serves a concise descriptive title.
* I then provided all of the images with a proper alt attributes that effectively describe the image while also helping with ESO
* Going to the CSS file, I reorganized the structure of the document so that it followed a cascading/top-down model
* From there I removed the div tags that were used to create a <header> and <footer>, instead using the proper header and footer tags
* In the header I also removed the div tags that were being used to form a list, instead using <nav> as it would be semantically correct
* Once again, I removed the div tags being used to form two seperate portions of the website, instead using <main> and <aside>. From there I removed all of the div tags from the <main> body, using the <section> tag to create individual bodies of text 
    * As there were a total of six different groups within the <main> and <aside> bodies, each was previously using its own css class even though they were all formatted the same. In order to clean up the html and css, I got rid of the classes for each section, instead using the elements <section> and <aside> to direct how the css file should format. As the classes for floating left and right were useful in being kept seperate I didn't remove those (Note: I kept the ID tags as those allowed the hyperlinks to function). 


# Issues I Encountered 
* One of the biggest mistakes I made was accidently leaving extra "<>" within the code, which would then find its way onto the project. I had trouble finding them and removing them from the html until I remembered that Google Dev Tools can quickly allow me to find where something on the page is located within the code. 

* Another issue that I ran into was that I originally tried to place my banner's jpeg within the html, which resulted in the banner not being able to properly adjust when the webpage was adjusted. I needed to ask the tutor how to place an alt text on a banner that is situated within css. 

* I also removed the id tags within the main body as I could not find the corresponding id tags within the css, which lead me to believe that they were useless. Turns out they were what was directing the hyperlinks within the nav bar, and I did not even notice the issue until I met up with my group.

# What I Learned 
The most important lesson that I took away from this was that there is no one-way of handeling coding. There is definitely incorrect things you can do, such as using <nav> tags for everything instead of proper tags such as <header> and <footer>. That being said, when meeting with my group we went over the homework and it was fascinating to see all the different ways we went about solving this issue. I also learned that I HAVE to check over my work for tiny breaks or glitches, such as when I deleted the ID tags that attached to the hyperlinks. If my group hadn't caught that I would have turned in a faulty project

