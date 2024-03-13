
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Profile</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <div class="main-l">
        <nav class="navbar navbar-expand-lg navbar-light bg-light">
            <div class="container-fluid">
                <a class="navbar-brand" href="#"></a>
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse"
                    data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false"
                    aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse nav-div" id="navbarNavAltMarkup">
                    <img src="./EX-1/images/me.png" alt="dp" class="dp">
                    <ul class="navbar-nav flex-column nav-lists">
                        <!-- Inserting your content -->
                        <li class="nav-item">
                            <a href="#about" id="nav-link">About</a>
                        </li>
                        <li class="nav-item">
                            <a href="#edu" id="nav-link">Educational Details</a>
                        </li>
                        <li class="nav-item">
                            <a href="#" id="nav-link">Technical Skills</a>
                        </li>
                        <li class="nav-item">
                            <a href="#" id="nav-link">Co-Curriculum</a>
                        </li>
                        <li class="nav-item">
                            <a href="#" id="nav-link">Contact</a>
                        </li>
                        <!-- End of inserted content -->
                </div>
            </div>
        </nav>
    </div>
    <!-- <iframe src="./EX-1/resume.html" frameborder="0"></iframe> -->
    <!-- content main -->
    <section id="main-r">
        <!-- about-section -->
        <div id="about">
            <p class="name">Giridharan S</p>
            <p class="place">Native<br><span class="pla">Dharmapuri</span></p>
            <p class="langs">Known Languages<br><span class="lang">English, Tamil</span></p>
        </div>
        <!-- education-section -->
        <div id="edu">
            <table bgcolor="#eee" border="5" cellspacing="3" cellpadding="5" style="margin-left: 20px; text-align: center;">

                <tr>
                    <th>Name of the degree</th>
                    <th>Name of the Institution</th>
                    <th>Year of passing</th>
                    <th>Percentage/CGPA</th>
                </tr>
                <tr>
                    <td>B.tech IT</td>
                    <td>Kongu Engineering College</td>
                    <td>2026(Excepted)</td>
                    <td>8.08</td>
                </tr>
                <tr>
                    <td>HSC</td>
                    <td>Marutham Matric Higher Secondary School</td>
                    <td>2022</td>
                    <td>89%</td>
                </tr>
                <tr>
                    <td>SSLC</td>
                    <td>Marutham Matric Higher Secondary School</td>
                    <td>2020</td>
                    <td>97%</td>
                </tr>
            </table>
        </div>
        <div id="area">
            <h3>Area of Interest</h3>
            <ul>
                <li class="ar-in">dbms</li>
                <li class="ar-in">java</li>
                <li class="ar-in">os</li>
            </ul>
            <h3>Programming Languages Known</h3>
            <ul>
                <li class="pro-lan">c</li>
                <li class="pro-lan">c++</li>
                <li class="pro-lan">python</li>
                <li class="pro-lan">java</li>
            </ul>
            <h3>area of specialization</h3>
            <ul>
                <li class="spec">UI/UX Design</li>
                <li class="spec">Front-End Development</li>
            </ul>
        </div>
        <div id="co-cur">
            <h3>Industrial Collaboration</h3>
            <table border="2">
                <tr>
                    <th>Type</th>
                    <th>Company</th>
                    <th>Year</th>
                    <th>Domain</th>
                </tr>
                <tr>
                    <td>Implant Training</td>
                    <td>Ratix Info Tech</td>
                    <td>2024</td>
                    <td>UI/UX Design</td>
                </tr>
                <tr>
                    <td>Industrial Visit	</td>
                    <td>Atees Info Tech</td>
                    <td>2023</td>
                    <td>Web Development</td>
                </tr>
                <tr>
                    <td>Implant Training</td>
                    <td>Ratix Info Tech</td>
                    <td>2023</td>
                    <td>Web Development</td>
                </tr>
            </table>
        </div>
    </section>
</body>

</html>
