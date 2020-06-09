
var question1=["What is the capital of Canada.","National animal of Canada.","National animal of Canada"];
var options1=["<input name=choice1 type=radio >Alberta</br> <input name=choice1 type=radio>Toronto</br> <input name=choice1 onclick=rightAnswer('first') value=Ottawa type=radio>Ottawa","<input name=choice2 type=radio>Lion</br> <input name=choice2 onclick=rightAnswer('second') type=radio>Beaver</br> <input name=choice2 type=radio>Polar Bear","<input name=choice2 type=radio>Peacock</br> <input name=choice2 type=radio>Sparrrow</br> <input name=choice2 onclick=rightAnswer('third') type=radio>Gray Jay"];

var a = 0;
var first = false;
var second = false;
var third = false;

window.onload=function Myfunction(){
	
	document.getElementById("questionDisplay").innerHTML= question1[0];
	
	document.getElementById("optionsDisplay").innerHTML=options1[0];
	
	document.getElementById("nextButton").innerHTML = "<button onclick=next()>Next</button>";
	
	document.getElementById("reset").innerHTML="<button onclick=repeat()>Restart</button>";
	
}

function next(){
	
	
	document.getElementById("questionDisplay").innerHTML= question1[1];
	
	document.getElementById("optionsDisplay").innerHTML=options1[1];
	
	document.getElementById("nextButton").innerHTML = "<button onclick=next1()>Next</button>";
	
	document.getElementById("reset").innerHTML="<button onclick=repeat()>Restart</button>";
		
	
}
function next1(){
	
	document.getElementById("questionDisplay").innerHTML= question1[2];
	
	document.getElementById("optionsDisplay").innerHTML=options1[2];
	
	document.getElementById("nextButton").innerHTML = "<button onclick=result()>Submit Quiz</button>";
	
	document.getElementById("reset").innerHTML="<button onclick=repeat()>Restart</button>";
		

}

function rightAnswer(question){
	if(question == "first"){
		first = true;
	}
	if(question == "second"){
		second = true;
	}
	if(question == "third"){
		third = true;
	}
	
	a++;

}


function result(){
	
	if(first){
		document.getElementById("a").classList.remove("circle");
		document.getElementById("a").classList.add("right");
	}else{
		document.getElementById("a").classList.remove("circle");
		document.getElementById("a").classList.add("wrong");
	}
	
	if(second){
		document.getElementById("b").classList.remove("circle");
		document.getElementById("b").classList.add("right");
	}else{
		document.getElementById("b").classList.remove("circle");
		document.getElementById("b").classList.add("wrong");
	}
	
	if(third){
		document.getElementById("c").classList.remove("circle");
		document.getElementById("c").classList.add("right");
	}else{
		document.getElementById("c").classList.remove("circle");
		document.getElementById("c").classList.add("wrong");
	}
	
 document.getElementById("aba").innerHTML="You got "+ a +" correct out of 3";	
	
	
}

function repeat(){
	
            location.reload();
			
        }
function help(){
	
	document.getElementById("aba").innerHTML="Help! <br>1)This quiz contains 3 questions. <br>2)Choose one correct option. <br>3)Use restart button to restart game";
}
