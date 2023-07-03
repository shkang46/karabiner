# KSH Karabiner

-   Karabiner는 <strong>MacOS</strong>만 지원함
-   <strong>Windows</strong> 유저는 [kanata](https://github.com/jtroo/kanata) 참조

---

## Install Karabiner

### 설치

[Karabiner](https://karabiner-elements.pqrs.org/)

### 하단배열 확인

1. Open `Karabiner-EventViewer`
2. 하단배열 입력하여 현재 키 코드 확인
3. (변경이 필요한 경우) 키보드 자체 매핑 프로그램
   또는 시스템 설정 → 키보드 → 키보드 단축키 → 보조 키
4. 권장: <kbd>left_control</kbd> <kbd>left_option</kbd> <kbd>left_command</kbd> <kbd>spacebar</kbd> <kbd>f19</kbd> <kbd>(right_option)</kbd> <kbd>right_control<kbd>

---

## 한영전환

1. Open `Karabiner-Elements`
2. Simple Modification → For all devices
3. <kbd>한/영으로 쓸 키</kbd> → <kbd>f19</kbd>
4. 시스템 설정 → 키보드 → 키보드 단축키 → 입력 소스 → 입력 메뉴에서 다음 소스 선택 → <kbd>한/영으로 쓸 키</kbd> 입력 → 완료

---

## Capslock Mod

1. Import to Karabiner

```
karabiner://karabiner/assets/complex_modifications/import?url=https://raw.githubusercontent.com/shkang46/karabiner/main/ksh_karabiner.json
```

2. Enable `ksh_karabiner`
3. Move to Simple Modification → For all devices
4. <kbd>caps_lock</kbd>(Modifier Keys) 또는 <kbd>나만의 키</kbd> → <kbd>f20</kbd>(Function Keys)
5. (Optional) 필요한 경우 <kbd>caps_lock</kbd> 또는 <kbd>나만의 키</kbd>를 안쓰는 키에 할당

#### Detail

| From                                   | To                                                                                                                       | Description             | Dependency                |
| -------------------------------------- | ------------------------------------------------------------------------------------------------------------------------ | ----------------------- | ------------------------- |
| <kbd>caps_lock</kbd> <kbd>W</kbd>      | <kbd>↑</kbd>                                                                                                             | Up                      |                           |
| <kbd>caps_lock</kbd> <kbd>A</kbd>      | <kbd>←</kbd>                                                                                                             | Left                    |                           |
| <kbd>caps_lock</kbd> <kbd>S</kbd>      | <kbd>↓</kbd>                                                                                                             | Down                    |                           |
| <kbd>caps_lock</kbd> <kbd>D</kbd>      | <kbd>→</kbd>                                                                                                             | Right                   |                           |
| <kbd>caps_lock</kbd> <kbd>Q</kbd>      | <kbd>Ctrl</kbd> <kbd>Shift</kbd> <kbd>Tab</kbd>                                                                          | 이전 탭                 | Browser                   |
| <kbd>caps_lock</kbd> <kbd>E</kbd>      | <kbd>Ctrl</kbd> <kbd>Tab</kbd>                                                                                           | 다음 탭                 | Browser                   |
| <kbd>caps_lock</kbd> <kbd>Z</kbd>      | <kbd>Ctrl</kbd> <kbd>←</kbd>                                                                                             | 이전 데스크탑           | MacOS                     |
| <kbd>caps_lock</kbd> <kbd>X</kbd>      | <kbd>Ctrl</kbd> <kbd>→</kbd>                                                                                             | 다음 데스크탑           | MacOS                     |
| <kbd>caps_lock</kbd> <kbd>R</kbd>      | <kbd>Cmd</kbd> <kbd>Shift</kbd> <kbd>R</kbd>                                                                             | 강력 새로고침           |                           |
| <kbd>caps_lock</kbd> <kbd>J</kbd>      | <kbd>Opt</kbd> <kbd>←</kbd>                                                                                              | 이전 한 단어 커서 이동  |                           |
| <kbd>caps_lock</kbd> <kbd>L</kbd>      | <kbd>Opt</kbd> <kbd>→</kbd>                                                                                              | 다음 한 단어 커서 이동  |                           |
| <kbd>caps_lock</kbd> <kbd>U</kbd>      | <kbd>Opt</kbd> <kbd>Backspace</kbd>                                                                                      | 이전 한 단어 지우기     |                           |
| <kbd>caps_lock</kbd> <kbd>O</kbd>      | <kbd>Opt</kbd> <kbd>Delete</kbd>                                                                                         | 다음 한 단어 지우기     |                           |
| <kbd>caps_lock</kbd> <kbd>I</kbd>      | <kbd>Opt</kbd> <kbd>↑</kbd>                                                                                              | 현재 라인 위로 옮기기   | VSCode                    |
| <kbd>caps_lock</kbd> <kbd>K</kbd>      | <kbd>Opt</kbd> <kbd>↓</kbd>                                                                                              | 현재 라인 아래로 옮기기 | VSCode                    |
| <kbd>caps_lock</kbd> <kbd>P</kbd>      | <kbd>Backspace</kbd>                                                                                                     | 앞 글자 지우기          |                           |
| <kbd>caps_lock</kbd> <kbd>M</kbd>      | <kbd>Delete</kbd>                                                                                                        | 뒷 글자 지우기          |                           |
| <kbd>caps_lock</kbd> <kbd>Y</kbd>      | <kbd>Insert</kbd>                                                                                                        |                         |                           |
| <kbd>caps_lock</kbd> <kbd>H</kbd>      | <kbd>Page Up</kbd>                                                                                                       |                         |                           |
| <kbd>caps_lock</kbd> <kbd>N</kbd>      | <kbd>Page Down</kbd>                                                                                                     |                         |                           |
| <kbd>caps_lock</kbd> <kbd>.</kbd>      | <kbd>Ctrl</kbd> <kbd>Cmd</kbd> <kbd>Space</kbd>                                                                          | 이모티콘                |                           |
| <kbd>caps_lock</kbd> <kbd>F</kbd>      | <kbd>Cmd</kbd> <kbd>Shift</kbd> <kbd>F</kbd>                                                                             | 한 줄 지우기            | VSCode                    |
| <kbd>caps_lock</kbd> <kbd>ESC</kbd>    | <kbd>Backtick</kbd> </kbd>                                                                                               |                         |                           |
| <kbd>caps_lock</kbd> <kbd>g</kbd>      | <kbd>Ctrl</kbd> <kbd>Opt</kbd> <kbd>L</kbd>                                                                              | Log 생성                | VSCode, Turbo Console Log |
| <kbd>caps_lock</kbd> <kbd>{</kbd>      |                                                                                                                          |                         |                           |
| <kbd>caps_lock</kbd> <kbd>}</kbd>      |                                                                                                                          |                         |                           |
| <kbd>caps_lock</kbd> <kbd>insert</kbd> | <kbd>s</kbd><kbd>a</kbd><kbd>l</kbd><kbd>e</kbd><kbd>s</kbd><kbd>f</kbd><kbd>o</kbd><kbd>r</kbd><kbd>c</kbd><kbd>e</kbd> |                         |                           |

---

## Tiles.app

[Tiles](https://freemacsoft.net/tiles/)

1. Import to Karabiner

```
karabiner://karabiner/assets/complex_modifications/import?url=https://github.com/shkang46/karabiner/blob/main/RightControlForTilesApp.json
```

2. Enable 'ksh_right_control_for_tiles_app<kbd>

#### Detail

| From                               | To                                         | Description    | Dependency |
| ---------------------------------- | ------------------------------------------ | -------------- | ---------- |
| <kbd>Right Ctrl</kbd> <kbd>↑</kbd> | <kbd>Opt</kbd> <kbd>Cmd</kbd> <kbd>↑</kbd> | 화면 상단 정렬 | Tiles      |
| <kbd>Right Ctrl</kbd> <kbd>←</kbd> | <kbd>Opt</kbd> <kbd>Cmd</kbd> <kbd>←</kbd> | 화면 좌측 정렬 | Tiles      |
| <kbd>Right Ctrl</kbd> <kbd>↓</kbd> | <kbd>Opt</kbd> <kbd>Cmd</kbd> <kbd>↓</kbd> | 화면 하단 정렬 | Tiles      |
| <kbd>Right Ctrl</kbd> <kbd>→</kbd> | <kbd>Opt</kbd> <kbd>Cmd</kbd> <kbd>→</kbd> | 화면 우측 정렬 | Tiles      |
