# WEB APPLICATION SECURITY

### EVALUATION
<ul>
<li>FINAL EVALUATION = HOMEWORK PROJECT (40%) + PRACTICAL TASKS (30%) + EXAM (30%). </li>
</ul>

### HOMEWORK PROJECT
Main goals:
- Create secure Web application using any programming language you are already known e.g. PHP, JAVA, ASP ect.
- Web application should have functionallity against top 10 most common web security vulnerabilities. (https://www.toptal.com/security/10-most-common-web-security-vulnerabilities). 
- Create login page all data should save to database e.g. MySQL. Also you should implement one web page with basic CRUD (Create, Read, Update, Delete) operations.   
- Create roles for users e.g. Administrator - have full control access, Basic user - have less access to web page functionalitty, Guest - only can see home page.    

### PRACTICAL TASKS
___
### 1 TASK (10 points)
___
- Software already installed in computer classrooms if you using personal computers you can download from software section. 
- Using OWASP Zed Attack Proxy Project (ZAP tool) try to find vulnerable website in "URL to Attack" field enter URL address and press start scan. In alerts tab you see all risks which is marked as warnings, medium and high priority risks. If you find web page with high priority risks first lecture you get bonus <strong>10 </strong>point to your final evaluation. 
- Run A Windows Web development environment for Apache, MySQL, PHP databases and try to launch http://localhost:8888 if it working try to find wwww/ directory and add new webpage named myFirstPage.php, open that file and add simple code line <?php echo 'hello world!!!' ?> if everythis is fine and browser open your web page with text hello world !!! then you are ready to do next tasks.   

___
### 2 TASK (10 points)
___
- Configure Damn Vulnerable Web Application - (http://www.dvwa.co.uk/) and run in localhost like you do it on 1 task run your firstpage. When you run it you need to configure security levels and change to low, then find link XSS stored and try to create script which let you pop up window with text hello world.
- Create script which store username amd password information, redirect to anypage, shows up advertisments, play video or audio sounds.

___
### 3 TASK (10 points)
___

- CAPTCHA (Completely Automated Public Turing
test to tell Computers and Humans Apart) – A CAPTCHA is a program that protects websites against bots by generating and grading tests that humans can pass but current computer programs cannot.
- Create your own unique CAPTCHA test which should have those components: picture, text, digit, quiz ect.   

___
### 4 TASK (10 points)
___

- Download WGET tool (http://gnuwin32.sourceforge.net/packages/wget.htm) and first read help or documentation.
- Using Windows operating system run command prompt add your wget tool path to installed wget bin directory cd "C:\Program Files (x86)\GnuWin32\bin".  
- Try to run wget tool enter command cd "C:\Program Files (x86)\GnuWin32\bin"
wget.exe --help read instructions and try to do some tasks. 
- Download any webpage source code using WGET tool. Finally write to text document summary what you learn to do using this tool.  

___
### 5 TASK (10 points)
___

- Create myFunction.php then create own unique function which secure against XSS attacks (do no use default libraries functions e.g. htmlentities()). 
- You should think how to ignore special characters in input fields, also your should implement data validation function.
- When you prepeare to show your created unique function you should have some prepeared testing data for your myFunction.php input fields.

___
### EXAM
- Quiz from top 10 OWASP (Open Web Application Security Project) vulnerabilities.

### SOFTWARE
- A Windows Web development environment for Apache, MySQL, PHP databases. (https://sourceforge.net/projects/wampserver/files/latest/download).
- Damn Vulnerable Web Application - (http://www.dvwa.co.uk/).
- OWASP Zed Attack Proxy Project - (https://github.com/zaproxy/zaproxy/wiki/Downloads).
- WGET - (http://gnuwin32.sourceforge.net/packages/wget.htm).

### LECTURE NOTES
- Web application security - (https://github.com/fontpoint/security/tree/master/lecture%20notes).

### LITERATURE

- Best place for beginners learn php, xml, html, JS, SQL - (http://www.w3schools.com/php/default.asp).  
- The Web Application Hacker's Handbook: Finding and Exploiting Security Flaws 2nd Edition by Dafydd Stuttard, Marcus ISBN-13: 860-1404288999
