# polor loza
polor loza is an ANSI color library for __Loza programming language__ 

### Installation
To install this library via the LPM package manager:

```bash
$ lpm install gh:Wsoum/polor-loza
```

# preview
Version 1
```bash
import 'polor.loza'

use polor

println $FgBlue + 'Loza'
println $BgHiGreen + $FgHiBlack + 'programming' + $Reset
println $Bold + 'language'
```

Version 2 
```bash
import 'polor.loza'

use polor

println $ftc->Blue + 'Loza'
println $bhitc->HiGreen + $fhitc->HiBlack + 'programming' + $ba->Reset
println $ba->Bold + 'language'
```

In the new update, Loza Class were added and we also updated this library.

**Warning: Note that in the new version of this library, the speed has dropped very slowly**

Output both codes
<div>
  <img 
    src="/data/polor-preview.png"
    alt="polor is a simple Terminal Color library for Loza programming language"
    style=""
  />
</div>

# Wiki
<p>For more examples click <a href="https://github.com/Wsoum/polor-loza/wiki">here</a></p>
