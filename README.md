# Dom-assignment solution

Assignment 1

task1 output :


let menu = document.getElementById('menu');
menu.children[2].innerHTML = " <li><a href='./contact/contact.html'>Project</a></li>";

let li = document.createElement("li");
li.innerText="Hire Me";

let newNode = document.getElementById("menu");
newNode.appendChild(li);

task 2 

let p = document.querySelector('div.search-field input');

p.placeholder ="Search My Project";

let project = document.querySelector('header nav ul');

project = project.children[2].innerHTML="project";


task 3 

let p = document.querySelector('section.hero-section div.hero-left-section p');

p.innerHTML="<p>I am an aspiring <span>Full Stack JavaScript Developer</span><br/>who is currently working as <span>as an Employee</span> for <br/> <span> iNeuron intelligence Pvt Ltd . </span>  </p>";


task 4

let image = document.querySelector('div.hero-right-section img');
image.src = "https://hiteshchoudhary.com/static/a8d73d1aac4c79e9bb689640e6090367/2eaab/person-image.jpg";

task 5

let button = document.createElement('button');

button.innerText = "Support Me";

let place = document.querySelector("div.hero-right-section-btns");

place.appendChild(button);





Assignment 2

task 1

let emp = document.querySelectorAll('.accordian')[0];

emp= emp.children[1];

emp.remove();

console.log(emp.innerHTML);

let emp1 = document.querySelectorAll('.accordian')[1];

emp1= emp1.children[1];

emp1.remove();



task 2




let div = document.createElement('div');
div.className="accordian";

let add = document.querySelector('.accordian-wrapper');
add.appendChild(div);

let h3 = document.createElement('h3');
h3.innerText="skills";

div.appendChild(h3);


Asignment 3

document.getElementsByClassName('enterName')[0].placeholder='FSJS 2.0';



document.getElementsByClassName('enterMail')[0].placeholder="fsjs@ineuron.ai";


document.getElementsByClassName('enterMessage')[0].placeholder="Hello World";

document.getElementsByClassName('userName')[0].placeholder='FSJS 2.0';



document.getElementsByClassName('userEmail')[0].placeholder="fsjs@ineuron.ai";


document.getElementsByClassName('userMessage')[0].placeholder="Hello World";


