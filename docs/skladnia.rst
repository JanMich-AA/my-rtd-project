Składnia elementów dokumentu
============================

Nagłówki
--------
Poziom 1
========
Poziom 2
--------
Poziom 3
~~~~~~~~
Poziom 4
^^^^^^^^

Akapity
--------
To jest zwykły akapit tekstu, który opisuje elementy dokumentacji.

Akapity informacyjne
-------------------
.. note::
   To jest akapit typu Note – możesz w nim umieścić ważną informację.

.. tip::
   To jest akapit typu Tip – przydatna wskazówka dla czytelnika.

Fragmenty kodu
--------------
Liniowy: ``print("Hello World")``

Blokowy:
.. code-block:: python

   def hello():
       print("Hello World")

Odnośniki
----------
- Lokalny (do podstrony w dokumentacji): :doc:`autor`
- Zewnętrzny: `Google <https://www.google.com>`_

Listy
-----
Numerowana:
1. Pierwszy punkt
2. Drugi punkt
3. Trzeci punkt

Wypunktowana:
- Punkt A
- Punkt B
- Punkt C

Listy definicji:
Nazwa
  Opis definicji 1
Inny termin
  Opis definicji 2

Obraz
-----
.. image:: path/do/obrazu.png
   :alt: Tekst alternatywny
   :caption: Podpis pod obrazem

Tabela
-----
+-----------+---------+
| Nagłówek  | Wartość |
+===========+=========+
| Pierwszy  | 123     |
+-----------+---------+
| Drugi     | 456     |
+-----------+---------+
