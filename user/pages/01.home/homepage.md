---
title: Home
body_classes: title-center title-h1h2

content:
        limit: 3
        items:
                '@page.children': '/giornalino'
        order:
                by: date
                dir: desc
event:
        limit: 1
        items:
                '@page.children': '/eventi'
        order:
                by: date
                dir: desc

event_right:
        limit: 3
        items:
                '@page.children': '/eventi'
        order:
                by: date
                dir: asc
                

---