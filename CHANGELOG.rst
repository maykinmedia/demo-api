=========
Changelog
=========

2.1.0
=====

*2018-10-01*

* De ``Quote``-resource ondersteund nu ``PUT`` (update) en ``PATCH`` (partial
  update) operaties, waarmee een ``Quote`` kan worden bijgewerkt.
* Attribuut ``Quote.laatstBijgewerkt`` (alleen lezen) toegevoegd. Deze wordt
  voorzien van de huidige datum/tijd als de ``Quote`` wordt bijgewerkt. Als het
  object nog nooit is bijgewerkt, heeft dit attribuut de waarde ``null``.
  De standaard waarde na migratie is de waarde ``null``.


2.0.0
=====

*2018-06-01*

* Attribuut ``Quote.bronNaam`` (verplicht) toegevoegd. De standaard waarde na
  migratie is "(Onbekend)". Deze waarde wordt gebruikt voor elke ``Quote`` die
  aangemaakt wordt middels versie 1.x van de API.
* Attribuut ``Quote.bronLink`` (optioneel) toegevoegd.


1.0.1
=====

*2017-02-01*

* Documentatie van ``Quote.url`` attribuut toegevoegd.


1.0.0
=====

*2017-01-01*

* Initiële release.
