# chapter-5
quizzes

laugh function 

function laugh() {
return "hahahahahahahahahaha!";
}
console.log(laugh());

function laugh(num) {
    var str = '';
    for(var i = 1; i <= num; i++) {
        str += "ha";
    }
    return str + "!";
}
