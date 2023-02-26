My first readme
root@f15678e86530:/# cd alx-pre_course
root@f15678e86530:/alx-pre_course# mkdir 0×01-git
root@f15678e86530:/alx-pre_course# cd 0×01-git
root@f15678e86530:/alx-pre_course/0×01-git# touch README.md
root@f15678e86530:/alx-pre_course/0×01-git# echo My first readme > README.md
root@f15678e86530:/alx-pre_course/0×01-git# cat README.md
My first readme
root@f15678e86530:/alx-pre_course/0×01-git# cd ..
root@f15678e86530:/alx-pre_course# ls
0×01-git  README.md
root@f15678e86530:/alx-pre_course# pwd
/alx-pre_course
root@f15678e86530:/alx-pre_course# git add .
root@f15678e86530:/alx-pre_course# git commit -m 'My first commit'
[master 5d25476] My first commit
 1 file changed, 1 insertion(+)
 create mode 100644 "0\303\22701-git/README.md"
root@f15678e86530:/alx-pre_course# git push
Password for 'https://alx-pre_course@github.com': 
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 2 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 283 bytes | 283.00 KiB/s, done.
Total 2 (delta 0), reused 0 (delta 0)
To https://github.com/majdoubiadil/alx-pre_course.git
   9a88548..5d25476  master -> master
