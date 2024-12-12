<!DOCTYPE html>
<html lang="en">
<style>
    h3 {
        font-style: italic;
        font-size: 23px;
        font-weight: 300;
    }

    .main {
        width: auto;
    }

    .navbar {
        width: auto;
        height: 70px;
    }

    .logo {
        width: 30%;
        float: left;
    }

    .nav-items {
        width: 70%;
        float: left;
    }

    .nav-items ul {
        list-style-type: none;
        margin: 10px;
        padding: 20px;
        overflow: hidden;
        background-color: #333333;
    }

    .nav-items li {
        float: left;
        color: #fff;
        padding: 0px 30px 0px 0px;
    }

    .nav-items li a {
        display: block;
        color: white;
        text-align: center;
        padding: 16px;
        text-decoration: none;
    }

    .nav-items li a:hover {
        background-color: #111111;
    }

    .slider {
        height: 250px;
        text-align: center;
        border-bottom: 1px solid;
    }

    .slider h1 {
        padding-top: 50px;
        font-style: italic;
        font-size: 50px;
        margin-bottom: 1px;
    }

    .slider p {
        margin-top: 3px;
        color: gray;
    }

    .about-section {
        width: 100%;
        border-bottom: 1px solid;
        float: left;

    }

    .Projects {
        width: 25%;
        float: left;
        border-right: 1px solid;
        padding: 20px 0px 0px 20px;
    }

    .Projects ul {
        list-style-type: none;
        overflow: hidden;

    }

    .Projects li {
        color: #333333;
        padding: 10px 0px 10px 0px;
        border-bottom: 1px solid;
    }

    .Work-exp {
        width: 40%;
        float: left;

        border-right: 1px solid;
    }

    .Work-exp1 {
        padding: 24px 20px;
        border-bottom: 1px solid;
    }

    .Eduction {
        width: 30%;
        float: left;
        padding: 20px;
    }

    .Eduction ul {
        list-style-type: none;
        overflow: hidden;

    }

    .Eduction li {

        padding: 10px 0px 0px 0px;

    }

    .review-section {
        float: left;
        padding: 20px;
    }

    .reviews {
        width: 17%;
        border: 1px solid;
        border-radius: 40px;
        float: left;
        padding: 38px 56px;
        margin: 2px 48px;
        align-items: center;
    }

    .comment-by {
        color: gray;
        line-height: 2px;
    }
</style>

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Basic Website Design</title>
</head>

<body>
    <div class="main">
        <div class="navbar">
            <div class="logo">
                <img src="">
            </div>
            <div class="nav-items">
                <ul>
                    <li>Home</li>
                    <li>Projects</li>
                    <li>Articles</li>
                    <li>About Us</li>
                    <li>Contact Us</li>
                </ul>
            </div>
        </div>
        <div class="slider">
            <h1>Froted Developer</h1>
            <p>html only with proper layout, no styling</p>
        </div>
        <div class="about-section">
            <div class="Projects">
                <h3>Projects</h3>
                <ul>
                    <li><b>HTML Only Portfolio</b></li>
                    <li><b>Calculator</b></li>
                    <li><b>Quiz App</b></li>
                    <li> <b>Countdown Time</b></li>
                    <li><b>Products Upcoming Page</b></li>
                </ul>
            </div>
            <div class="Work-exp">
                <div class="Work-exp1">
                    <h3>Work Experience</h3>
                    <i>roadmap.sh</i>
                    <p>Solved all fronted projects</p>
                    <a href="#">Visit my profile</a>
                </div>

                <div class="Work-exp1">
                    <p><i>OpenSource Wokr</i></p>
                    <p><b>Contributed to 50 opensource projects. Made my own projects with 200 GitHub stars.</b></p>
                    <a href="#">Visit my GitHub profile</a>
                </div>
            </div>
            <div class="Eduction">
                <h3>Eduction</h3>
                <p>Graduated with 3.76 out of 4 CGPA. Won Acme Hackathon. Organized 30 sessions.</p>
                <b>Courses I took:</b>
                <ul>
                    <li>Object Oriented Programming</li>
                    <li>Data Structre and Algorithms</li>
                    <li>web Engineering</li>
                    <li>Artifical Intelligence</li>
                    <li>Human Computer Intercation</li>
                    <li>Computer Graphics</li>
                    <li>Database Management System</li>
                    <li>Distrbuted Database System</li>
                    <li>Discreet Mathematics</li>
                </ul>
            </div>
        </div>
        <div class="review-section">
            <h3>Reviews from my teacher</h3>
            <div class="reviews">
                <p>John doe was a brilliant student; always stood out with his assignments.</p>
                <div class="comment-by">Jane Doe</div><br />
                <div class="comment-by">Assitant Professor</div>
            </div>
            <div class="reviews">
                <p>John doe was a brsilliant student; always stood out with his assignments.</p>
                <div class="comment-by">Jane Doe</div><br />
                <div class="comment-by">Assitant Professor</div>
            </div>
            <div class="reviews">
                <p>John doe was a brilliant student; always stood out with his assignments.</p>
                <div class="comment-by">Jane Doe</div><br />
                <div class="comment-by">Assitant Professor</div>
            </div>
        </div>
    </div>

</body>

</html>
https://roadmap.sh/projects/basic-html-website
