# Sintaxe de escritura con markdown en documentación de GitHub 

## - Índice
- [Sintaxe de formato básica](#sintaxe-de-formato-básica)
  - [Encabezados](#encabezados)
  - [Estilos de texto](#estilos-de-texto)
  - [Entrecomillado de texto](#entrecomillado-de-texto)
  - [Código de cita](#código-de-cita)
  - [Modelos de cor compatibles](#modelos-de-cor-compatibles)
  - [Vínculos](#vínculos)
  - [Enlaces de sección](#enlaces-de-sección)
  - [Vínculos relativos](#vínculos-relativos)
  - [Imaxes](#imaxes)
  - [Listas](#listas)
  - [Listas de tarefas](#listas-de-tarefas)
  - [Mencionar persoas e equipos](#mencionar-persoas-e-equipos)
  - [Facer referencia a propostas e solicitudes de extracción](#facer-referencia-a-propostas-e-solicitudes-de-extracción)
  - [Facer referencia a recursos externos](#facer-referencia-a-recursos-externos)
  - [Cargar activos](#cargar-activos)
  - [Usar emojis](#usar-emojis)
  - [Párrafos](#párrafos)
  - [Notas ó pie](#notas-ó-pie)
  - [Alertas](#alertas)
  - [Ocultar o contido con comentarios](#ocultar-o-contido-con-comentarios)
  - [Ignorar formato de Markdown](#ignorar-formato-de-markdown)
  - [Inhabilitar a representación da linguaxe de marcado](#inhabilitar-a-representación-da-linguaxe-de-marcado)


## Sintaxe de formato básica

### Encabezados
Os encabezados en Markdown créanse antepoñendo de 1 a 6 símbolos #, seguido dun espazo e o texto do encabezado. Cantos máis símbolos se antepoñan ó encabezado menor será o tamaño do texto:

# Este é o encabezado con 1 '#'
## Este é o encabezado con 2 '#'
### Este é o encabezado con 3 '###'
#### Este é o encabezado con 4 '####'
##### Este é o encabezado con 5 '#####'
###### Este é o encabezado con 6 '######'
-------------------

### Estilos de texto
Para resaltar un texto en negrita empréganse os símbolos ** ou __ o inicio e final do texto a resaltar.

- **Este texto está en negrita empregando os símbolos:`**`**

- __Este tamén pero cos símbolos:`__`__ 

Para resaltar un texto en cursiva empréganse os símbolos `_` ou `*` ó inicio e final do texto a resaltar.

- _Este texto está en cursiva empregando o símbolo:`_`_

- *Este tamén pero co símbolo:`*`*

Para resaltar un texto mediante o tachado emprégase os símbolos `~~` ó inicio e ó final do texto a resaltar.

- ~~Este texto está tachado~~

-------------------

### Entrecomillado de texto:
Pódese entrecomillar un texto co símbolo `>` para resaltar unha cita.

> Se a vida son dous días, quedo co sábado e co domingo.
-------------------

### Código de cita

Pódese resaltar un código mediante comillas simples ` ou un bloque de código entre comillas triples ```. 

Comando simple:
`git init`

Bloque de código:
```
git status
git add
git commit
```
-------------------
### Modelos de cor compatibles

Cando aparece algún problema, ou nas solicitudes de incorporación de código e nos debates, podemos resaltar texto con cores dentro dunha oración mediante comillas simples, en tres formatos admitidos hex `#0969DA`, rgb `rgb(9, 105, 218)` ou hsl `hsl(212, 92%, 45%)`. A visualización de cor só se admite en problemas, solicitudes de incorporación de cambios e debates, polo que non se implementa neste documento. 

A cor de fondo no modo claro é `#ffffff` e `#000000` para o modo oscuro.

-------------------

### Vínculos

Pódese crear un vínculo en liña escribindo o texto entre corchetes `[]` e a URL entre parénteses `()`.

Existen [métodos abreviados ou atallos do teclado](https://docs.github.com/es/get-started/accessibility/keyboard-shortcuts) para incorporar a sintaxe a documentos de GitHub, que se poden ver no seguinte enlace. 

-------------------

### Enlaces de sección

-------------------

### Vínculos relativos

-------------------

### Imaxes

-------------------

Especificar un tema en el que se muestra una imagen

-------------------

### Listas

Pódense crear listas desordeadas empregando os símbolos `-`, `*` ou `+` antes da liña de texto.

+ Contornos de desenvolvemento
- Sistemas informáticos
* Programación
* Linguaxe de marcas
- Bases de datos
+ Formación e orientación laboral

Para crear listas ordeadas, en lugar de empregar os símbolos anteriores, antepoñemos un número á liña de texto.

1. Contornos de desenvolvemento
2. Sistemas informáticos
3. Programación
4. Linguaxe de marcas
5. Bases de datos
6. Formación e orientación laboral
  
#### Listas aniñadas

Para crear listas aniñadas temos que deixar sangría nos elementos inferiores a outro.

1. Asignaturas primeiro curso de DAM:
   + Contornos de desenvolvemento
       * Teoría
       - Práctica
   + Sistemas informáticos
       * Teoría
       - Práctica
   - Programación
   * Linguaxe de marcas
   - Bases de datos
   - Formación e orientación laboral
     

-------------------

### Listas de tarefas

Tamén podemos facer listas de tarefas, para o que empregamos un guión `-` antepoñendo a liña de texto, seguido de corchetes `[]` e o texto. Para marcar unha tarefa como realizada poñemos unha `x` entre os corchetes.

Lista da compra:
- [x] Patacas
- [x] Ovos
- [] Sal
- [] Aceite
-------------------

### Mencionar persoas e equipos

-------------------

### Facer referencia a propostas e solicitudes de extracción

-------------------

### Facer referencia a recursos externos

-------------------

### Cargar activos

-------------------

### Usar emojis

-------------------

### Párrafos

-------------------

### Notas ó pé

Pódense agregar notas ó pé empregando `^` e un número entre corchetes `[]` o final da liña que queremos referenciar cunha nota ó pé, que se verá no pé de páxina. A información da nota especifícase do mesmo xeito que cando a agregamos despois de dous puntos `:`.

As notas ó pé vense ó pé de páxina[^1].

[^1]:Esta é unha nota ó pé.

-------------------

### Alertas

As alertas baséanse na sintaxe blockquote e empréganse para resaltar información crítica. Amósanse con cores no código e iconas distintas segundo a importancia do contido. Edeme empregarse unha liña blockquote especificando o tipo de alerta seguida da información entrecomillada con `>`.

> [!NOTE]
> Información importante que os usuarios deberían coñecer.

> [!TIP]
> Comentarios de axuda para facilitar ou facer cousas dunha forma máis sinxela.

> [!IMPORTANT]
> Información clave que os usuarios precisan saber para acadar os seus resultados.

> [!WARNING]
> Información urxente que necesita a atención inmediata do usuario e evitar problemas.

> [!CAUTION]
> Comentarios sobre riscos ou resultados negativos de certas accións.

-------------------

### Ocultar o contido con comentarios

Para facer comentarios ocultos empregamos a mesma sintaxte que para un comentario en HTML.

<!-- Este contido non aparece na visualización do documento -->

-------------------

### Ignorar formato de Markdown

GitHub vai ignorar o formato de marcado se empregamos unha barra inclinada `\` antes do carácter que queremos omitir.

*Este texto está en cursiva*

\*Este non porque omitimos a linguaxe de marcado para os símbolos `*` antepoñendo `\`.\*

-------------------

### Inhabilitar a representación da linguaxe de marcado

-------------------

Organizar la información en tablas
Creación de una tabla
Formatear el contenido dentro de tu tabla

-------------------

Organización de la información con secciones contraídas
Creación de una sección contraída

-------------------

Crear y resaltar bloques de código
Bloques de código delimitados
Resaltado de sintaxis

-------------------

Crear diagramas
Crear diagramas de Mermaid

-------------------

Expresiones matemáticas

-------------------

Adjuntar archivos

-------------------


