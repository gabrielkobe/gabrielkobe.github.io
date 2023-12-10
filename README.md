# gabrielkobe.github.io

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Nunito:400,700&display=swap">
    <title>Final Project Showcase</title>
    <style>
        body {
            font-family: 'Nunito', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #232323;
            color: #E0E0E0;
            line-height: 1.6;
        }

        header {
            background: linear-gradient(135deg, #2C3E50, #34495E);
            color: #fff;
            text-align: center;
            padding: 2em;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.2);
        }

        h1 {
            margin: 0;
            font-size: 2.8em;
            color: #fff;
        }

        section {
            max-width: 900px;
            margin: 2em auto;
            padding: 2em;
            background-color: #2C3E50;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.3);
            border-radius: 15px;
            margin-top: -20px;
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
        }

        h2 {
            color: #3498DB;
            border-bottom: 2px solid #3498DB;
            padding-bottom: 0.5em;
            margin-bottom: 1.5em;
            font-size: 2em;
        }

        .personal-info {
            width: 100%;
            font-size: 1.1em;
            margin-bottom: 2em;
            color: #E0E0E0;
        }

        .personal-info table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 1em;
        }

        .personal-info th, .personal-info td {
            border: 1px solid #2C3E50;
            padding: 0.8em;
            text-align: left;
            background-color: #34495E;
            color: #E0E0E0;
        }

        .detail {
            width: 100%;
            font-size: 1.1em;
            margin-bottom: 2em;
            color: #E0E0E0;
        }

        .projects {
            width: 100%;
            margin-top: 2em;
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
        }

        .project {
            width: calc(48% - 1em);
            margin-bottom: 1.5em;
            padding: 1.5em;
            background-color: #34495E;
            border-radius: 15px;
            transition: transform 0.3s ease-in-out;
            box-sizing: border-box;
            color: #E0E0E0;
        }

        .project:hover {
            transform: scale(1.03);
        }

        .project h3 a {
            color: #E0E0E0;
            text-decoration: none;
            font-weight: bold;
        }

        .project h3 a:hover {
            text-decoration: underline;
        }

        .project p {
            font-size: 1.2em;
            margin-bottom: 1em;
            color: #E0E0E0;
        }

        .project a {
            color: #3498DB;
            text-decoration: none;
            font-weight: bold;
        }

        .project a:hover {
            text-decoration: underline;
        }

        .reflection {
            width: 100%;
            margin-top: 2em;
            background-color: #2C3E50;
            padding: 2em;
            border-radius: 15px;
            color: #E0E0E0;
        }

        .reflection h2 {
            color: #3498DB;
            border-bottom: 2px solid #3498DB;
            padding-bottom: 0.5em;
            margin-bottom: 1.5em;
            font-size: 2em;
        }
    </style>
</head>
<body>

    <header>
        <h1>Final Project Showcase</h1>
    </header>

    <section>
        <div class="personal-info">
            <h2>Personal Information</h2>
            <table>
                <tr>
                    <th>Attribute</th>
                    <th>Details</th>
                </tr>
                <tr>
                    <td>Student Name</td>
                    <td>Your Name</td>
                </tr>
                <tr>
                    <td>Email</td>
                    <td>your.email@example.com</td>
                </tr>
                <tr>
                    <td>Phone</td>
                    <td>+123 456 7890</td>
                </tr>
                <tr>
                    <td>Birthday</td>
                    <td>January 1, 2000</td>
                </tr>
                <tr>
                    <td>Location</td>
                    <td>City, Country</td>
                </tr>
            </table>
        </div>

        <div class="detail">
            <h2>Details</h2>
            <p>This is a brief detail about the student. You can add information such as academic achievements, skills, or any other relevant details.</p>
        </div>

        <section class="projects">
            <h2>Projects</h2>

            <!-- Add more projects as needed -->
            <div class="project">
                <h3><a href="#">Project 1</a></h3>
                <p>Brief description of the project. Technologies used: [Tech stack]. <a href="#">LINK</a></p>
            </div>

            <div class="project">
                <h3><a href="#">Project 2</a></h3>
                <p>Brief description of the project. Technologies used: [Tech stack]. <a href="#">LINK</a></p>
            </div>
        </section>
    </section>

    <div class="reflection">
        <h2>Reflection and Learnings</h2>
        <p>Share your reflections, key learnings, and insights gained from these projects. This is an opportunity to showcase your growth and development as a student and aspiring professional.</p>
    </div>

</body>
</html>
