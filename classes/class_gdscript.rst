.. Generated automatically by doc/tools/makerst.py in Godot's source tree.
.. DO NOT EDIT THIS FILE, but the GDScript.xml source instead.
.. The source is found in doc/classes or modules/<name>/doc_classes.

.. _class_GDScript:

GDScript
========

**Inherits:** :ref:`Script<class_script>` **<** :ref:`Resource<class_resource>` **<** :ref:`Reference<class_reference>` **<** :ref:`Object<class_object>`

**Category:** Core

Brief Description
-----------------

A script implemented in the GDScript programming language.

Member Functions
----------------

+--------------------------------------------+----------------------------------------------------------------------------+
| :ref:`PoolByteArray<class_poolbytearray>`  | :ref:`get_as_byte_code<class_GDScript_get_as_byte_code>` **(** **)** const |
+--------------------------------------------+----------------------------------------------------------------------------+
| :ref:`Object<class_object>`                | :ref:`new<class_GDScript_new>` **(** **)** vararg                          |
+--------------------------------------------+----------------------------------------------------------------------------+

Description
-----------

A script implemented in the GDScript programming language. The script exends the functionality of all objects that instance it.

:ref:`new<class_GDScript_new>` creates a new instance of the script. :ref:`Object.set_script<class_Object_set_script>` extends an existing object, if that object's class matches one of the script's base classes.

Member Function Description
---------------------------

.. _class_GDScript_get_as_byte_code:

- :ref:`PoolByteArray<class_poolbytearray>` **get_as_byte_code** **(** **)** const

Returns byte code for the script source code.

.. _class_GDScript_new:

- :ref:`Object<class_object>` **new** **(** **)** vararg

Returns a new instance of the script.

For example:

::

    var MyClass = load("myclass.gd")
    var instance = MyClass.new()
    assert(instance.get_script() == MyClass)


