
       
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
            // Get the hobby images
            var images = document.querySelectorAll(".hobby img");
            // Loop through the images
            for (var i = 0; i < images.length; i++) {
                // Add a click event listener to each image
                images[i].addEventListener("click", function() {
                    // Get the hobby name from the image alt attribute
                    var hobby = this.alt;
                    // Display an alert message with the hobby name
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
            <p>An accomplished graduate student, with experience in building databases, developing code to enhance web pages and the content within the website, analyzing data using tools such as Excel to solve algorithms and specific problems. With rich experience with coding and using tools, can provide accurate and highly efficient results.</p>
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
                <li><a href="https://example.com/project1">Project 1</a>: A social media platform for web developers".</li>
                <li><a href="https://example.com/project2">Project 2</a>: A e-commerce website for selling books".</li>
                <li><a href="https://example.com/project3">Project 3</a>: A blog website for sharing tips and tutorials about coding".</li>
            </ul>
        </div>
        <div class="section">
            <h2>Hobbies</h2>
            <div class="hobbies">
                <div class="hobby">
                    <img src="hobby1.jpg" alt="Coding">
                    <h3>Reading</h3>
                </div>
                <div class="hobby">
                    <img src="hobby2.jpg" alt="Gaming">
                    <h3>Gaming</h3>
                </div>
                <div class="hobby">
                    <img src="hobby3.jpg" alt="Traveling">
           <h3>Traveling</h3>   
        </div>
    </div>
</body>
</html>
