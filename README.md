**TITLE** : Maquetador Avanzado con LESS y SASS.
**AUTHOR** : Gaby Gonzalez Romero @ Educacion IT

---
# Table of Contents
## Tareas previas

- [X] Repositorio - GitHub
- [ ] Proyecto ?
- [ ] Kahoot ?
- [ ] Preguntas por clases.
- [X] Crear msg de bienvenida para el grupo en Discord

---
## Clases
1. Clase [7/7] - `05/12/2022` de 20 a 22 hs.
    - [X] Checklist de la clase.
    - [X] Sobre la plataforma.
    - [X] Discord + email personal.
    - [X] Encuesta sobre conocimientos previos.
    - [X] Repaso de CSSC.
        - Estructura HTML > `head` + ( `body` > `Header` | `Aside` | `Main` | `Footer` )
            - `section` > `article` > `Header` | `Aside` | `Main` | `Footer`.
        - Clases en CSS : `class='...'` (HTML) y en el archivo CSS : `.[...]`
        - ID en CSS : `id='...'` (HTML) y en el archivo CSS `#[...]`. Tratemos de reservarlo para el uso de JS (`js-[...]`). 
        - Nomeclatura **BEM** ( Bloque - Elemento - Modificador ).
        - Estructura de un selector en CSS : `.body { [propiedad] : [valor] ; }`
        - Shorthand :
            - propiedades > `[]-top` | `[]-right` | `[]-buttom` | `[]-left`
            - valores :
                - `propiedad : [1 valor para top | right | buttom | left ]`',
                - `propiedad : [1 valor top y buttom] [1 valor para right y left]`.
                - `propiedad [1 valor para top] [1 valor para rigth] [1 valor para buttom] [1 valor para left]`
        - Posicionamiento : `absolute` | `relative`.
        - Flexbox : `display : flex | inline-flex | block | grid | ... |`
        - Variables CSS : `:root { --[] ; }`
    - [X] CSS vs. LESS (JS) vs SASS (Ruby).
        | Extension ingreso | Compilador    | Extension de egreso   |
        | :---:             | :---:         | :---                  |
        | .less             | LESS con JS   | .css                  |
        | .scss             | SASS con Ruby | .css                  |
        | .sass             | SASS con Ruby | .css                  |
    - [X] Instalacion de SASS & LESS.
        - Instalar NodeJS y NPM.
        - Ver instrucciones en Discord.
        - En el caso de que lo tengan instalado, verificar con :
            - NodeJS : `node -v`.
            - NPM : `npm -v`.
            - Less : `less --version`.
            - Sass : `sass --version`.
---
2. Clase [4/4] - `07/12/2022` de 20 a 22 hs.
    - [X] Checklist de la clase.
    - [X] Repaso de la clase anterior
    - [X] Arquitectura CSS.
        - Como ordenamos los archivos antes de ser compilados ?
          - Crear un solo archivo `styles.[ less / sass / scss ]` que se compilara en un solo archivo `styles.css`.
          - Recordar que los archivos con inicial `_[...]` (guion bajo) son de ambito privado para el compilador.
          - Nomenclatura de los archivos :
            | Inicial    | Ambito     |
            |:----------:|:-----------|
            | `_l-[...]` | Layout     |
            | `_u-[...]` | Utilities  |
            | `_c-[...]` | Components |
            | `_h-[...]` | Helpers    |
            | `_e-[...]` | Extends    |
    
    - [X] Introduccion a LESS & SASS ( y SCSS ).

---
3. Clase [4/5] - `12/12/2022` de 20 a 22 hs.
    - [X] Checklist de la clase
    - [X] Repaso de la clase anterior.
    - [X] Compiladores + NodeJS.
        - `node init` para iniciar el proyecto con NodeJS y NPM.
        - Creamos un script en el archivo `package.json` para compilar SASS.
    - [X] Normalizador y Reset en Vanilla CSS.
        - [Reset CSS](https://raw.githubusercontent.com/elad2412/the-new-css-reset/main/css/reset.css)
        - [New Nornalizador CSS](https://raw.githubusercontent.com/necolas/normalize.css/master/normalize.css) 
    - [ ] Operaciones ~~matematicas~~ con LESS & SASS.

---
4. Clase [5/6] - `14/12/2022` de 20 a 22 hs.
    - [X] Checklist de la clase.
    - [X] Repaso de la clase anterior.
    - [x] Funciones con less.
    - [X] @import vs @use.
    - [X] Variables con SASS.
    - [ ] Funciones con SASS.

5. Clase [0/3] - `19/12/2022` de 20 a 22 hs.
    - [X] Checklist de la clase.
    - [X] Repaso de la clase anterior.
    - [ ] ~~Uso de PostCSS~~.
    - [ ] Trabajo de clase con SASS.
      - [X] List
      - [x] Maps
      - [X] @mixin ( + default ) / @include
      - [X] @for
    - [ ] Funciones avanzadas con SASS ( Maps + @mixin + @for).
    - [ ] Bucles y condicionales con SASS.

6. Clase [0/6] - `21/12/2022` de 20 a 22 hs. 
    - [ ] Checklist de la clase.
    - [ ] Repaso de la clase anterior.

7. Clase [0/6] - `26/12/2022` de 20 a 22 hs.
    - [ ] Checklist de la clase.
    - [ ] Repaso de la clase anterior.
    - [ ] Transformaciones.
    - [ ] Transformaciones avanzadas.
    - [ ] Transiciones.
    - [ ] Transiciones avanzadas.
    - [ ] Animaciones.
    - [ ] Animaciones avanzadas.
    - [ ] Conceptos avanzados.
    - [ ] Animaciones y JS.

8. Clase [0/6] - `28/12/2022` de 20 a 22 hs.
    - [ ] Checklist de la clase.
    - [ ] Repaso de la clase anterior
    - [ ] Repaso de LESS y SASS.
    - [ ] Estructura de un proyecto completo con SASS.
    - [ ] Cierre final.
