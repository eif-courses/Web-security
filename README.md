## WEB APPLICATIONS SECURITY COURSE


```diff
- FALL SEMESTER ENDS 2016 NOVEMBER 25TH.  
+ EXAM DATE FOR ERASMUS 2016 11 28, CLASSROOM 311, 7.45 AM.

```


___
**EVALUATION** = HOMEWORK PROJECT (40%) + PRACTICAL TASKS (30%) + EXAM (30%). 

HERE YOU FIND YOUR TASK RESULTS: (https://vikolt-my.sharepoint.com/personal/m_gzegozevskis_ad_viko_lt/_layouts/15/guestaccess.aspx?guestaccesstoken=Ss%2fV1SI2K7L8UnimYN4n1Mgc2N6D3uy0kRAxsiCDm4U%3d&docid=0ef88d5256c2247439a1b62b5c610f973&rev=1).

___

For PHP SERVER IP ADRESS: http://10.1.16.81/shared

Edit files directory address: ``` \\MARIUS\shared```


Remote desktop server address: **192.168.10.24** or **192.168.10.25**. User credentials same for both servers you are already have.
___

**HOMEWORK PROJECT.** Create secure Web application using any programming language you are already known e.g. PHP, JAVA, .NET ASP, Python ect:
___
- Web application should have functionallity against <a href="https://www.toptal.com/security/10-most-common-web-security-vulnerabilities">top 10</a>  most common web security vulnerabilities.
- Web application should have implemented login page. All app data should store in database e.g. MySQL. Also you should implement basic CRUD (Create, Read, Update, Delete) operations.   
- Create few roles for users e.g. **Administrator** - have full control access, **Basic user** - have less access to web page functionalitty, **Guest** - only can browse home page.

____

####PRACTICAL TASKS
___
**Task 1** (10 points)
___
- Software already installed in computer classrooms if you using personal computers you can download from software section. 
- Using OWASP Zed Attack Proxy Project (ZAP tool) try to find vulnerable website in "URL to Attack" field enter URL address and press start scan. In alerts tab you see all risks which is marked as warnings, medium and high priority risks. If you find web page with high priority risks first lecture you get bonus **10 points** to your final evaluation. 
- Run A Windows Web development environment for Apache, MySQL, PHP databases and try to launch http://localhost:8888 in computer classrooms if it working try to find www/ directory and add new webpage named myFirstPage.php, open that file and add simple code line <?php echo 'hello world!!!' ?> if it works run your page in browser type: (http://localhost:8888/myFirstPage.php). 

___
**Task 2** (10 points)
___
- Configure Damn Vulnerable Web Application - (http://www.dvwa.co.uk/) and run in localhost using WAMP server. When you run it you need to configure security levels and change it to low, then find link XSS stored and try to create script which let you pop up window with text **hello world**.
- Later create script which redirect you to your page hack.php and display fake page with same design look login form like in DVWA program and store username and password information to your data source e.g. database or textfile. Also try to implement different script where you can display ads or run audio files. 

___
**Task 3** (10 points)
___
- CAPTCHA (Completely Automated Public Turing
test to tell Computers and Humans Apart) – A CAPTCHA is a program that protects websites against bots by generating and grading tests that humans can pass but current computer programs cannot.
- Create your own unique CAPTCHA test which should have those components: picture, text, digit, quiz ect.   

___
**Task 4** (10 points)
___

- Download WGET tool (http://gnuwin32.sourceforge.net/packages/wget.htm) and first read help or documentation.
- Using Windows operating system run command prompt add your wget tool bin directory path using command e.g. **cd "C:\Program Files (x86)\GnuWin32\bin"**.  
- Run wget tool on command prompt call **wget.exe --help** read instructions and try to do some tasks. 
- Download any webpage source code using WGET tool. Finally write to text document summary what you learn to do using this tool.  

___
**Task 5** (10 points)
___

- Create **myFunction.php** then create own unique function which secure against XSS attacks (do not use default libraries functions e.g. htmlentities()). 
- You should think how to ignore special characters in input fields, also you should implement data validation function.
- When you prepeare to show your created unique function you should have some prepeared testing data for your myFunction.php input fields.

___
**Extra task** (10 points)
___
Install Wireshark packet sniffer program (https://www.wireshark.org/download.html). Try to get some sensitive data from different computer in your network e.g. e-mail message, login username and password, pictures ect. 
___

**EXAM**
- Quiz from top 10 OWASP (Open Web Application Security Project) vulnerabilities.

**SOFTWARE**
- A Windows Web development environment for Apache, MySQL, PHP databases (WAMP server). (https://sourceforge.net/projects/wampserver/files/latest/download).
- Damn Vulnerable Web Application - (http://www.dvwa.co.uk/).
- OWASP Zed Attack Proxy Project - (https://github.com/zaproxy/zaproxy/wiki/Downloads).
- WGET - (http://gnuwin32.sourceforge.net/packages/wget.htm).
- WIRESHARK - (https://www.wireshark.org/download.html).

**LECTURE NOTES**
- Web application security - (https://github.com/fontpoint/Security/tree/master/EN).

**LITERATURE**

- Best place for beginners learn php, xml, html, JS, SQL - (http://www.w3schools.com/php/default.asp).  
- The Web Application Hacker's Handbook: Finding and Exploiting Security Flaws 2nd Edition by Dafydd Stuttard, Marcus ISBN-13: 860-1404288999
- Official PHP manual - (http://php.net/manual/en/).
- Open Web Application Security Project - (https://www.owasp.org/index.php/Main_Page).
