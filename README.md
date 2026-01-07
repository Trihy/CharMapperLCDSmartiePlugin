# CharMapperLCDSmartiePlugin

Char Mapper / Replacer for any Plugin

## Usage

### Example use:
$dll(CharMapper,1,,) → Replace character  
$dll(CharMapper,2,,) → Cycle from $Chr(0) to $Chr(255) and show the Hexa equivalent.  
$dll(CharMapper,2,<param>) → Supports auto, next, prev, reset, current. Empty = auto  

### Example replaces characters on other plugins:
$dll(CharMapper,1,$dll(NowPlaying,1,,),)

; General format on cfg file: 
;   In=input_value Out=output_value 
; 
; Value can be: 
;   Decimal: 225 
;   Hex with 0x: 0xE1 
;   Hex with $: $E1 
;
; Example
In=$E1 Out=$9D 
In=120 Out=205 
