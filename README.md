# user-info
<h2 align="left">Hi 👋! My name is Apoorv</h2>

###

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=maurodesouza&hide_title=false&hide_rank=false&show_icons=true&include_all_commits=true&count_private=true&disable_animations=false&theme=dracula&locale=en&hide_border=false" height="150" alt="stats graph"  />
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=maurodesouza&locale=en&hide_title=false&layout=compact&card_width=320&langs_count=5&theme=dracula&hide_border=false" height="150" alt="languages graph"  />
</div>

###

<img align="right" height="150" src="https://i.imgflip.com/65efzo.gif"  />

###

<div align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="30" alt="javascript logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" height="30" alt="typescript logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" height="30" alt="react logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" height="30" alt="html5 logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" height="30" alt="css3 logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="30" alt="python logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/csharp/csharp-original.svg" height="30" alt="csharp logo"  />
</div>

###

<div align="left">
  <img src="https://img.shields.io/static/v1?message=Youtube&logo=youtube&label=&color=FF0000&logoColor=white&labelColor=&style=for-the-badge" height="35" alt="youtube logo"  />
  <img src="https://img.shields.io/static/v1?message=Instagram&logo=instagram&label=&color=E4405F&logoColor=white&labelColor=&style=for-the-badge" height="35" alt="instagram logo"  />
  <img src="https://img.shields.io/static/v1?message=Twitch&logo=twitch&label=&color=9146FF&logoColor=white&labelColor=&style=for-the-badge" height="35" alt="twitch logo"  />
  <img src="https://img.shields.io/static/v1?message=Discord&logo=discord&label=&color=7289DA&logoColor=white&labelColor=&style=for-the-badge" height="35" alt="discord logo"  />
  <img src="https://img.shields.io/static/v1?message=Gmail&logo=gmail&label=&color=D14836&logoColor=white&labelColor=&style=for-the-badge" height="35" alt="gmail logo"  />
  <img src="https://img.shields.io/static/v1?message=LinkedIn&logo=linkedin&label=&color=0077B5&logoColor=white&labelColor=&style=for-the-badge" height="35" alt="linkedin logo"  />
</div>

###

<br clear="both">

<img src="https://raw.githubusercontent.com/maurodesouza/maurodesouza/output/snake.svg" alt="Snake animation" />

###

# Adding information in card
const mainContainer = document.getElementById("mainContainer"); This line gets the DOM element with the id "mainContainer" and assigns it to the variable mainContainer. This element likely corresponds to a container in your HTML. const frame = document.getElementById("frame"); Similarly, this line gets the DOM element with the id "frame" and assigns it to the variable frame. This element is likely a frame or container for displaying user information. function UserDetail(){ ... } This is a function named UserDetail which appears to be responsible for collecting user input, storing it in local storage, and updating the UI with the provided information.

Inside UserDetail: The function prompts the user to enter various pieces of information such as first name, last name, country, etc. Each piece of information is stored in local storage using localStorage.setItem("key", "value"). For example, localStorage.setItem("name", Fname) stores the value of Fname (First Name) with the key "name" in local storage. The next part updates the HTML content inside the frame element with user information. It uses template literals (backticks ``) for creating a multi-line string with placeholders. Inside this string, you have placeholders like Tejas which suggests that there are elements in the HTML with IDs like "name", "lname", etc. These will be used to display the user's information.

After updating the HTML content, the function retrieves the elements with these IDs (e.g., const name = document.getElementById("name")) and sets their innerText to the corresponding values from local storage.

Finally, the frame element (with updated content) is appended to the mainContainer element.

document.addEventListener('DOMContentLoaded', function() { ... });

This event listener waits for the DOM content to be fully loaded before executing the provided function. It's used to ensure that the JavaScript doesn't run until the HTML has been completely parsed and is ready to be interacted with. const darkModeToggle = document.getElementById('darkModeToggle');

This line gets the DOM element with the id "darkModeToggle" and assigns it to the variable darkModeToggle. This element is likely a checkbox or toggle switch used for enabling or disabling dark mode. darkModeToggle.addEventListener('change', function() { ... });

This adds an event listener to the darkModeToggle element. It listens for a change in the element's state (e.g., when a checkbox is checked or unchecked). Inside the event listener:

document.body.classList.toggle('dark-mode'); toggles the class "dark-mode" on the body element. This is a common technique used to switch between dark and light mode styles.

