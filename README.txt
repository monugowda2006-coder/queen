BCA STUDENT PORTFOLIO WEBSITE
=============================

FILES
-----
index.html  - Page content and sections
style.css   - Colors, layout, responsive design
script.js   - Mobile menu, current year, contact email demo
assets/     - Put your profile image or other assets here

HOW TO OPEN
-----------
1. Extract BCA_Portfolio_Website.zip to a folder.
2. Open the extracted folder in Visual Studio Code.
3. Open index.html.
4. Right-click inside index.html and choose "Open with Live Server" if Live Server is installed.
   OR double-click index.html in File Explorer to open it in your browser.

HOW TO CUSTOMIZE
----------------
1. In index.html, change the name, college name, current year, education and project details.
2. The profile circle currently displays "P". To use a photo, copy your image into assets and name it profile.jpg.
   Then replace:
       <div class="profile-placeholder" aria-label="Profile image placeholder">P</div>
   with:
       <img class="profile-photo" src="assets/profile.jpg" alt="Prakruthi">
   Add this CSS to style.css:
       .profile-photo { width:150px; height:150px; object-fit:cover; border-radius:50%; border:7px solid white; margin:0 auto 22px; display:block; }
3. Replace your-email@example.com in script.js with your own email address.
   The form opens the visitor's email app; it does not store messages in a database.
4. For the resume button, put your resume PDF beside index.html and name it resume.pdf.
5. Update project cards to describe your real completed work.

NOTE
----
This is a static website. It does not need Node.js or MongoDB to run.
The Google Fonts import requires internet access; the website otherwise works with fallback fonts.
