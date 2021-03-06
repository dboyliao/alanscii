alanscii
========

This repository hosts a variety of languages which I have played with to do a trivial task of printing ASCII art that represents one of the mascots at [Cerner Engineering](http://engineering.cerner.com/).

### ASCII example
This ASCII representation is a cartoon mascot at [Cerner Engineering](http://engineering.cerner.com/), which is [Alan Turing](http://en.wikipedia.org/wiki/Alan_Turing).
```
                                                        ___ 
                                                       | __)
                       .l: .cl. 'l:  :l. cl.     ____  |__ \   
                    .lollddllddoldxlcdkxookc    (___ \ (___/
                  .lkkl,;oo,,ld:,:do,;dd;:Kk      __) )
                  ,XXc,,,;,,,,;,,,;,,,;;,:Kk     / __/ 
                .,ckk:,,,,,,,,,,,,,,,,,,,:Kk    | |___ 
                oXk,,,,,,,,,,,,,,,,,,,,,,;kd'.  |_____) 
                oXk,,,,,,,,,,,,,,,,,,,,,,,,:K0. kK00000X0k,
                oXk,,,,,,,,,,,,,,,,,,,,,,,,:K0. OO::::dXo
            cOOkKXO;,,,,,,:::;''''''::::'''cX0. OO::::dXo
            lXOdddl,'',,';O0Xk''''''x0X0,''cX0. OK0000KXKk,
       .....dXOdddl;,'''''':ko''''''';kd'';lK0. .:X0xxxxOX:
     ..o0000KXOdddddc'''''''''''....''''',dOX0.  ,X0ddddkX:
   .'oOo::::dX0kkkxdc'''''''''''.....'''',dOKKollxXKOOOO0X:
   oXx::::::oOOk0XKdc''''''''''',,,,''',oodxkxlccccoKK:,,,.
   oXx:::::::::cdX0dooooooooooooooooooooxddddo,'''';KK.
   oXxlccccccccccloddddddddxkkkkkxdddddddddddo,'''':KK.
    .cKx::::loool:codddddddddxkxddddddddddddddxxxxxkXK.
     :Xk::::lxl,,'',cddddddddxkxddddddddkkOOOO00000k'.
     :Xk::::okc''''':ddddddddxkxddddddkkKO.
     :Xk::::lxc'',,,cddddddddxkxddddddkkKO.
     :Xk:::::::::cdddddddddddxkxddddddkkKO.
     ;OkooooooooodOOKK000000000000000000XO.
       dOOOOOOOOOOOOKXl::::::::::::::::cKO.
                 .ccdxc:::::dxxdc::::::cKO.
                :odo:::::cxx:;;:xx::::::dol;
             .oloo:::::ckx;'   .0Kc::::::c0d
             'XKOOOOOOOd'.     .0XOkkkkkkOXx
       .''''';lllllllllc''''''',lllllllllll;
```

### Languages
* [bash](https://www.gnu.org/software/bash/manual/) - [art.sh](bash/art.sh) (`bash art.sh`)
* [clojure](http://clojure.org/) - [art.clj](clojure/art.clj) (`java -cp clojure.jar clojure.main art.clj`)
* [c](http://en.wikipedia.org/wiki/C_(programming_language)) - [art.c](c/art.c) (`gcc art.c -o art && ./art`)
* [c++](http://en.wikipedia.org/wiki/C%2B%2B) - [art.cpp](cpp/art.cpp) (`g++ art.cpp -o art && ./art`)
* [coffeescript](http://coffeescript.org/) - [art.coffee](coffeescript/art.coffee) (`coffee art.coffee`)
* [d](http://dlang.org/) - [art.d](d/art.d) (`rdmd art.d`)
* [dart](https://www.dartlang.org/) - [art.dart](dart/art.dart) (`dart art.dart`)
* [elixir](http://elixir-lang.org/) - [art.exs](elixir/art.exs) (`elixir art.exs`)
* [erlang](http://www.erlang.org/) - [art.erl](erlang/art.erl) (`erl -pa ./art.erl -run art print -run init stop -noshell`)
* [go](https://golang.org/) - [art.go](go/art.go) (`go run art.go`)
* [groovy](http://groovy.codehaus.org/) - [art.groovy](groovy/art.groovy) (`groovy art.groovy`)
* [haskell](http://www.haskell.org/haskellwiki/Haskell) - [art.hs](haskell/art.hs) (`runhaskell art.hs`)
* [haxe](http://haxe.org/) - [Art.hx](haxe/Art.hx) (`haxe -main Art --interp`)
* [julia](http://julialang.org/) - [art.jl](julia/art.jl) (`julia art.jl`)
* [lua](http://www.lua.org/) - [art.lua](lua/art.lua) (`lua art.lua`)
* [mirah](http://www.mirah.org/) - [art.mirah](mirah/art.mirah) (`mirah art.mirah`)
* [objective-c](http://en.wikipedia.org/wiki/Objective-C) - [art.m](objectivec/art.m) (`clang -fobjc-arc art.m -o art && ./art`)
* [ocaml](https://ocaml.org) - [art.ml](ocaml/art.ml) (`ocaml art.ml`)
* [ooc](http://ooc-lang.org/) - [art.ooc](ooc/art.ooc) (`rock art.ooc && ./art`)
* [nickle](http://www.nickle.org/) - [art.nickle](nickle/art.nickle) (`nickle art.nickle`)
* [node.js](http://nodejs.org/) - [art.js](node/art.js) (`node art.js`)
* [pascal](http://freepascal.org/) - [art.pp](pascal/art.pp) (`fpc art.pp && ./art`)
* [perl](https://www.perl.org/) - [art.pl](perl/art.pl) (`perl art.pl`)
* [php](http://php.net/) - [art.php](php/art.php) (`php art.php`)
* [python](https://docs.python.org/3/) - [art.py](python/art.py) (`python art.py`)
* [r](http://www.r-project.org/) - [art.r](r/art.r) (`Rscript art.r`)
* [rebol](http://www.rebol.com/) - [art.r](rebol/art.r) (`rebol art.r`)
* [ruby](https://www.ruby-lang.org/en/) - [art.rb](ruby/art.rb) (`ruby art.rb`)
* [rust](http://www.rust-lang.org/) - [art.rs](rust/art.rs) (`rustc art.rs && ./art`)
* [scala](http://www.scala-lang.org/) - [Art.scala](scala/Art.scala) (`scalac Art.scala && scala Art`)
* [tcl](https://www.tcl.tk/) - [art.tcl](tcl/art.tcl) (`tclsh art.tcl`)
* [vala](https://wiki.gnome.org/Projects/Vala) - [art.vala](vala/art.vala) (`valac art.vala && ./art`)