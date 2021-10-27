# css
<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8"/>
    <meta http-equiv="X-UA-Compatible" content="IE=edge"/>
    <meta name="viewport" content="width=device-width, initial-scale=1"/>
    <title>Resume With CSS</title>
    <link rel="stylesheet" href="styles.css"/>

 <!-- Awesome font -->
 <script src="https://kit.fontawesome.com/a508a51525.js" crossorigin="anonymous"></script>


</head>
    <body>

        <div class="box">
            <div class="header">
                <div class="left-header">
                    <div class="name"> 
                      <h1 class="first-name">Akshad</h1>
                      <h1 class="last-name">Shivale</h1> 
                    </div>
                     <div class="pic">
                        <img src="JPEG File (.jpeg)" width="100" height="110" hspace="" align="">
                     </div>
                </div>

                <div class="right-header">
                    <div class="address"> 
                        <p>Sanpada, Navi Mumbai, Maharashtra-400701</p>
                    <i class="fas fa-address-card"></i>
                    </div>

                    <div class="email"> 
                        <p>akshadshivale123@gmail.com</p>
                        <i class="fas fa-envelope"></i>
                    </div>
                    <div class="phone">
                        <p>+91-99-874-28741 </p>
                  <i class="fas fa-phone"></i>
                    </div>
                    <div class="git">
                        <p>https://github.com/AkshadS</p>
                        <i class="fab fa-github"></i>
                    </div>
                  


                </div>
            </div>
               <hr>
           <div class="Objective">
               <div class="obj-head grey">
                   <i class="fas fa-bullseye"></i>
                   <h2>Career Objective</h2>
               </div>
            <p>An engineering student seeking an entry level opportunity in an esteemed organization.<br>
            To Succeed in an environment of growth and excellence and earn a job which provides me job satisfaction and self development and help me achieve personal as well as organization goals.</p>
           </div>

           <div class="education">
               <div class="edu-head grey">
                   <i class="fas fa-book-open"></i>
                   <h2>Academic Qualification</h2>
               </div>

               <table> 
<tr>
    <th>Qualification</th>
    <th>Board/University</th>
    <th>School/College</th>
    <th>Year of passing</th>
    <th>Marks</th>
</tr>

<tr>
    <td>B.E</td>
    <td>Mumbai University</td>
    <td>Pillai College Of Engineering, New Panvel</td>
    <td>2023</td>
    <td>8.9 CGPA</td>
</tr>

<tr >
    <td>HSC</td>
    <td>Mharashtra State Board Of Secondary & Higher Secondary Education</td>
    <td>R.F. Tilak Junior College,Nerul, Navi Mumbai</td>
    <td>2019</td>
    <td>75 %</td>
</tr>

<tr >
    <td>SSC</td>
    <td>ICSE</td>
    <td>SDA School,Sanpada</td>
    <td>2017</td>
    <td>80%</td>
</tr>

    </table>
           </div>

           <div class="skills">
               <div class="skill-head grey">
                   <i class="fas fa-tools"></i>
                   <h2>Skills</h2>
               </div>
               <ul style="list-style-type:square">
                 <li>Python</li>
                 <li>C programming</li>
                 <li>HTML, CSS</li>
                 <li>Marketing</li>
               </ul>
           </div>
         
          <div class="location">
              <div class="loc-head grey">
                  <i class="fas fa-map-marker-alt"></i>
                  <h2>Location</h2>
              </div>
              <p><iframe src="https://www.google.com/maps/dir/19.0641035,73.0117015/Sector+3,+Sanpada,+Navi+Mumbai,+Maharashtra+400705/@19.0639948,73.0088348,18z/data=!3m1!4b1!4m10!4m9!1m1!4e1!1m5!1m1!1s0x3be7c144c0a10341:0xf61a10d145b79648!2m2!1d73.0087956!2d19.0651648!3e0" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy"></iframe></p>
          </div>
    </div> 

    </body>
  @import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@1,300&display=swap');

body {
	margin: 0;
	padding: 0;
	background: rgb(240, 239, 239);
	font-family: 'Poppins', sans-serif;
}

h1{
	margin: 0;
	font-weight: 400;
	font-size: 2.8rem;
}

h2{
	margin: 0;
	font-weight: 400;
	display: inline;
}

.box{
	background: #fff;
	width: 50rem;
	padding: 3rem;
	margin: 1rem auto;
	border-radius: 0.5rem;
}

.header{
	display: grid;
	grid-template-columns: 40% 60%;
}

.left-header{
	display: grid;
	justify-items: center;
	align-items: center;
	font-size: 2rem;
}

.first-name{
	font-weight: 400;
	margin: 0;
}

.last-name{
	font-weight: 200;
	margin: 0;
}

.pic {
	padding-top: 5px;
}

.right-header{
	width: 100%;
	display: grid;
	justify-items: end;
}

.right-header p{
 display: inline;
}

.icon{
	color: rgb(223, 223, 232);
	font-size: 1.5rem;
	margin-right: 0.5rem;
}

.grey{
	background: rgb(133, 133, 133);
	color: #fff;
	padding: 0.5rem;
	border-radius: 0.3rem;
}

table{
	border: 3px solid #000;
	margin: 1rem 0;
	width: 100%;
	text-align: center;
	border-collapse: collapse;
}

td,th{
	border: 1px solid #000;
	padding: 0.4rem;
}

</html>
