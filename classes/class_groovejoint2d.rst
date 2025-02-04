:github_url: hide

.. DO NOT EDIT THIS FILE!!!
.. Generated automatically from Godot engine sources.
.. Generator: https://github.com/godotengine/godot/tree/master/doc/tools/make_rst.py.
.. XML source: https://github.com/godotengine/godot/tree/master/doc/classes/GrooveJoint2D.xml.

.. _class_GrooveJoint2D:

GrooveJoint2D
=============

**Inherits:** :ref:`Joint2D<class_Joint2D>` **<** :ref:`Node2D<class_Node2D>` **<** :ref:`CanvasItem<class_CanvasItem>` **<** :ref:`Node<class_Node>` **<** :ref:`Object<class_Object>`

Groove constraint for 2D physics.

.. rst-class:: classref-introduction-group

Description
-----------

Groove constraint for 2D physics. This is useful for making a body "slide" through a segment placed in another.

.. rst-class:: classref-reftable-group

Properties
----------

.. table::
   :widths: auto

   +---------------------------+--------------------------------------------------------------------+----------+
   | :ref:`float<class_float>` | :ref:`initial_offset<class_GrooveJoint2D_property_initial_offset>` | ``25.0`` |
   +---------------------------+--------------------------------------------------------------------+----------+
   | :ref:`float<class_float>` | :ref:`length<class_GrooveJoint2D_property_length>`                 | ``50.0`` |
   +---------------------------+--------------------------------------------------------------------+----------+

.. rst-class:: classref-section-separator

----

.. rst-class:: classref-descriptions-group

Property Descriptions
---------------------

.. _class_GrooveJoint2D_property_initial_offset:

.. rst-class:: classref-property

:ref:`float<class_float>` **initial_offset** = ``25.0``

.. rst-class:: classref-property-setget

- void **set_initial_offset** **(** :ref:`float<class_float>` value **)**
- :ref:`float<class_float>` **get_initial_offset** **(** **)**

The body B's initial anchor position defined by the joint's origin and a local offset :ref:`initial_offset<class_GrooveJoint2D_property_initial_offset>` along the joint's Y axis (along the groove).

.. rst-class:: classref-item-separator

----

.. _class_GrooveJoint2D_property_length:

.. rst-class:: classref-property

:ref:`float<class_float>` **length** = ``50.0``

.. rst-class:: classref-property-setget

- void **set_length** **(** :ref:`float<class_float>` value **)**
- :ref:`float<class_float>` **get_length** **(** **)**

The groove's length. The groove is from the joint's origin towards :ref:`length<class_GrooveJoint2D_property_length>` along the joint's local Y axis.

.. |virtual| replace:: :abbr:`virtual (This method should typically be overridden by the user to have any effect.)`
.. |const| replace:: :abbr:`const (This method has no side effects. It doesn't modify any of the instance's member variables.)`
.. |vararg| replace:: :abbr:`vararg (This method accepts any number of arguments after the ones described here.)`
.. |constructor| replace:: :abbr:`constructor (This method is used to construct a type.)`
.. |static| replace:: :abbr:`static (This method doesn't need an instance to be called, so it can be called directly using the class name.)`
.. |operator| replace:: :abbr:`operator (This method describes a valid operator to use with this type as left-hand operand.)`
