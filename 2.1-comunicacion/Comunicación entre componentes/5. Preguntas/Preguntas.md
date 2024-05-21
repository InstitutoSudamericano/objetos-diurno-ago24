# Nathaly Caballero
---

1. ¿Qué etiqueta se utiliza en Angular para indicar que una variable proviene del componente padre hacia el componente hijo?

- [ ] @Output
- [ ] @Inject
- [ ] @Input

Respuesta correcta: c) Porque esta etiqueta marca una propiedad en el componente hijo como una propiedad de entrada, lo que significa que su valor puede ser establecido por el componente padre. Esto es útil para pasar datos del padre al hijo y facilitar la comunicación entre componentes en una aplicación Angular.

2. ¿Cuál es el método de Angular utilizado para acceder a los atributos del hijo después de que la vista esté completamente cargada?

- [ ] ngOnInit()
- [ ] ngAfterContentInit()
- [ ] ngAfterViewInit()

Respuesta correcta: c) Porque este método asegura que la vista completa, incluyendo los componentes hijos, esté completamente cargada y lista para ser manipulada.

3. Cuál es el mejor lugar para inyectar dependencias en un componente Angular?

- [ ] ngOnInit()
- [ ] El constructor
- [ ] ngAfterViewInit()

Respuesta correcta: b) Porque es el lugar donde Angular realiza la inyección de dependencias, garantizando que todas las dependencias estén disponibles tan pronto como se crea el componente.

# David Correa
---

4. ¿Qué eventos del ciclo de vida se utilizan específicamente para manejar la inicialización y verificación de cambios en los componentes hijos?

- [ ] ngOnInit y ngDoCheck
- [ ] ngAfterContentInit y ngAfterContentChecked
- [ ] ngAfterViewInit y ngAfterViewChecked

La respuesta verdadera es: b) Porque estos eventos están específicamente diseñados para manejar la inicialización y la verificación de cambios en el contenido de los componentes hijos.

5. ¿Qué ocurre si no implementamos las funciones de interfaz en nuestra clase de componente durante la compilación del código TypeScript?

- [ ] El navegador mostrará un error
- [ ] Se generará un error de compilación
- [ ] No ocurrirá nada

Respuesta correcta: b) Porque TypeScript verifica que todas las clases que implementan una interfaz proporcionen las implementaciones necesarias para los métodos definidos en dicha interfaz. Si no lo hacen, el compilador de TypeScript arroja un error durante la compilación, garantizando así la integridad del código.

6. ¿En cuál fase del ciclo de vida de un componente Angular se incluyen los eventos ngOnInit y ngOnDestroy?

- [ ] Fase de los Hijos del Componente
- [ ] Fase del Componente Mismo
- [ ] Fase de Inicialización

Respuesta correcta: b) Porque tanto ngOnInit como ngOnDestroy son eventos del ciclo de vida que se enfocan en la inicialización y destrucción del propio componente.