# KSH Karabiner

## Install Karabiner
### 설치
[Karabiner](https://karabiner-elements.pqrs.org/)
### 하단배열 확인
1. Open `Karabiner-EventViewer`
2. 하단배열 입력하여 현재 키 코드 확인
3. (변경이 필요한 경우) 키보드 자체 매핑 프로그램
   또는 시스템 설정 → 키보드 → 키보드 단축키 → 보조 키

## 한영전환
1. Open `Karabiner-Elements`
2. Simple Modification → For all devices
3. `한/영으로 쓸 키` → `f19`
4. 시스템 설정 → 키보드 → 키보드 단축키 → 입력 소스 → 입력 메뉴에서 다음 소스 선택 → `한/영으로 쓸 키` 입력 → 완료

## Capslock Mod
1. Import to Karabiner
```
karabiner://karabiner/assets/complex_modifications/import?url=https://raw.githubusercontent.com/shkang46/karabiner/main/ksh_karabiner.json
```
2. Enable `ksh_karabiner`
3. Move to Simple Modification → For all devices
4. `caps_lock(Modifier Keys) 또는 나만의 키` → `f20(Function Keys)`
5. (Optional) 필요한 경우 `caps_lock 또는 나만의 키`를 안쓰는 키에 할당

#### Detail
| From              | To                    | Description             | Dependency |
| ----------------- | --------------------- | ----------------------- | ---------- |
| `caps_lock` `W`                 | ↑                     | Up                      |            |
| `caps_lock` `A`                 | ←                     | Left                    |            |
| `caps_lock` `S`                 | ↓                     | Down                    |            |
| `caps_lock` `D`                 | →                     | Right                   |            |
| `caps_lock` `Q`                 | `Ctrl` `Shift` `Tab`  | 이전 탭                   | Browser    |
| `caps_lock` `E`                 | `Ctrl` `Tab`          | 다음 탭                   | Browser    |
| `caps_lock` `Z`                 | `Ctrl` `←`            | 이전 데스크탑              | MacOS      |
| `caps_lock` `X`                 | `Ctrl` `→`            | 다음 데스크탑              | MacOS      |
| `caps_lock` `R`                 | `Cmd` `Shift` `R`     | 강력 새로고침              |            |
| `caps_lock` `J`                 | `Opt` `←`             | 이전 한 단어 커서 이동       |            |
| `caps_lock` `L`                 | `Opt` `→`             | 다음 한 단어 커서 이동       |            |
| `caps_lock` `U`                 | `Opt` `Backspace`     | 이전 한 단어 지우기         |            |
| `caps_lock` `O`                 | `Opt` `Delete`        | 다음 한 단어 지우기         |            |
| `caps_lock` `I`                 | `Opt` `↑`             | 현재 라인 위로 옮기기        | VSCode     |
| `caps_lock` `K`                 | `Opt` `↓`             | 현재 라인 아래로 옮기기      | VSCode     |
| `caps_lock` `P`                 | `Backspace`           | 앞 글자 지우기             |            |
| `caps_lock` `M`                 | `Delete`              | 뒷 글자 지우기             |            |
| `caps_lock` `Y`                 | `Insert`              |                         |            |
| `caps_lock` `H`                 | `Page Up`             |                         |            |
| `caps_lock` `N`                 | `Page Down`           |                         |            |
| `caps_lock` `.`                 | `Ctrl` `Cmd` `Space`  | 이모티콘                  |            |
| `caps_lock` `F`                 | `Cmd` `Shift` `F`     | 한 줄 지우기               |    VSCode  |
| `caps_lock` `ESC`               | `Backtick` `          |                         |            |
| `caps_lock` `g`                 | `Ctrl` `Opt` `L`      |  Log 생성                |   VSCode, Turbo Console Log  |
| `caps_lock` `{`                 |                       |                         |            |
| `caps_lock` `}`                 |                       |                         |            |


## Tiles.app

[Tiles](https://freemacsoft.net/tiles/)

1. Import to Karabiner
```
karabiner://karabiner/assets/complex_modifications/import?url=https://github.com/shkang46/karabiner/blob/main/RightControlForTilesApp.json
```
2. Enable  'ksh_right_control_for_tiles_app`

#### Detail
| From              | To                    | Description             | Dependency |
| ----------------- | --------------------- | ----------------------- | ---------- |
| `Right Ctrl` `↑`  | `Opt` `Cmd` `↑`       | 화면 상단 정렬             | Tiles      |
| `Right Ctrl` `←`  | `Opt` `Cmd` `←`       | 화면 좌측 정렬             | Tiles      |
| `Right Ctrl` `↓`  | `Opt` `Cmd` `↓`       | 화면 하단 정렬             | Tiles      |
| `Right Ctrl` `→`  | `Opt` `Cmd` `→`       | 화면 우측 정렬             | Tiles      |

