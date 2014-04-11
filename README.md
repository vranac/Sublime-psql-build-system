Sublime-psql-build-system
=========================

Postres psql build system so you can execute your queries from ST and see results quick.

Well, the idea is that you take this build system, put it in your project directory (possibly give it some meaningful name),
edit it for your credentials, and then…

Create a symlink to your Sublime Text build system location.

Depending on your OS, and Sublime Text version that would be for either in the Packages or Packages/User directory in
your Sublime Text path (I prefer the Packages/User), for OSX, the path would be ~/Library/Application Support/Sublime Text 3/Packages/User

Once you have done that, open a new file in Sublime Text, save it, select the build system from Tools –> Build System,
and on mac press cmd+b (or select Tools –> Build), if you setup everything properly, the results.txt should be created,
and you can open it to see results.