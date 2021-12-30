<p align="center">
    <img src="https://github.com/GeeksHubsAcademy/2020-geekshubs-media/blob/master/image/logo.png" >	
</p>


    Considere el siguiente problema:

    Escriba un programa corto que permita generar un pequeño gráfico matricial tal que :
    
     N = 5 
    
        *
       **
      ***
     ****
    *****

    Observe que su base y altura son ambas iguales.
    Cada iteración define un salto de línea.
    La imagen se dibuja usando símbolos de asterisco '*' y espacios.
    La última línea no le precede ningún espacio.   
    
    El resultado se debe de ser un String con el cálculo del gráfico matricial con 'N' Tiers.
    
    
    Se atiente al siguiente ejemplo:
   
    N = 1     N = 2     N = 3     N = 4    ...    N
    
        *         *         *         *          
                 **        **        **        
                          ***       ***       
                                   ****      
                                  
    

    En la carpeta 'tests/test_kata.js' se encuentra el fichero con la definición de nuestro método vacío.
    
    El modus operandi de trabajo es el siguiente:
    
    Debes 'forkear' el proyecto a tu cuenta.
    Puedes hacer PR's ilimitadas e ir validando poco a poco la solución contra nuestro respositorio con CI.
    Puedes trabajar en local y subir la solución haciendo un PR a nuestro repositorio.
    Cuando se envíe la PR final, debes indicar el tiempo de dedicación y los intentos que has hecho.
    También puedes añadir un comentario para dar cualquier tipo de feedback.
    
    En caso de duda, revisa en el apartado de 'Referencias'.       
    

    [Suite Tests]
    
    def test_apply_01(self)
    def test_apply_02(self)
    def test_apply_03(self)
    def test_apply_04(self)
    def test_apply_05(self)
    def test_apply_06(self)
    def test_apply_07(self)

    Tests
	
	
	tests/test_kata.py::Test_kata::test_apply_01 PASSED                                            [ 14%]
    tests/test_kata.py::Test_kata::test_apply_02 PASSED                                            [ 28%]
    tests/test_kata.py::Test_kata::test_apply_03 PASSED                                            [ 42%]
    tests/test_kata.py::Test_kata::test_apply_04 PASSED                                            [ 57%] 
    tests/test_kata.py::Test_kata::test_apply_05 PASSED                                            [ 71%] 
    tests/test_kata.py::Test_kata::test_apply_06 PASSED                                            [ 85%]
    tests/test_kata.py::Test_kata::test_apply_07 PASSED                                            [100%]

## Referencias

* [Tutorial - Testing Automatizado](https://github.com/GeeksHubsAcademy/2020-js-vanilla-testing-FFFF/blob/master/README.md)
