# Sample project for OpenClassroom's fundamentals of Java

## pour compiler

**src** :  les sources
**bin** : Les classes générées

pour vérifier l'existance de java
```bash 
> java -version
```

Dans le répértoire racide de src, il y a au moins ce README.md et symptoms.txt et le répertoire src

### Compiler

```bash
> javac -d .\bin\ -cp .\src .\src\com\hemebiotech\analytics\AnalyticsCounter.java
```

### Tester
Lancer le programme si tous va bien 

```bash
java -cp .\bin\ com.hemebiotech.analytics.AnalyticsCounter
```





