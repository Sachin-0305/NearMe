# Ex04 Places Around Me
## Date: 11/04/2024

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
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MAP</title>
</head>
<script>
    function coordinate(event)
    {
        let x=event.clientX;
        let y=event.clientY;
        document.getElementById("text1").value=x;
        document.getElementById("text2").value=y;
    }
</script>
<body>
    <img src="HHH.jpg" width="1000px" usemap="#MyMap" onmousemove="coordinate(event)"><br>
    <map name="MyMap">
        <area shape="rect" coords="678,204,764,251" href="https://en.wikipedia.org/wiki/Russia" title="RUSSIA">
        <area shape="rect" coords="655,350,691,408" href="https://en.wikipedia.org/wiki/India" title="INDIA">
        <area shape="rect" coords="675,296,787,365" href="https://en.wikipedia.org/wiki/China" title="CHINA">     
    </map>
    X coordinate <input type="text" name="" id="text1">
    Y coordinate <input type="text" name="" id="text2">
</body>
</html>

## OUTPUT
![Screenshot 2024-04-17 094612](https://github.com/Sachin-0305/NearMe/assets/149985717/66bb3849-fcb5-4770-af96-a2129a9d8129)
![Screenshot 2024-04-17 094632](https://github.com/Sachin-0305/NearMe/assets/149985717/e5a0a018-6f3b-4cab-bba3-579da0a292ac)
![Screenshot 2024-04-17 094645](https://github.com/Sachin-0305/NearMe/assets/149985717/bfc40082-c3be-4c57-901d-3de4e4ad46f1)
![Screenshot 2024-04-17 094657](https://github.com/Sachin-0305/NearMe/assets/149985717/ce5afc57-657d-4f68-bb47-0fa60e1acc98)
![Screenshot 2024-04-17 094711](https://github.com/Sachin-0305/NearMe/assets/149985717/922b1b44-34a0-4d6a-bbcc-d5f71890f43c)
![Screenshot 2024-04-17 094725](https://github.com/Sachin-0305/NearMe/assets/149985717/36d7d99d-ae29-4d97-9fdf-0dc9b5276dac)


## RESULT:
THE PROGRAM FOR IMPLEMENTATION IMAGE MAPPING USING HTML IS EXECUTED SUCCESSFULLY.





## RESULT
The program for implementing image maps using HTML is executed successfully.
