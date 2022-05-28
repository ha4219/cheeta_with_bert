# [emogenius](https://github.com/ha4219/emogenius)

![emogenius](https://github.com/ha4219/emogenius/blob/dev/assets/readme/0.png?raw=true)

## Contents

- [Title](#-title)
- [Description](#-Description)
- [Team](#-Team)
- [Install](#-Install)
- [Run](#-Run)
- [Task](#-Task)
- [Release](#-Release)
- [License](#-License)
- [Reference](#-Reference)

## 🎉 Title

- [emogenius](https://github.com/ha4219/emogenius)

## 📖 Description
![summary](https://github.com/ha4219/emogenius/blob/dev/assets/readme/summary.png?raw=true)
- 한국어 문장을 감정 별로 분류해 그에 맞는 Emoji를 추천한다.



## 😀 Team

- [정동하](https://github.com/ha4219)


## 🎯 Install
![deploy_](https://github.com/ha4219/emogenius/blob/dev/assets/readme/1.png?raw=true)


현재 배포 심사 중 입니다. 따라서 아래 방법을 따라해주세요!
1. [emogenius donwload link](https://github.com/ha4219/emogenius/releases/download/1.0.0/emogenius.zip)를 통해 해당 파일을 다운받고 압축을 풉니다.
2. chrome://extensions/로 이동합니다.
3. 오른쪽 상단에서 개발자 모드를 사용 설정합니다.
<img src="https://github.com/ha4219/emogenius/blob/dev/assets/readme/2.png?raw=true" style="display: block;  width: 200px; height: 70px;"/>

4. "압축해제된 확장 프로그램을 로드합니다"를 클릭합니다.
<img src="https://github.com/ha4219/emogenius/blob/dev/assets/readme/3.png?raw=true" style="display: block;"/>

5. 앱 또는 확장 프로그램 폴더를 찾아 선택합니다.

6. Chrome 다음에서 새 탭을 열고 앱을 클릭한 다음 다음 앱 또는 확장 프로그램을 클릭합니다. 올바르게 로드되고 작동하는지 확인합니다.
<img src="https://github.com/ha4219/emogenius/blob/dev/assets/readme/4.png?raw=true" style="display: block; width: 400px; height: 200px;"/>


## 🚘 Run

![run_gif](https://github.com/ha4219/emogenius/blob/dev/assets/readme/run.gif?raw=true)

- 문장을 드래그한 후 단축키를 눌러주세요!
 
- `Window`: Ctrl+Shift+U
- `Mac`: Command+U 

- 단축키 변경은 chrome 확장 프로그램에서 좌측 상단 메뉴바를 클릭 한 후 단축키를 누르면 변경할 수 있습니다.
<img src="https://github.com/ha4219/emogenius/blob/dev/assets/readme/5.png?raw=true" style="display: block;"/>

## ✅ Task
- [x] Fine Tuning KoBERT 
- [x] Deploy Flask server 
- [x] Make Chrome Extension


## 🌋 Release
- v1.0.0 (22.05.29)
  - 초기 앱 릴리즈

## 📄 License
`KoBERT` 프로그램이 `Apache-2.0`를 따르기에 그대로 사용했습니다. 잘 못 올렸을 경우 알려주세요. 수정하겠습니다.

## 👍 Reference

- [감성 대화 말뭉치](https://aihub.or.kr/aidata/7978)
- [SKTBrain/KoBERT](https://github.com/SKTBrain/KoBERT)
- [emojidb](https://emojidb.org/)