# Java-Cadenas-Texto

# Alphabetical
     recibir cadenas de texto y ordenarlas en orden alfabetico 

# Anagrams
     validar si una cadena de texto es un anagrama

# CharactersSame
     Validar si todos los caracteres son iguales
# CheckAnagrams
    Validar la existencia de anagramas
  
# CheckVowels
     validar la existencia de vocales
# HorspoolSearch
     El algoritmo de Horspool es una simplificación del algoritmo de Boyer-Moore en
     que utiliza solo uno de los dos métodos heurísticos para aumentar el número
     de caracteres desplazados al encontrar una mala coincidencia en el texto. Este método es
    generalmente llamado cambio de "símbolo malo" o "carácter malo". El mal símbolo
    el método de cambio se clasifica como un método de mejora de entrada en la teoría de
    algoritmos. La mejora de entrada es (de wikipedia) el principio de que
    procesar una entrada dada a un problema y alterarla de una manera específica
    aumentar la eficiencia del tiempo de ejecución o la eficiencia del espacio, o ambos. Ambos algoritmos intentan
    para hacer coincidir el patrón y el texto comparando los símbolos del patrón con los del texto
    de derecha a izquierda.
  
    En el método de cambio de símbolo incorrecto, se crea una tabla antes de la búsqueda,
    llamada la "tabla de símbolos malos". La tabla de símbolos incorrectos contiene los valores de cambio
    para cualquier símbolo en el texto y patrón. Para estos símbolos, el valor es el
    longitud del patrón, si el símbolo no está en el primero (longitud - 1) de la
    patrón. De lo contrario, es la distancia desde su aparición más a la derecha en el patrón.
    hasta el último símbolo del patrón. En la práctica, sólo calculamos los valores
    para los que existen en el primero (longitud - 1) del patrón.<br>
 
# LongestPalindromicSubstring
     encontrar palindromos en subcadenas
# Lower
    convertir caracteres mayuscula en minuscula
# Palindrome
    confirmar si una cadena es palindromos
# Pangram
     Un pangrama u oración holoalfabética es una oración que usa cada letra de un alfabeto dado
     al menos una vez. Los pangramas se han utilizado para mostrar tipos de letra, probar equipos 
     y desarrollar habilidades en escritura a mano, caligrafía y mecanografía.
     El pangrama inglés más conocido es "El rápido zorro marrón salta sobre el perro perezoso". 
    Se ha utilizado desde al menos finales del siglo XIX, fue utilizado por Western Union para
    probar la precisión y confiabilidad de los equipos de comunicación de datos Telex/TWX, [1] 
    y ahora es utilizado por una serie de programas de computadora para mostrar fuentes de computadora, 
    más notablemente el visor de fuentes integrado en Microsoft Windows.
# PermuteString
    Es un algoritmo que mediante backtracking hace lo siguiente: -
    >>Fija un carácter en la primera posición e intercambie el resto del carácter con el primer carácter.
    Al igual que en ABC, en la primera iteración se forman tres cadenas: ABC, BAC y CBA intercambiando A con
    A, B y C respectivamente.
    >>Repite el paso 1 para el resto de los caracteres, como arreglar el segundo carácter B y así sucesivamente.
    >> Ahora cambie de nuevo para volver a la posición anterior. Por ejemplo, de ABC, formamos ABC fijando B nuevamente,
    y retrocedemos a la posición anterior e intercambiamos B con C. Entonces, ahora tenemos ABC y ACB.
    >>Repite estos pasos para BAC y CBA, para obtener todas las permutaciones.
 
# ReverseString
     voltea una cadena de texto y la entrega en su forma reversa, ej. hola -> aloh
# Rotation
    Dada una cadena, mover varios caracteres delante de la cadena hasta el final
    de la cadena. Por ejemplo, mueva los dos caracteres 'a' y 'b' delante de
    la cadena "abcdef" al final de la cadena, de modo que la cadena original
    se convierte en la cadena "cdefab"

# Upper
    Convertir una palabra con caracteres minusculas a caracteres mayusculas

# WordLadder
    **Problem Statement:**
    A transformation sequence from word beginWord to word endWord using a dictionary wordList is a sequence of words beginWord -> s1 -> s2 -> ... -> sk such that:
    Every adjacent pair of words differs by a single letter.
    Every si for 1 <= i <= k is in wordList. Note that beginWord does not need to be in wordList.
    sk == endWord
    Given two words, beginWord and endWord, and a dictionary wordList, return the number of words in the shortest transformation sequence from beginWord to endWord, or 0 if no such sequence exists.
 
    **Example 1:**
    Input: beginWord = "hit", endWord = "cog", wordList = ["hot","dot","dog","lot","log","cog"]
    Output: 5 
    Explanation: One shortest transformation sequence is "hit" -> "hot" -> "dot" -> "dog" -> cog", which is 5 words long.
   
    **Example 2:**
    Input: beginWord = "hit", endWord = "cog", wordList = ["hot","dot","dog","lot","log"]
    Output: 0
    Explanation: The endWord "cog" is not in wordList, therefore there is no valid transformation sequence.
 
    **Constraints:**
    1 <= beginWord.length <= 10
    endWord.length == beginWord.length
    1 <= wordList.length <= 5000
    wordList[i].length == beginWord.length
    beginWord, endWord, and wordList[i] consist of lowercase English letters.
    beginWord != endWord
    All the words in wordList are unique.
 
