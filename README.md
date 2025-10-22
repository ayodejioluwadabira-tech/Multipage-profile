A MULTIPAGE APPLICATION<br>
I created a semantic, accessible, and responsive multi-page website built with plain HTML, CSS, and vanilla JavaScript.<br>
It includes an home page, a Contact Us page with form validation and an About Me page for reflection — all styled consistently and keyboard accessible.<br>
<br>
1.The first page is the Homepage which consist of the profile picture, the name and the profession of the individual.<br>
--On the homepage, there are three links on top namely; home, about me, contact us, respectively, which helps to navigate freely among the pages.<br>
2.The Contact Us page contains a form including your name, email subject and message which requires validation and is keyboard accessible.<br>
--The email address must be entered correctly and must be valid or it will return error. And the message must have atleast 10 characters.<br>
--On successful submission of the form, a confirmation message is displayed.<br>
--In case of invalid, empty or incorrect entery, error messages appear directly under the input blocks.<br>
3.The About me page contains Bio, Goals in this program, Areas of low confidence, Note to future self and Extra thoughts, where you can know more about the individual.<br>
--It is fully responsive and readable on all screen sizes.<br>
<br>
All visible elements include the 'data-testid' attribute for automated testing.<br>
 Page    | Field           | data-testid   <br>             
         |                 |                 <br>    
 Contact | Full Name       | test-contact-name  <br>       
 Contact | Email           | test-contact-email   <br>      
 Contact | Subject         | test-contact-subject  <br>     
 Contact | Message         | test-contact-message     <br>  
 Contact | Submit Button   | test-contact-submit      <br>  
 Contact | Error Messages  | test-contact-error-<field> <br>
 Contact | Success Message | test-contact-success   <br>    
 About   | Bio             | test-about-bio       <br>      
 About   | Goals           | test-about-goals      <br>     
 About   | Confidence      | test-about-confidence  <br>    
 About   | Future Note     | test-about-future-note <br>    
 About   | Extra Thoughts  | test-about-extra <br>
<br>
 HOW TO RUN IT<br>
-Clone or download this folder:<br>
  (git clone https://github.com/ayodejioluwadabira-tech/multi-page-site.git)<br>
-Open the folder in your code editor or file explorer.<br>
-Double-click index.html — it opens in your browser.<br>
-Use the navbar links to move between pages:<br>
  (Home → About Me → Contact Us)<br>
-Try filling out the Contact Us form to test validation and success messages.<br>
