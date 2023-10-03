# studiaJava

Introduzione a Java

Java è un linguaggio di programmazione ad alto livello, orientato agli oggetti e con tipizzazione statica. È nato agli inizi degli anni '90 con l'obiettivo di soddisfare cinque principali criteri:

    Semplicità: Java è progettato per essere un linguaggio di programmazione intuitivo e facile da imparare.

    Robustezza e Sicurezza: Java è noto per la sua robustezza e sicurezza, grazie a funzionalità come la gestione automatica della memoria e la verifica dei tipi.

    Indipendenza dalla Piattaforma: I programmi Java sono scritti una volta e possono essere eseguiti su diverse piattaforme senza modifiche.

    Strumenti e Librerie per il Networking: Java include un ricco set di librerie e strumenti per la gestione delle operazioni di rete.

    Esecuzione Sicura del Codice Remoto: Java è progettato per eseguire codice da sorgenti remote in modo sicuro, prevenendo potenziali minacce alla sicurezza.

Librerie Importanti

Java dispone di molte librerie importanti, alcune delle più comuni includono:

    java.lang
    java.io
    java.awt
    java.swing
    java.net
    java.util

Queste librerie possono essere importate nelle prime righe del tuo codice, ad esempio:

java

import java.util.*;

Definizione delle Classi

In Java, tutto è considerato un oggetto, e per scrivere un programma è necessario definire una classe. Ad esempio:

java

class Saluto {
    public static void main(String args[]) {
        System.out.println("Hello world");
    }
}

In questo esempio, mostriamo come stampare una semplice scritta.
Input ed Output

Per la lettura dei dati, viene utilizzato un componente chiamato Scanner. Ecco come dichiarare e inizializzare uno Scanner:

java

import java.util.Scanner;

public class InputExample {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        String nome;
        System.out.print("Inserisci il tuo nome: ");
        nome = sc.next();
    }
}

Il Metodo Main

Il metodo main è il punto di ingresso principale dell'applicazione. All'interno del suo blocco di codice, viene definito il comportamento della classe. Quando un programma viene eseguito, il metodo main è il primo ad essere individuato ed eseguito. Deve avere le seguenti caratteristiche:

    Deve essere dichiarato come public.
    Deve essere dichiarato come static.
    Deve essere dichiarato come void.
    Deve accettare un unico argomento di tipo String[] (array di stringhe).

Commenti

I commenti sono importanti nella programmazione, sia per rendere il codice comprensibile ad altre persone, sia per aiutare il programmatore stesso a comprendere il proprio codice. In Java, i commenti vengono preceduti dal simbolo //.
Modificatori di Accesso

I modificatori di accesso determinano la visibilità degli elementi all'interno di una classe. I principali modificatori di accesso sono:

    public: Gli elementi sono accessibili ovunque nel progetto.
    private: Gli elementi sono accessibili solo all'interno della loro classe.
    protected: Gli elementi sono accessibili all'interno dello stesso package e dalle classi derivate nello stesso package.

Se non viene specificato alcun modificatore, l'elemento avrà una visibilità di default all'interno dello stesso package.
Modificatori final e static

Il modificatore final viene utilizzato per definire una variabile che diventa una costante e non può essere modificata successivamente. Il modificatore static permette di richiamare un metodo senza dover istanziare la classe che lo contiene e definisce una variabile globale accessibile a tutte le istanze di una classe.
