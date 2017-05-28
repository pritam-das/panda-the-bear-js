1.
 $('.profile-image').attr("src", "https://media4.s-nbcnews.com/j/newscms/2016_36/1685951/ss-160826-twip-05_8cf6d4cb83758449fd400c7c3d71aa1f.nbcnews-ux-400-400.jpg")

 1.2.
 $('.photography').attr("src", "http://lorempixel.com/325/225/nature/")

 2.
 var nameChange = "Pritam Das"
 $('#name_highlight').text(nameChange);

 3.
 var employment = "Job History"
 $('#job').text(employment);

4.
$('#time-travel').remove()

5.
$('body').css("background-color", "green")

6.
$('.highlight').css("color", "yellow")

7.
$('h1').css("font-family", "monospace")

8.
$('.action-icon').css("color", "black")

9.
$('#name').attr("placeholder", "Your name please");

10.
$('#message').attr("placeholder", "State your business");

11.
$('#name').val("Your Nemesis");

12.
$('#email').val("koalathebear@gmail.com");

13.
$('#submit').val("En grade");

ADDING ELEMENTS TO THE DOM:

1.
$('.pikachu').clone().appendTo('.portfolio-container')  

2.
for(var i=0; i<10; i++)
{ $('.pikachu').clone().appendTo('.portfolio-container')
}

3.
