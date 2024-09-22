# Profile-portfolio
A description of skills and knowledge regarding my educational and experience journey.
<!DOCTYPE html>
<html lang="en">
<head>
  <title>Lakshmi Priya Komalli - Profile</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">
  <link href="https://fonts.googleapis.com/css?family=Montserrat|Lato" rel="stylesheet" type="text/css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.7.1/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/typed.js@2.0.12"></script>
  <style>
    body {
      font: 400 15px Lato, sans-serif;
      line-height: 1.8;
      color: #818181;
      background-color: #f4f4f4;
    }
    .jumbotron {
      background-color: #3498db;
      color: #fff;
      padding: 100px 25px;
      font-family: Montserrat, sans-serif;
    }
    .container-fluid {
      padding: 60px 50px;
    }
    .navbar {
      margin-bottom: 0;
      background-color: #3498db;
      z-index: 9999;
      border: 0;
      font-size: 12px;
      letter-spacing: 4px;
      font-family: Montserrat, sans-serif;
    }
    .navbar li a, .navbar .navbar-brand {
      color: #fff !important;
    }
    .navbar-nav li a:hover, .navbar-nav li.active a {
      color: #3498db !important;
      background-color: #fff !important;
    }
    .carousel-control.right, .carousel-control.left {
      background-image: none;
      color: #3498db;
    }
    .carousel-indicators li {
      border-color: #3498db;
    }
    .carousel-indicators li.active {
      background-color: #3498db;
    }
    .section-title {
      text-align: center;
      margin-bottom: 50px;
    }
    .section-title h2 {
      font-size: 36px;
      font-weight: 700;
      color: #303030;
    }
    .skills-section .progress {
      margin-bottom: 20px;
    }
    .progress-bar {
      background-color: #3498db;
    }
    .projects .card {
      transition: transform 0.3s ease;
    }
    .projects .card:hover {
      transform: scale(1.05);
    }
    footer {
      background-color: #3498db;
      color: #fff;
      padding: 25px;
      text-align: center;
    }
  </style>
</head>
<body id="myPage" data-spy="scroll" data-target=".navbar" data-offset="60">

  <nav class="navbar navbar-default navbar-fixed-top">
    <div class="container">
      <div class="navbar-header">
        <button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#myNavbar">
          <span class="icon-bar"></span>
          <span class="icon-bar"></span>
          <span class="icon-bar"></span>
        </button>
        <a class="navbar-brand" href="#myPage">Lakshmi Priya Komalli</a>
      </div>
      <div class="collapse navbar-collapse" id="myNavbar">
        <ul class="nav navbar-nav navbar-right">
          <li><a href="#about">ABOUT</a></li>
          <li><a href="#education">EDUCATION</a></li>
          <li><a href="#experience">EXPERIENCE</a></li>
          <li><a href="#projects">PROJECTS</a></li>
          <li><a href="#skills">SKILLS</a></li>
          <li><a href="#contact">CONTACT</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <div class="jumbotron text-center">
    <h1>Lakshmi Priya Komalli</h1>
    <p><span id="typed"></span></p>
    <p>Innovative Web Developer | AI & ML Enthusiast | Cloud Computing Specialist</p>
  </div>

  <script>
    var typed = new Typed("#typed", {
      strings: ["Software Engineer", "Web Developer", "AI & ML Enthusiast", "Cloud Computing Specialist"],
      typeSpeed: 50,
      backSpeed: 25,
      loop: true
    });
  </script>

  <!-- About Section -->
  <div id="about" class="container-fluid">
    <div class="section-title">
      <h2>About Me</h2>
      <p>I'm Lakshmi Priya Komalli, a passionate software engineer with a focus on web development, AI, ML, and cloud computing. I love creating dynamic and user-friendly solutions using the latest technologies and tools.</p>
    </div>
  </div>

  <!-- Education Section -->
  <div id="education" class="container-fluid bg-grey">
    <div class="section-title">
      <h2>Education</h2>
    </div>
    <div class="row">
      <div class="col-sm-8 col-sm-offset-2">
        <h4>Master of Engineering in Computer Science</h4>
        <p>University of Cincinnati, Ohio (August 2023)</p>
        <h4>Bachelor of Technology in Computer Science and Engineering</h4>
        <p>SRM University, Andhra Pradesh (May 2023) | GPA: 8.7/10</p>
      </div>
    </div>
  </div>

  <!-- Experience Section -->
  <div id="experience" class="container-fluid">
    <div class="section-title">
      <h2>Experience</h2>
    </div>
    <div class="row">
      <div class="col-sm-8 col-sm-offset-2">
        <div class="panel panel-default">
          <div class="panel-heading">Placement Training Timetable Maintenance System</div>
          <div class="panel-body">
            <p>Developed a fully automated timetable system that optimized resource usage and reduced manual efforts by 30% for SRM University.</p>
          </div>
        </div>
        <div class="panel panel-default">
          <div class="panel-heading">Intern at 360 Research Foundations</div>
          <div class="panel-body">
            <p>Improved a women empowerment website with front-end technologies, resulting in a 15% increase in user interaction.</p>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- Projects Section -->
  <div id="projects" class="container-fluid">
    <div class="section-title">
      <h2>Projects</h2>
    </div>
    <div class="row projects">
      <div class="col-sm-4">
        <div class="card">
          <h4>Library Management System</h4>
          <p>Created a dual-feature system for students to search books and administrators to manage book data, increasing student interactions by 30%.</p>
        </div>
      </div>
      <div class="col-sm-4">
        <div class="card">
          <h4>Online Book Store</h4>
          <p>Developed a user-friendly online book store, optimizing user experience and reducing costs by 20% through retailer competition.</p>
        </div>
      </div>
      <div class="col-sm-4">
        <div class="card">
          <h4>Enchanted Pathways: A Strategic Board Game</h4>
          <p>Developed a snake and ladder game in C using GNU GCC, improving speed and reducing system crashes by 20%.</p>
        </div>
      </div>
    </div>
  </div>

  <!-- Skills Section -->
  <div id="skills" class="container-fluid bg-grey">
    <div class="section-title">
      <h2>Skills</h2>
    </div>
    <div class="row">
      <div class="col-sm-6">
        <h4>Frontend</h4>
        <div class="progress">
          <div class="progress-bar" role="progressbar" style="width: 90%;">HTML, CSS, JavaScript</div>
        </div>
        <h4>Backend</h4>
        <div class="progress">
          <div class="progress-bar" role="progressbar" style="width: 85%;">Python, Java, C, MySQL</div>
        </div>
      </div>
      <div class="col-sm-6">
        <h4>Technologies</h4>
        <div class="progress">
          <div class="progress-bar" role="progressbar" style="width: 80%;">AI, ML, Cloud Computing (AWS, Azure, GCP)</div>
        </div>
        <h4>Tools</h4>
        <div class="progress">
          <div class="progress-bar" role="progressbar" style="width: 75%;">Git, Visual Studio, Eclipse</div>
        </div>
      </div>
    </div>
  </div>

  <!-- Contact Section -->
  <div id="contact" class="container-fluid">
    <div class="section-title">
      <h2>Contact</h2>
    </div>
    <div class="row">
      <div class="col-sm-8 col-sm-offset-2">
        <p><span class="glyphicon glyphicon-map-marker"></span> Cincinnati, Ohio, USA</p>
        <p><span class="glyphicon glyphicon-phone"></span> 945-246-2956</p>
        <p><span class="glyphicon glyphicon-envelope"></span> komallla@mail.uc.edu</p>
        <p><a href="https://www.linkedin.com/in/lakshmi-priya01/" target="_blank">LinkedIn</a> | <a href="https://github.com/lakshmipriya2001/" target="_blank">GitHub</a></p>
      </div>
    </div>
  </div>

  <footer class="container-fluid text-center">
    <a href="#myPage" title="To Top">
      <span class="glyphicon glyphicon-chevron-up"></span>
    </a>
    <p>Powered by Lakshmi Priya Komalli</p>
  </footer>

</body>
</html>
