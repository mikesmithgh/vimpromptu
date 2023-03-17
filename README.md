
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
- https://yadm.io/ - yet another dotfiles manager
- https://github.com/hpjansson/chafa - conver images to ansi (gifs)

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

- `:Ni!` 
```
Do you demand a shrubbery?
```

- `:help holy-grail` or `:help smile`
```
You found it, Arthur!				*holy-grail* *:smile*
```

- `:help nunmap`
```
:nunmap can also be used outside of a monastery.
```

- https://www.vim.org/images/vimassistant.gif
![ClippyVim](https://www.vim.org/images/vimassistant.gif)

- `:help 42`
```
What is the meaning of life, the universe and everything?  *42*
Douglas Adams, the only person who knew what this question really was about is
now dead, unfortunately.  So now you might wonder what the meaning of death
is...
```

- `:help quotes` `// vim (not in neovim)`
```
Here are some nice quotes about Vim that I collected from news and mail.


vim (vim) noun - Ebullient vitality and energy.  [Latin, accusative of vis,
strength]  (Dictionary)

Vim is so much better than vi that a great many of my old vi :map's became
immediately obsolete! (Tony Nugent, Australia)

Coming with a very GUI mindset from Windows, I always thought of people using
Vi as some kind of outer space alien in human clothes.  Once I tried I really
got addicted by its power and now I found myself typing Vim keypresses in the
oddest places! That's why I would like to see Vim embedded in every
application which deals with text editing.  (José Fonseca)

I was a 12-year emacs user who switched to Vim about a year ago after finally
giving up on the multiple incompatible versions, flaky contributed packages,
disorganized keystrokes, etc.  And it was one of the best moves I ever made.
(Joel Burton)

Although all of the programs were used during the preparation of the new and
revised material, most of the editing was done with Vim versions 4.5 and 5.0
under GNU-Linux (Redhat 4.2).  (Arnold Robbins, Israel, author of "Learning
the Vi editor")

Out of all the open software i've ever seen and used, and i've seen a lot, Vim
is the best, most useful and highest quality to work with, second only to the
linux kernel itself.  (Peter Jay Salzman)

It's well worth noting that the _entirety_ of SourceForge was written using
Vim and its nifty PHP syntax highlighting.  I think the entire SF.net tech
staff uses Vim and we're all excited to have you aboard! (Tim Perdue)

Vim is one of a select bunch of tools for which I have no substitute.  It is
a brilliant piece of work! (Biju Chacko)

A previous girlfriend of mine switched to emacs.  Needless to say, the
relationship went nowhere.  (Geoffrey Mann)

I rarely think about Vim, in the same way that I guess a fish rarely thinks
about water.  It's the environment in which everything else happens.  I'm a
fairly busy system administrator working on a lot of different platforms.  Vim
is the only thing that's consistent across all my systems, and it's just about
the only thing that doesn't break from time to time.  When a new system comes
in the door without Vim, I install it right away.  Great to have a tool that's
the same everywhere, that's completely reliable, so I can ignore it and think
about other things.  (Pete Schaeffer)

Having recently succeeded in running Vim via telnet through a Nokia
Communicator, I can now report that it works nicely on a Palm Pilot too.
(Allan Kelly, Scotland)

You've done a tremendous job with 'VIM', Bram!  The more I use it, the more
impressed I get (I am an old 'vi' die hard who once started out with early
versions of 'emacs' in the late 1970's and was relieved by finding 'vi' in the
first UNIX I came across in 1983).  In my opinion, it's about time 'VIM'
replace 'emacs' as the standard for top editors.  (Bo Thide', Sweden)

I love and use Vim heavily too.  (Larry Wall)

Vi is like a Ferrari, if you're a beginner, it handles like a bitch, but once
you get the hang of it, it's small, powerful and FAST! (Unknown)
Vim is like a new model Ferrari, and sounds like one too - "VIIIIIIMMM!"
(Stephen Riehm, Germany)

Schon bei Nutzung eines Bruchteils der Vim-Funktionen wird der Benutzer recht
schnell die Vorzuege dieses Editors kennen- und schaetzenlernen.
Translated: Even when only using a fraction of Vim-functions, the user will
quickly get used to and appreciate the advantages of this editor.  (Garry
Glendown, conclusion of an article on Vim in iX magazine 9/1998)

I've recently acquired the O'Reilly book on Vi (it also discusses Vim
in-depth), and I'm amazed at just how powerful this application is.  (Jeffrey
Rankin)

This guide was written using the Windows 9.x distribution of gvim, which is
quite possibly the greatest thing to come along since God created the naked
girl.  (Michael DiBernardo)

Boy, I thought I knew almost everything about Vim, but every time I browse the
online documentation, I hit upon a minor but cool aspect of a Vim feature that
I didn't know before!  I must say the documentation is one the finest I've
ever seen in a product -- even better than most commercial products.
(Gautam Mudunuri)

Vim 4.5 is really a fantastic editor.  It has sooooo many features and more
importantly, the defaults are so well thought out that you really don't have
to change anything!!  Words cannot express my amazement and gratitude to the
creators of Vim.  Keep it up.  (Vikas, USA)

I wonder how long it will be before people will refer to other Vi editors as
Vim clones?  (Darren Hiebert)

I read about [auto-positioning-in-file-based-on-the-errors-from-make] in one
of those "Perfect Programmer's Editor" threads and was delighted to discover
that Vim already supports it.  (Brendan Macmillan, Australia)

I just discovered Vim (5.0) and I'm telling everyone I know about it!
I tell them Vim stands for Vi for the new (M)illenium.  Thanks so much!
(Matt F. Valentine)

I think from now on "vi" should be called "Vim Imitation", not the other way
around.  (Rungun Ramanathan)

The Law of Vim:
For each member b of the possible behaviour space B of program P, there exists
a finite time t before which at least one user u in the total user space U of
program P will request b becomes a member of the allowed behaviour space B'
(B' <= B).
In other words: Sooner or later everyone wants everything as an option.
(Negri)

Whenever I move to a new computing platform, the first thing I do is to port
Vim.  Lately, I am simply stunned by its ease of compilation using the
configure facility.  (A.M. Sabuncu, Turkey)

The options are really excellent and very powerful.  (Anish Maharaj)

The Spring user-interface designs are in, and word from the boutiques is that
80x24 text-only mode is back with a *vengeance! Vi editor clone Vim burst onto
March desk-tops with a dazzling show of pastel syntax highlights for its 5.0
look.  Strident and customizable, Vim raises eyebrows with its interpretation
of the classic Vi single-key macro collection.
http://www.ntk.net/index.cgi?back=archive98/now0327.txt&line=179#l

I just wanted to take this opportunity to let you know that Vim 5 ROCKS!
Syntax highlighting: how did I survive without it?!  Thank you for creating
mankind's best editor!  (Mun Johl, USA)

Thanks again for Vim.  I use it every day on Linux.  (Eric Foster-Johnson,
author of the book "UNIX Programming Tools")

The BEST EDITOR EVER (Stuart Woolford)

I have used most of Vim's fancy features at least once, many frequently, and I
can honestly say that I couldn't live with anything less anymore.  My
productivity has easily doubled compared to what it was when I used vi.
(Sitaram Chamarty)

I luv Vim.  It is incredible.  I'm naming my first-born Vimberly.  (Jose
Unpingco, USA)

Hint:  "Vim" is "vi improved" - much better! (Sven Guckes, Germany)

I use Vim every day.  I spend more time in Vim than in any other program...
It's the best vi clone there is.  I think it's great.  (Craig Sanders,
Australia)

I strongly advise using Vim--its infinite undo/redo saved me much grief.
(Terry Brown)

Thanks very much for writing what in my opinion is the finest text editor on
the planet.  If I were to get another cat, I would name it "Vim".
(Bob Sheehan, USA)

I typed :set all and the screen FILLED up with options.  A whole screen of
things to be set and unset.  I saw some of my old friends like wrapmargin,
modelines and showmode, but the screen was FILLED with new friends!   I love
them all!   I love Vim!   I'm so happy that I've found this editor!  I feel
like how I once felt when I started using vi after a couple of years of using
ed.  I never thought I'd forsake my beloved ed, but vi ... oh god, vi was
great.  And now, Vim.  (Peter Jay Salzman, USA)

I am really happy with such a wonderful software package.  Much better than
almost any expensive, off the shelf program.  (Jeff Walker)

Whenever I reread the Vim documentation I'm overcome with excitement at the
power of the editor.  (William Edward Webber, Australia)

Hurrah for Vim!! It is "at your fingertips" like vi, and has the extensions
that vi sorely needs: highlighting for executing commands on blocks, an easily
navigable and digestible help screen, and more.  (Paul Pax)

The reason WHY I don't have this amazingly useful macro anymore, is that I
now use Vim - and this is built in!! (Stephen Riehm, Germany)

I am a user of Vim and I love it.  I use it to do all my programming, C,
C++, HTML what ever.  (Tim Allwine)

I discovered Vim after years of struggling with the original vi, and I just
can't live without it anymore.  (Emmanuel Mogenet, USA)

Emacs has not a bit of chance to survive so long as Vim is around.  Besides,
it also has the most detailed software documentation I have ever seen---much
better than most commercial software!  (Leiming Qian)

This version of Vim will just blow people apart when they discover just how
fantastic it is! (Tony Nugent, Australia)

I took your advice & finally got Vim & I'm really impressed.  Instant convert.
(Patrick Killelea, USA)

Vim is by far my favorite piece of shareware and I have been particularly
pleased with version 3.0.  This is really a solid piece of work.  (Robert
Colon, USA)

Vim is a joy to use, it is so well thought and practical that I wonder why
anybody would use visual development tools.  Vim is powerful and elegant, it
looks deceptively simple but is almost as complex as a 747 (especially when I
look at my growing .vimrc), keep up that wonderful job, Vim is a centerpiece
of the free software world.  (Louis-David Mitterand, USA)

I cannot believe how great it is to use Vim.  I think the guys at work are
getting tired of hearing me bragging about it.  Others eyes are lighting up.
(Rick Croote)

Emacs takes way too much time to start up and run, it is too big and bulky for
effective use and the interface is more confusing than it is of any help.  Vim
however is short, it is fast, it is powerful, it has a good interface and it
is all purpose.  (Paal Ditlefsen Ekran)

From the first time I got Vim3.0, I was very enthusiastic.  It has almost no
problems.  The swapfile handling and the backup possibilities are robust, also
the protection against editing one file twice.  It is very compatible to the
real VI (and that is a MUST, because my brain is trained over years in using
it).  (Gert van Antwerpen, Holland)

Visual mode in Vim is a very powerful thing! (Tony Nugent, Australia)

I have to say that Vim is =THE= single greatest piece of source code to ever
come across the net (Jim Battle, USA).

In fact, if you do want to get a new vi I'd suggest Vim-3.0.  This is, by
far, the best version of vi I've ever seen (Albert W. Schueller).

I should mention that Vim is a very good editor and can compete with anything
(Ilya Beloozerov).

To tell the truth sometimes I used elvis, vile, xvi, calvin, etc.  And this is
the reason that I can state that Vim is the best! (Ferenc Deak, Hungary)

Vim is by far the best editor that I have used in a long time, and I have
looked at just about every thing that is available for every platform that I
use.  Vim is the best on all of them.  (Guy L. Oliver)

Vim is the greatest editor since the stone chisel.  (Jose Unpingco, USA)

I would like to say that with Vim I am finally making the 'emacs to vi'
transition - as an Editor it is so much better in many ways: keyboard layout,
memory usage, text alteration to name 3.  (Mark Adam)

In fact, now if I want to know what a particular setting does in vi, I fire up
Vim and check out its help!  (Nikhil Patel, USA)

As a vi user, Vim has made working with text a far more pleasant task than
before I encountered this program.  (Steinar Knutsen, Norway)

I use Vim since version 3.0.  Since that time, it is the ONLY editor I use,
with Solaris, Linux and OS/2 Warp.  I suggest all my friends to use Vim, they
try, and they continue using it.  Vim is really the best software I have ever
downloaded from the Internet, and the best editor I know of.  (Marco
Eccettuato, Italy)


In summary:
     __     ___		    _	    _	_  ___ _____ `
     \ \   / (_)_ __ ___   (_)___  | | | |/ _ \_   _| `
      \ \ / /| | '_ ` _ \  | / __| | |_| | | | || | `
       \ V / | | | | | | | | \__ \ |  _  | |_| || | `
        \_/  |_|_| |_| |_| |_|___/ |_| |_|\___/ |_| `
	     ____ _____ _   _ _____ _____ _ _ `
	    / ___|_   _| | | |	___|  ___| | | `
	    \___ \ | | | | | | |_  | |_  | | | `
	     ___) || | | |_| |	_| |  _| |_|_| `
	    |____/ |_|	\___/|_|   |_|	 (_|_)	    (Tony Nugent, Australia) `

```

- `:help!`
```
E478: Don't panic!
```

- `:hi!`
```
Greetings, Vim user!
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
- https://github.com/karb94/neoscroll.nvim - keep on scrolling baby
- https://github.com/edluffy/hologram.nvim - image plugin that integrates with kitty protocol
- https://github.com/johngrib/vim-game-code-break


## Vim Colorschemes
- https://vimcolorschemes.com/
- https://github.com/Lokaltog/vim-distinguished - My first favorite 
- https://github.com/morhetz/gruvbox
- https://github.com/ellisonleao/gruvbox.nvim - My current jam
- https://github.com/folke/tokyonight.nvim
- https://github.com/rose-pine/neovim
- https://github.com/sainnhe/everforest
- https://github.com/rebelot/kanagawa.nvim
- https://github.com/savq/melange

## Vim Testing
- https://github.com/Vimjas/vim-testbed Because unit testing a Vim plugin is a pain in the ass.
- https://github.com/junegunn/vader.vim I use Vader to test Vimscript.


## font stuff
Download https://github.com/tonsky/FiraCode/releases to ~/Library/fonts
unzip
kitty conf:
symbol_map U+21,U+2b,U+2d,U+2f,U+3c,U+3d,U+3e,U+5c Fira Code Regular

Download https://github.com/source-foundry/Hack/releases/tag/v3.003 to ~/Library/fonts
unzip
kitty conf

## random
- http://metaphorpsum.com/


## TODO
- https://github.com/chomosuke/term-edit.nvim
- https://github.com/knubie/vim-kitty-navigator
- https://github.com/sharkdp/vivid
- https://github.com/sorenisanerd/gotty
- https://github.com/anuvyklack/hydra.nvim
- https://github.com/lukas-reineke/headlines.nvim
- https://github.com/danymat/neogen
- https://github.com/p-gen/smenu
- https://github.com/MordechaiHadad/bob

