# piedra_papel_tijera_swicht

echo "# piedra_papel_tijera_swicht" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/QuijoteAriel/piedra_papel_tijera_swicht.git
git push -u origin main

// Mismo Ejercicio pero con swich

var tijera = 1;
var piedra = 2;
var papel =  3;
var user = parseInt

(
prompt ("Escoge un valor : Tijera 🖖 1, Piedra ✊ 2, Papel 🤚 3")
)


maquina = Math.floor(Math.random() * (4 - 1 ) +1 )


switch (true)
{
    case user===1 && maquina===3:
    console.log("Gana el Usuario con 🖖!!")
    break;

    case user===2 && maquina===1:
    console.log("Gana el Usuario con ✊ !!")
    break;
    
    case user===3 && maquina===2:
    console.log("Gana el Usuario  con 🤚!!")
    break;

    case maquina === 1 && user === 3:
    console.log("Gana la Maquina con 🖖")
    break;

    case maquina === 2 && user === 1:
    console.log("Gana la Maquina con ✊")
    break;

    case maquina === 3 && user === 2:
    console.log("Gana la Maquina con 🤚")
    break;

    case maquina === 3 && user === 3:
    console.log("Empate con  🤚")
    break;
    case maquina === 2 && user === 2:
    console.log("Empate con  ✊")
    break;
    case maquina === 3 && user === 2:
    console.log("Empate con  🖖")
    break;

    
    default:
    console.log("No es valida tu jugada")

    
}
