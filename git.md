# git

JetBrains사 IDE의 Git bash를 이용해 commit시 한글 로그가 깨지는 현상  

``` bash
git config --global -l
```
확인 후

``` bash
i18n.commitencoding=UTF-8
```
이 없다면

```bash
git config --global i18n.commitencoding "UTF-8"
```
설정을 해주자.

reference : https://sang5c.tistory.com/47

--- 
