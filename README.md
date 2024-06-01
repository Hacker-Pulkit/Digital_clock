**Circular Analog Clock
This project is a circular analog clock built using HTML, CSS, and JavaScript. 
It displays the current time with animated circular indicators for hours, minutes, and seconds, as well as a digital display with an AM/PM indicator.

Table of Contents
 1.Installation
 2.Usage
 3.Project Structure
 4.Customization
 5.Contributing
 6.License

 
A. Installation
 1.Clone the repository: git clone https://github.com/yourusername/circular-analog-clock.git
 2.Navigate to the project directory: cd circular-analog-clock

B. Usage
1.Open index.html in your preferred web browser. This can be done by double-clicking the file or opening it through your browser's file menu.
2.The clock will start running automatically and display the current time with animated circular indicators for hours, minutes, and seconds.

C. Project Structure
circular-analog-clock/
├── index.html
├── styles.css
└── script.js
1.index.html: The main HTML file that contains the structure of the clock.
2.styles.css: The CSS file that styles the clock and its components.
3.script.js: The JavaScript file that controls the clock's functionality and animations.

D. Customization
1.Colors
Each circle's color can be customized by modifying the --color variable in the inline style attribute of each .circle div in the index.html file.
      <div class="circle" style="--color: #ff2972"> <!-- Hours circle -->
      <div class="circle" style="--color: #fee800"> <!-- Minutes circle -->
      <div class="circle" style="--color: #04fc43"> <!-- Seconds circle -->
2.Font
The font can be changed by modifying the @import URL in the styles.css file.
      @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@100;300;400;500;600;700;800;900&display=swap');
3.Size
The size of the circles can be adjusted by changing the width and height properties in the .circle class in the styles.css file.
     #time .circle {
              width: 150px;
              height: 150px;
                 }

E. Contributing
Contributions are welcome! Please open an issue or submit a pull request if you have any suggestions or improvements.                 
 a.Fork the repository.
 b.Create a new branch (git checkout -b feature-branch).
 c.Make your changes.
 d.Commit your changes (git commit -m 'Add some feature').
 e.Push to the branch (git push origin feature-branch).
 f.Open a pull request.
 
F.License
This project is licensed under the MIT License. See the LICENSE file for details.

