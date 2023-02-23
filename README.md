# **Calculadora TPD altitud**
Este proyecto es basado en un tema de Aerodinamica de la universidad.
 
<div class="plane"></div>
.plane {
  width: 60px;
  height: 20px;
  position: relative;
  background-color: #555;
  animation: move-plane 3s infinite;
}

@keyframes move-plane {
  0% {
    left: 0;
  }
  50% {
    left: calc(100% - 60px);
  }
  100% {
    left: 0;
  }
}



   <hr style="border-color:red;">
Descripcion<p>
Este software determina la temperatura, presion y densidad de acuerdo a la altitud que se encuentre una aeronave.<p>
Instrucciones

 
- Tener [Labview 2019](httphttps://www.ni.com/es-co/shop/labview.html:// "Labview 2019").
- Descargar el archivo llamado "Calculadora Altitud.vi"
