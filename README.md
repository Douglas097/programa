var idade, altura, sexo, i, midade=0, M, quantM=0, quantF=0, F

for (i= 1; i <= 5; i++){
idade = parseInt(prompt("Digite sua idade: "));
alturra = parseInt(prompt("Digite sua altura: "));
sexo = prompt("Digite seu sexo F/M: ");

if (idade > midade){ 
midade = idade; 
}
if (sexo == 'M') {
quantM++
} else if (sexo == 'F') {
quantF++
}
}
alert("A maior idade é: " +midade)
alert("Essa idade pertence ao sexo: " +sexo )
alert("A quantidade de Homens é: " +quantM)
alert("A quantidade de Mulheres é: " +quantF)
