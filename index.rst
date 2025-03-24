.. CPU MOCKUP UP board for P5 documentation master file, created by
   sphinx-quickstart on Wed Mar 19 10:08:30 2025.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.
   


P5 CPU MOCKUP UP board with Dual processor AM6442+AM2434
================================================================================================================

P5 CPU mockup module is designed for Powerlogic P5 for Spear1380 EOL and FPGA-free(supply chain risk) to extend the life cycle of P5.

The purpose of designing this board is to verify whether the TI-based platform can cover all the functions of the current P53.


SPEAR1380 (HUA35783) allocation of LTB
---------------------------------------------------------------------------------------------------------------


.. note::
	
	According to current forecast, SPEAR1380 can cover P5 until early 2027.
	
.. tip::
	
	hello danny??

.. sourcecode:: asm
	
    SET     r30, r30, PE_BIT    ; PE_BIT置位(正常显示模式) | Set PE for normal display
	SET     r30, r30, HSYNC_BIT ; bit 17
	SET     r30, r30, VSYNC_BIT ; bit 18
	

This is the introduction section.

.. warning::
	
	hello danny!!


This is the installation section.

.. _fig-label:
.. figure:: _static/images/480_272.png
   :width: 100%
   :align: center
   :alt: pic1
   
   系统架构示意图

参见 :numref:`Figure %s <fig-label>`，该图展示了...

.. _fig-label2:
.. figure:: _static/images/480_272.png
   :width: 100%
   :align: center
   :alt: pic1
   
   系统架构示意图2
   
参见 :numref:`Figure %s <fig-label2>`，该图展示了...

Add your content using ``reStructuredText`` syntax. See the
`reStructuredText <https://www.sphinx-doc.org/en/master/usage/restructuredtext/index.html>`_
documentation for details.

.. toctree::
   :maxdepth: 4             
   :caption: key section
   :numbered:                

   chapter1/index            
   chapter2/index
   chapter3/index
