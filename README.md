# slides

This is a template for projects with presentations or slides. It is strongly encouraged to use it as such (but you can of course go old school and do a fork)

It holds plenty of slides giving a small glimpse of what is possible.

It uses [reveal.js](https://revealjs.com/) as foundation - if you have questions about how to do something - please see there...

The presentation skeleton is done in a way that you only have to write markdown to fill it: You have to edit [slides.md](slides.md) to do so. 
But it is of course possible to unleash the full power of
[reveal.js](https://revealjs.com/) by editing [index.html](index.html).

Whenever you commit changes to the project, it is rebuilt via a CI/CD pipeline so that the live version (uses pages functionality) is always up to date.

You will - regardless whether you forked or used the template - have to edit the link to the live presentation here:

[Live](https://elbosso.github.io/reveal.js-slides-template)

You can of course write the presentation locally and dont have to wait for the github pipeline to run after each commit - 
for that you just have to open [index.html](index.html) in a recent browser.
But beware: It might not work out of the box as for example firefox blocks loading local files because of 
[CORS](https://developer.mozilla.org/en-US/docs/Web/HTTP/CORS/Errors/CORSRequestNotHttp).
