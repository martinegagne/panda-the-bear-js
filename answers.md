QUESTION 1.1

var image = document.querySelector(".profile-image")
image.src = "https://placebear.com/400/400"

QUESTION 1.2
var image = document.querySelector("#left-image > img");
image.src = "https://placebear.com/325/225"

QUESTION 3
var h1 = document.querySelector("h1")
h1.innerText = "Martine Elizabeth Gagne"

QUESTION 4
var body = document.querySelector("body");
body.style.backgroundColor = "orange"

QUESTION 5
var highlightElementColour = document.querySelectorAll(".highlight")
highlightElementColour.forEach(function(text) {
text.style.background = "grey";
});

QUESTION 6
var h1 = document.querySelector("h1");
h1.style.fontFamily = "monospace";

QUESTION 7
var icon = document.querySelectorAll(".action-icon-bg")
icon.forEach(function(icon) {
icon.style.background = "orange";
});

QUESTION 8
var contactNameField = document.querySelector("#name");
contactNameField.placeholder = "Identify yourself"

QUESTION 9
var contactMessageField = document.querySelector("#message");
contactMessageField.placeholder = "State your business"

QUESTION 10
var contactName = document.querySelector("#name");
contactName.setAttribute("value","your nemesis");

QUESTION 11
var contactEmail = document.querySelector("#email");
contactEmail.setAttribute("value", "koalathebear@gmail.com");

QUESTION 12
var contactSubmitButton = document.querySelector("#submit");
contactSubmitButton.setAttribute("value", "En garde!");

QUESTION 13
var contactSubmitButton = document.querySelector("#submit");
contactSubmitButton.setAttribute("disabled", " ");

QUESTION 14
var bioInfo = document.querySelector("ul.bio-info")
bioInfo.remove("bio-info-item");

///////////////////////////////////////////////////////////////////////////////////////////////

QUESTION 1
var timeTravel = document.querySelector("div#time-travel.bar-filled.highlight");
timeTravel.remove(timeTravel);

QUESTION 2
