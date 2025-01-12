Control any switch you want from different brands and models. My goal is to support as much as possible.
Feel free to contribute: in topics or github. Give brand, model als the even_types like: single_left, single_right.

Todo:
- Improve descriptions/guides and topic
- icons for for the different switches
- Better readme (how to obtain the different event types)
:white_check_mark: Collapsible based on choice of what kind of switch you use. (a dropdown so the right switch's options will be collapsed)
- Other ideas, please feel free to ask or give tips.
- Add more switches (give me brand, model, and options/event types )
  (in develop tools, like: event_types: hold, button_1_release, button_1_single, button_1_double, button_1_triple, button_2_release, button_2_single, button_2_double, etc. etc...)
- A tutorial article on my site [https://gadget-freakz.com](https://gadget-freakz.com)

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fremb0%2Fblueprints%2Fblob%2Fmain%2FDifferent_switches_zigbee2mqtt.yaml)
 

     ## 🔧 Requirements:
    ***NOTE:*** Use zigbee2MQTT > 2025.1 or above whitout lecacy options 

    ## 🔧 Changelog:
    ***Added:***
    WXKG12LM
    Philips
    Aqara WXKG07LM for DAVIZINHO (Aqara_switches)  

    ***Compatibility list:***
    Aqara: Aqara (double) rocker, WXKG07LM, 
    Aqara: single switches: WXKG12LM, WXKG01LM (single switch)
    Ikea:  E1743
    Lidl: HG08164 (single switch)
    Opple: WXCJKG12LM, WXCJKG13LM
    Philips: 929003017102, 929002398602, 324131092621


**Update the Blueprint**  
If the blueprint is updated on github, you have to re-import it and reload blueprints in Home Assistant:
- Go to **Settings** > **automations and scenes**.
- Go to **Blueprints** on the top bar.
- search for the blueprint of remb0 and click on the 3 dots on the end of the line.
- Click the **Reload/import Blueprints** .
- If necessary, reapply the blueprint to an automation:
- Navigate to **Settings** > **Automations & Scenes**.
- Select the automation using the blueprint.
- Make any required updates and save.

[![Home Assistant Community Topic]](https://community.home-assistant.io/t/zigbee2mqtt-2-0-different-switches-aqara-opple-ikea/823618)


<script type="text/javascript" src="https://cdnjs.buymeacoffee.com/1.0.0/button.prod.min.js" data-name="bmc-button" data-slug="remb0" data-color="#FFDD00" data-emoji="☕"  data-font="Cookie" data-text="Buy me a coffee" data-outline-color="#000000" data-font-color="#000000" data-coffee-color="#ffffff" ></script>
