CClassesRepo
============

It is a repository for classes in C (for l2sh team)

So...
Today(15.10.2013) I wanted to read something about Git. I have found a really good site everyone can understand.
It is http://git-scm.com/book/ru/
If you want to learn it, you are pleased.

I have two variants of commiting. I have downloaded Git and had two programmes: one of them was Git Bash and
the other was Git GUI. GUI is Graphics User Interface, so if you can't work with command line, you may use it and 
you will see ordinary buttons and windows, where you can understand everything. If you like a command line, the best way
to make commits, you are welcome:

At first, you must clone the repository(repo) to your local computer. To do this, just type:
          
          git clone "https://github.com/vmkvmshL2SH1/CClassesRepo.git"
          
After it you can type a directory, where to hold it, but it is optional. In default it stores in Users/you/CClassesRepo
When you are working in command line type

          cd CClassesRepo
          
and you woll be in the repo (If you use a default path)

So now if you want to commit a file to repository you must make some steps:

1. Make a file.
2. Put it into your LOCAL repo path (Default: C:/Users/you/CClassesRepo)
3. Index it (add it to local repo)
4. Commit it.
5. Push it to remote repo.

To index it type:

          git add FileName.*
          
To Commit it type:

          git commit -m "Your message with description"
          
And at last you should push it to repo. There are two ways. If you downloaded GitHub for Windows
(YOU MUST DO IT), you would just click a button "Publish" and it will be pushed. But if you are a hardcore man...
Read further:

This way you should find a name of your remote repo. To do this, you may type:

          git remote -v
          
and you will have a list of your repo-s where to fetch and push. Usully it's name is origin. Let's use it in example.
To push it you should write name of repo and name of branck (main branch is called master). This way you type:

          git push origin master
          
That's all! Who came there says "Moooo!" and continues working! Bye! Good Luck!
