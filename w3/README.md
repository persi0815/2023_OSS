# 2023_OSS   
## 2023 OSS 수업   
### 3주차 git   

### 이미지   
![kau](https://user-images.githubusercontent.com/121751509/227792911-0413c631-2008-4cac-8a98-69d7e8b2df42.png)   

### 링크   
[LMS](https://lms.kau.ac.kr/login.php)   

### ProGit 링크   
[ProGit](https://git-scm.com/book/ko/v2)   

### 2주차 숙제
```
#!/usr/bin/env bash
echo "----------"
echo "name :"

echo

echo "----------"
echo "student id :"


file_path=`find /home/kau2/ -name w2_homework.txt 2> /dev/null`
echo "----------"
echo
echo "file path :"
echo $file_path
echo

line_num=`wc -l $file_path | cut -c 1 -`
echo "----------"
echo "line number :"
echo $line_num
echo

echo "----------"
echo "lask line :"
tail -n 1 $file_path
```
