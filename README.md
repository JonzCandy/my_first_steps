# 1- 

https://github.com/JonzCandy/my_first_steps.git

# 2-

João Miguel@PC-Do-JOAO MINGW64 /c/area de trabalho/Alpha_Treino/my_first_steps
$ git init
Initialized empty Git repository in C:/area de trabalho/Alpha_Treino/my_first_steps/.git/

João Miguel@PC-Do-JOAO MINGW64 /c/area de trabalho/Alpha_Treino/my_first_steps (master)
$ git remote add origin https://github.com/JonzCandy/my_first_steps.git

# 3-

João Miguel@PC-Do-JOAO MINGW64 /c/area de trabalho/Alpha_Treino/my_first_steps (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        ola_mundo.txt

nothing added to commit but untracked files present (use "git add" to track)

João Miguel@PC-Do-JOAO MINGW64 /c/area de trabalho/Alpha_Treino/my_first_steps (master)
$ git add .

João Miguel@PC-Do-JOAO MINGW64 /c/area de trabalho/Alpha_Treino/my_first_steps (master)
$ git commit -m "Adicionando arquivo txt"
[master (root-commit) 03e9085] Adicionando arquivo txt
 1 file changed, 4 insertions(+)
 create mode 100644 ola_mundo.txt

João Miguel@PC-Do-JOAO MINGW64 /c/area de trabalho/Alpha_Treino/my_first_steps (master)
$ git push origin master
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 267 bytes | 267.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'master' on GitHub by visiting:
remote:      https://github.com/JonzCandy/my_first_steps/pull/new/master
remote:
To https://github.com/JonzCandy/my_first_steps.git

 * [new branch]      master -> master

# 4-

/serei_ignorado.txt

