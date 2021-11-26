d 目錄
r 可讀
w 可寫
x 可執行
chmod 可控制檔案如何被他人調動
mode 許可權設定字串
u 檔案擁有者
g 與該檔案的擁有者同一個群體者
o 其他以外的人
a 三者皆是
= 唯一設定許可權
+ 增加許可權
- 取消許可權

檔案 filel.txt 設為所有人皆可讀取
chmod ugo+r filel. txt
chmod ugo+r filel. txt
將檔案 filel. txt 與file2.txt 設為該檔案擁有者，與其所屬同一個群體者可寫人，但其他
以外的人則不可寫入：
chmod ug+w, o-w filel.txt file2. txt
將exL.py 設定為只有該檔案擁有者可以執行：
chmod u+x exl.py
將目前目錄下的所有檔案與子目錄皆設為任何人可讀取：
chmod -R a+r *
chmod a=rwx file = chmod 777 file
chmod ug=rwx, o=x file = chmod 771 file
