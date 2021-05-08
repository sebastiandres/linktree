# linktree

**Objective**: Emulate, as simply as possible, the behavior and appeareance of linktree. This allows to have a second level of links for a given subject, that can be stored and display directly on a repository.

* **links_v1.html**: The first functional version. Mimics the colors and buttons with bare html + css. Does not handle: orientation/smartphones, proper size of button,

* **links_v2.html**: Second version, handles selective orientation. Gracias a:
  * https://developer.mozilla.org/en-US/docs/Web/CSS/@media/orientation : Definir selectivamente segun orientación.
  * https://stackoverflow.com/questions/11516291/css-get-height-of-screen-resolution : Definir en proporcion al ancho (vh, vw)

** Testing it**:
  * Just go to [home](https://raw.githack.com/sebastiandres/linktree/main/home.html) or click on the file online_test.html.
  * online_test is a simple redirect as in https://www.w3schools.com/howto/howto_js_redirect_webpage.asp