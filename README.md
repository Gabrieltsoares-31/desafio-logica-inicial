// 1 Desafio Classificador de nível de Heroi

// variaveis para o heroi

let pontosDeXp = 0
let nomeDoHeroi = "Tavares3103"
let nivel = 0

// introdução da jornada

console.log("Digite o nome do seu heroi")
console.log("Bem vindo " + nomeDoHeroi)
console.log(nomeDoHeroi + " iniciou sua jornada")
console.log(nomeDoHeroi + " começou com " + nivel + " XP")

for(let contador = 1; contador <=15; contador++){
    if(contador == 2){

        console.log("perdeu a batalha " + contador + " sem recompensa pra você")

    }else{
    pontosDeXp += 750
    
    console.log("batalha " + contador + " concluída")
    console.log("XP atual " + pontosDeXp)
}

// Estrutura de decisão

if(pontosDeXp <= 1000){
    nivel = "Ferro"

}else if(pontosDeXp <= 2000){
    nivel = "Bronze"

}else if(pontosDeXp <= 5000){
    nivel = "Prata"

}else if(pontosDeXp <= 7000){
    nivel = "Ouro"

}else if(pontosDeXp <= 8000){
    nivel = "Platina"

}else if(pontosDeXp <= 9000){
    nivel = "Ascendente"

}else if(pontosDeXp <= 10000){
    nivel = "Imortal"

}else{
    nivel = "Radiante"
} }

// Saída final

console.log("O Herói de nome " + nomeDoHeroi + " está no nível de " + nivel)
