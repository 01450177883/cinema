//condicionais - if - else
//menores de 18 anos -> menor de idade(meia)
//entre 18 e 60-> adultos(meia apenas com carteirinha)
//maiores de 60 anos -> idoso(meia)

const idade= 75
const temCarteirinha = true


if(idade < 18) {
  console.log("meia")
} else if(idade <= 60) {
  //adulta
  if(temCarteirinha === true) {
    console.log("meia")
  } else {
    console.log("inteira")
  }
  
} else {
  console.log("meia")
