# Ex04 Places Around Me
## Date: 22-04-2025

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google.

### STEP 3
Using ```<map>``` tag name the map.

### STEP 4
Create clickable regions in the image using ```<area>``` tag.

### STEP 5
Write HTML programs for all the regions identified.

### STEP 6
Execute the programs and publish them.

## CODE
```
map.html
 <html>
 <head>
 <title>MyCity</title>
 </head>
 <body>
<h1 align="center">
 <font color="blue"><b>vellore</b></font>
 </h1>
 <h3 align="center">
 <font color="Yellow">Praveen Santhalingam M(212224040246)</font>
 </h3>
 <center>
  <img src="Screenshot 2025-04-08 113925.png" usemap="#MyCity">  -->


 <map name="MyCity">
    <area target="" alt="cafe coffee" title="cafe coffee" href="cafe.html" coords="50,492,245,604" shape="rect">
    <area target="" alt="vadu" title="vadu" href="vadu.html" coords="503,212,719,309" shape="rect">
    <area target="" alt="poigai" title="poigai" href="poigai.html" coords="698,447,812,505" shape="rect">
    <area target="" alt="vellore" title="vellore" href="vellore.html" coords="886,403,1014,471" shape="rect">
    
</map>
</center>
</body>
</html>


cafe.html


<html>
    <body bgcolor="red">
        <font size="100">
            <li>"coffee cafe is the good coffee to take cafe"</li>
            <li>"this is the best cafe and the cost is best"</li>
        </font>
    </body>
</html> 



 vadu.html


<html>
    <body bgcolor="Yellow">
        <font size="100">
            <li>"Approximately 90.92% of males in the village are literate. ​"</li>
            <li>"The female literacy rate stands at 76.15%."</li>
        </font>
    </body>
</html> 


poigai.html



<html>
    <body bgcolor="orange">
        <font size="100">
            <li>"A temple dedicated to Lord Ganesha, located within Poigai."</li>
            <li>" Situated along the Chennai - Bengaluru Highway in Sathiyamangalam, near Poigai."</li>
        </font>
    </body>
</html> 


vellore.html 


<html>
    <body bgcolor="pink">
        <font size="100">
            <li>"Vellore is a historic city in Tamil Nadu, known for the majestic Vellore Fort and the beautiful Jalakandeswarar Temple within it."</li>
            <li>"It is also famous for the Christian Medical College (CMC) and the Golden Temple at Sripuram, making it a blend of heritage and modern significance."</li>
        </font>
    </body>
</html> 

```

## OUTPUT
![alt text](<Screenshot 2025-04-22 144419.png>)
![alt text](<Screenshot 2025-04-22 144622.png>)
![alt text](<Screenshot 2025-04-22 144741.png>)
![alt text](<Screenshot 2025-04-22 144859.png>)





## RESULT
The program for implementing image maps using HTML is executed successfully.
