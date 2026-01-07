# CharMapperLCDSmartiePlugin
Char Mapper / Replacer for any Plugin

Usage:

EXAMPLE USE:
$dll(CharMapper,1,,) → Replace character
$dll(CharMapper,2,,) → Cycle from $Chr(0) to $Chr(255) and show the Hexa equivalent.
$dll(CharMapper,2,<param>) → Supports auto, next, prev, reset, current. Empty = auto

EXAMPLE REPLACES CHARACTERS ON OTHER PLUGINS:
$dll(CharMapper,1,$dll(NowPlaying,1,,),)

