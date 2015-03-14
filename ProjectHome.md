This project hosts custom source snapshots of [Hugs](http://haskell.org/hugs) oriented towards use of Hugs as [Yhc Core](http://haskell.org/haskellwiki/Yhc/API/Core) producer. Such usage of Hugs was made possible recently by pushing a specific patch to the [main Hugs source repository](http://darcs.haskell.org/hugs98/) in June 2008, and introduction of several Haskell packages on [Haskell Community server](http://code.haskell.org).

The purpose of making such snapshots is to provide a easier way to build Hugs with recent Haskell libraries, and Yhc Core generation enabled, since mere downloading sources from Hugs and libraries' repos does not always result in successfully compilable code.

Custom snapshots of Hugs include source code of Hugs itself, and also source code of Haskell packages/libraries available in their repositories at the time snapshots were taken. The selection of libraries may differ from the selection available in official Hugs releases.

Custom snapshots of Hugs are **not** official releases. Although every effort is done to make sure they compile upon downloading, Haskell libraries may contain runtime errors resulting from their own development history.

Custom snapshots of Hugs are intended for experimentation rather than for production use.

Custom snapshots of Hugs are distributed under [The Hugs 98 License](http://cvs.haskell.org/Hugs/pages/users_guide/license.html) which is BSD-style.