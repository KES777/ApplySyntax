# ApplySyntax
ApplySyntax is a plugin for Sublime Text 2 and 3 that allows you to detect and apply the syntax of files that might not otherwise be detected properly. For example, files with the `.rb` extension are usually Ruby files, but when they are found in a Rails project, they could be RSpec spec files, Cucumber step files, Ruby on Rails files (controllers, models, etc), or just plain Ruby files. This is actually the problem I was trying to solve when I started working on this plugin.

# Credits
DetectSyntax was originally created by phillipkoebbe.  In his words, these are his credits:

> It all started by forking the plugin created by JeanMertz [(1)][1]. I modified it quite extensively until I ended up with something entirely my own [(2)][2]. @maxim and @omarramos commented on the gist and suggested it should be part of Package Control. As I had created it solely for my own consumption, it seemed a bit "hard-coded" to be valuable as a package, but then I took a look at SetSyntax [(3)][3]. and saw how using settings would make it very flexible. That set me on the path that led to DetectSyntax.

[1]: https://gist.github.com/925008
[2]: https://gist.github.com/1497794
[3]: https://github.com/aparajita/SetSyntax

# Installation
ApplySyntax can be installed in a variety of ways:

* Through Package Control [Package Control](https://packagecontrol.io/)

    - Open Package Control
    - Select 'Install Package'
    - Find and select 'ApplySyntax'

* By cloning this repository in Packages

    - cd into your Packages folder
    - `git clone git://github.com/facelessuser/ApplySyntax.git`

* By downloading the files and placing them in a directory under `Packages/ApplySyntax`. If you download and extract a compressed archive from GitHub, the directory will be `facelessuser-ApplySyntax`. Remove `facelessuser-`.

# Documentation
http://facelessuser.github.io/ApplySyntax/
