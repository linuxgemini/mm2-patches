# mm2-patches

an attempt at binary patching sergsero's ModeSMixer2 to fix the (currently) broken frontend, as the software itself has been abandoned for >2 years

static web items of ModeSMixer2 are compressed with gzip, then encoded to base64 to be stored.

in ELF files, the base64 data is within `.rodata`.