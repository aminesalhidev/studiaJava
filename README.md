# Introduzione a Java

Il linguaggio Java è nato agli inizi degli anni '90 ed è un linguaggio di programmazione ad alto livello, orientato agli oggetti e con tipizzazione statica. Si propone di soddisfare cinque obiettivi principali:

## Obiettivi di Java
- **Semplicità**: Java è progettato per essere intuitivo e facile da imparare.
- **Robustezza e Sicurezza**: Java è noto per la sua robustezza e sicurezza grazie a funzionalità come la gestione automatica della memoria.
- **Indipendenza dalla Piattaforma**: I programmi Java sono portabili su diverse piattaforme.
- **Strumenti e Librerie per il Networking**: Java offre un ricco set di librerie per la gestione delle operazioni di rete.
- **Esecuzione Sicura del Codice Remoto**: Java è progettato per eseguire codice da sorgenti remote in modo sicuro.

## Librerie Importanti
- `java.lang`
- `java.io`
- `java.awt`
- `java.swing`
- `java.net`
- `java.util`

Per importare queste librerie, usa il seguente esempio:
```java
import java.util.*;
import java.io.*;
java.awt.*;
java.swing.*;
java.net.*;

##Definizione delle classi
**In java tutto  e definito un oggetto, e per scriver un programma è neccessario definire una classe Ad Esempio:

In Java, tutto è considerato un oggetto, e per scrivere un programma è necessario definire una classe. Ad esempio:

java

class Saluto {
    public static void main(String args[]) {
        System.out.println("Hello world");
    }
}

In questo esempio, mostriamo come stampare una semplice scritta.
Input ed Output

Per la lettura dei dati, utilizza il componente Scanner. Ecco un esempio:

import java.util.Scanner;

public class InputExample {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        String nome;
        System.out.print("Inserisci il tuo nome: ");
        nome = sc.next();
    }
}

##Il Metodo Main

Il metodo main è il punto di ingresso principale dell'applicazione. Deve avere le seguenti caratteristiche:

    Deve essere dichiarato come public.
    Deve essere dichiarato come static.
    Deve essere dichiarato come void.
    Deve accettare un unico argomento di tipo String[] (array di stringhe).

##Commenti

**I commenti sono importanti nella programmazione, sia per rendere il codice comprensibile ad altre persone, sia per aiutare il programmatore stesso a comprendere il proprio codice. In Java, i commenti vengono preceduti dal simbolo //.
Modificatori di Accesso

**I modificatori di accesso determinano la visibilità degli elementi all'interno di una classe. I principali modificatori di accesso sono:

    public: Gli elementi sono accessibili ovunque nel progetto.
    private: Gli elementi sono accessibili solo all'interno della loro classe.
    protected: Gli elementi sono accessibili all'interno dello stesso package e dalle classi derivate       nello stesso package.

**Se non viene specificato alcun modificatore, l'elemento avrà una visibilità di default all'interno dello stesso package.
Modificatori final e static

**Il modificatore final definisce una variabile costante, mentre il modificatore static permette di richiamare un metodo senza dover istanziare la classe che lo contiene e definisce una variabile globale accessibile a tutte le istanze di una classe.

