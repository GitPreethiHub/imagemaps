# Places Around Me
## AIM:
To develop a website to display details about the places around my house.

## Design Steps:

### Step 1:
     Develop an image from google maps to create image map.
     Use online image map maker to create an image map for desired places
     Mention the the links for clickable places.
     Get the final code and design a webserver to display imagemap.
        clone the repository
        modify index.html under static/html.
        create django project.
        modify the settings.py
        Git add andpush the code to your repository.
     Run the server. 

## Code:
    <!DOCTYPE html>
     <html lang="en">
     <head>
        <title>My Area</title>
     </head>
     <body>
     <h1 align="center">
      <font color="red"><b>Saveetha Engineering College</b></font>
     </h1>
      <h3 align="center">
            <font colour="blue"><b>Preethi M(220000914)</b></font>
     </h3>
     <center>  
     <img src="imagemap.png" usemap="#image-map">

     <map name="image-map">
     <area target="_blank" alt="Saveetha Women's Hostel" title="Saveetha Women's Hostel" href="https://goo.gl/maps/fCg7q3YXJki9ckcW9" coords="1418,533,1627,633" shape="rect">
     <area target="_blank" alt="Saveetha Cricket Club" title="Saveetha Cricket Club" href="https://goo.gl/maps/z5JEYb8tDXXtgGmb8" coords="63,279,213,352" shape="rect">
     <area target="_blank" alt="Amaravati Guest House" title="Amaravati Guest House" href="https://goo.gl/maps/ZGL5MAHKbThFUwt8A" coords="1215,636,1426,746" shape="rect">
     <area target="_blank" alt="Saveetha Water Park" title="Saveetha Water Park" href="https://goo.gl/maps/Rg1PywavSVbFGqS37" coords="1100,260,1270,358" shape="rect">
     <area target="_blank" alt="Saveetha College of Architecture" title="Saveetha College of Architecture" href="https://goo.gl/maps/DVgwQ5cCbUCspWeM6" coords="325,554,473,649" shape="rect">
     </map>
     </center>
     </body>
      </html>

## Output:
    
![Outputscreen](/images/Outputscreen.png)
![SaveethaWomen'sHostel](/images/SaveethaWomen'sHostel.png)
![SaveethaCricketclub](/images/SaveethaCricketclub.png)
![AmaravatiResidency](/images/AmaravatiResidency.png)
![Saveethawaterpark](/images/Saveethawaterpark.png)
![SaveethaArchitecture](/images/SaveethaArchitecture.png)

Validation report

![validation](/images/Validation.png)

## Result:

  Thus, a website to display places around me in the form of imagemaps was successfully created.
