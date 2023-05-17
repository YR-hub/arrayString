public static String reverse(String texto) {
    StringBuilder reversed = new StringBuilder();
    for (int i = texto.length() - 1; i >= 0; i--) {
        reversed.append(texto.charAt(i));
    }
    return reversed.toString();
}

// Ejemplo de uso
String cadenaInvertida = reverse("hola mundo");
System.out.println(cadenaInvertida); // Imprime "odnum aloh"

String[] array = {"elemento1", "elemento2", "elemento3"};

for (String elemento : array) {
    System.out.println(elemento);
}

int[][] array = {{1, 2, 3}, {4, 5, 6}, {7, 8, 9}};

for (int i = 0; i < array.length; i++) {
    for (int j = 0; j < array[i].length; j++) {
        System.out.println("Posición [" + i + "][" + j + "]: " + array[i][j]);
    }
}

import java.util.Vector;

Vector<String> vector = new Vector<>();
vector.add("elemento1");
vector.add("elemento2");
vector.add("elemento3");
vector.add("elemento4");
vector.add("elemento5");

vector.remove(1);
vector.remove(1);

for (String elemento : vector) {
    System.out.println(elemento);
}

 import java.util.ArrayList;
import java.util.LinkedList;
import java.util.List;

List<String> arrayList = new ArrayList<>();
arrayList.add("elemento1");
arrayList.add("elemento2");
arrayList.add("elemento3");
arrayList.add("elemento4");

List<String> linkedList = new LinkedList<>(arrayList);

for (String elemento : arrayList) {
    System.out.println(elemento);
}

for (String elemento : linkedList) {
    System.out.println(elemento);
}

  import java.util.ArrayList;
import java.util.Iterator;

List<Integer> numeros = new ArrayList<>();
for (int i = 1; i <= 10; i++) {
    numeros.add(i);
}

Iterator<Integer> iterator = numeros.iterator();
while (iterator.hasNext()) {
    int numero = iterator.next();
    if (numero % 2 == 0) {
        iterator.remove();
    }
}

for (int numero : numeros) {
    System.out.println(numero);
}

 public static void dividePorCero() throws ArithmeticException {
    throw new ArithmeticException();
}

public static void main(String[] args) {
    try {
        dividePorCero();
        System
