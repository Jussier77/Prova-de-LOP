# Prova-de-LOP
Código da prova
<script>
  //link para o video explicativo: https://drive.google.com/file/d/1YZU9E8mLfX4gpeoxPjREWszrTBuMrEOC/view?usp=sharing
  var esporte = prompt("Digite seu esporte (Futebol, natação, surf e LOL):")
  var idade = parseInt(prompt("Digite sua idade:"))
  var categoria
  if(esporte === "Futebol"){
    if(idade<20){
      alert("Sub-20 - Futebol")
    } else if(idade>=20 && idade<=39){
      alert("Adulto - Futebol")
    } else if(idade>40){
      alert("Veteranos - Futebol")
    }
  }
  if(esporte === "natação"){
    if(idade<13){
      alert("Junior - Natação")
    } else if(idade>=13 && idade<=16){
      alert("Infanto-Juvenil - Natação")
    } else if(idade>=17 && idade<=30){
      alert("Junior-Senior - Natação")
    } else if(idade>31){
      alert("Senior - Natação")
    }
  }
  if(esporte === "surf"){
    if(idade<=15){
      alert("Mirim - Surf")
    } else if(idade>=16 && idade<=18){
      alert("Junior - Surf")
    } else if(idade>=19 && idade<=39){
      alert("Open - Surf")
    } else if(idade>40){
      alert("Grand Master - Surf")
    }
  }
  if(esporte === "LOL"){
    if(idade<13){
      alert("Bronze - LOL")
    } else if(idade>=13 && idade<=16){
      alert("Prata - LOL")
    } else if(idade>17){
      alert("Ouro - LOL")
    } 
  }
</script>
