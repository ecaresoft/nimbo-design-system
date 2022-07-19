---
title: "Input"
weight: 1
# bookFlatSection: false
# bookToc: true
# bookHidden: false
# bookCollapseSection: false
# bookComments: false
# bookSearchExclude: false
---

{{<csstabs "lostabs">}}
    {{< csstab id="0" label="CSS" default="true">}}
        {{< codepen BaYyXOo >}}
    {{< /csstab >}}
    {{< csstab id="1" label="Ember">}}
    {{< highlight js >}}
{{input
    id="name"
    type="text"
    data-autoid="accounts-new-name"
    value=accountSignup.name
    placeholder=(t "components.forms.signup-form.full-name")}}
    {{< /highlight >}}
    {{< /csstab >}}
{{</csstabs>}}