PART 1
Question 1 pt1
var image = document.body.querySelector('.profile-image');
var image.src = 'https://placebear.com/400/400';

Question 1 pt2
var left = document.body.querySelector('#left-image');
var clouds = left.querySelector('img');
clouds.src = 'https://placebear.com/325/225';

Question 2
var bio_name = document.body.querySelector("ul > li > .bio-info-name");
bio_name.textContent = 'Tyler The Bear';

Question 3
var employment = document.body.querySelector('section > div > .info-outter-container > #employment > .info-title');
employment.textContent = Employers;

Question 4
var body = document.body;
body.style.backgroundColor = 'blue';

Question 5
var highlight = document.body.querySelectorAll('.highlight');
for (var index = 0; index < highlight.length; index++) { highlight[index].style.color = 'red'};

Question 6
var h1 = document.body.querySelector('h1');
h1.style.fontFamily = 'monospace';

Question 7
var buttons = document.body.querySelectorAll('.action-icon-bg');
for(var index = 0; index < buttons.length; index++) {buttons[index].style.backgroundColor = 'pink'};

Question 8
var nameField = document.body.querySelector('input#name');
nameField.placeholder = 'Identify Yourself';

Question 9
var message = document.querySelector('textarea#message');
message.placeholder = 'State Your Business';

Question 10
var nameField = document.body.querySelector('input#name');
nameField.placeholder = 'Your Nemesis';

Question 11
var emailField = document.querySelector('input#email');
emailField.placeholder = 'koalathebear@gmail.com';

Question 12
var submit = document.querySelector('input#submit');
submit.value = 'En garde!';

Question 13
var submit = document.querySelector('input#submit');
submit.disabled = true;

Question 14
var list = document.querySelector('ul.bio-info');
var item = list.querySelectorAll('li');
item.forEach(function(li){list.removeChild(li)});

PART 2
// Warm Up //
var timeTravelDiv = document.querySelector('#time-travel');
var timeTravelDivParent = timeTravelDiv.parentNode;
timeTravelDivParent.remove()

Question 1
var pikachu = document.querySelector('#right-image');
var pikachuImage = pikachu.querySelector('img');
var clone = pikachuImage.cloneNode(true);
var element = document.querySelector('.portfolio-container');
element.appendChild(clone);

Question 2
for(var index = 0; index < 10; index++) {
  var clone = pikachuImage.cloneNode(true);
  element.appendChild(clone)
};

Question 3
var list = document.querySelector('.bio-info');
var listItem = document.querySelector('.bio-info-item');
var listClone = listItem.cloneNode(true);
var spanLeft = listClone.querySelector('.bio-info-title');
var spanRight = listClone.querySelector('.bio-info-value');
spanLeft.textContent = 'Page last updated on'
spanRight.textContent = Date()
list.appendChild(listClone)
