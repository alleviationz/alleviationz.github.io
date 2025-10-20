# Software Engineering

# Full-stack Development

# Narrative:
The artifact was a full-stack application that uses an SPA for the admin side application and a traditional Express routing API for the regular front-end users. It was created around June of 2025. I chose this artifact because it was an expansive topic with lots of room for improvement. I enjoy the full-stack path, but getting back into it was definitely difficult after such a long break. The main enhancements I made to this artifact were the inclusion of a registration form and the refactoring of it to use more secure validators. I also refactored the login form and some of the HTML files into Handlebars partials. The password portion of the login and registration included a simple alphanumeric regex with character limits. I included null validators for other values.

This shows my ability to rework code into more dynamic standards, use common frameworks like the Validators module, and think about the security of the features I implement. There are several other areas I would have liked to improve on, such as MFA inclusion and more robust testing, but I did not have enough time. A lot of the learning came from revisiting the vast majority of code and topics that were quickly created with bootstrapping and other variously guided tools during this process. It helped to solidify some of the knowledge I had learned before. I also clarified some topics that I previously thought I understood, like the difference between the API and the routers used. Additionally, I learned how Validators worked and the various attribute bindings and error catching you can use in Angular.

# Purpose:
The main purpose of this enhancement was to add some registration functionality for admin users. In a production setting, MFA is absolutely necessary for admin permissions.
The use of validators displays a security mindset that prioritizes good frameworks over the pride of trying to create and use complex regexes myself. Some files were also cleaned up and
CSS files were deleted to pull from one main css style.

# Registration function 
<img width="948" height="494" alt="image" src="https://github.com/user-attachments/assets/c1febe59-ad88-4388-9189-68c713f7b810" />
<img width="1476" height="646" alt="image" src="https://github.com/user-attachments/assets/5a5e54b4-6a7f-4501-8e22-34d3cee254de" />


# Registration HMTL form using Angular's Form Control
<img width="765" height="621" alt="image" src="https://github.com/user-attachments/assets/cad273fa-a24e-4162-82ca-566626c403f9" />
<img width="1917" height="622" alt="image" src="https://github.com/user-attachments/assets/b3d6345f-f963-42c1-9809-8bea48216259" />


# Auth API registration call
<img width="900" height="375" alt="image" src="https://github.com/user-attachments/assets/0d1dae6f-3c24-4458-80d2-18c9e3a9c143" />

# Postman test

<img width="880" height="553" alt="image" src="https://github.com/user-attachments/assets/4db34660-4ac1-4a63-829a-f9f99a8cb11d" />

# Mongo Result from Registration Call
<img width="1081" height="180" alt="image" src="https://github.com/user-attachments/assets/aaefe358-7f05-4bd8-9556-aa13c8f909d8" />

#Full Project repo
<a href="https://github.com/alleviationz/CS-465-Fullstack_Development">Full Project</a>
