# vimpromptu

I'm not sure what exactly this is going to turn into to. But, the plan is to start documenting dev things. Probably vim and cli focused.




## Laundry List of interesting finds

- https://github.com/uncrustify/uncrustify > a source code beautifier for C, C++, C#, Objective-C, D, Java, Pawn and Vala.
- https://github.com/ogham/exa > a modern replacement for ls.
- https://github.com/FineFindus/artem > ascii art cli
- https://github.com/twpayne/chezmoi > dotfiles management
- https://github.com/atanunq/viu cli image viewer
- https://github.com/microsoft/java-debug - Java Debug Server for Visual Studio Code
- https://github.com/dgileadi/vscode-java-decompiler - Decompiler for Java™ in Visual Studio Code
- https://github.com/microsoft/vscode-java-test - Test Runner for Java
- https://github.com/testforstephen/vscode-pde - Eclipse PDE support for VS Code
- https://github.com/jesseduffield/lazygit - A simple terminal UI for git commands, written in Go with the gocui library.
- https://asciinema.org/ - Screen record cli

## Vim keymap ideas / alt leaders
- esc in normal mode https://www.reddit.com/r/neovim/comments/zmu22y/uses_for_escape_in_normal_mode/?utm_source=share&utm_medium=ios_app&utm_name=iossmf
- normal mode:
 - s
 - S
 - backspace
 - delete
 - space is already my leader
 - f1...f12
 - enable alt in iterm
 - arrow keys
 - tab
 - enter

## Vim Easter Eggs
- :h |
https://en.wikipedia.org/wiki/The_Treachery_of_Images
```
							*bar*
|			To screen column [count] in the current line.
			|exclusive| motion.  Ceci n'est pas une pipe.
```
- :h UserGettingBored
```
 							*UserGettingBored*
UserGettingBored		When the user presses the same key 42 times.
				Just kidding! :-)
```
- :smile
```
:smile
                            oooo$$$$$$$$$$$$oooo
                        oo$$$$$$$$$$$$$$$$$$$$$$$$o
                     oo$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$o         o$   $$ o$
     o $ oo        o$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$o       $$ $$ $$o$
  oo $ $ "$      o$$$$$$$$$    $$$$$$$$$$$$$    $$$$$$$$$o       $$$o$$o$
  "$$$$$$o$     o$$$$$$$$$      $$$$$$$$$$$      $$$$$$$$$$o    $$$$$$$$
    $$$$$$$    $$$$$$$$$$$      $$$$$$$$$$$      $$$$$$$$$$$$$$$$$$$$$$$
    $$$$$$$$$$$$$$$$$$$$$$$    $$$$$$$$$$$$$    $$$$$$$$$$$$$$  """$$$
     "$$$""""$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$     "$$$
      $$$   o$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$     "$$$o
     o$$"   $$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$       $$$o
     $$$    $$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$" "$$$$$$ooooo$$$$o
    o$$$oooo$$$$$  $$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$   o$$$$$$$$$$$$$$$$$
    $$$$$$$$"$$$$   $$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$     $$$$""""""""
   """"       $$$$    "$$$$$$$$$$$$$$$$$$$$$$$$$$$$"      o$$$
              "$$$o     """$$$$$$$$$$$$$$$$$$"$$"         $$$
                $$$o          "$$""$$$$$$""""           o$$$
                 $$$$o                                o$$$"
                  "$$$$o      o$$$$$$o"$$$$o        o$$$$
                    "$$$$$oo     ""$$$$o$$$$$o   o$$$$""
                       ""$$$$$oooo  "$$$o$$$$$$$$$"""
                          ""$$$$$$$oo $$$$$$$$$$
                                  """"$$$$$$$$$$$
                                      $$$$$$$$$$$$
                                       $$$$$$$$$$"
                                        "$$$""""
```
- :smile `// neovim`
```
 #xxn`          #xnxx`        ,+x@##@Mz;`        .xxxxxxxxxnz+,      znnnnnnnnnnnnnnnn.
 n###z          x####`      :x##########W+`      ,#############M;    W################.
 n####;         x####`    `z##############W:     ,################   W################.
 n####W.        x####`   ,W#################+    ,#################  W################.
 n#####n        x####`   @###################    ,#################i W################.
 n######i       x####`  .#########@W@########*   ,#################W`W################.
 n######@.      x####`  x######W*.  `;n#######:  ,####x,,,,:*M######iW###@:,,,,,,,,,,,`
 n#######n      x####` *######+`       :M#####M  ,####n      `x#####xW###@`
 n########*     x####``@####@;          `x#####i ,####n       ,#####@W###@`
 n########@     x####`*#####i            `M####M ,####n        x#########@`
 n#########     x####`M####z              :#####:,####n        z#########@`
 n#########*    x####,#####.               n####+,####n        n#########@`
 n####@####@,   x####i####x                ;####x,####n       `W#####@####+++++++++++i
 n####*#####M`  x#########*                `####@,####n       i#####MW###############W
 n####.######+  x####z####;                 W####,####n      i@######W###############W
 n####.`W#####: x####n####:                 M####:####@nnnnnW#######,W###############W
 n####. :#####M`x####z####;                 W####,#################z W###############W
 n####.  #######x#########*                `####W,################W` W###############W
 n####.  `M#####W####i####x                ;####x,###############W,  W####+**********i
 n####.   ,##########,#####.               n####+,##############n.   W###@`
 n####.    ##########`M####z              :#####:,###########Wz:     W###@`
 n####.    x#########`*#####i            `M####M ,####x.....`        W###@`
 n####.    ,@########``@####@;          `x#####i ,####n              W###@`
 n####.     *########` *#####@+`       ,M#####M  ,####n              W###@`
 n####.      x#######`  x######W*.  `;n######@:  ,####n              W###@,,,,,,,,,,,,`
 n####.      .@######`  .#########@W@########*   ,####n              W################,
 n####.       i######`   @###################    ,####n              W################,
 n####.        n#####`   ,W#################+    ,####n              W################,
 n####.        .@####`    .n##############W;     ,####n              W################,
 n####.         i####`      :x##########W+`      ,####n              W################,
 +nnnn`          +nnn`        ,+x@##@Mz;`        .nnnn+              zxxxxxxxxxxxxxxxx.

                                                                                   ,+M@#Mi
                                                                                 .z########
                                                                                i@#########i
                                                                              `############W`
                                                                             `n#############i
                                                                            `n##############n
     ``                                                                     z###############@`
    `W@z,                                                                  ##################,
    *#####`                                                               i############@x@###i
    ######M.                                                             :#############n`,W##+
    +######@:                                                           .W#########M@##+  *##z
    :#######@:                                                         `x########@#x###*  ,##n
    `@#######@;                                                        z#########M*@nW#i  .##x
     z########@i                                                      *###########WM#@#,  `##x
     i##########+                                                    ;###########*n###@   `##x
     `@#MM#######x,                                                 ,@#########zM,`z##M   `@#x
      n##M#W#######n.               `.:i*+#zzzz##+i:.`             ,W#########Wii,`n@#@` n@##n
      ;###@#x#######n         `,i#nW@#####@@WWW@@####@Mzi.        ,W##########@z.. ;zM#+i####z
       x####nz########    .;#x@##@Wn#*;,.`      ``,:*#x@##M+,    ;@########xz@WM+#` `n@#######
       ,@####M########xi#@##@Mzi,`                     .+x###Mi:n##########Mz```.:i  *@######*
        *#####W#########ix+:`                             :n#############z:       `*.`M######i
        i#W##nW@+@##@#M@;                                   ;W@@##########W,        i`x@#####,
        `@@n@Wn#@iMW*#*:                                     `iz#z@######x.           M######`
         z##zM###x`*, .`                                          `iW#####W;:`        +#####M
         ,###nn##n`                                                ,#####x;`        ,;@######
          x###xz#.                                                   in###+        `:######@.
          ;####n+                                                    `Mnx##xi`   , zM#######
          `W####+                i.                                   `.+x###@#. :n,z######:
           z####@`              ;#:                                     .ii@###@;.*M*z####@`
           i####M         `   `i@#,           ::                           +#n##@+@##W####n
           :####x    ,i. ##xzM###@`     i.   .@@,                           .z####x#######*
           ,###W;   i##Wz#########     :##   z##n                           ,@########x###:
            n##n   `W###########M`;n,  i#x  ,###@i                           *W########W#@`
           .@##+  `x###########@. z#+ .M#W``x#####n`                         `;#######@z#x
           n###z :W############@  z#*  @##xM#######@n;                        `########nW+
          ;####nW##############W :@#* `@#############*                        :########z@i`
          M##################### M##:  @#############@:                       *W########M#
         ;#####################i.##x`  W#############W,                       :n########zx
        #######################:       z##################@x+*#zzi            `@#########.
        W########W#z#M#########;       *##########################z            :@#######@`
       `@#######x`;#z ,x#######;       z###########M###xnM@########*            :M######@
       i########, x#@`  z######;       *##########i *#@`  `+########+`            n######.
       n#######@` M##,  `W#####.       *#########z  ###;    z########M:           :W####n
       M#######M  n##.   x####x        `x########:  z##+    M#########@;           .n###+
       W#######@` :#W   `@####:         `@######W   i###   ;###########@.            n##n
       W########z` ,,  .x####z           @######@`  `W#;  `W############*            *###;
      `@#########Mi,:*n@####W`           W#######*   ..  `n#############i            i###x
      .#####################z           `@#######@*`    .x############n:`            ;####.
      :####################x`,,`        `W#########@x#+#@#############i              ,####:
      ;###################x#@###xi`      *############################:              `####i
      i##################+########M,      x##########################@`               W###i
      *################@; @########@,     .W#########################@                x###:
      .+M#############z.  M#########x      ,W########################@`               ####.
      *M*;z@########x:    :W#######i        .M########################i               i###:
      *##@z;#@####x:        :z###@i          `########################x               .###;
      *#####n;#@##            ;##*             ,x#####################@`               W##*
      *#######n;*            :M##W*,             *W####################`               n##z
      i########@.         ,*n#######M*`           `###################M                *##M
      i########n        `z#####@@#####Wi            ,M################;                ,##@`
      ;WMWW@###*       .x##@ni.``.:+zW##z`           `n##############z                  @##,
      .*++*i;;;.      .M#@+`          .##n            `x############x`                  n##i
      :########*      x#W,              *#+            *###########M`                   +##+
      ,#########     :#@:                ##:           #nzzzzzzzzzz.                    :##x
      .#####Wz+`     ##+                 `MM`          .znnnnnnnnn.                     `@#@`
      `@@ni;*nMz`    @W`                  :#+           .x#######n                       x##,
       i;z@#####,   .#*                    z#:           ;;;*zW##;                       ###i
       z########:   :#;                    `Wx          +###Wni;n.                       ;##z
       n########W:  .#*                     ,#,        ;#######@+                        `@#M
      .###########n;.MM                      n*        ;iM#######*                        x#@`
      :#############@;;                      .n`      ,#W*iW#####W`                       +##,
      ,##############.                        ix.    `x###M;#######                       ,##i
      .#############@`                         x@n**#W######z;M###@.                       W##
      .##############W:                        .x############@*;zW#;                       z#x
      ,###############@;                        `##############@n*;.                       i#@
      ,#################i                         :n##############W`                       .##,
      ,###################`                         .+W##########W,                        `##i
      :###################@zi,`                        ;zM@@@WMn*`                          @#z
      :#######################@x+*i;;:i#M,                 ``                               M#W
      ;################################@x.                                                  n##,
      i#####################@W@@@@Wxz*:`                                                    *##+
      *######################+```                                                           :##M
      ########################M;                                                            `@##,
      z#########################x,                                                           z###
      n###########################n:                                                         ;##W`
      x#############################Mz#++##*                                                 `W##i
      M####################################@`                                                 ###x
      W#####################################`                                                 .###,
      @####################################M                                                   n##z
      @##################z*i@WMMMx#x@#####,.                                                   :##@.
     `#####################@xi`     `::,*                                                       x##+
     .#####################@#M.                                                                 ;##@`
     ,#####################:.                                                                    M##i
     ;###################ni`                                                                     i##M
     *#################W#`                                                                       `W##,
     z#################@Wx+.                                                                      +###
     x######################z.                                                                    .@#@`
    `@#######################@;                                                                    z##;
    :##########################:                                                                   :##z
    +#########################W#                                                                    M#W
    W################@n+*i;:,`                                                                      +##,
   :##################WMxz+,                                                                        ,##i
   n#######################W..,                                                                      W##
  +#########################WW@+. .:.                                                                z#x
 `@#############################@@###:                                                               *#W
 #################################Wz:                                                                :#@
,@###############################i                                                                   .##
n@@@@@@@#########################+                                                                   `##
`      `.:.`.,:iii;;;;;;;;iii;;;:`       `.``                                                        `nW
```

## Vim
- neovim as man pager > `export MANPAGER='nvim +Man!'
`
- https://github.com/nanotee/nvim-lua-guide nvim lua guude

## Vim Videos
- https://youtu.be/w7i4amO_zaE Primeagen neovim setup
- https://youtu.be/stqUbv-5u2s Telescope Johnson kickstart ide
## Vim Plugins for days
- https://github.com/VonHeikemen/lsp-zero.nvim all the goodies from lsp bundled up
- https://github.com/mbbill/undotree undo history visualizer
- https://github.com/ThePrimeagen/harpoon act like you don't know
  ![Harpoon](https://raw.githubusercontent.com/ThePrimeagen/harpoon/master/harpoon.png)
- https://github.com/tpope/vim-surround better surroundings
- https://github.com/adelarsq/vim-matchit `// included by default in nvim`
- https://github.com/tpope/vim-fugitive
- https://github.com/NvChad/NvChad
- https://github.com/bennypowers/nvim-regexplainer
- https://github.com/ellisonleao/nvim-plugin-template plugin template
- https://github.com/rcarriga/nvim-notify fancy notifications
- https://github.com/mfussenegger/nvim-jdtls - java lsp
- https://github.com/mfussenegger/nvim-dap - Neovim DAP (Debug Adapter Protocol)
- https://github.com/lotabout/skim - fuzzy finder

## Vim Colorschemes
- https://vimcolorschemes.com/
- https://github.com/Lokaltog/vim-distinguished - My first favorite 
- https://github.com/morhetz/gruvbox
- https://github.com/ellisonleao/gruvbox.nvim - My current jam
- https://github.com/folke/tokyonight.nvim
- https://github.com/rose-pine/neovim
- https://github.com/sainnhe/everforest
- https://github.com/rebelot/kanagawa.nvim
