# Ex04 Places Around Me
## Date: 

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


![Screenshot 2024-04-17 094612](https://github.com/selvasachein/NearMe/assets/149985717/83375482-90a5-4b48-9c3a-f383a1bbb610)
![Screenshot 2024-04-17 094632](https://github.com/selvasachein/NearMe/assets/149985717/397b19a3-d564-4782-b73a-6ebd9ba73b7f)
![Screenshot 2024-04-17 094645](https://github.com/selvasachein/NearMe/assets/149985717/f531fd3a-b04b-46e3-9d40-c069a5972242)
![Screenshot 2024-04-17 094657](https://github.com/selvasachein/NearMe/assets/149985717/adf940da-7eb8-407f-b61a-608feeb4a405)
![Screenshot 2024-04-17 094711](https://github.com/selvasachein/NearMe/assets/149985717/dfdbe399-13df-486c-9571-4dd4bcb2c8c7)
![Screenshot 2024-04-17 094725](https://github.com/selvasachein/NearMe/assets/149985717/b962183d-6910-4e7c-9d95-62783feb895c)






## RESULT
The program for implementing image maps using HTML is executed successfully.
