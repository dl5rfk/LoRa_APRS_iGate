# Mane76 - Lora APRS iGate firmware - Fork of LoRa APRS iGate
# Update 06/2023 - Fork will be discontinued, see https://github.com/Mane76/LoRa_APRS_iGate_2nd_gen


This code is a fork of the iGate firmware published by Peter Buchegger, OE5BPA.

I appreciate the work of OE5BPA to promote Lora APRS on cheap hardware. https://github.com/lora-aprs/LoRa_APRS_iGate

Further descriptions about hardware, firmware, howtos, ..., can be found in the above mentioned link.

Changes I made because they are relevant to me:

- Decrease number of digits for SNR and FreqError sent to syslog
- Enabling digipeating without WIDE in path 

ATTENTION: 

Do only enable digipeating if you know what you are doing. TX freq and RX freq must (!) be different, otherwise you will get a ping-pong and lock the frequency. You have been warned
Do only use the TX function of the iGate if you know what you are doing.

By using this software you are responsible to be inline with the regulations in your country


