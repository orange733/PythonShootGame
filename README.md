# PythonShootGame

A simple shoot game written in Python.

# Introduction

This project only include two simple .py files: 

1. mainGame.py: The initialization and main loop of the game.
2. gameRole.py: Class of the game role.

# Requirement

1. Python 2.7
2. Python-Pygame
  
# How To Start Game
  
```bash
$ python mainGame.py
```

# License
GPL

# Screeshot

![](http://s2.postimg.org/728c1wy4p/Screenshot_5.png)

![](http://s30.postimg.org/fflxcv9ld/Screenshot_6.png)

# Doc
[使用Pygame制作微信打飞机游戏PC版](https://www.cnblogs.com/dukeleo/p/3339780.html) (a Chinese startup)

-------------------------------------------------------------------------------------------------------
# 2021.01.21

게임 패배 시 space키로 재시작 기능 추가

총알 속도 20, 적 출현 속도 50, 적 10마리 처치 시 챕터 상승
챕터 상승 시 총알 속도 -0.3, 적 출현 속도 -1, 최대 챕터 45
(총 총알 13.5 감소, 적 출현 속도 45 감소)

score 7000시 배경화면 변경

처치한 적, 놓친 적 kill/loss 표기

놓친 적이 3마리 일 때 게임 패배

패배시 최고기록 표기
