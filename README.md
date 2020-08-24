# HW Password Generator
// created html file 
// created css for html 
// made a div in the body for the password generator 
// I also included in the div the button for the generator
// outside the div I created the script for the java that I used
// I created the the function and var for the random password generator
// I included all numbers, most symbols, and lower case and upper case letters 
// I gave the password length to 20
// here is the random number code that I used for my generator
  for (var i=0; i<passwordLength; i++){
                var randomNumber = Math.floor(Math.random() * charset.length);
                password += charset.substring(randomNumber, randomNumber+1);
// in the css I included the colors and sizing for the generator text and boxes
// I set the font size to 24px
// I also set the font size for h1 to 50px
