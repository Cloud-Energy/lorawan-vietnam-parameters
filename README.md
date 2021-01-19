# LoRaWAN Viet Nam Parameters

## Introduction
Base on the recent release of LoRaWAN Alliance to update [RP2-1.0.1 LoRaWAN® Regional Parameters](https://lora-alliance.org/resource_hub/rp2-101-lorawan-regional-parameters/) and Viet Nam regulations about [LPWAN 920MHz-923MHz](https://mic.gov.vn/Upload_Moi/VanBan/38TT.PDF) we highly recommend the details of parameters for LoRaWAN connection.

## Join channels
There are 2 options for joining channels, depend on which device and gateway you have and the ability to adjust the join channels of them.
```
AS923   (923.2MHz and 923.4MHz) easy to adapt to the old device with some limitations on activation and custom frequencies plan.
AS923_2 (921.4MHz and 921.6MHz) make sure both gateway and device can adjust to work with these join channels.
```

## Activation
In OTAA activation the join channels are mandatory. On other hand, in ABP activation the join channels are optional.
```
AS923   Device should use ABP for better connectivity.
AS923_2 Device is possible to activate with OTAA and ABP.
```

## Frequencies Plan
This is the recommended frequencies plan for general devices, the devices can freely to choose 8ch between 920MHz-923MHz.
```
Uplink
1 - 920.2MHz SF7BW125 to SF12BW125
2 - 920.4MHz SF7BW125 to SF12BW125
3 - 920.6MHz SF7BW125 to SF12BW125
4 - 920.8MHz SF7BW125 to SF12BW125
5 - 921MHz SF7BW125 to SF12BW125
6 - 921.2MHz SF7BW125 to SF12BW125
7 - 921.4MHz SF7BW125 to SF12BW125
8 - 921.6MHz SF7BW125 to SF12BW125
9 - 921.5MHz SF7BW250
10 - 921.8MHz FSK

Downlink
Uplink channels 1-10 (RX1)
921.4MHz - SF10BW125 (RX2)
```

## Contributors
Tony Doan - Lead engineers at [Cloud Energy](https://cloude.sg)

Joyanta Majumder - Presales and Support Manager APAC at [KERLINK](https://www.kerlink.com/)

Michel Gilbert - Radio Access Expert at [KERLINK](https://www.kerlink.com/)

## License
[MIT](https://choosealicense.com/licenses/mit/)
