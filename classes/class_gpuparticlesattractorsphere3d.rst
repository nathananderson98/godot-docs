:github_url: hide

.. Generated automatically by doc/tools/make_rst.py in Godot's source tree.
.. DO NOT EDIT THIS FILE, but the GPUParticlesAttractorSphere3D.xml source instead.
.. The source is found in doc/classes or modules/<name>/doc_classes.

.. _class_GPUParticlesAttractorSphere3D:

GPUParticlesAttractorSphere3D
=============================

**Inherits:** :ref:`GPUParticlesAttractor3D<class_GPUParticlesAttractor3D>` **<** :ref:`VisualInstance3D<class_VisualInstance3D>` **<** :ref:`Node3D<class_Node3D>` **<** :ref:`Node<class_Node>` **<** :ref:`Object<class_Object>`

Ellipse-shaped 3D particle attractor affecting :ref:`GPUParticles3D<class_GPUParticles3D>` nodes.

Description
-----------

Ellipse-shaped 3D particle attractor affecting :ref:`GPUParticles3D<class_GPUParticles3D>` nodes.

\ **Note:** Particle attractors only affect :ref:`GPUParticles3D<class_GPUParticles3D>`, not :ref:`CPUParticles3D<class_CPUParticles3D>`.

Properties
----------

+---------------------------+--------------------------------------------------------------------+---------+
| :ref:`float<class_float>` | :ref:`radius<class_GPUParticlesAttractorSphere3D_property_radius>` | ``1.0`` |
+---------------------------+--------------------------------------------------------------------+---------+

Property Descriptions
---------------------

.. _class_GPUParticlesAttractorSphere3D_property_radius:

- :ref:`float<class_float>` **radius**

+-----------+-------------------+
| *Default* | ``1.0``           |
+-----------+-------------------+
| *Setter*  | set_radius(value) |
+-----------+-------------------+
| *Getter*  | get_radius()      |
+-----------+-------------------+

The attractor sphere's radius in 3D units.

\ **Note:** Stretched ellipses can be obtained by using non-uniform scaling on the ``GPUParticlesAttractorSphere3D`` node.

.. |virtual| replace:: :abbr:`virtual (This method should typically be overridden by the user to have any effect.)`
.. |const| replace:: :abbr:`const (This method has no side effects. It doesn't modify any of the instance's member variables.)`
.. |vararg| replace:: :abbr:`vararg (This method accepts any number of arguments after the ones described here.)`
.. |constructor| replace:: :abbr:`constructor (This method is used to construct a type.)`
.. |static| replace:: :abbr:`static (This method doesn't need an instance to be called, so it can be called directly using the class name.)`
.. |operator| replace:: :abbr:`operator (This method describes a valid operator to use with this type as left-hand operand.)`
