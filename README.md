<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">

        <link rel="stylesheet" href="assets/css/styles.css">

        <!-- =====BOX ICONS===== -->
        <link href='https://cdn.jsdelivr.net/npm/boxicons@2.0.5/css/boxicons.min.css' rel='stylesheet'>

        <title>Hermina's Portfolio</title>
    </head>
    <body>
        <!--===== HEADER =====-->
        <header class="l-header">
            <nav class="nav bd-grid">
                <div>
                    <a href="#" class="nav__logo">Hermina Judith Chinnappan</a>
                </div>

                <div class="nav__menu" id="nav-menu">
                    <ul class="nav__list">
                        <li class="nav__item"><a href="#home" class="nav__link active-link">Home</a></li>
                        <li class="nav__item"><a href="#about" class="nav__link">About</a></li>
                        <li class="nav__item"><a href="#skills" class="nav__link">Skills</a></li>
                        <li class="nav__item"><a href="#work" class="nav__link">Work</a></li>
                        <li class="nav__item"><a href="#project" class="nav__link">Project</a></li>
                        <li class="nav__item"><a href="#contact" class="nav__link">Contact</a></li>
                    </ul>
                </div>

                <div class="nav__toggle" id="nav-toggle">
                    <i class='bx bx-menu'></i>
                </div>
            </nav>
        </header>

        <main class="l-main">
            <!--===== HOME =====-->
            <section class="home bd-grid" id="home">
                <div class="home__data">
                    <h1 class="home__title"><br> <span class="home__title-color" >Hermina Judith Chinnappan</span><br> </h1>
                    <span style="font-size: medium; row-gap: 2rem;">Master's in Project Management <br>The George Washington University</span>
                </div>

                <div class="home__social">
                    <a href="https://www.linkedin.com/in/hermina-judith-chinnappan" class="home__social-icon"><i class='bx bxl-linkedin'></i></a>
                    <a href="https://github.com/bhumika-1815" class="home__social-icon"><i class='bx bxl-github' ></i></a>
                </div>

                <div class="home__img">
                    <svg class="home__blob" viewBox="0 0 479 467" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
                        <mask id="mask0" mask-type="alpha">
                            <path d="M9.19024 145.964C34.0253 76.5814 114.865 54.7299 184.111 29.4823C245.804 6.98884 311.86 -14.9503 370.735 14.143C431.207 44.026 467.948 107.508 477.191 174.311C485.897 237.229 454.931 294.377 416.506 344.954C373.74 401.245 326.068 462.801 255.442 466.189C179.416 469.835 111.552 422.137 65.1576 361.805C17.4835 299.81 -17.1617 219.583 9.19024 145.964Z"/>
                        </mask>
                        <g mask="url(#mask0)">
                            <path d="M9.19024 145.964C34.0253 76.5814 114.865 54.7299 184.111 29.4823C245.804 6.98884 311.86 -14.9503 370.735 14.143C431.207 44.026 467.948 107.508 477.191 174.311C485.897 237.229 454.931 294.377 416.506 344.954C373.74 401.245 326.068 462.801 255.442 466.189C179.416 469.835 111.552 422.137 65.1576 361.805C17.4835 299.81 -17.1617 219.583 9.19024 145.964Z"/>
                            <image class="home__blob-img" x="-30" y="-320" href="assets/img/file2.png"/>
                        </g>
                    </svg>
                </div>
            </section>

            <!--===== ABOUT =====-->
            <section class="about section " id="about">
                <h2 class="section-title">About</h2>

                <div class="about__container bd-grid">
                    <div class="about__img">
                        <img src="assets/img/Bhu.JPG" alt="">
                    </div>
                    
                    <div>
                        <h2 class="about__subtitle">I'am Hermina,</h2>
                        <p class="about__text" style="text-align:justify;">Motivated Data Science graduate student with a strong quantitative background and excellent programming skills in Python. Experienced in data exploration, visualization, and analysis using libraries such as pandas, scikit-learn, pytorch, and TensorFlow. Proficient in developing state-of-the-art models, feature engineering, and executing model training cycles in cloud environments like AWS. Adept at creating benchmark statistics and implementing drift detection methodologies. Committed to innovation, integrity, and delivering customer-focused solutions..</p>           
                    </div>                                   
                </div>
            </section>

            <!--===== SKILLS =====-->
            <section class="skills section" id="skills">
                <h2 class="section-title">Technical Skills</h2>
            
                <div class="skills__container bd-grid">          
                    <div class="skills__data">
                        <div>
                            <span class="skills__names">LANGUAGES</span>
                            <p class="about__text">Python (Pandas, NumPy, Scikit-learn, OpenCV), R, SQL, Java (Spring Boot), HTML, JavaScript, CSS, TypeScript, .NET (C#)</p>       
                        </div>
                    </div>
                    <div class="skills__data">
                        <div>
                            <span class="skills__names">DATA ANALYSIS AND VISUALIZATION TOOLS</span>
                            <p class="about__text">Python (Jupyter), R (Tidyverse, RStudio), Tableau, Looker, Power BI, Excel</p>
                        </div> 
                    </div>
                    <div class="skills__data">
                        <div>
                            <span class="skills__names">DATABASE</span>
                            <p class="about__text">MySQL, MongoDB, Neo4j</p>
                        </div>
                    </div>
                    <div class="skills__data">
                        <div>
                            <span class="skills__names">DATA PLATFORMS</span>
                            <p class="about__text">Snowflake, SQL Server, Azure ML</p>
                        </div>
                    </div>
                    <div class="skills__data">
                        <div>
                            <span class="skills__names">MACHINE LEARNING FRAMEWORKS</span>
                            <p class="about__text">TensorFlow, XGBoost, Scikit-learn, Keras, Google Colab</p>
                        </div>
                    </div>
                    <div class="skills__data">
                        <div>
                            <span class="skills__names">MACHINE LEARNING TECHNIQUES</span>
                            <p class="about__text">Classification, Regression, Clustering, Natural Language Processing</p>
                        </div>
                    </div>
                    
                    <div class="skills__data">
                        <div>
                            <span class="skills__names">CLOUD TECHNIQUES</span>
                            <p class="about__text">AWS (S3, Hive, Athena, Glue, AWS Batch, Redshift, CloudWatch, RDS, Lambda), GCP</p>
                        </div>
                    </div>
                </div>
            </section>
            
            <!--===== WORK =====-->
            <!-- <section class="work section" id="work">
                <h2 class="section-title">Professional Experience</h2>
                <h2 class="work__subtitle">I'am Bhumika Mallikarjun Horapet</h2>
                        <p class="work__text" style="text-align:justify;">Motivated Data Science graduate student with a strong quantitative background and excellent programming skills in Python. Experienced in data exploration, visualization, and analysis using libraries such as pandas, scikit-learn, pytorch, and TensorFlow. Proficient in developing state-of-the-art models, feature engineering, and executing model training cycles in cloud environments like AWS. Adept at creating benchmark statistics and implementing drift detection methodologies. Committed to innovation, integrity, and delivering customer-focused solutions..</p>           
            </section> -->

            <section class="section" id="work">
                <h2 class="section-title">Professional Experience</h2>
              
                <div class="experience__container">
                  <div class="experience__item">
                    <div class="experience__title">DIGITAL SPECIALIST ENGINEER</div>
                    <div class="experience__company">INFOSYS, Bangalore, India | August 2022 - July 2023</div>
                    <ul class="experience__details" >
                      <li>Managed and maintained micro frontends within an Angular environment to enhance modularity and ease of maintenance across various internal projects.</li>
                      <li>Ensured seamless integration and communication between frontend and backend components.</li>
                      <li>Implemented innovative solutions to streamline both frontend and backend components, resulting in improved efficiency and performance of internal projects.</li>
                      <li>Boosted client data processing capabilities by developing .NET-based microservice generators.</li>
                      <li>Achieved a 25% increase in development speed specifically for banking services through these enhancements.</li>
                      <li>Spearheaded clear and effective communication strategies across cross-functional teams, including development, QA, and project management.</li>
                      <li>Employed Agile methodologies to ensure the timely and optimal implementation of technical solutions in large-scale software development projects.</li>
                      <span style="font-weight: bold;">Achievements</span>
                      <li>Facilitated substantial improvements in project delivery timelines by fostering effective communication and collaboration within cross-functional teams.</li>
                      <li>INSTA Award: Honored with the INSTA Award for exceptional contributions to the improvement and ramp-up of microservices modules and API Gateways.</li>
                    </ul>
                  </div>
              
                  <div class="experience__item">
                    <div class="experience__title">CLOUD COMPUTING INTERN</div>
                    <div class="experience__company">TECHNOLOGICS, Bangalore, India | August - December 2021</div>
                    <ul class="experience__details" style="text-align: justify;">
                      <li>Researched and analyzed Spotify's use of cloud computing technologies.</li>
                      <li>Created and delivered a comprehensive presentation of findings.</li>
                      <li>Identified optimization opportunities and collaborated with cross-functional teams to implement improvements.</li>
                      <li>Drove continuous improvement initiatives by implementing recommendations from the analysis.</li>
                      <li>Successfully communicated complex technical findings to diverse stakeholders.
                    </li>
                    </ul>
                  </div>
                </div>
              </section>


            <!-- PROJECT -->
             <!-- <section id="project">
            <h2 class="section-title">Project Experience</h2>
            <div class="work__container bd-grid">
                <a href="" class="work__img">
                    <img src="assets/img/work1.jpg">
                </a>
                <a href="" class="work__img">
                    <img src="assets/img/work2.jpg" alt="">
                </a>
                <a href="" class="work__img">
                    <img src="assets/img/work3.jpg" alt="">
                </a>
                <a href="" class="work__img">
                    <img src="assets/img/work4.jpg" alt="">
                </a>
                <a href="" class="work__img">
                    <img src="assets/img/work5.jpg" alt="">
                </a>
                <a href="" class="work__img">
                    <img src="assets/img/work6.jpg" alt="">
                </a>
            </div>
        </section> -->


        <section class="section" id="project">
            <h2 class="section-title">Project Experience</h2>
            <div class="work__container bd-grid">
              <div class="work__img">
               <a href="https://github.com/bhumika-1815/Bridging-the-Gap"><img src="assets/img/Housingimage.jpg"></a> 
                <div class="work__details">
                  <h3>Bridging the Gap: The Impact of Wages and Housing Markets on U.S. Financial Stability</h3>
                  <p>May 2024</p>
                  <ul>
                    <li>Conducted a comprehensive analysis of U.S. financial stability, focusing on wage policies, housing affordability, and economic resilience during recessions, utilizing datasets from the Federal Reserve Bank of St. Louis and advanced data visualization techniques in Tableau.
                    </li>
                    <br>
                  </ul>
                    <section class="contact" type="button">
                        <a href="https://github.com/bhumika-1815/Bridging-the-Gap" class="contact__button button" target="_blank"><span style="color: white;">GitHub</span></a>
                    </section>
                </div>
              </div>
              <div class="work__img">
               <a href="https://github.com/bhumika-1815/Human-Action-Recognition-CNN"><img src="assets/img/humanaction.webp"></a> 
                <div class="work__details">
                  <h3>Human Action Recognition using Convolution Neural Networks</h3>
                  <p>May 2024</p>
                  <ul>
                    <li>Engineered a Convolutional Neural Network (CNN) model using TensorFlow for Human Action Recognition, achieving 66.75% classification accuracy on 12,000 images by applying advanced data preprocessing techniques.</li>
                  </ul>
                  <section class="contact" type="button">
                    <a href="https://github.com/bhumika-1815/Human-Action-Recognition-CNN" class="contact__button button" target="_blank"><span style="color: white;">GitHub</span></a>
                </section>
                </div>
              </div>
              <div class="work__img">
                <a href="https://github.com/bhumika-1815/AWS-Youtube-Analytics-Pipeline"></a><img src="assets/img/aws.jpg" alt="">
                <div class="work__details">
                  <h3>AWS YouTube Video Analytics Pipeline</h3>
                  <p>April 2024</p>
                  <ul>
                    <li>Led the design and deployment of an end-to-end data processing and analytics pipeline on AWS, integrating services like S3, Glue, Lambda, Athena, and Quick Sight for comprehensive data management, transformation, and visualization, enhancing data-driven decision-making capabilities.</li>
                    <br>
                  </ul>
                  <section class="contact" type="button">
                    <a href="https://github.com/bhumika-1815/AWS-Youtube-Analytics-Pipeline" class="contact__button button" target="_blank"><span style="color: white;">GitHub</span></a>
                </section>
                </div>
              </div>
              <div class="work__img">
                <a href="https://github.com/bhumika-1815/Wine-Quality-Prediction-Project"></a><img src="assets/img/wine.jpg">
                <div class="work__details">
                  <h3>Wine Quality Prediction</h3>
                  <p>December 2023</p>
                  <ul>
                    <li>Developed R-based machine learning model to predict red and white wine quality ratings; applied exploratory data analysis (EDA), statistical tests, and advanced modeling techniques.</li>
                    <li>Produced comprehensive report summarizing data insights, modeling approach, results, and recommendations.</li>
                  </ul>
                  <section class="contact" type="button" style="position: absolute;"">
                    <a href="https://github.com/bhumika-1815/Wine-Quality-Prediction-Project" class="contact__button button" target="_blank"><span style="color: white;">GitHub</span></a>
                </section>
                </div>
              </div>
              <!-- <div class="work__img">
                <img src="assets/img/work5.jpg" alt="">
                <div class="work__details">
                  <h3>Vehicle Insurance Fraud Detection</h3>
                  <p>December 2023</p>
                  <ul>
                    <li>Built Python-based machine learning model to detect fraudulent insurance claims by analyzing prior patterns and client data; applied SMOTE oversampling, XGBoost classification, and SHAP value analysis.</li>
                    <li>Improved performance of model using machine learning techniques, data processing, and feature selection optimization to significantly decrease number of false positives and negatives.</li>
                  </ul>
                  <a href="https://github.com/yourgithubprofile/project5" target="_blank">GitHub Link</a>
                </div>
              </div> -->
            </div>
          </section>


        
            <!--===== CONTACT =====-->
            <section class="contact section" id="contact">
                <h2 class="section-title">Contact</h2>

                <div class="contact__container bd-grid">
                    <!-- <form action="" class="contact__form">
                        <input type="text" placeholder="Name" class="contact__input">
                        <input type="mail" placeholder="Email" class="contact__input">
                        <textarea name="" id="" cols="0" rows="10" class="contact__input"></textarea>
                        <input type="button" value="Enviar" class="contact__button button">
                    </form> -->
                    <h2 class="about__subtitle">Bhumika Mallikarjun Horapet</h2>
                    <p class="about__text" style="text-align:justify;">Email: bhumikahorpet@gmail.com</p> 
                    <p class="about__text" style="text-align:justify;">Arlington, Virginia - 22202</p>
                    <p class="about__text" style="text-align:justify;">Mobile: +1 (571) 547-9418</p>
                    <p class="about__text" style="text-align:justify;"><a href="https://www.linkedin.com/in/bhumikamh/">LinkedIn</a> | <a href="https://github.com/bhumika-1815">GitHub</a></p>      
                </div>
            </section>
        </main>

        <!--===== FOOTER =====-->
        <footer class="footer">
            <p class="footer__title"></p>
            <div class="footer__social">
            </div>
        </footer>


        <!--===== SCROLL REVEAL =====-->
        <script src="https://unpkg.com/scrollreveal"></script>

        <!--===== MAIN JS =====-->
        <script src="assets/js/main.js"></script>
    </body>
</html>
