### Mac yarn 설치
# 홈브루를 /opt 디렉토리에 설치하기 위해 이동
cd /opt

# 루트 권한으로 homebrew 폴더를 만든다
sudo mkdir homebrew

# homebrew 폴더의 루트 권한을 유저로 바꿔준다
sudo chown -R $(whoami) /opt/homebrew
//sudo chown -R 유저명 경로 = 경로의 권한을 유저한테 준다는 뜻 

# homebrew 다운로드
curl -L https://github.com/Homebrew/brew/tarball/master | tar xz --strip 1 -C homebrew

# homebrew bin 디렉토리를 PATH에 추가
echo "export PATH=/opt/homebrew/bin:$PATH" >> ~/.zshrc

# homebrew 홈페이지에 있던 명령어를 이제 실행!
/bin/bash -c "$(curl -fsSL https://gist.githubusercontent.com/nrubin29/bea5aa83e8dfa91370fe83b62dad6dfa/raw/48f48f7fef21abb308e129a80b3214c2538fc611/homebrew_m1.sh)"

# 설치완료 

# 참고사이트
https://im-designloper.tistory.com/53 -- 감사합니다 --


### 리액트를 활요한 기본 퍼블리싱 작업
# 난이도 : 5점 중 3점
쉬운건 확실히 html,css, js를 활용한 퍼블리싱 혹은 개발이 쉬울 것이다 
그러나 
손에 익어서 작업이 쉬운 것이지 react 라이브러리들을 활용하고 prop으로 넘어가는 것을 잘 활용한다면 훨신 더 쉬울 것 같아 3점을 줬고 더 쉬워졌으면 한다 

### 사용 슬라이드
https://react-slick.neostack.com/docs/example/simple-slider -- 도움이 많이 됬습니다.


