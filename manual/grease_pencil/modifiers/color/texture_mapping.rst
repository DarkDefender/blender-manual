.. index:: Grease Pencil Modifiers; Texture Mapping Modifier
.. _bpy.types.TextureGpencilModifier:

************************
Texture Mapping Modifier
************************

The *Texture Mapping* Modifier change the strokes texture UV position.


Options
=======

.. figure:: /images/grease-pencil_modifiers_color_texture_mapping_panel.png
   :align: right

   Texture Mapping.

Mode
   The texture transformation will be applied to the stroke/fill or stroke UVs.

   Stroke
      Stroke Fit Method
         Selects the texture fitting method.

         Constant Length
            The texture keep a consistent length along the strokes.

         Stroke Length
            The texture is normalized to fit the stroke length.

      UV Offset
         Moves the texture along the strokes.

      Scale
         Factor for the texture scale.

   Fill
      Fill Rotation
         Sets the texture angle.

      Offset
         Moves the texture origin.

         X, Y

      Scale
         Factor for the texture scale.


Influence
---------

See :ref:`grease-pencil-modifier-influence-filters`.


Example
=======

.. list-table:: Opacity Factor samples.

   * - .. figure:: /images/grease-pencil_modifiers_color_texture_mapping-1.png
          :width: 200px

          Rotation: 0°.

     - .. figure:: /images/grease-pencil_modifiers_color_texture_mapping-2.png
          :width: 200px

          Rotation: 45°.

     - .. figure:: /images/grease-pencil_modifiers_color_texture_mapping-3.png
          :width: 200px

          Rotation: 90°.
