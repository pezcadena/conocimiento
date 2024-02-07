#dev #angular
# Signals
#### Input
 Los `signals` tienen un constructor llamado "`input`" que sirve para usarlos como entradas de componente.
 ```
inputSignal = input<string>('default value');
```
Tambien tienen la opción (como cualquier input) de hacerlo "``required``", de tener un "``alias``" o de usar un "``transformer``".
#### toObservable - toSignal
Se puede usar todo el poder de RxJS se pueden convertir en observables con esa función, y luego regresar a ``signal`` con la otra.
#### untracked
Esta función lee el valor del ``signal`` en vez de llamarlo de la manera tradicional.