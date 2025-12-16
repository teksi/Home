Modules
===========

The TEKSI community helps to devek various modules to address the management of public infrastructure :
 * wastewater collection and treatment network, 
 * drinking water distribution network, 
 * district heating network, 
 * cemetery, 
 * roads, 
 * lighting
are some examples.

.. image::
   https://github.com/teksi/Home/blob/main/Ressources/Logos/general/240515-teksi-illus.png?raw=true

They are all developed in open-source and are freely available under the `AGPLv3 license <https://www.gnu.org/licenses/agpl-3.0.en.html>`_.

They are all based on `QGIS <https://qgis.org/en/site/>`_ and `PostgreSQL/PostGIS <https://www.postgresql.org/>`_ technologies.

The modules are designed to be interoperable with each other. They are usually based on swiss norms and standards, but can be adapted to other countries as well.

Main features
-------------

All TEKSI modules aim to provide the following main features:
- Asset management : inventory, geolocation, documentation, condition assessment, etc.
- Network modelling : hydraulic and hydrologic simulation, water quality simulation, energy flow simulation (depending on the module)
- Operation management : work orders, interventions, maintenance planning, etc.
- Reporting and analysis : dashboards, maps, charts, data export, etc.

For a more detailed overview of the features provided by each module, please refer to the respective module documentation.

Installation and management
---------------------------

Each TEKSI module can be installed and managed using the `TEKSI Module Management Tool (TMMT) <https://plugins.qgis.org/plugins/teksi_module_management_tool>`_ plugin for QGIS.

A detailed guide on how to install and manage TEKSI modules using TMMT is available in the `Provider Guide <../provider-guide/index.rst>`_.

Available Modules
-----------------

Here are the different TEKSI Modules currently available:

.. toctree::
   :maxdepth: 3

   wastewater
   drinking_water
   district_heating

In discussion:

    Cemetery
    Roads
    Lighting