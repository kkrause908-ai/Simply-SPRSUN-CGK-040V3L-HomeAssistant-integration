Simply integration for SPRSUN-CGK_040V3L heat pump (and other SPRSUN heatpumps with EW-11 converter). 

# Sprsun Heat Pump Home Assistant Integration

Modbus-based integration for Sprsun heat pumps using an EW-11 adapter.

## Prerequisites
Configure the **EW-11 adapter** as shown on image.

<img width="1062" height="880" alt="{8D3E6804-855B-49FA-808D-C3777B4DC776}" src="https://github.com/user-attachments/assets/7618d6bc-c7ba-432b-84b8-35005affc8ce" />
<img width="1064" height="837" alt="{DC43BC1E-84FB-4C08-998C-2B06FA5818E4}" src="https://github.com/user-attachments/assets/65e04a39-859e-4297-a8cb-6efc2509fa53" />
(Remember to remove original configuration then add new card with TCP Server).
!!IF YOU WANT TO RESTORE ORIGINAL SPRSUN CLOUD "HEATPUMP" APP YOU SHOULD MAKE BACKUP OF YOUR EW-11 CONFIGURATION!!

Put IP address of your EW-11 in this tab (configuration.yaml)
<img width="290" height="214" alt="{BD300DB2-693F-4A26-8DB5-BB14CDDA0EFD}" src="https://github.com/user-attachments/assets/6b28444f-165a-4201-9687-dfce834b2006" />



## Installation
You can choose your language. For polish people - pl_configuration.yaml.
1. Copy the provided YAML configuration code into your `configuration.yaml` file.
2. Restart Home Assistant. The Modbus integration will be initialized automatically, and the entities will become available.

## Dashboard Setup
1. Open your Home Assistant dashboard.
2. Click **Edit Dashboard**.
3. Add a new card or view and paste the code from the `dashboard.yaml` file. Use "RAW CONFIGURATION EDITOR"!!
<img width="300" height="238" alt="{1B82751C-F88C-4440-B062-6028B772E0EC}" src="https://github.com/user-attachments/assets/9f8f3c1e-1c4e-42ed-9659-c00e458abf47" />


   
