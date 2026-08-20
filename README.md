# Awesome-Cyber-Asset-Management

The strongest open-source building blocks here are **GLPI, Snipe-IT, Ralph, OCS Inventory NG, Open-AudIT, CMDBuild, iTop, NetBox, osquery/Fleet, Wazuh, Nmap, CloudQuery, Steampipe, Cartography, and Zabbix**. Snipe-IT is explicitly positioned as FOSS asset management, Ralph as an open-source CMDB/asset-management system, and osquery provides SQL-based endpoint inventory; these make particularly useful foundations for a self-hosted stack. :contentReference[oaicite:0]{index=0}



For the **CAASM-specific gap**, the important architectural point is that these projects generally need to be combined: discovery tools find assets, endpoint/cloud tools enrich them, CMDB/ITAM tools organize them, and a normalization/entity-resolution layer turns the resulting records into a unified cyber asset graph. Open-source ITAM/discovery surveys likewise identify GLPI, OCS Inventory, Ralph, Snipe-IT, CMDBuild, Open-AudIT, and related projects as key components of this ecosystem. :contentReference[oaicite:1]{index=1}
