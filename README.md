# gl-pump-controller
This board is a SpikeGadgets ECU accessory, which acts as an RJ-45 breakout board for 8 or the DIO ports, and as a pump controller for the other 8 DIO ports in the bank. KiCAD is required to open/edit this project, and can be downloaded at https://www.kicad.org/download/

# Download Instructions
1. Clone the repo `git clone --recursive https://github.com/gillespielab/gl-pump-controller`
2. Open the KiCAD Symbol Editor. Then click: "File" -> "Add Library"
3. Select Global
4. In the prompt, select/open: gl-pump-controller/gl-electronics/symbols/Uploaded.kicad_sym

# BOM
Description | Component Number | Quantity | Part Number/Link
------------- | ------------- | ------------- | -------------
8-bit Buffer | U9-U10 | 2 | [SN74ABT541BPW](https://www.digikey.com/en/products/detail/texas-instruments/SN74ABT541BPW/1575499)
2x10 90deg Header Pins | J11 | 2 | [2057-PH2RA-20-UA-ND](https://www.digikey.com/en/products/detail/adam-tech/PH2RA-20-UA/9830622?s=N4IgTCBcDa4AwFYDsBaACgCTAJQIIrDhQFV8A5AERAF0BfIA)
8x1 RJ-45 Array | J9 | 1 | [432238182](https://www.digikey.com/en/products/detail/molex/0432238182/481095)
SSD Relays | U1-U8 | 8 | [AQY211EHAX](https://www.digikey.com/en/products/detail/panasonic-electric-works/AQY211EHAX/2804732)
1.02kO Resistor | R1-R8 | 8 | [RC1206FR-071K02L](https://www.digikey.com/en/products/detail/yageo/RC1206FR-071K02L/728390)
10kO Resistor | R9 | 1 | [ERJ-8ENF1002V](https://www.digikey.com/en/products/detail/panasonic-electronic-components/ERJ-8ENF1002V/89059?s=N4IgTCBcDaIAoEYAMA6JBpAYgYQCoFoA5AERAF0BfIA)
1uF Ceramic Capacitor | C1-C8 | 8 | [AGC1206X7R101-104KNE-CT](https://www.digikey.com/en/products/detail/venkel/AGC1206X7R101-104KNE-CT/21344624)
100uF Electrolytic Capacitor | C9 | 1 | [50ZLH100MEFC8X11.5](https://www.digikey.com/en/products/detail/rubycon/50ZLH100MEFC8X11-5/3563386)
2P2D Switch | S1 | 1 | [100DP1T2B4M6QE](https://www.digikey.com/en/products/detail/e-switch/100DP1T2B4M6QE/378873)
DC Power Jack | J10 | 1 | [163-179PH-EX](https://www.mouser.com/ProductDetail/Kobiconn/163-179PH-EX?qs=Xb8IjHhkxj5l2UOaIqcGCw%3D%3D)
JST PH-2 Connectors | J1-J8 | 8 | [Amazon](https://www.amazon.com/dp/B0C89MRNSH?ref=fed_asin_title&th=1)
