
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Alisha Shaheer - Resume</title>
    <style>
        body {
            font-family: sans-serif;
            margin: 20px;
            background-color: #f4f4f4;
            color: #333;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            background-color: white;
            padding: 20px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        .header { /* Styles for the name/title header */
            text-align: center;
            margin-bottom: 20px;
            width: 100%;
        }

        .name-title-wrapper { /* Wrapper for centering */
            display: flex;
            flex-direction: column;
            align-items: center;
            width: 100%;
            margin: 20px 0;
        }
        .name {
            font-size: 2em;
            margin-bottom: 5px;
        }
        .title {
            font-size: 1.2em;
            color: #777;
        }

        .columns-wrapper { /* Wrapper for columns */
            display: flex;
        }
        .left-column {
            width: 30%;
            padding-right: 20px;
        }
        .right-column {
            width: 70%;
        }

        .section {
            margin-bottom: 20px;
        }
        .section-title {
            font-size: 1.5em;
            margin-bottom: 10px;
            border-bottom: 1px solid #ddd;
            padding-bottom: 5px;
        }
        .contact-info {
            line-height: 1.6;
        }
        .contact-info a {
            color: #007bff;
            text-decoration: none;
        }
        .skills-list {
            /* No columns for exact match */
        }
        .skills-list li {
            margin-bottom: 5px;
        }
        .experience-item {
            margin-bottom: 15px;
        }
        .experience-title {
            font-weight: bold;
            margin-bottom: 5px;
        }
        .experience-company {
            color: #777;
            margin-bottom: 5px;
        }
        .education-list {
            list-style: none;
            padding: 0;
        }
        .education-item {
            margin-bottom: 10px;
        }
        .education-degree {
            font-weight: bold;
            margin-bottom: 5px;
        }
        .education-school {
            color: #777;
        }
        .about-text {
            text-align: justify;
        }
    </style>
</head>
<body>

    <div class="container">
        <div class="header">
            <div class="name-title-wrapper">
                <div class="name">Alisha Shaheer</div>
                <div class="title">Student</div>
            </div>
        </div>
        <div class="columns-wrapper">
            <div class="left-column">
                <div class="section">
                    <div class="section-title">Contact</div>
                    <div class="contact-info">
                        <div>Email: <a href="mailto:alishashaheer97@gmail.com">alishashaheer97@gmail.com</a></div>
                        <div>GitHub: <a href="https://github.com/alisha-22" target="_blank">alisha-22</a></div>
                        <div>LinkedIn: <a href="https://www.linkedin.com/in/alisha-shaheer" target="_blank">Alisha Shaheer</a></div>
                    </div>
                </div>

                <div class="section">
                    <div class="section-title">Skills</div>
                    <ul class="skills-list">
                        <li>MS Excel</li>
                        <li>HTML</li>
                        <li>CSS</li>
                        <li>JavaScript</li>
                        <li>Content Writing</li>
                        <li>SQL</li>
                    </ul>
                </div>

                <div class="section">
                    <div class="section-title">Education</div>
                    <ul class="education-list">
                        <li class="education-item">
                            <div class="education-degree">BCA (Pursuing)</div>
                            <div class="education-school">Integral University | 2023 - 2026</div>
                        </li>
                        <li class="education-item">
                            <div class="education-degree">12th</div>
                            <div class="education-school">Buddha Public School | 2021 - 2022</div>
                        </li>
                        <li class="education-item">
                            <div class="education-degree">10th</div>
                            <div class="education-school">Buddha Public School | 2019 - 2020</div>
                        </li>
                    </ul>
                </div>
            </div>

            <div class="right-column">
                <div class="section">
                    <div class="section-title">About</div>
                    <div class="about-text">
                        I am a highly motivated and enthusiastic BCA student with a strong passion for software development. I am eager to secure a challenging role in a dynamic organization where I can utilize my technical skills and contribute to innovative projects. I am particularly interested in companies that foster a collaborative and growth-oriented environment.
                    </div>
                </div>

                <div class="section">
                    <div class="section-title">Work Experience</div>
                    <div class="experience-item">
                        <div class="experience-title">Content Writer</div>
                        <div class="experience-company">Earth5R | Present</div>
                        <ul>
                            <li>Create daily content for the Earth5R Foundation.</li>
                            <li>Manage and post daily content on the Earth5R app.</li>
                        </ul>
                    </div>
                    <div class="experience-item">
                        <div class="experience-title">Content Creator</div>
                        <div class="experience-company">Kshitiksha Foundation | Jan 29 - Feb 4</div>
                        <ul>
                            <li>Developed four pieces of content for the Kshitiksha Foundation.</li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </div>

</body>
</html>
