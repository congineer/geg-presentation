# Source code development environment setup

## Host prerequisites

* Revision control `Git`: [Download Git][1]
* Code editor `VSCode`: [Download VSCode][2]
* Recommended code editor extensions: (TODO)

### Pulling latest code changes from remote repository

1. Open a dedicated terminal window (in system or in editor).
2. Navigate into the source code folder `cd ~/git/projects/geg-presentation`
3. Pull source code changes from remote repository `git pull`

## Guest prerequisites

* None.

### Launching development

1. Open a dedicated terminal window (in system or in editor).
2. Navigate into the source code folder `cd ~/git/projects/geg-presentation`
3. If *"package-lock.json"* file has been modified (upon Git pull on host):
    * Install the most recent project dependencies with `npm install` (or use `npm i` as shorthand)
4. Launch development environment with `npm start`
5. Open web browser on host machine and navigate to [https://localhost:PORT](https://localhost:PORT)
6. To stop a running development environment use `Ctrl + C`

[1]: https://git-scm.com/downloads
[2]: https://code.visualstudio.com/download
