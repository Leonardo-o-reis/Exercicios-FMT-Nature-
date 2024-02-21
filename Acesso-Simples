const prompt = require("prompt-sync")();
let frutas = ["maça", "banana", "pera"]
let ordem = prompt("Escolha suas frutas: maçã(0), banana(1), pera(2): ")
let escolhas = ordem.split(",").map(Number)
    if (escolhas.some(isNaN)) {
        console.log("Escolha invalida, por favor tente novamente!")
    } else {
       escolhas.forEach((escolha) => {
        switch(escolha) {
            case 0:
            console.log(`Você escolheu a ${frutas[0]}`)
            break;
            case  1:
            console.log(`Você escolheu a ${frutas[1]}`)
            break;    
            case 2:
            console.log(`Você escolheu a ${frutas[2]}`)
            break;
            default:
            console.log("Seleção invalida")
                 }
            });         
        }
