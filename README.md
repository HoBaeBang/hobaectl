# HoBaeCTL Project
해당 프로젝트는 쓰고 싶은 명령어를 내맘대로 입맛에 맞게 사용하고자 진행하는 내맘대로ctl 프로젝트인다.

해당 명령어가 정말 필요 없더라도 그냥 개인적인 만족감에 사용 가능하다.

## 지원 OS
현재 지원 하는 OS 목록은
- Mac OS를 기준으로 진행한다.
- 추후 linux 계열(debian) 부터 차례대로 업데이트 예정이다.

### 설치 방법
해당 프로젝트를 다운받는다면 터미널에서 사용 할 수 있도록 
~/.bash_profile, ~/.bashrc, 또는 source ~/.zshrc에 맞게 아래의 코드를 추가한다.

```
export PATH="$PATH:해당 파일이 위치한 경로(pwd)"
```

### 권한 설정
```
chmod +x hobaectl
```

### 터미널 설정 리로딩
자신의 터미널에 맞도록
source ~/.bash_profile, source ~/.bashrc, 또는 source ~/.zshrc를 실행합니다

### 테스트
테스트를 위해 아래의 명령을 진행한다.
```
hobaectl --help
```


### 사용법
현재 지원하는 명령어 리스트
1. hobaectl wtf
- 정말 하기싫을때 해당 명령어를 치면 한숨이 나오지만 다시 하게된다.

2. hobaectl --help
- 해당 명령어는 가장 우선적으로 업데이트 예정이다.

3. hobaectl ls
- 그냥 사용하는 ls로 일단 재미를 위해 넣어둔 기능이다.

4. hoabectl free
- 현재 Mac의 메모리의 정보를 확인 할 수 있다.

5. hobaectl info
- 가장 많이 사용하는 기능으로 내 MacOS의 정보를 확인할때 사용한다.
