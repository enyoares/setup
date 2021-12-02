# zsh 설치

## 일단 패키지 레파지토리 인덱스부터 업데이트 하고
```sudo apt update```

## git과 zah
```sudo apt install git zsh```


# Oh my zsh 설치 및 구성

## 설치
```sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"```

## 테마 구성

zsh_theme 항목 변경
```vi ~/.zshrc```
```ZSH_THEME="agnoster"```
> agnoster 테마는 powerline font 설치 필요
> https://github.com/powerline/fonts

https://mulder21c.github.io/2021/01/28/setting-up-wsl-2-dev-env-and-zsh-on-windws-10/
