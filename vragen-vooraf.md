Dan kunnen we nu gaan beginnen met het experiment! Allereerst hebben we een paar algemene
vragen voor je.

::multiplechoice
---
q: Met welk geslacht identificeer jij jezelf het meest?
options: ['Man','Vrouw','Zeg ik liever niet','Anders, namelijk...']
reference: geslacht
open: Anders, namelijk...
---
::

::multiplechoice
---
q: Wat is je leeftijd?
reference: leeftijd
options: 
  - 18-25
  - 26-30
  - 31-35
  - 36-40
  - 41-45
  - 46-50
  - 51-55
  - 56-60
  - 61-65
  - 65+
---
::

::multiplechoice
---
q: Wat is je hoogst voltooide opleiding?
reference: opleiding
options:
  - Geen
  - Basisonderwijs
  - Voorbereidend middelbaar beroepsonderwijs (vmbo)
  - Middelbaar beroepsonderwijs (mbo)
  - Hoger algemeen voortgezet onderwijs (havo)
  - Voorbereidend wetenschappelijk onderwijs (vwo)
  - Hoger beroeps onderwijs (hbo)
  - Wetenschappelijk onderwijs (wo)
---
::

::howoften
---
q: Hoe vaak lees je online nieuwsberichten? (bijv. via sociale media of op nieuwswebsites)
reference: leesnieuwsberichten
---
::


::howoften
---
q: Hoe vaak lees je de reacties onder deze online nieuwsberichten?
reference: leesreacties
---
::

::howoften
---
q: Hoe vaak reageer je zelf op deze online nieuwsberichten?
reference: reageeronline
---
::

::volgende{link="/voor-text-1" opslaan=true}
---
check: ['geslacht', 'leeftijd', 'opleiding', 'leesnieuwsberichten', 'leesreacties', 'reageeronline']
---
Start de test 
::
