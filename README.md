# linktree

**Objective**: Emulate, as simply as possible, the behavior and appeareance of linktree. This allows to have a second level of links for a given subject, that can be stored and display directly on a repository.

* **links_v1.html**: The first functional version. Mimics the colors and buttons with bare html + css. Does not handle: orientation/smartphones, proper size of button,

* **links_v2.html**: Second version, handles selective orientation. Gracias a:
  * https://developer.mozilla.org/en-US/docs/Web/CSS/@media/orientation : Definir selectivamente segun orientación.
  * https://stackoverflow.com/questions/11516291/css-get-height-of-screen-resolution : Definir en proporcion al ancho (vh, vw)

* **links_v3.html**: Third version, handles the details of smartphone: proper width and height, text wrapping, and font size. Includes a "linktree version" so its easier to know when you need to upgrade an old link.

* **links_v4.html**: Fourth version. Let's move all the style to a file, so we only need to update that instead of updating all the files, d'ouh! That's why css where invented on the first place, to separate CONTENT from STYLE.

** Testing it**:
  * Just go to [index.html](https://sebastiandres.github.io/linktree/index.html) or, if at the local repo, click on the file online_test.html.
  * online_test is a simple redirect
  * 