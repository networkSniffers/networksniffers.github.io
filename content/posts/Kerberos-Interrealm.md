---
title: "Kerberos Interrealm"
date: 2024-06-21T10:46:16+02:00
draft: false
tags: ActiveDirectory
---
*Author: LaRancion*

---

Che cosa succede quanto proviamo ad utilizzare un servizio su un Parent Domain o su un altra foresta da un child domain??

**SPOILER**:: I Domain controller possiedono una trust key che utilizzano per le richieste tra domini o foreste in cui è presente un trust.  


{{< figure src="https://raw.githubusercontent.com/networkSniffers/networksniffers.github.io/main/images/interreal%20dark.jpg" >}}





## Risorse 

Il blog di **exploit.ph** (https://exploit.ph/external-trusts-are-evil.html) è ultra interessante e mostra come anche nel caso di un external trust sia possibile muoversi lateralmente creando un oggetto in AD 