# Responsive Portfolio

## Summary
Using Boostrap CSS Framework, a responsive portfolio was designed under the premise that it can be utilized on multiple devices 
whether it be a desktop screen resized or even a mobile device. Taking into account three common window sizes, the webpage was built on responsiveness in regards to the content as well as buttons on the page whether they are hyperlinks or submission forms. Using placeholder images in the "Portfolio" section, it can be looked at as an evolving webpage.
<br>
<br>

## Site Picture
![Site](Assets/Images/screenshot.png)
<br>
<br>

## What Was Done
A deep dive using Bootstrap was necessary in the creation of this reactive portfolio. The navigation bar and the body content was all manipulated using Bootstrap as the main source of style code. One aspect that allowed for the cleaner look on the portfolio page is the use of a combination of grid system in unison with multiple rows of content in one container of content. Semantics were utilized for cleaner code and ease to read and differentiate between important snippets of code. In the effort to keep the code looking cleaner, comments were left at the end of longer code lines while referencing specific lines above for ease in understanding what was being done.
<br>
<br>

## Code Snippet
```html
   <figure class="container">
                  <div class="row">
                    <div class="col mb-4">
                      <img src="https://via.placeholder.com/350"></img>
                    </div>
                    <br>
                    <div class="col">
                      <img src="https://via.placeholder.com/350"></img>
                    </div>
                  </div>
                  <br>
                  <div class="row">
                    <div class="col mb-4">
                      <img src="https://via.placeholder.com/350"></img>
                    </div>
                    <br>
                    <div class="col">
                      <img src="https://via.placeholder.com/350"></img>
                    </div>
                  </div>
                  <br>
                  <div class="row">
                    <div class="col">
                      <img src="https://via.placeholder.com/350"></img>
                    </div>
                  </div>
                </figure>
```
This snippet from portfolio.html showcases Bootstraps utilization of the grid system of multiple rows in a single container. It was a problem area during initial tests of the deployed site as the placeholder images in a row were not spacing correctly when the page was being resized to a smaller small or mobile sized window. To remedy this the 2020 syntax for Bootstrap 4 of mb-4 (margin bottom) was used to give the proper spacing between the images. 
<br>
<br>

## Built With

* [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
* [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)
* [BootStrap](https://getbootstrap.com/)

<br>
<br>

## Deployed Link

[Live Link "Responsive Portfolio"](https://michaelanthonyyy.github.io/responsive-portolio/)

<br>

## Authors

**Michael Medina** 
- [Link to Github](https://github.com/michaelanthonyyy)
- [Link to LinkedIn](https://www.linkedin.com/in/michael-medina-22aa70200?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3B311BosSLTMS4JkhAfkX61A%3D%3D)

<br>
<br>

## License

This project is licensed under the MIT License 