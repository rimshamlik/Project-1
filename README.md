# Project-1
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Project-1</title>
    
    <link rel="stylesheet" href="style.css">

</head>
<body>
    <div id="navbar" class="uni-padding">
        <h2>Namecheap</h2>
        <ul>
            <li>Domains</li>
            <li>Hosting</li>
            <li>WordPress</li>
            <li>Email</li>
            <li>Marketing Tools</li>
            <li>Security</li>
            <li>Transfer to Us</li>
            <li>Help center</li>
            <li>Account</li>
        </ul>
    </div>
    <div id="banner">
        <h1>R.S <p>malik</p></h1>
        <h4>I'm Rimsha</h4>
    </div>
</body>
</html>

CSS Style:
* {
    padding: 0;
    margin: 0;
    /* border: 1px solid red; */
}

.uni-padding {
    padding: 0 3%;
}

#navbar {
    background-color: rgb(167, 227, 218);
    height: 10vh;
    display: flex;
    justify-content: space-between;
}

#navbar h2 {
    color: black;
    align-content: center;
}

#navbar ul {
    width: 80%;
    display: flex;
    justify-content: space-evenly;
}

#navbar ul li {
    list-style-type: none;
    font-size: 20px;
    color: black;
    align-content: center;
}

#navbar ul li:hover {
    color: rgb(163, 190, 181);
    cursor: pointer;
    text-decoration: underline;
}

#banner {
    height: 90vh;
    width: 100vw;
    background-image: url(images/images.jpg);
    background-size: cover;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    gap: 16px;   
}

#banner h1 {

    height: 150px;
    width: 150px;
    font-size: 50px;
    border-radius: 50%;
    border: 1px solid black;
    backdrop-filter: blur(5px);
    box-shadow: 0px 0px 6px 3px;

    align-content: center;
    text-align: center;
}

#banner h1 p {
    font-size: 19px;
}

#banner h4 {
    text-decoration: underline;
    font-size: 17px;
}
