# Saccharyn Website

This is the main website for a musician called Saccharyn. It is designed to be accessible and responsive across different devices. The style is simple in order to make it easy for fans and potential music industry professionals to easily find information relating to the musician's live show dates, social media profiles and media content. There is also a form where visitors can add their e-mails to receive the artist's newsletter. 


---


## User Experience (UX)

* User Stories

    + First time visitor goals:

        a. As a first time visitor I want to understand the purpose of the website.

        b. I want to be able to easily navigate the site and its contents.

        c. I want to be able to find links to external social media profiles.

        d. I want to find media content showcasing the artist’s music.

        ---

    + Returning visitor:

        a. As a returning visitor I want to find news on any upcoming releases or shows the artist has lined up.

        b. I want to find functioning links to social media profiles where there may be new posts from the artist.

        ---

    + Frequent visitor:

        a. As a frequent visitor I want to find updates from the artist about new shows or releases.

        b. I want to be able to sign up to a newsletter in order to receive frequent updates from the artist on their upcoming releases and shows.
    
    ---

* Design

    + Colour scheme:
        
        - The colours chosen were picked using the [Eye Dropper](https://eyedropper.org/) extension on Google Chrome to pick out the colours used in the imagery provided for use on the website. A dark gray colour was picked from the background of the main logo image to use for continuity purposes in different sections of the website, providing a seamless quality between images and background. A pink hue and a blue hue offering sufficient contrast between the background grey and any lettering used were also picked from the hero image using the Eye Dropper.

        ---

    + Typography:

        - [Google Fonts](https://fonts.google.com/) was used to source the main fonts used on this website.
        - The Sacramento font was used for the navigation bar writing and section headers as it most closely resembled the handwritten style of the main logo, whilst also being readable.
        - The Josefin Sans font was used for the writing on the rest of the website, in order to make the smaller fonts more readable.
        - Sans Serif was chosen as the fallback font in case either of the above fonts failed to be imported.
        - This [website](https://kevq.uk/whats-in-a-font-researching-website-typography/) was consulted when making choices regarding the typography to the used on the website. 

        ---

    + Imagery:

        - The images chosen were commissioned by the artist for use in social media websites and other marketing materials, including this website. They include a title banner displaying the word "Saccharyn" in a glow neon-pink and a main image of a bust of the artist also in a glow neon-pink with blue and pink background details. Both images have the same very dark grey background colour, which ties the style together. 
        - The title banner was used as a header whereas the bust image was used as a hero image.
        - Imagery is very important as it ties together with all marketing materials relating to the artist, including social media profiles and pages on services such as [Spotify](https://open.spotify.com/artist/7BrG3qmLmDp8B30dzd657d).

    ---

* Wireframes

    + [Desktop Wireframe](assets/images/wireframe1.png)
    + [Tablet Wireframe](assets/images/wireframe2.png)
    + [Mobile Wireframe](assets/images/wireframe3.png)


---


## Features

* Responsive on all device sizes


---


## Technologies Used

* Languages Used
    + [HTML5](https://kevq.uk/whats-in-a-font-researching-website-typography/)
    + [CSS3](https://en.wikipedia.org/wiki/CSS)

    ---

* Frameworks, Libraries and Programs Used
    + [Bootstrap 4.5](https://getbootstrap.com/docs/4.5/getting-started/introduction/)
        - Bootstrap was used to assist with responsiveness and styling of website.

    + [Google Fonts](https://fonts.google.com/)
        - Google Fonts was used to import 'Sacramento' and 'Josefin Sans' fonts into the style.css file which is used throughout the project
    
    + [Font Awesome](https://fontawesome.com/)
        - Font Awesome was used to source the social media icons found on the footer of the website
    
    + [Git](https://git-scm.com/)
        - Git was used for version control by utilizing the Gitpod terminal to commit to Git and Push to GitHub.
    
    + [GitHub](https://github.com/)
        - GitHub was used to store the projects code after being pushed from Git.
    
    + [Balsamiq](https://balsamiq.com/)
        - Balsamiq was used to create the wireframes for the project.

---


## Testing

* Bugs Discovered

    + Navigation logo issue:
        - An image was provided of the word 'Saccharyn' written in neon pink to be used as the logo for the header of the website, however this image did not fit with the style of the header bar, as it was too small for its purpose and increasing its size meant increasing the height of the header, pushing the hero image further down, which affected the overall design of the page.
        - The logo image was resized and moved around, cropped and resized, however the issue persisted. It was also found during this process that the colours used in this logo differed from the colours used in the hero image, which looked inconsistent when generating the colour palette for the website.
        - As a result it was decided that the logo image would be replaced by text styled with CSS using the colour palette from the hero image to be consistent with the pink neon light effect by using a text-shadow function. This also meant a hover pseudo-class could be employed to alter the colour of the text logo when being hovered over, which was not possible with a static image.
        - Overall using text was found to be a more elegant solution for making the website more consistent, whilst also looking better in terms of design, improving user experience.
        - In future a new logo will be commissioned with different parameters to fit the spcifications of the website design, as the original logo provided was designed as a cover image for social media websites such as [Twitter](www.twitter.com), [Instagram](www.instagram.com) and [Facebook](www.facebook.com), and not designed with a website in mind.
        

    

    ---

* W3C Markup Validator

    ---

* Testing User Stories from User Experience (UX) Section

    ---

* Further Testing


---


## Deployment


---


## Credits

* Code

    + Adapted code from the Love Running exercise website for the hero image zoom effect in this website which can be found [here](https://learn.codeinstitute.net/courses/course-v1:CodeInstitute+CSE101+2020_Q2/courseware/be0e510a3aca4bccb6e0bba4cf7cf06b/83c6c94d55f44c79a3646810d80ce7a3/).

    + Used [Bootstrap4](https://getbootstrap.com/docs/4.5/getting-started/introduction/) throughout website for styling purposes, namely the naviation bar, the grid for the live shows content, and also for responsiveness across different devices.

    + Used [this code](https://stackoverflow.com/questions/21983508/strange-underlines-in-font-awesome-css) to fix issue with blue line appearing when hovering over Font Awesome icons on footer.

* Content

    + All content was written by the developer

* Media

    + Hero image was created by [Sara Christova](https://www.sarachristova.com/)

* Acknowledgements

    + My mentor Dick Vlaanderen for his advice and feedback.

    + The tutor support at Code Institute for their assistance.

---