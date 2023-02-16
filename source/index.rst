Convexify
=========

.. meta::
   :description lang=en: A Cross-platform Unity utility for reading and writing .ico files.

`Convexify`_ is a cross-platform implementation of the `VHACD`_ algorithm to generate convex compound colliders at runtime.

The package contains a C# port of the renowned VHACD algorithm, which is widely used in game/physics engines to speed up physics calculations because it aids in creation of strictly convex shapes approximating any complex geometry.


In Unity, convex decomposition is required, if you want to have accurate dynamic Rigidbody collisions for a mesh with complex geometry. For more information, refer to the screenshots and the documentation linked below.


This library is intended to be used by those that wish to do convex decomposition at runtime. It's implemented in pure C# and runs on all Platforms that Unity supports.


.. _Convexify: https://assetstore.unity.com/packages/slug/245029
.. _VHACD: https://github.com/kmammou/v-hacd

.. toctree::
   :maxdepth: 2
   :hidden:
   :caption: Overview

   Introduction <self>

.. toctree::
   :maxdepth: 1
   :hidden:
   :caption: Usage

   /getting-started