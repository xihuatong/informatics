_`Option digitmed`
==================

.. currentmodule:: info.docfunc

Description
-----------

Medical image related tools (data mainly in :ref:`DICOM <DICOM>` protocol). Operations include regrouping and
re-sorting slices, read meta information, link to other type of DICOM files and etc. In addition, measurement
for images as feature extraction is also supported. Dependencies of `SimpltITK <http://simpleitk.org>`_ and
`pydicom <https://github.com/pydicom/pydicom>`_ are required.

Namespace of this module is mainly in ``info.toolbox.digitmed.rebuild``. For convenience in practice, use main
entry of ``info.med``.

.. autosummary::
   :nosignatures:

   DcmSetConstructor
   DcmSeries
   dcm_hierarchical_parser
   dcm_attr_loader
   dcm_constructor
   dcm_regroup
   radiomics_features

Docstrings
----------

.. autoclass:: DcmSetConstructor

.. autoclass:: DcmSeries

.. autodata:: dcm_hierarchical_parser
   :no-value:

.. autodata:: dcm_attr_loader
   :no-value:

.. autodata:: dcm_constructor
   :no-value:

.. autodata:: dcm_regroup
   :no-value:

.. autodata:: radiomics_features
   :no-value:

----

:Authors: Chen Zhang
:Version: 0.0.4
:|create|: Jun 29, 2023
