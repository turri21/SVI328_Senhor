-=(SVI328_Senhor notes)=-

Tested: Working Video 720p, 1080p & sound.

Senhor additions: MegaROM support, Hardware reset and OSD option for tape sound On/Off.

MegaROM contributors: [teiram](https://github.com/teiram), [retrocrypta](https://github.com/retrocrypta)

ADC input does not exist on Senhor, therefore it's not supported.

Dev notes: Clocks swapped in sys.tcl
___
# Spectravideo SV-328 

Core by fpganoob on misterfpga.org


Place the rom in a boot.rom file in the SVI328 folder

## Loading Games

### Cartridges

1) Load the cartridge in the OSD

* note - you will need to reboot to get out of the cartridge until this is fixed

### Cassettes - either with a file, or through ADC input

Tapes take a long time to load (5-6 minutes?) so be patient. Having the sound on will help your nerves.

1) load  CAS file on the OSD menu (F12) 
2) SOUND ON (optionnel: sound for the K7)
3) CLOAD
4) RUN 
or
3) BLOAD "CAS:",R
