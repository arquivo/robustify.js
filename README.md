# robustify.js

This project was **abandoned** because the robustify script broke the navigability across web-archived pages. Now, we suggest a soft-404 approach.

robustify.js is a javascript that attempts to fight [link rot](https://en.wikipedia.org/wiki/Link_rot) or content drift with an implementation of Herbert Van de Sompel's [Memento Robust Links - Link Decoration](http://robustlinks.mementoweb.org/spec/) specification, in context of the [Hiberlink](http://hiberlink.org/) project.

robustify.js will make any clicked hyperlink test if the linked page is available online. If it is not, it will redirect the user to a web archive, by default using the [Memento Time Travel service](http://timetravel.mementoweb.org/).

This repository is a fork from robustify.js, where is provided a customized version named [robustifyArquivoPT.js](https://github.com/arquivo/robustify.js/blob/master/js/robustifyArquivoPT.js) that use the [Arquivo.pt Robustify Service](http://robustify.arquivo.pt) to verify the status code of a URL and retrieving an archived version of the URL from the Arquivo.pt infrastructure.

Information about how to use robustify with Arquivo.pt on the [Wiki](https://github.com/arquivo/robustify.js/wiki).

Websites using the robustify.js with [Arquivo.pt](http://arquivo.pt) infrastrutucture:
- http://sobre.arquivo.pt
- http://visibilidade.net
- http://semplanos.com
- http://cascaisgarage.pt
