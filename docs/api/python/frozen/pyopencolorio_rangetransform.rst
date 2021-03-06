..
  SPDX-License-Identifier: CC-BY-4.0
  Copyright Contributors to the OpenColorIO Project.
  Do not edit! This file was automatically generated by share/docs/frozendoc.py.

.. py:class:: RangeTransform
   :module: PyOpenColorIO

   Represents a range transform

   The Range is used to apply an affine transform (scale & offset) and clamps values to min/max bounds on all color components except the alpha. The scale and offset values are computed from the input and output bounds.

   Refer to section 7.2.4 in specification S-2014-006 "A Common File Format
   for Look-Up Tables" from the Academy of Motion Picture Arts and Sciences and the American Society of Cinematographers.

   The "noClamp" style described in the specification S-2014-006 becomes a MatrixOp at the processor level.


   .. py:method:: RangeTransform.__init__(*args, **kwargs)
      :module: PyOpenColorIO

      Overloaded function.

      1. __init__(self: PyOpenColorIO.RangeTransform) -> None

      Creates an instance of :ref:`RangeTransform`.

      2. __init__(self: PyOpenColorIO.RangeTransform, minInValue: float = nan, maxInValue: float = nan, minOutValue: float = nan, maxOutValue: float = nan, direction: PyOpenColorIO.TransformDirection = <TransformDirection.TRANSFORM_DIR_FORWARD: 0>) -> None

      Creates an instance of :ref:`RangeTransform`.


   .. py:method:: RangeTransform.__str__(self: PyOpenColorIO.RangeTransform) -> str
      :module: PyOpenColorIO


   .. py:method:: RangeTransform.equals(self: PyOpenColorIO.RangeTransform, other: PyOpenColorIO.RangeTransform) -> bool
      :module: PyOpenColorIO

      Checks if this equals other.


   .. py:method:: RangeTransform.getDirection(self: PyOpenColorIO.Transform) -> PyOpenColorIO.TransformDirection
      :module: PyOpenColorIO


   .. py:method:: RangeTransform.getFileInputBitDepth(self: PyOpenColorIO.RangeTransform) -> PyOpenColorIO.BitDepth
      :module: PyOpenColorIO


   .. py:method:: RangeTransform.getFileOutputBitDepth(self: PyOpenColorIO.RangeTransform) -> PyOpenColorIO.BitDepth
      :module: PyOpenColorIO


   .. py:method:: RangeTransform.getFormatMetadata(self: PyOpenColorIO.RangeTransform) -> PyOpenColorIO.FormatMetadata
      :module: PyOpenColorIO


   .. py:method:: RangeTransform.getMaxInValue(self: PyOpenColorIO.RangeTransform) -> float
      :module: PyOpenColorIO

      Get the maximum value for the input.


   .. py:method:: RangeTransform.getMaxOutValue(self: PyOpenColorIO.RangeTransform) -> float
      :module: PyOpenColorIO

      Get the maximum value for the output.


   .. py:method:: RangeTransform.getMinInValue(self: PyOpenColorIO.RangeTransform) -> float
      :module: PyOpenColorIO

      Get the minimum value for the input.


   .. py:method:: RangeTransform.getMinOutValue(self: PyOpenColorIO.RangeTransform) -> float
      :module: PyOpenColorIO

      Get the minimum value for the output.


   .. py:method:: RangeTransform.getStyle(self: PyOpenColorIO.RangeTransform) -> PyOpenColorIO.RangeStyle
      :module: PyOpenColorIO


   .. py:method:: RangeTransform.getTransformType(self: PyOpenColorIO.Transform) -> PyOpenColorIO.TransformType
      :module: PyOpenColorIO


   .. py:method:: RangeTransform.hasMaxInValue(self: PyOpenColorIO.RangeTransform) -> bool
      :module: PyOpenColorIO

      Is the maximum value for the input set?


   .. py:method:: RangeTransform.hasMaxOutValue(self: PyOpenColorIO.RangeTransform) -> bool
      :module: PyOpenColorIO

      Is the maximum value for the output set?


   .. py:method:: RangeTransform.hasMinInValue(self: PyOpenColorIO.RangeTransform) -> bool
      :module: PyOpenColorIO

      Is the minimum value for the input set?


   .. py:method:: RangeTransform.hasMinOutValue(self: PyOpenColorIO.RangeTransform) -> bool
      :module: PyOpenColorIO

      Is the minimum value for the output set?


   .. py:method:: RangeTransform.setDirection(self: PyOpenColorIO.Transform, direction: PyOpenColorIO.TransformDirection) -> None
      :module: PyOpenColorIO

      Note that this only affects the evaluation and not the values stored in the object.


   .. py:method:: RangeTransform.setFileInputBitDepth(self: PyOpenColorIO.RangeTransform, bitDepth: PyOpenColorIO.BitDepth) -> None
      :module: PyOpenColorIO


   .. py:method:: RangeTransform.setFileOutputBitDepth(self: PyOpenColorIO.RangeTransform, bitDepth: PyOpenColorIO.BitDepth) -> None
      :module: PyOpenColorIO


   .. py:method:: RangeTransform.setMaxInValue(self: PyOpenColorIO.RangeTransform, value: float) -> None
      :module: PyOpenColorIO

      Set the maximum value for the input.


   .. py:method:: RangeTransform.setMaxOutValue(self: PyOpenColorIO.RangeTransform, value: float) -> None
      :module: PyOpenColorIO

      Set the maximum value for the output.


   .. py:method:: RangeTransform.setMinInValue(self: PyOpenColorIO.RangeTransform, value: float) -> None
      :module: PyOpenColorIO

      Set the minimum value for the input.


   .. py:method:: RangeTransform.setMinOutValue(self: PyOpenColorIO.RangeTransform, value: float) -> None
      :module: PyOpenColorIO

      Set the minimum value for the output.


   .. py:method:: RangeTransform.setStyle(self: PyOpenColorIO.RangeTransform, style: PyOpenColorIO.RangeStyle) -> None
      :module: PyOpenColorIO

      Set the Range style to clamp or not input values.


   .. py:method:: RangeTransform.unsetMaxOutValue(*args, **kwargs)
      :module: PyOpenColorIO

      Overloaded function.

      1. unsetMaxOutValue(self: PyOpenColorIO.RangeTransform) -> None

      Unset the maximum value for the output.

      2. unsetMaxOutValue(self: PyOpenColorIO.RangeTransform) -> None

      Unset the maximum value for the output.


   .. py:method:: RangeTransform.unsetMinInValue(self: PyOpenColorIO.RangeTransform) -> None
      :module: PyOpenColorIO

      Unset the minimum value for the input.


   .. py:method:: RangeTransform.unsetMinOutValue(self: PyOpenColorIO.RangeTransform) -> None
      :module: PyOpenColorIO

      Unset the minimum value for the output.


   .. py:method:: RangeTransform.validate(self: PyOpenColorIO.Transform) -> None
      :module: PyOpenColorIO

      Will throw if data is not valid.

