# TP_N_4
## consigna
Crear tres clases en Python, que cumplan con lo siguiente:

* Una clase llamada "Nota".

 * Sus variables de instancia son:
  1. id: Un n�mero secuencial autom�tico
  2. texto: El texto de la nota
  3. etiquetas: una serie de palabras-clave separadas por espacios
  4. fecha_creacion: la fecha de creaci�n de la nota

 * Adem�s del m�todo iniciador (__init__) debe tener un m�todo llamado "coincide", que reciba como par�metro una cadena, y que retorne True si la cadena forma parte del texto o de las etiquetas, y False de lo contrario.

* Una clase llamada "Anotador". Su �nica variable de instancia es "notas", una lista de objetos Nota.
 * Sus m�todos son:
  1. nueva_nota: Recibe un texto y agrega a la lista una nueva nota con ese texto.
  2. _buscar_por_id: Recibe un id, y retorna la el objeto Nota correspondiente, o None si no existiera.
  3. modificar_nota: Recibe un id y un nuevo texto, y actualiza el texto de la nota.
  4. modificar_etiquetas: Recibe un id y las nuevas etiquetas, y actualiza las etiquetas de la nota.
  5. buscar: Recibe un "filtro" (cadena de b�squeda) y retorna una lista compuesta por las notas cuyo texto o etiquetas coincidan con el filtro recibido.

* Una clase llamada Menu, que contiene una interfaz de usuario b�sica en l�nea de comandos.
