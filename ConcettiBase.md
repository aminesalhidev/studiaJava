## Le variabili

una variabile e un identificatore di una zona di memoria, ed ogni variabile è associata ad un tipo che identifica ciò che la data porzione di memoria dovrà contenere.

Abbiamo diversi tipi di variabile :

- **int var1;**
- **string var2;**
- **double var3;**

# Dichiarazione ed inizializzazione delle variabili

int numero;

stiamo dichiarando che la variabile numero e un identificatore di un elemento di tipo intero.

- quando assegniamo il valore alla variabile per la prima volta viene chiamata ‘inizializzazione della variabile’ mentre in genere viene detto assegnazione se stiamo dando alla variabile un nuovo valore.

L’inizializzazione della variabile viene effettuato utilizzando l’operatore ‘=’

```java
int var ; //dichiarazione
var = 10; // assegniazione
var = 110; assegniazione di un nuovo valore
int var = 110; //dichiariazione ed inizializzazione 
```

## Le costanti

Le costanti, possono assumere un solo valore durante tutta l’esecuzione del programma. 

1. Per dichiarare una costante bisogna fare affidamento alla parola chiave **finalb>**

```java
final double YARD_METRO = 0.90
```

“Se si tenta di modificare il valore della costante viene generato un errore”

Per convenzione il nome della costanti viene indicato tutto in lettere maiuscole

## I Tipi Di Dati

Ogni linguaggio di programmazione ha i propri tipi di dati:

- tipi numerici interi
- tipi numerici a virgola mobile: ad esempio : float & double
- ***Boolean* : ammette i soli valori true e false**

![Immagine WhatsApp 2023-10-05 ore 17.56.40_9658f1e0.jpg](https://prod-files-secure.s3.us-west-2.amazonaws.com/fdac6285-3db9-4608-ba1f-708f8221654e/869ac303-d0a0-401e-b6d0-325ec30e92c5/Immagine_WhatsApp_2023-10-05_ore_17.56.40_9658f1e0.jpg)

## Le stringhe

Una stringa e un’istanza della classe String, un oggetto che incapsula una sequenza di caratteri. Esistono molte classi che servono per manipolare le stringhe, quelli più utilizzate si trovano nel package java.lang e sono :

1. String
2. StringBuffer
3. StringBuilder

Per creare una stringa si utilizza l’invocazione del costruttore della classe String o tramite un string literal :

```java
String s = new String ("ciao");
String s1 = "ciao";
```

La concatenazione di due o piu stringhe avviene tramite l’operatore di concatenazione + :

```java
String s2 = "ciao mondo";
System.ou.println(si + s2); 
//stampiamo ciao mondo
```

Le Stringhe si possono confrontare attraverso il metodo **equals, c**he permette il confronto case-sensitive con un’altro oggetto String :

```java
boolean b = s1.equals(s2),
```

In questo caso, le due stringhe sono diverse quindi la variabile b e uguale a False. in caso contrario, se le due stringhe sono uguale, la variabile b sarà uguale a true,

Tramite il metodo lenght e possibile ottenere il numero di caratteri di una stringa;

### Le conversioni di tipo

Le conversioni in java si chiamano anche operazioni di cast. Una conversione ammessa dal linguaggio puo essere realizzata in due soli modi : 

1. cast implicito
2. cast esplicito (viene gestito automaticamente);

Le regole piu importanti da seguire :

- non sono ammesse conversioni di tipi booloean a tipi numerici.
- sono ammesse tutte le conversioni da un certo tipo numerico a un altro tipo numerico.
- richiedono necessariamente il cast esplicito tutte le conversioni da un tipo numeri più “Grande” verso un tipo numerico più “piccolo”, per esempio da long verso int.
- Per quanto riguarda invece le classi :
- - le conversioni da un sottotipo a un supertito non richiedono cast esplicito, per esempio da String a Object
- Le conversioni da un supertito a un suo sottotipo richiedono il cast esplicito.

# Gli array

il vettore o array e un insieme di elementi o oggetti omogenei tra loro. con una variabile possiamo indicare solo un dato, con l’array invece possiamo indicare tanti dati dello stesso tipo con un solo nome collettivo.

Ogni elemento del vettore e individuato attraverso un indice che e un numero intero.

Il primo elemento avrà come indice = 0 ;Quindi la dimensione del vettore e composta dal numero di elementi : ESEMPIO:

```java
tipo nomeArray[] = new,
tipo[dimensione];

```

Abbiamo anche un secondo modo per dichiarare

```java
tipo [] nomeArray = new
tipo[dimensione];

int vettore[] = new int [10];
int dim = 5;
String[] nomi = new String [dim]
```

Esempio di array :

```java
Scanner leggi = new Scanner(system,in);
int[] vet = new int[5];
  fot (int i = 0; i<5; i++) {
     System.out.print("Inserisci il numero " +i+"del vettore  : ");
vet[i] 0 leggi.nextInt();
```
