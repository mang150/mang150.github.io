<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>My Resume</title>
    <style>
        /* CSS styles for the webpage */
        body {
            font-family:Times New Roman;
            margin: 0;
            background-color: #f0f0f0;
        }

        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            background-color: white;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
        }

        .header {
            display: flex;
            align-items: center;
            justify-content: space-between;
        }

        .header h1 {
            margin: 0;
            font-size: 32px;
            color: #333;
        }

        .header img {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            object-fit: cover;
        }

        .section {
            margin: 20px 0;
            border-bottom: 1px solid #ccc;
        }

        .section:last-child {
            border-bottom: none;
        }

        .section h2 {
            margin: 0;
            font-size: 24px;
            color: #333;
        }

        .section ul {
            list-style: none;
            padding: 0;
        }

        .section li {
            margin: 10px 0;
        }

        .section p {
            margin: 10px 0;
            line-height: 1.5;
        }

        .contact {
            display: flex;
            align-items: center;
        }

        .contact span {
            margin-right: 10px;
        }

        .hobbies {
            display: flex;
            flex-wrap: wrap;
        }

        .hobby {
            width: 33.33%;
            padding: 10px;
            text-align: center;
        }

        .hobby img {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            object-fit: cover;
            transition: transform 0.3s;
        }

        .hobby img:hover {
            transform: scale(1.1);
        }

        .hobby h3 {
            margin: 10px 0;
            font-size: 18px;
            color: #333;
        }
    </style>
    <script>
        // JavaScript features for the webpage
        window.addEventListener("load", function() {
            // Get hobby images
            var images = document.querySelectorAll(".hobby img");
            // Loop through the images
            for (var i = 0; i < images.length; i++) {
                // Add a click event listener to each image
                images[i].addEventListener("click", function() {
                    // Get the hobby name from the image alt attribute
                    var hobby = this.alt;
                    // Display message with the hobby name
                    alert("You clicked on " + hobby + "!");
                });
            }
        });
    </script>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>Arielle Hassarath</h1>
        </div>
        <div class="section">
            <h2></h2>
            <ul>
                <li><span class="contact"><span>📧</span> arielle.hassarath@my.liu.edu</span></li>
                <li><span class="contact"><span>📞</span>+1 234 567 890</span></li>
                <li><span class="contact"><span>🌎</span>Brooklyn, New York, USA</span></li>
            </ul>
        </div>
        <div class="section">
            <h2>Summary</h2>
            <p>An accomplished graduate student, with experience in building databases, developing code to enhance web pages and the content within the website, analyzing data using tools such as Excel to solve algorithms and 						specific problems. With rich experience with coding and using tools, can provide accurate and highly efficient results.</p>
        </div>
        <div class="section">
            <h2>Skills</h2>
            <ul>
                <li>HTML, CSS, JavaScript</li>
                <li>Github, Gitlab, Excel</li>
                <li>C++, C </li>
              
            </ul>
        </div>
        <div class="section">
            <h2>Projects</h2>
            <ul>
                <li><a href="https://www.wix.com">Project 1</a>: A social media platform for web developers".</li>
                <li><a href="https://bookscouter.com">Project 2</a>: A e-commerce website for selling books".</li>
                <li><a href="https://www.w3schools.com/">Project 3</a>: A blog website for sharing tips and tutorials about coding".</li>
            </ul>
        </div>
        <div class="section">
            <h2>Hobbies</h2>
            <div class="hobbies">
                <div class="hobby">
                    <img src="https://contentstatic.techgig.com/photo/76304455/7-hobbies-of-programmers-that-improves-their-coding-skills.jpg?73651"alt="Coding">
                    <h3>Coding</h3>
                </div>
                <div class="hobby">
                    <img src="https://www.facebookportraitproject.com/wp-content/uploads/2021/04/Gaming-Hobby-3.jpg" alt="Gaming">
                    <h3>Gaming</h3>
                </div>
                <div class="hobby">
                <img src="https://www.mydomaine.com/thmb/avn4HO6LrawbKTN30Mjzb65NE2Y=/2121x1414/filters:no_upscale():max_bytes(150000):strip_icc()/hocus-focus_GettyImages_travelthemedtoplay-44ad9a47ea4d46289dd6eb64d8fb07a2.jpeg" alt="Traveling">
           <h3>Traveling</h3>   
        </div>
        <div class= "hobby">
        <img src = "https://austinchildrensacademy.org/wp-content/uploads/2020/11/learning.png" alt ="Reading"> 
        <h3>Reading</h3> 
   </div>     
 </div>
