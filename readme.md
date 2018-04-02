Game Development
================

Learn Game Development and build your own Game Engine using SFML and C++

Blog: [http://gamedev.glenfletcher.com](http://gamedev.glenfletcher.com "Game Development Blog")

---

This repository provides a series of tagged commits matching the blog posts on my Game Development Blog

To use this repository you should clone it using the following command:

    $ git clone --recursive https://github.com/glenfletcher-gamedev/game-development-blog.git <local folder>

Then you can build/open the code associated with a specific blog post using:

    $ cd <local folder>
    $ git checkout <post slug>
    $ git submodule update --init --recursive
    $ cd projects/<project slug>
    $ codeblocks <project slug>.workspace [--build] [--target=(Debug|Release)]

For example to open the code from the first blog post ([https://gamedev.glenfletcher.com/getting-started/](https://gamedev.glenfletcher.com/getting-started/ "Getting Started with SFML")) use:

    $ git clone --recursive https://github.com/glenfletcher-gamedev/game-development-blog.git game-development
    $ cd game-development
    $ git checkout getting-started
    $ git submodule update --init --recursive
    $ cd projects/getting-started
    $ codeblocks getting-started.workspace

or to build the Release target change the last line to:

    $ codeblocks getting-started.workspace --build --target=Release 
