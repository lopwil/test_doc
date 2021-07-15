*****************
Ceci est un titre
*****************

----
Ceci est une séparation

Ceci est un titre de niveau 1
=============================

Ceci est un titre de niveau 2
-----------------------------

Ceci est un titre de niveau 3
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Ceci est un titre de niveau 4
+++++++++++++++++++++++++++++

Ceci est un titre de niveau 5
*****************************

----

Ceci est un lien vers un titre: `Ceci est un titre de niveau 1`_

----

.. _lien_tableaux:
Ceci est un tableau
===================

==== ==== ========
A    B    A et B
--------- --------
\         a et b
==== ==== ========
Faux Faux Faux
Vrai Faux Faux
==== ==== ========

.. table:: Ceci est un tableau ayant un titre

==== ==== ========
A    B    A et B
--------- --------
\         a et b
==== ==== ========
Faux Vrai Faux
Vrai Vrai Vrai
==== ==== ========

----

Ceci est la date : |today|

Ceci est la version : |release|

----

Ceci est une substitution : |remplacement|

.. |remplacement| replace:: un mot substitué

----

Ceci est une table des matières :

.. contents:: Table des matières

        :depth: 2
        :local:
        :backlinks: top

----

Ceci est une image :

.. image:: logo-cebox-wisper.png

----

Ceci est un encadré flottant :

.. sidebar:: Encadré flottant
                :subtitle: Sous-titre

                `Syntaxe`_
.. _Syntaxe: http://espe-rtd-reflexpro.u-ga.fr/docs/sandbox2/fr/latest/_sources/syntaxe_rest.txt


----

Les admonitions :

.. admonition:: Ceci est une admonition avec un titre modifiable

        `Syntaxe`_

.. note:: L'intitulé de cette admonition et des suivantes dépendent de la langue définie dans le fichier conf.py.

.. caution:: `Syntaxe`_

.. danger:: `Syntaxe`_

.. error:: `Syntaxe`_

.. hint:: `Syntaxe`_

.. important:: `Syntaxe`_

.. tip:: `Syntaxe`_

.. warning:: `Syntaxe`_

----

Lien vers une ancre :

:ref:`lien_tableaux` 

----

Ceci est un widget d'intégration de code :

.. code-block:: bash

        sudo

----

Intégration d'une vidéo dans une page

.. raw:: html
        
        <iframe width="560" height="315" src="https://www.youtube.com/embed/IGeUST2j-RU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>