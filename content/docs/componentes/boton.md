---
title: "Botón"
weight: 1
# bookFlatSection: false
# bookToc: true
# bookHidden: false
# bookCollapseSection: false
# bookComments: false
# bookSearchExclude: false
---
este es el contenido de la pagina uno

{{<csstabs "lostabs">}}
    {{< csstab id="0" label="CSS" default="true">}}
        {{< codepen BaYjEar >}}
    {{< /csstab >}}
    {{< csstab id="1" label="Ember">}}
    {{< highlight js >}}
<button class="button btn-primary" local-class="send" onclick={{action ...}}>
{{t "your.translation.path"}}
</button>
    {{< /highlight >}}
    {{< /csstab >}}
{{</csstabs>}}