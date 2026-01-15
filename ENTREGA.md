1. El resultado de:


$ git log --oneline --graph --decorate --all
*   a3ca733 (HEAD -> develop, origin/develop) Merge branch 'hotfix/1.0.1' into develop
|\
| * 6ab4b32 (tag: v1.0.1, origin/main, main) fix: hotfix add multiply
| *   bd08f1f (tag: v1.0.0) Merge branch 'release/1.0.0'
| |\
* | \   dd573f7 Merge branch 'release/1.0.0' into develop
|\ \ \
| | |/
| |/|
| * | 19565d3 chore: release polish.
| * | 7322375 chore: bump version 1.0.0.
|/ /
* / 8465fc9 feat: add subtract.
|/
* 8c255e7 chore: initial version.

2. El resultado de: 

$ git tag -n
v1.0.0          Release 1.0.0
v1.0.1          Hotfix 1.0.1

3. Enlace a github: 

https://github.com/Maanuel77/minicalc-gitflow/tree/develop



