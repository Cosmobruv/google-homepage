<!This project's goal is to deconstruct then reconstruct a simple webpage
At the end of this, I should be able to manipulate a div
color a background
find a url via image
center an element
have a good handle on how to use CSS> 

<html>
<head>
<style>
ul {
    list-style-type: none;
    margin:0;
    padding:0;    
}
li{
    display: inline;
}
</style>
</head>
    <body>
        <ul class="horizontal">
    <li>
    <a href=#>About</a>
    </li>
    <li>
    <a href=#>Store</a>
    </ul>
        <img src= "/images/branding/googlelogo/2x/googlelogo_color_272x92dp.png" alt= "Google Logo">
        <div><input type="text"></div>
        <div><button type="submit">Google Search</button>
        <button type="submit">I'm Feeling Lucky</button></div>        
    </body>
</html>