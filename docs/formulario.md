#Input Radio y Checkbox 

## Radio (Radio Button)
- Usamos radio cuando tenemos un conjunto de opciones y solo queremos que el usuario escoja 1
- Plan de pagos (Netflix) => 3 planes y solo que el usuario tenga 1
- Plan de celular => Solo quiere que tengas 1
- Curso junior - intermedio - avanzado
## Checkbox
-Usamos checkbox cuando queremos que el usuario marque mas de una opcion
- Netflix (Cuando entremos por primera y nos permite seleccionar multiples generos de pelicula o series)
- Lista de mercado (marcamos las opciones que compramos)
- compras un carro (escoger y marcar las opciones de tu carro)
## checked
Permite que mi checkbox o radio esten marcados por defecto

## readonly vs disabled

-Se usa cuando queremos hacer que un imput no sea editable, pero queremos mantener su valor al momento de enviar su informacion 

## disabled 

- Se usa cuando queremos hacer que un imput no sea editable pero no conserva su valor 
* Porque al meomento de enviar la información, sabemos que enviamos el valor de cada input pero si el input tiene la propiedad *disable* este valor será nulo, sin embargo si usas *readonly* el valor será enviado