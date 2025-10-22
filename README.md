A MULTIPAGE APPLICATION
I created a semantic, accessible, and responsive multi-page website built with plain HTML, CSS, and vanilla JavaScript.
It includes an home page, a Contact Us page with form validation and an About Me page for reflection — all styled consistently and keyboard accessible.

1.The first page is the Homepage which consist of the profile picture, the name and the profession of the individual.
--On the homepage, there are three links on top namely; home, about me, contact us, respectively, which helps to navigate freely among the pages.
2.The Contact Us page contains a form including your name, email subject and message which requires validation and is keyboard accessible.
--The email address must be entered correctly and must be valid or it will return error. And the message must have atleast 10 characters.
--On successful submission of the form, a confirmation message is displayed.
--In case of invalid, empty or incorrect entery, error messages appear directly under the input blocks.
3.The About me page contains Bio, Goals in this program, Areas of low confidence, Note to future self and Extra thoughts, where you can know more about the individual.
--It is fully responsive and readable on all screen sizes.

All visible elements include the 'data-testid' attribute for automated testing.
 Page    | Field           | data-testid                
         |                 |                     
 Contact | Full Name       | test-contact-name         
 Contact | Email           | test-contact-email         
 Contact | Subject         | test-contact-subject       
 Contact | Message         | test-contact-message       
 Contact | Submit Button   | test-contact-submit        
 Contact | Error Messages  | test-contact-error-<field> 
 Contact | Success Message | test-contact-success       
 About   | Bio             | test-about-bio             
 About   | Goals           | test-about-goals           
 About   | Confidence      | test-about-confidence      
 About   | Future Note     | test-about-future-note     
 About   | Extra Thoughts  | test-about-extra 

 HOW TO RUN IT
-Clone or download this folder.
  (git clone https://github.com/ayodejioluwadabira-tech/multi-page-site.git)
-Open the folder in your code editor or file explorer.
-Double-click index.html — it opens in your browser.
-Use the navbar links to move between pages:
  (Home → About Me → Contact Us)
-Try filling out the Contact Us form to test validation and success messages.
