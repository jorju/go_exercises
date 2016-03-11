Go basic exercises for students

- Go programmers typically keep all their Go code in a single workspace.
- A workspace contains many version control repositories (managed by Git, for example).
- The src subdirectory typically contains multiple version control repositories (such as for Git or Mercurial) that track the development of one or more source packages.
- Each repository contains one or more packages.
- Each package consists of one or more Go source files in a single directory.
- The path to a package's directory determines its import path.
- The go tool builds source packages and installs the resulting binaries to the pkg and bin directories.

Note that this differs from other programming environments in which every project has a separate workspace and workspaces are closely tied to version control repositories.
