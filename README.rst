========
Demo API
========

:Version: 1.0.1
:Source: https://github.com/maykinmedia/demo-api
:Keywords: VNG, VNG-realisatie, demo, api

Een voorbeeld van een OAS 3.0 API met bijbehorende referentie implementatie.
Deze repository is hoofdzakelijk voor intern gebruik bij VNG.

De referentie implementatie staat in de `API component repository`_.


Inleiding
=========

Om verschillende zaken gerelateerd aan het nieuwe API-landschap te begrijpen,
beheren, ontwikkelen, uitrollen, testen, etc. kan deze repository gebruikt 
worden.

Het is een volledig werkende API met 1 resource en endpoint en is een
vereenvoudigde weergave van allerlei (ontwerp)beslissingen aangaande gebruikte
technieken zoals RESTful APIs, Docker, OAS 3.0, versiebeheer, etc.


API versies
===========

=========== =============== ===================================================
Versie      Release datum   Opmerkingen
=========== =============== ===================================================
`1.0.1`_    2017-02-01      Patch release
`1.0.0`_    2017-01-01      Initiële release van API versie 1
=========== =============== ===================================================

Zie ``CHANGELOG.rst`` voor een volledige geschiedenis van de API.

**API release**

Een major versie update (bijv. van 1.x naar 2.x) bevat breaking changes t.o.v.
de vorige versie.

**Update release**

Een minor versie update bevat inhoudelijke wijzigingen aan de API die geen
breaking changes betreffen.

**Patch release**

Een patch versie is een minimale wijziging die geen inhoudelijke wijziging
betreft maar voornamelijk bedoeld is voor documentatie wijzigingen.


Ondersteuning
-------------

Elke major API versie krijgt minimaal 1 jaar ondersteuning vanaf de release
datum van de volgende major API versie.

=========== =============== ===================================================
Versie      Release datum   Einddatum ondersteuning
=========== =============== ===================================================
1.x         2017-01-01
=========== =============== ===================================================


Referenties
===========

* `API component repository`_
* `Issues <https://github.com/maykinmedia/demo-api/issues>`_
* `Code <https://github.com/maykinmedia/demo-api>`_

.. _API component repository: https://github.com/maykinmedia/demo-api-component
.. _1.0.0: http://rebilly.github.io/ReDoc/?url=https://raw.githubusercontent.com/maykinmedia/demo-api/1.0.0/openapi.yaml
.. _1.0.1: http://rebilly.github.io/ReDoc/?url=https://raw.githubusercontent.com/maykinmedia/demo-api/1.0.1/openapi.yaml


Licentie
========

Copyright © VNG Realisatie 2019

Licensed under the EUPL_

.. _EUPL: LICENCE.md
