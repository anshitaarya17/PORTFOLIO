# PORTFOLIO
HTML + CSS + JS

<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Personal Portfolio Website</title>
  <link rel="stylesheet" href="./style.css">
  <script src="https://kit.fontawesome.com/a076d05399.js"></script>
  <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/typed.js/2.0.12/typed.min.js"></script>

  <script src="https://cdnjs.cloudflare.com/ajax/libs/waypoints/4.0.1/jquery.waypoints.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/OwlCarousel2/2.3.4/owl.carousel.min.js"></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/OwlCarousel2/2.3.4/assets/owl.carousel.min.css" />
</head>

<body>
  <div class="scroll-up-btn">
    <i class="fas fa-angle-up"></i>
  </div>
  <nav class="navbar">
    <div class="max-width">
      <div class="logo"><a href="#">Portfo<span>lio.</span></a></div>
      <ul class="menu">
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#services">Services</a></li>
        <li><a href="#skill">Skills</a></li>
        <li><a href="#teams">Teams</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
      <div class="menu-btn">
        <i class="fas fa-bars"></i>
      </div>
    </div>
  </nav>

  <!-- ! HOME ! -->
  <section class="home" id="home">
    <div class="max-width">
      <div class="home-content">
        <div class="text-1">Hello, my name is </div>
        <div class="text-2">Anshita Arya </div>
        <div class="text-3">And I'm a <span class="typing"></span> </div>
        <!--  <a href="#">Hire me</a> -->
      </div>
    </div>
  </section>


  <!-- ! ABOUT ! -->
  <section class="about" id="about">
    <div class="max-width">
      <h2 class="title">About me</h2>
      <div class="about-content">
        <div class="column left">
          <img src="https://images.pexels.com/photos/3756681/pexels-photo-3756681.jpeg?auto=compress&cs=tinysrgb&w=600"
            alt="My Image">
        </div>
        <div class="column right">
          <div class="text">I'm Anshita and I'm a <span class="typing-2"></span></div>
          <p>
            Highly organized and detail-oriented student curently persuing B.Tech in IT from Presidency University,
            Bangalore seeking an internship
            as an Front-End Developer. Having experience in blending the art of design with skill of programming to
            deliver an immersive
            and engaging user experience through efficient website development, animations, and relentless debugging.
            <br>
            Very passionate about aesthetics and UI design.
          </p>
          <a href="cv.html" target="_blank" rel="noopener noreferrer">Download CV</a>
        </div>
      </div>
    </div>
  </section>

  <!-- ! SERVICES ! -->
  <section class="services" id="services">
    <div class="max-width">
      <h2 class="title">My services</h2>
      <div class="serv-content">
        <div class="card">
          <div class="box">
            <i class="fas fa-paint-brush"></i>
            <div class="text">Web Design</div>
            <p class="subtext">
              As a web designer, my job is to create the layout and design of a website. In simple terms, I try to make
              a site look good.</p>
          </div>
        </div>

        <div class="card">
          <div class="box">
            <i class="fas fa-chart-line"></i>
            <div class="text">Advertising</div>
            <p>I focuses on creating and executing effective advertisements and campaigns in addition to other
              marketing-related initiatives that help companies meet their business objectives.</p>
          </div>
        </div>

        <div class="card">
          <div class="box">
            <i class="fas fa-code"></i>
            <div class="text">Apps Design</div>
            <p>I also create programs for smartphones, tablets and computers. They work in a range of industries and
              across a number of platforms, including Apple iOS and macOS, Google Android, and Windows.</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ! SKILLS ! -->
  <section class="skills" id="skill">
    <div class="max-width">
      <h2 class="title">My skills</h2>
      <div class="skills-content">
        <div class="column left">
          <div class="text">My creative skills & expriences</div>
          <p>I possess a diverse range of skills that make me a valuable asset to any team. With exceptional
            communication abilities, I effectively convey ideas both verbally and in writing. I excel at
            problem-solving, utilizing a meticulous approach to identify and resolve challenges. Proficiency in various
            software applications, including Microsoft Office Suite, enables me to streamline workflows and enhance
            productivity. I am highly organized, adept at prioritizing tasks, and thrive in collaborative team
            environments.</p>
          <a href="##">Read more</a>
        </div>

        <div class="column right">
          <div class="bars">
            <div class="info">
              <span>C++</span>
              <span>96%</span>
            </div>
            <div class="line c"></div>
          </div>
          <div class="bars">
            <div class="info">
              <span>Python</span>
              <span>94%</span>
            </div>
            <div class="line python"></div>
          </div>
          <div class="bars">
            <div class="info">
              <span>HTML</span>
              <span>90%</span>
            </div>
            <div class="line html"></div>
          </div>
          <div class="bars">
            <div class="info">
              <span>CSS</span>
              <span>70%</span>
            </div>
            <div class="line css"></div>
          </div>
          <div class="bars">
            <div class="info">
              <span>JavaScript</span>
              <span>60%</span>
            </div>
            <div class="line js"></div>
          </div>
          <div class="bars">
            <div class="info">
              <span>React Native</span>
              <span>75%</span>
            </div>
            <div class="line react"></div>
          </div>
          <div class="bars">
            <div class="info">
              <span>PHP</span>
              <span>45%</span>
            </div>
            <div class="line php"></div>
          </div>
          <div class="bars">
            <div class="info">
              <span>MySQL</span>
              <span>70%</span>
            </div>
            <div class="line mysql"></div>
          </div>
          <div class="bars">
            <div class="info">
              <span>Django</span>
              <span>85%</span>
            </div>
            <div class="line django"></div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ! TEAMS??? ! -->

  <section class="teams" id="teams">
    <div class="max-width">
      <h2 class="title">My Projects</h2>
      <div class="carousel owl-carousel">
        <div class="card">
          <div class="box">
            <img src="CmingSoon.png" alt="">
            <div class="text">Coming Soon</div>
            <p>In progres, will be Updating Soon <br>
              Stay Tuned!!
            </p>
          </div>
        </div>
        <div class="card">
          <div class="box">
            <img src="OpenUp.png">
            <div class="text">OpenUp!!</div>
            <p>Providing Domestic Violence Awareness and Legal Assistants</p>
          </div>
        </div>
        <div class="card">
          <div class="box">
            <img src="CmingSoon.png">
            <div class="text">Coming Soon</div>
            <p>In progres, will be Updating Soon <br>
              Stay Tuned!!
            </p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ! CONTACTS ! -->

  <section class="contact" id="contact">
    <div class="max-width">
      <h2 class="title">Contact Me</h2>
      <div class="contact-content">
        <div class="column left">
          <div class="text">Get in Touch</div>
          <p>I bring a wealth of experience and expertise in my field, making me a valuable resource for tackling
            complex challenges and driving innovative solutions.</p>
          <div class="icons">
            <div class="row">
              <i class="fas fa-user"></i>
              <div class="info">
                <div class="head">Name</div>
                <div class="sub-title">Anshita Arya</div>
              </div>
            </div>
            <div class="row">
              <i class="fas fa-map-marker-alt"></i>
              <div class="info">
                <div class="head">Address</div>
                <div class="sub-title">Bangalore, Karnataka</div>
              </div>
            </div>
            <div class="row">
              <i class="fas fa-envelope"></i>
              <div class="info">
                <div class="head">Email</div>
                <div class="sub-title">anshitaarya1243@gmail.com</div>
              </div>
            </div>
          </div>
        </div>
        <div class="column right">
          <div class="text">Message me</div>
          <form action="ajax.html">
            <div class="fields">
              <div class="field name">
                <input type="text" placeholder="Name" required>
              </div>
              <div class="field email">
                <input type="email" placeholder="Email" required>
              </div>
            </div>
            <div class="field">
              <input type="text" placeholder="Subject" required>
            </div>
            <div class="field textarea">
              <textarea id="" cols="30" rows="10" placeholder="Describe project.." required></textarea>
            </div>
            <div class="button">
              <a href="ajax.html">
                <button type="submit">Send message</button>
              </a>


            </div>
          </form>
        </div>
      </div>
    </div>
  </section>

  <!-- ! FOOTER ! -->
  <footer>
    <span>Created By <a href="#">ANSHITA </a> | <span class="far fa-copyright"></span> 2023 All rights reserved.</span>
  </footer>

  <script type="text/javascript" src="script.js"></script>
</body>

</html>