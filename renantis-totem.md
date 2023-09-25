
## Link per accedere ai test interni - extendi

Come ottenere il link da aprire con il dispositivo?

```bash
  eas device:create  
```
    
Una volta che il dispositivo è stato abilitato basta aggiornare (certificati) la build o crearne una nuova.
Puoi usare il comando

```bash
  eas device:list  
```
per averne conferma

Come aggiornare i certificati di una build?

```bash
  eas build:resign  
```
o per una nuova build

```bash
  eas build -p ios --profile preview --non-interactive
```

##  Iscrivere il dispotivo ai tester - renantis
- aprire il primo l'url generato che consente di iscriversi;
- una volta iscritto aprire la url per scaricare l'app;
- l'ultimo passaggio (solo per iOS>16) è quello di abilitare la modalità sviluppatore;
