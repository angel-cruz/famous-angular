---
layout: "docs_api"
version: "unstable"
versionHref: "/docs/unstable"
path: "api/directive/faAnimateLeave/"
title: "fa-animate-leave"
header_sub_title: "Directive in module famous.angular"
doc: "faAnimateLeave"
docType: "directive"
---

<div class="improve-docs">
  <a href='https://github.com/Famous/famous-angular/edit/master/src/scripts/directives/fa-animate-leave.js#L2'>
    Improve this doc
  </a>
</div>





<h1 class="api-title">

  fa-animate-leave



</h1>





Attaches the passed function/expression to Angular ngAnimate "leave" events on the given element.
Useful when you want to manage animations in Famo.us that are tied into Angular's data-driven events, e.g. on directives like ng-repeat, ui-view, and ng-if.






  
<h2 id="usage">Usage</h2>
  
```html
<fa-view ng-repeat="view in views" fa-animate-leave="myAnimationFunction($done)">
</fa-view>
```
  
  

  





