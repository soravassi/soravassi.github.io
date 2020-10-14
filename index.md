---
layout: default
---
# Welcome!
<script type="text/javascript" src="https://platform.linkedin.com/badges/js/profile.js" async defer></script>
<head>
    <style>
    {
        box-sizing: border-box;
    }
    /* Set additional styling options for the columns*/
    .column {
    float: left;
    width: 50%;
    display: inline-block;

    }

#content-desktop {display: block;}
#content-mobile {display: none;}

@media screen and (max-width: 768px) {

#content-desktop {display: none;}
#content-mobile {display: block;}

}

.float-container {
}

.float-child {
    width: 50%;
    float: left;
}  

        
.button {
  font-family : inherit;
  border: none;
  color: white;
  padding: 16px 32px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  margin: 4px 2px;
  transition-duration: 0.4s;
  cursor: pointer;
}
.button {
  background-color: #f2f2f2; 
  color: black; 
  border: 2px solid black;
}
.button:hover {
  background-color: #666666;
  color: white;
}
.header img {
  float: left;
  height: 50px;
  border: 0px
}
.header h2 {
  position: relative;
  top: 20px;
  left: 10px;
}
    .row:after {
    content: "";
    display: table;
    clear: both;
    }
    </style>
 </head>
 <body>

<div class="float-container">
  <div class="float-child">

    <div class="LI-profile-badge"  data-version="v1" data-size="medium" data-locale="en_US" data-type="horizontal" data-theme="light" data-vanity="andrescarmo"><a class="LI-simple-link" target = "_blank" href='https://br.linkedin.com/in/andrescarmo?trk=profile-badge'>André Soravassi do Carmo</a></div>
    </div>

 <div class="float-child">

   <p>Currently I work with Salesforce Development at BTG Pactual, the largest investment bank in Latin America.
I have also worked with Data Analysis and Business Intelligence using tools like Python and Power BI.
In this website I plan to post some of my personal projects.</p>
        </div>
  </div>
 

 </body>


<div class="header">
  <img src="pbi.png" alt="logo" />
  <h2>Power BI Dashboards</h2>
</div>
<br><br>
<a href="./seattle-crime.html" class="button">Seattle Crime Trends</a>
<a href="./covid-dashboard.html" class="button">Covid Dashboard</a>
<div class="header">
  <img src="sfdc.png" alt="logo" />
  <h2>Salesforce</h2>
</div>
<br><br>
<a href="https://trailblazer.me/id/soravassi" target="_blank" class="button">Trailhead Profile</a>
