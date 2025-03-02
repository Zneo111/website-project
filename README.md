# website-project
*Overview*
The project is a car website that is expandable to fit as many cars as possible and acts as a point if reference for car buyers and those who just want to check out the cars.
 It alows users to make comparisons between the listed models and if more is wished, it could definetly be added without removing the core basics of the website structure.

The website is built using:
**HTML5**, **CSS**, **Bootstrap**

*Installation and setup*
1. Clone this repository into your computer:
`git@github.com:Zneo111/website-project.git`

2. Navigate to the project directory using terminal:
`cd website-project`

3. Open ***cars.html*** in your default browser, make sure to click on **Go Live** on VS Code.

*Features*
 Contains deatailed information on the cars, which includes style,performance and interior.
 *Example*

 ## This is an h2
 <h2>Futuristic and Aerodynamic</h2>
* This is a heading tag (<h2></h2>) with the content inside it being what is to be dispayed on the website when you go live.

## This is a paragraph.

<p>Designed for maximum efficiency and speed, the Nevera’s sleek lines, active aerodynamics, and aggressive stance make it look straight out of the future.</p>
* The paragraph tag <p></p> lets the browser know that the text being written is a paragraph.

These are the basic styles amongst many, that make the website what it is once it runs live in the browser. Without some of these basic tags notheing would appear.

## Bootstrap
* The website uses bootsrap to help in styling of the website.
* One example of this is

<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">

 <nav>
        <ul class="nav nav-pills">
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="../cars.html">Home</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="../about.html">Info</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="../contacts.html">Contacts</a>
            </li>
            <li class="nav-item">
              <a class="nav-link disabled" aria-disabled="true"></a>
            </li>
          </ul>
    </nav>

* The first link (CDN) Content Delivery Network. Tells the html that a bootstrap code is included i the html document.


*Folder Structure*
The File contains different folders:
`Carimages`- where some of the photod ised in this website are stored. Others are from external sites.
`subhtml`- Contains all the subfiles that contain the styling and the html details for each specific car in the website.



