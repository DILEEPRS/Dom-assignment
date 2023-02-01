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





