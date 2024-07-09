### <b>Instructions</b>
## setup-
<ol>
<li> Download the Archieve file and extract the folder using tools like WinRar </li>
<li> Open The Root folder of the Project in IDE like VS code </li>
<li> Download Extensions of Php,Laravel to run the Project </li>
<li> Use Command line tool of Laravel "artisan" to perform inbuilt tasks and configurations </li>
<li> Now for Accessing database open Server side tools like xampp and Start it(turn on 'apache' and 'mysql modules') </li>
<li> open a new database named "laravel_samples" in database section on Xampp. </li>
<li> now come back to IDE and type "php artisan migrate" or "php artisan migrate:refresh" to migrate dependecy. </li>
<li> wait for it and when everything loads up. </li>
<li> Type "php artisan serve" to run the Project. </li>
</ol>
(P.S-if any issues check database is connected correctly and do "composer install" on cmd prompt once so that all necessary are installed )
 
<h2> <b>Pages</h2>

<h3> Homepage</h3>
 <p>Contains Navigation bar and notification about user login status</p>
<h3>  Login</h3>
 <p>Contains Login Form , 3 Fields </p>
 <ul><P>Inputs:</P>
  <li>UserName</li>
  <li>UserPass</li>
  <li>Human Verification</li>  
 </ul>
<h3> Register</h3>
 <p>Contains Registration Form with 7 Fields</p>
  <ul><P>Inputs:</P>
  <li>UserName</li>
  <li>UserPass</li>
  <li>ConfirmPass</li>
  <li>UserMail</li>
  <li>UserGender</li>
  <li>UserDOB</li>
  <li>UserPhone</li>  
 </ul>
<h3> Profile </h3>
 <p>Contains User Information Like Name,MailId,Phone Number,etc...</p>

<h2> Functions </h2>
<h3>Unique Code</h3>
 It's a 17 Letter Code
<ul>
 <li><b>First 3 letters</b> are "UID" e.g. UID**************</li>
 <li><b> 4th to 11th letters</b> are  Date of Creation <b>Format</b> :  ddmmyyyy , e.g. "09072024"</li>
 <li><b>12th to 17th letters</b> are Time of Creation <b>Format</b> :hhiimm , e.g.  "144555"</li>
 <li>Final Generated code will be like e.g. <b>UID09072024144555</b></li>
</ul>
in which  are 
then from letters are Date of Creation 
<b>Format</b> :  ddmmyyyy , e.g. 09072024
<h5>Snapshot</h5>
<div>
 <img src="assets/Auth_snapshot (7).png" />
</div>

### SnapShots

<img src="assets/Auth_snapshot (1).png" />
<img src="assets/Auth_snapshot (2).png" />
<img src="assets/Auth_snapshot (3).png" />
<img src="assets/Auth_snapshot (4).png" />
<img src="assets/Auth_snapshot (5).png" />
<img src="assets/Auth_snapshot (6).png" />

