# Resume-krishti-bhutani-
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Modern Resume</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f3f3f3;
            color: #333;
        }
        .container {
            max-width: 900px;
            margin: 30px auto;
            background: #ffffff;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            overflow: hidden;
        }
        .header {
            background: #0073e6;
            color: #ffffff;
            padding: 20px;
            text-align: center;
        }
        .header h1 {
            margin: 0;
            font-size: 36px;
        }
        .header p {
            margin: 5px 0;
            font-size: 18px;
        }
        .section {
            padding: 20px;
            border-bottom: 1px solid #ddd;
        }
        .section h2 {
            margin: 0 0 10px 0;
            color: #0073e6;
        }
        .skills span {
            display: inline-block;
            margin: 5px;
            padding: 8px 15px;
            background: #0073e6;
            color: #ffffff;
            border-radius: 20px;
            font-size: 14px;
        }
        .download-btn {
            display: block;
            margin: 20px auto;
            text-align: center;
            background: #0073e6;
            color: #ffffff;
            text-decoration: none;
            padding: 10px 20px;
            border-radius: 5px;
            width: 150px;
        }
        .download-btn:hover {
            background: #005bb5;
        }
        .experience ul {
            list-style-type: disc;
            margin: 10px 0 0 20px;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>krishti bhutani</h1>
            <p>Address | Phone | Email | LinkedIn | Portfolio</p>
        </div>

        <div class="section">
            <h2>web developer</h2>
            <p>
            Web developers create websites, write code, and collaborate with designers and programmers. They also maintain and update websites, and ensure they are cross-browser compatible. 
            </p>
        </div>

        <div class="section">
            <h2>Core Competencies</h2>
            <div class="skills">
                <span>HTML</span>
                <span>CSS</span>
                <span>JAVASCRIPT</span>
                <span>WORDPRESS</span>
              
            </div>
        </div>

        <div class="section experience">
            <h2>Experience</h2>
            <p>I am totally fresher</p>

        <div class="section">
            <h2>Education</h2>
            <p><strong>Bachlor of arts </strong> | Delhi University | Graduation 2 Year</p>
        </div>

        <div class="section">
            <h2>Certifications</h2>
            <p><strong>web development</strong> | 2023| Year</p>
        </div>

        <a href="#" id="downloadBtn" class="download-btn">Download Resume</a>
    </div>

    <script>
        // Example: Alert on download button click
        document.getElementById('downloadBtn').addEventListener('click', function () {
            alert('Download feature is not yet implemented.');
        });
    </script>
</body>
</html>
