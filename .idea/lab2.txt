var computerChoice = Math.random();
console.log(computerChoice);

if(computerChoice > 0 && computerChoice < 0.33){
    computerChoice = "Rock";
}
else if(computerChoice > 0.34 && computerChoice < 0.66){
    computerChoice = "Paper";
}
else{
    computerChoice = "Scissors";
}
