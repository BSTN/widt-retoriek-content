::multiplechoice
---
q: 1. Om mee te kunnen doen, moet je 18 jaar of ouder zijn. Is dit voor jou het geval?
options: ['ja', 'nee']
reference: vooraf1
---
::

::multiplechoice
---
q: 2. Daarnaast moet jouw moedertaal Nederlands zijn. Is dat het geval?
options: ['ja', 'nee']
reference: vooraf2
---
::

::multiplechoice
---
q: 3. Met welk geslacht identificeer jij jezelf het meest?
options: ['Man','Vrouw','Zeg ik liever niet','Anders, namelijk...']
reference: vooraf3
open: Anders, namelijk...
---
::

::multiplechoice
---
q: 4. Wat is je leeftijd?
reference: leeftijd
options: 
  - 18-25
  - 26-30
  - 31-35
  - 36-40
  - 41-45
  - 46-50
  - 51-55
::

::multiplechoice
---
q: 5. Wat is je hoogst voltooide opleiding?
reference: vooraf5
options:
  - Geen
  - Basisonderwijs
  - Voorbereidend middelbaar beroepsonderwijs (vmbo)
  - Middelbaar beroepsonderwijs (mbo)
  - Hoger algemeen voortgezet onderwijs (havo)
  - Voorbereidend wetenschappelijk onderwijs (vwo)
  - Hoger beroeps onderwijs (hbo)
  - wetenschappelijk onderwijs (wo)
::

::howoften
---
q: 6. Hoe vaak lees je online nieuwsberichten?
reference: vooraf6
---
::


::howoften
---
q: 7. Hoe vaak lees je de reacties onder online nieuwsberichten?
reference: vooraf7
---
::

::howoften
---
q: 8. Hoe vaak reageer je zelf op online nieuwsberichten?
reference: vooraf8
---
::

::volgende{link="/voor-text-1" opslaan=true}
---
check: ['vooraf1','vooraf2','vooraf3', 'leeftijd', 'vooraf5', 'vooraf6', 'vooraf7', 'vooraf8']
---
Start de test 
::