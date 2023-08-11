# 오셀로 게임 프로젝트

![Othello](./othello_readme_example1.jpg)

이 프로젝트는 React를 사용하여 개발한 오셀로 게임입니다. 오셀로 게임은 흑돌과 백돌이 번갈아가며 돌을 놓아 상대방 돌을 뒤집어 자신의 돌로 바꾸는 전략 보드 게임입니다.

## 기술 스택

- Frontend: React
- Styling: styled-components
- Routing: react-router-dom

## 게임 소개

게임을 시작하면 오셀로 보드판이 나타나며, 흑돌부터 게임이 시작됩니다. 각 턴마다 플레이어는 자신의 돌을 보드 위에 놓을 수 있습니다. 이때, 플레이어 돌의 옆에 상대방 돌이 한개나 여러개가 같은줄에 연속에서 있다면, 반대편에 놓을 수 있습니다. 자신의 돌 사이에 놓인 상대의 돌은 모두 자신의 돌로 변하게 됩니다. 게임이 진행됨에 따라 더 많은 돌을 가진 사람이 승리합니다..

## 시작 화면

![Start Screen](./othello_readme_example2.png)

게임을 시작할 때 보이는 시작 화면에서는 두 가지 옵션이 제공됩니다:

1. **Game Start!**: 이 버튼을 클릭하여 게임을 시작합니다.
2. **How to play?**: 이 버튼을 클릭하면 게임의 규칙과 플레이 방법에 대한 설명이 나타납니다.

## 게임 진행

![Game Board](./othello_readme_example3.png)

게임이 시작되면 보드 위에는 현재 상태가 표시됩니다. 각 칸은 흑돌, 백돌, 빈 공간을 나타내는데, 플레이어는 자신의 차례에 놓을 수 있는 위치에 "+(플러스)"가 표시됩니다.

## AI PUT!
이 버튼을 클릭하면 위치에 따른 점수를 부여하는 식의 알고리즘을 활용하여 컴퓨터가 돌을 놓을 위치를 선택하게 할 수 있습니다. 컴퓨터는 현재 보드 상황을 고려하여 가장 안정성이 높은 위치를 선택합니다.

## 게임 종료 및 승리
게임이 진행됨에 따라 돌을 놓을 수 있는 위치가 없어지거나, 모든돌이 검은돌이나 하얀돌이되면 게임이 종료됩니다. 이때, 돌의 개수를 세어 더 많은 돌을 보유한 플레이어가 승리합니다. 또한 돌의 개수가 동일한 경우 무승부 처리됩니다.
