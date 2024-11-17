Soy Alex Peñafiel estudiante de la carrera de ing de software, este repositorio trata de ejercicios de basicos y intermedios de java script junto con html, 
cada dia tratando de aprender mas y mas
de estas herramientas que de poco en poco me van a encaminar al futuro ingeniero que sere. 
A continuacion un ejemplo de lo que hemos desarrollado.


function multiplos_numeros() { 
    let multi= parseInt(document.getElementById("multiplos").value);
    let cantidad= parseInt(document.getElementById("cant").value);
    let respuesta= document.getElementById("respu_multiplos");
    let resul= "";
    for(let i = 1; i <= cantidad; i++){
        if(i % multi ===0){
            resul +="El numero "+i+" es multiplo de "+multi+"\n";
        }
    }
    respuesta.value= resul;
}


<!---
alexap05/alexap05 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
