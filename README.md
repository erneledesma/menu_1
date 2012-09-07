<!DOCTYPE html>
<html lang="en">
  <head>
		 <head>
      <title>
         P&aacute;gina con Javascript.
      </title>
      <script language="javascript">
         
            function ver()
            {
               formulario.indice.value = formulario.menuProvincia.selectedIndex;
            }
         //-->
      </script>
   </head>
   <body>
      <form name="formulario">
         Indique su provincia:
         <select name="menuProvincia">
           
            <option value="02">Entre Rios</option>
            <option value="03">Santa Fe</option>
            <option value="04">Neuquen</option>
            <option value="33">Misiones</option>
            <option value="05">Rio Negro</option>
            <option value="06">San Luis</option>
            <option value="07">San Juan</option>
            <option value="08">Chaco</option>
            <option value="09">Formosa</option>
            <option value="10">Jujuy</option>
            <option value="11">Santa Cruz</option>
            <option value="39">La Pampa</option>
            <option value="12">Tieera del Fuego</option>
            <option value="51">Buenos Aires</option>
            <option value="13">Capital Federal</option>
            <option value="14">Chubut</option>
            
         </select>
         <br>

         <input type="button" value="Ver selectedIndex" onClick="ver();">
         <br>

         El &iacute;ndice seleccionado es:
         <input type="text" name="indice" size=2 disabled>

      </form>
   </body>
</html>
