# resume
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content=""IE=edge">
    <meta name="viewport" content="Width=device-Width, initial-scale=1.0" />
    <title>Responsive Resume Website</title>
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="container">
      <div class="header">
        <div class="img-area">
          <img src="NDGSiri@.jpg" alt="" />
        </div>
        <h1>Sirisha Yakkala</h1>
        <h3>Data Analytist</h3>
      </div>

      <div class="main">
        <div class=""left">
        <h2>personal Information</h2>
        <p><strong>Name:</strong> Sirisha Yakkala</p>
        <br />
        <p><strong>Email:</strong>siriyakkala0504@gmail.com</p>
        <br />
        <p><strong>phno:</strong>7842210769</p>
        <br />
        <p>
          <strong>Linkedin profile:</strong
          >Linkedin.com/in/sirisha-yakkala-20267727a
        </p>
        <br />
        <h2>Skills</h2>
        <ul>
          <li>c,java,python</li>
          <br />
          <li>Html,css</li>
          <br />
          <li>Javascript</li>
          <br />
          <li>ML,AI</li>
          <br />
        </ul>
        <h2>Education</h2>
        <h3>
          B-Tech computer science with Artificial Intelligence and Machine
          Learning
        </h3>
        <br />
        <p>
          ISTS WOMENS ENGINEERING COLLEGE,RAJANAGARAM,RAJAMUNDRY,ANDHRA PRADESH
        </p>
        <br />
        <h3>INTERMEDIATE</h3>
        <br />
        <p>ADITYA JUNIOR COLLEGE,MANDAPETA,ANDHRA PRADESH</p>
        <br />
        <h3>SSC</h3>
        <br />
        <p>(ZPGH school),MANDAPETA,ANDHRA PRADESH</p>
        <br />
      </div>

      <div class="right">
        <h1>Cetifications</h1>
        <h3>AWS cioud Practitioner (2022-present)</h3>
        <h3>JAVA Oracle Certification</h3>
        <h3>SQL Certification,Python certification</h3>
        <h3>Wadwani employability skills Certification</h3>
        <h3>Z-SCALAR virtual intenship certification</h3>

        <h1>Internships</h1>
        <h3>Z-SCALAR virtual intenship</h3>
        <h3>AICTE Govt Internship Attend offline</h3>
      </div>
    </div>
  </body>
</html>
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  font-family: montserrat;
}
body {
  background-color: #00b6c4;
}
.container {
  background: #f5f5f5;
  max-width: 800px;
  margin: 60px auto;
  height: 125px;
  padding: 20px;
  box-shadow: 0 2px 20px rgba(0, 0, 0, 0.3);
}
.header {
  text-align: center;
}
.header h1 {
  margin-bottom: 10px;
}
.header h3 {
  text-transform: uppercase;
  font-size: 15px;
  font-weight: 500;
}
.img-area {
  width: 200px;
  height: 200px;
  border-radius: 50%;
  overflow: hidden;
  margin: 25px auto;
  border: 15px groove deepskyblue;
}
.img-area img {
  width: 100%;
}
.main {
  display: flex;
  flex-wrap: wrap;
}
.left {
  flex: 1;
  padding: 30px;
}
.left p {
  line-height: 2;
}
.left ul li {
  line-height: 2;
}
h2 {
  background: #00b6c4;
  padding: 15px;
  color: #fff;
  margin: 30px 0;
  font-size: 20px;
  border-radius: 0 50px 50px 0;
}
.right {
  flex: 1;
  padding: 30px;
}
.right h3 {
  margin-bottom: 15px;
}
.right p {
  line-height: 2.9;
}
.right ul li {
  line-height: 2;
}

@media only screen and (min-width: 768px) and (max-width: 991px) {
  .container {
    width: 95%;
    height: auto;
  }
  h2 {
    font-size: 18px;
  }
}
@media screen and (max-width: 600px) {
  .main {
    flex-direction: column;
  }
  .left,
  .right {
    flex: none;
    width: 100%;
  }
  .container {
    width: 95%;
    height: auto;
  }
  h2 {
    font-size: 15px;
  }
}
