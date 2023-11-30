# homeassistant addon cups airprint
CUPS addon with working Avahi in reflector mode 

This fork adds support for certain Brother laser printers, including:
 - DCP-1510
 - DCP-1602
 - DCP-7030
 - DCP-7040
 - DCP-7055
 - DCP-7055W
 - DCP-7060D
 - DCP-7065DN
 - DCP-7080
 - DCP-L2500D
 - DCP-L2540DW
 - HL-1110 series
 - HL-1200 series
 - HL-L2300D series
 - HL-L2320D series
 - HL-L2340D series
 - HL-L2360D series
 - MFC-1910W
 - MFC-7240
 - MFC-7360N
 - MFC-7365DN
 - MFC-7840W
 - MFC-L2710DW
 - Lenovo M7605D 

See full list here: https://wiki.debian.org/Brother

Tested with Home Assistant version **2023.9**

CUPS administrator login: **print**, password: **print** (can be changed in the Dockerfile)

Configuration data is stored in **/data/cups** folder

[![Open your Home Assistant instance and show the add add-on repository dialog with a specific repository URL pre-filled.](https://my.home-assistant.io/badges/supervisor_add_addon_repository.svg)](https://my.home-assistant.io/redirect/supervisor_add_addon_repository/?repository_url=https%3A%2F%2Fgithub.com%2FArendJanKramer%2Fhomeassistant-addon-cups-airprint)
