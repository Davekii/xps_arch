# xps_arch
arch_linux_on_dell_xps_15_9550

내가 아치리눅스 에서 사용하고 있는 프로그램들 


Gimp - 이미지 편집 프로그램 

feh - 이미지 뷰어
nomcs - 이미지 뷰어

firefox - 브라우저
dwm - 리눅스 윈도우 매니저

zettlr - 글쓰기 프로그램

VSCODE - 코딩 프로그램 

neofetch - 사용하는 인터페이스 표시 프로그램

geary - 메일 클라이언트 관리 프로그램 

-- 구글 메일 사용시 https://myaccount.google.com/lesssecureapps 보안수준이 낮은 앱 허용에 체크를 해야한다. --


standard note - 일반 메모, 노트작성 프로그램 핸드폰과의 연동이 빠르고 간단하다. 유저인터페이스가 직관적이기 때문에 사용하기 편리하다.


vim 의 vundle 플러그인들과 oh my zsh 의 플러그인들 

vim의 vundle 설치 

git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim



sudo apt install zsh 

sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"



[zsh-syntax-highlighting]


git clone https://github.com/zsh-users/zsh-syntax-highlighting.git $ZSH_CUSTOM/plugins/zsh-syntax-highlighting 

위의 플러그인은 신택스 하이라이팅

[zsh-autosuggestions]

git clone https://github.com/zsh-users/zsh-autosuggestions $ZSH_CUSTOM/plugins/zsh-autosuggestions

이건 사용자가 쳤던 명령어들을 자동으로 추천해준다.


-- 데이터팀의 추천 개발환경 --

vs code 개발 ide # https://code.visualstudio.com/

jupyter notebook # pip install jupyterlab

dbeaver = 데이터베이스 관리 프로그램 # https://dbeaver.io/

** 회사의 서버는 총 3개 이다. **

1. 나이팟 
2. 델 워크스테이션 
3. AWS

