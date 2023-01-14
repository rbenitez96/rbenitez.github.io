# Práctica 3


En la actividad previa revisamos el contenido de elementos en línea y en bloque. Si desea revisar el contenido de los temas revisados en la actividad previa visite [S01D03](https://github.com/Bootcamp-Espol/FSD01/tree/main/S01D03/previa).

<a name="practica"> </a>

## 💻 Parte práctica

:one:  Modifique el archivo _index.html_ con sus datos de acuerdo con las siguientes consideraciones:

* Identifique la jerarquía de las etiquetas, por ejemplo: en una sección, una etiqueta `<h2>` precede a una etiqueta `<h3>`.  
* Valore el uso adecuado de las etiquetas y sus atributos, a partir de la documentación del [Estándar de la W3C](https://html.spec.whatwg.org/multipage/), la referencia del [MDN Web Docs](https://developer.mozilla.org/es/docs/Web/HTML/Element) y/o la referencia de [W3Schools](https://www.w3schools.com/tags/default.asp). Algunas consideraciones identificadas hasta ahora:

  + Use etiquetas `<table>` solo para organizar datos. Use etiquetas `<ol>` para listar datos cuyo orden es inamovible.
  + En el elemento `<label>` use el atributo **for** para indicar una referencia con un elemento `<input>` mediante el atributo **id**. 

* De ser necesario, use etiquetas semánticas (como `<section>` o `<aside>`) para contener o separar las secciones de su sitio web.

:two:     Use el [Inspector](https://carontestudio.com/blog/que-es-el-inspector-de-elementos-y-como-se-utiliza/) de su navegador para ver la jerarquía de elementos HTML de una página web.

:three:   Despliegue su sitio estático mediante las instrucciones del tutorial [GitHub Pages](https://github.com/Bootcamp-Espol/Tutoriales/tree/main/github_pages).

:four: Valide y verifique sus documentos html mediante [W3CValidator](https://validator.w3.org/).

* Realice las modificaciones en el archivo _index.html_ que indica el validador.

:five: Guarde los cambios de su proyecto 

* Primero, en el repositorio local, de acuerdo con las instrucciones en [Repositorio Local](https://github.com/Bootcamp-Espol/Tutoriales/blob/main/git/README.md#repositorio-local)

  + Guarde los cambios, con:

  ```
  git add .
  ```

  + Prepare los cambios, con:

  ```
  git commit -m "comentario de la actualización"
  ```

* Luego, para el repositorio remoto, de acuerdo con las instrucciones en [Repositorio Remoto](https://github.com/Bootcamp-Espol/Tutoriales/blob/main/git/README.md#repositorio-remoto). 

  + Envíe los cambios, con:

  ```
  git push origin main
  ```



<a name="preg_sobre_clases"></a>

## :grey_question: Preguntas sobre la clase

<a name="terminos"></a>

## Términos:

funcionamiento del navegador, despliegue, validadores html 5, versionamiento.

<a name="referencias"></a>

## Referencias

* Validación de errores HTML. (n.d.). Lenguajehtml.Com. Retrieved October 16, 2022, from https://lenguajehtml.com/html/introduccion/validacion-html/
* Markup Validation Service. (n.d.). Validator.W3.Org. Retrieved October 16, 2022, from https://validator.w3.org/
* What is deployment in software & web development? . (2023). Retrieved 14 January 2023, from https://umbraco.com/knowledge-base/deployment/
* Qué es el control de versiones xAtlassian Git Tutorial. (2023). Retrieved 14 January 2023, from https://www.atlassian.com/es/git/tutorials/what-is-version-control