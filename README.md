# Try Out Decompilation In Your Browser
- Supported formats:	ELF, PE, COFF, AR (archive), Intel HEX
- Supported architectures (32b):	Intel x86, ARM, ARM+Thumb, MIPS, PIC32, PowerPC
- Supported file: .so, .o, etc...

# Web
## [https://retdec.com/decompilation/](https://retdec.com/decompilation/)
> retdec-idaplugin: [https://github.com/avast-tl/retdec-idaplugin](https://github.com/avast-tl/retdec-idaplugin)

# Alternative
- ## https://derevenets.com/
- ## objdump: [https://en.wikipedia.org/wiki/Objdump](https://en.wikipedia.org/wiki/Objdump)
> `objdump -D --disassembler-options intel sjt.o` to get Intel syntax assembly

> `objdump -D --disassembler-options att sjt.o or objdump -D sjt.o` to get AT&T syntax assembly

> [https://gist.github.com/utsengar/1329947](https://gist.github.com/utsengar/1329947)

- ## gobjdump
```
brew install binutils
```

- ## emilpro
> [https://github.com/SimonKagstrom/emilpro](https://github.com/SimonKagstrom/emilpro)

- ## otool
> [https://gist.github.com/yujikosuga/1508560](https://gist.github.com/yujikosuga/1508560)