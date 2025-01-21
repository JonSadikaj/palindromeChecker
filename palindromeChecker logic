  let checkButton = document.getElementById("check-btn");
checkButton.addEventListener("click", checkWord);
    

function checkWord() {
    const userInput = document.getElementById("text-input").value;
    const resultMsg = document.getElementById("result");

    const cleanedInput = cleanInputString(userInput.toLowerCase());

    const reversedInput = cleanedInput.split("").reverse().join("");

    if (reversedInput === cleanedInput) {
        resultMsg.innerText = `${userInput} is a palindrome.`;
    } else {
        resultMsg.innerText = `${userInput} is not a palindrome.`;
    }

    if(userInput === ""){
        alert("Please input a value");
    }
}

function cleanInputString(str) {
    let regex = /[^a-zA-Z0-9]/g;
    return str.replace(regex, "");
}
  
