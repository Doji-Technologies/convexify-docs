Getting started
===============

A simple example on how to use the library can be found in the 'Basic Sample' that can be imported via the Package Manager.

Essentially, this is the code necessary to calculate a convex decomposition:

   .. code-block:: C#
      :linenos:

      vhacd = new VHACD();
	  ConvexDecomposition cd = vhacd.Compute(mesh);
      vhacd.GenerateColliders(cd, gameObject);

That's really all there is to it. To configure the precision/speed of the calculations, there's a 'Parameter' instnace you can modify like so:

   .. code-block:: C#
      :linenos:

      vhacd.Parameters.Resolution = 64;

This will increase the resolution that the algorithm uses, which will result in a more precise decomposition, but will also take longer to run.
For more information on all the settings visit the documentation on the link above.