# About
<script type="module" src="https://unpkg.com/esp-web-tools@5.2.0/dist/web/install-button.js?module"></script>
<style>
    button:hover {
    box-shadow: rgb(0 0 0 / 14%) 0px 4px 8px 0px, rgb(0 0 0 / 12%) 0px 1px 7px 0px, rgb(0 0 0 / 20%) 0px 3px 1px -1px;
    }
    button {
        position: relative;
        cursor: pointer;
        font-size: 14px;
        padding: 8px 28px;
        color: var(--esp-tools-button-text-color, #fff);
        background-color: var(--esp-tools-button-color, #03a9f4);
        border: none;
        border-radius: 4px;
        }
</style>
Just a series of templates for devices I own, or based on templates that people have offered. 

# Installation

You can use one of the buttons below to install the pre-built firmware directly to your device via USB from the browser.<br>

<table>
<thead>
    <tr>
        <th style='text-align:center'>Name</th>
        <th style='text-align:center'>Install</th>
        <th style='text-align:center'>Download</th>
        <th style='text-align:center'>YAML</th>
    </tr>
</thead>
<tbody><tr><td style='text-align:center'> esp32 gateway </td><td style='text-align:center'> <esp-web-install-button manifest='./esp32-gateway-esp32/manifest.json'><button slot='activate'>Install via Web</button></esp-web-install-button> </td><td style='text-align:center'> <a href='esp32-gateway-esp32/esp32-gateway-esp32.bin'><button>Download Firmware</button></a> </td><tdstyle='text-align:center'><a href='https://github.com/cpyarger/esphome-templates/blob/main/esp32-gateway.yaml'>YAML<a></td></tr>
<tr><td style='text-align:center'> shelly 1 </td><td style='text-align:center'> <esp-web-install-button manifest='./shelly-1-esp8266/manifest.json'><button slot='activate'>Install via Web</button></esp-web-install-button> </td><td style='text-align:center'> <a href='shelly-1-esp8266/shelly-1-esp8266.bin'><button>Download Firmware</button></a> </td><tdstyle='text-align:center'><a href='https://github.com/cpyarger/esphome-templates/blob/main/shelly-1.yaml'>YAML<a></td></tr>
<tr><td style='text-align:center'> sonoff basic </td><td style='text-align:center'> <esp-web-install-button manifest='./sonoff-basic-esp8266/manifest.json'><button slot='activate'>Install via Web</button></esp-web-install-button> </td><td style='text-align:center'> <a href='sonoff-basic-esp8266/sonoff-basic-esp8266.bin'><button>Download Firmware</button></a> </td><tdstyle='text-align:center'><a href='https://github.com/cpyarger/esphome-templates/blob/main/sonoff-basic.yaml'>YAML<a></td></tr>
<tr><td style='text-align:center'> sonoff ifan04 l </td><td style='text-align:center'> <esp-web-install-button manifest='./sonoff-ifan04-l-esp8266/manifest.json'><button slot='activate'>Install via Web</button></esp-web-install-button> </td><td style='text-align:center'> <a href='sonoff-ifan04-l-esp8266/sonoff-ifan04-l-esp8266.bin'><button>Download Firmware</button></a> </td><tdstyle='text-align:center'><a href='https://github.com/cpyarger/esphome-templates/blob/main/sonoff-ifan04-l.yaml'>YAML<a></td></tr>
<tr><td style='text-align:center'> sonoff rfbridge </td><td style='text-align:center'> <esp-web-install-button manifest='./sonoff-rfbridge-esp8266/manifest.json'><button slot='activate'>Install via Web</button></esp-web-install-button> </td><td style='text-align:center'> <a href='sonoff-rfbridge-esp8266/sonoff-rfbridge-esp8266.bin'><button>Download Firmware</button></a> </td><tdstyle='text-align:center'><a href='https://github.com/cpyarger/esphome-templates/blob/main/sonoff-rfbridge.yaml'>YAML<a></td></tr>
<tr><td style='text-align:center'> sonoff th16 </td><td style='text-align:center'> <esp-web-install-button manifest='./sonoff-th16-esp8266/manifest.json'><button slot='activate'>Install via Web</button></esp-web-install-button> </td><td style='text-align:center'> <a href='sonoff-th16-esp8266/sonoff-th16-esp8266.bin'><button>Download Firmware</button></a> </td><tdstyle='text-align:center'><a href='https://github.com/cpyarger/esphome-templates/blob/main/sonoff-th16.yaml'>YAML<a></td></tr>
<tr><td style='text-align:center'> sonoff tx t1 </td><td style='text-align:center'> <esp-web-install-button manifest='./sonoff-tx-t1-esp8266/manifest.json'><button slot='activate'>Install via Web</button></esp-web-install-button> </td><td style='text-align:center'> <a href='sonoff-tx-t1-esp8266/sonoff-tx-t1-esp8266.bin'><button>Download Firmware</button></a> </td><tdstyle='text-align:center'><a href='https://github.com/cpyarger/esphome-templates/blob/main/sonoff-tx-t1.yaml'>YAML<a></td></tr>
<tr><td style='text-align:center'> sonoff tx t2 </td><td style='text-align:center'> <esp-web-install-button manifest='./sonoff-tx-t2-esp8266/manifest.json'><button slot='activate'>Install via Web</button></esp-web-install-button> </td><td style='text-align:center'> <a href='sonoff-tx-t2-esp8266/sonoff-tx-t2-esp8266.bin'><button>Download Firmware</button></a> </td><tdstyle='text-align:center'><a href='https://github.com/cpyarger/esphome-templates/blob/main/sonoff-tx-t2.yaml'>YAML<a></td></tr>
<tr><td style='text-align:center'> sonoff tx t3 </td><td style='text-align:center'> <esp-web-install-button manifest='./sonoff-tx-t3-esp8266/manifest.json'><button slot='activate'>Install via Web</button></esp-web-install-button> </td><td style='text-align:center'> <a href='sonoff-tx-t3-esp8266/sonoff-tx-t3-esp8266.bin'><button>Download Firmware</button></a> </td><tdstyle='text-align:center'><a href='https://github.com/cpyarger/esphome-templates/blob/main/sonoff-tx-t3.yaml'>YAML<a></td></tr>
<tr><td style='text-align:center'> sp501e </td><td style='text-align:center'> <esp-web-install-button manifest='./sp501e-esp8266/manifest.json'><button slot='activate'>Install via Web</button></esp-web-install-button> </td><td style='text-align:center'> <a href='sp501e-esp8266/sp501e-esp8266.bin'><button>Download Firmware</button></a> </td><tdstyle='text-align:center'><a href='https://github.com/cpyarger/esphome-templates/blob/main/sp501e.yaml'>YAML<a></td></tr>
<tr><td style='text-align:center'> ttgo higrow stick </td><td style='text-align:center'> <esp-web-install-button manifest='./ttgo-higrow-stick-esp32/manifest.json'><button slot='activate'>Install via Web</button></esp-web-install-button> </td><td style='text-align:center'> <a href='ttgo-higrow-stick-esp32/ttgo-higrow-stick-esp32.bin'><button>Download Firmware</button></a> </td><tdstyle='text-align:center'><a href='https://github.com/cpyarger/esphome-templates/blob/main/ttgo-higrow-stick.yaml'>YAML<a></td></tr>
<tr><td style='text-align:center'> wyze plug </td><td style='text-align:center'> <esp-web-install-button manifest='./wyze-plug-esp8266/manifest.json'><button slot='activate'>Install via Web</button></esp-web-install-button> </td><td style='text-align:center'> <a href='wyze-plug-esp8266/wyze-plug-esp8266.bin'><button>Download Firmware</button></a> </td><tdstyle='text-align:center'><a href='https://github.com/cpyarger/esphome-templates/blob/main/wyze-plug.yaml'>YAML<a></td></tr>
</tbody></table><br>
