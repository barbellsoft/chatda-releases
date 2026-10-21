# Chatda (찾다)

**Free desktop search for Windows and macOS.** Chatda finds files on your PC, external drives and network folders by name and by the text inside documents.

[Website](https://barbellsoft.com/chatda/) · [Download](https://barbellsoft.com/chatda/download.html) · [Help](https://barbellsoft.com/chatda/help.html) · [한국어](#한국어)

## Download

| System | File |
|---|---|
| Windows 10 / 11 (64-bit) | [Chatda_x64-setup.exe](https://github.com/barbellsoft/chatda-releases/releases/latest/download/Chatda_x64-setup.exe) |
| macOS (Apple silicon and Intel) | [Chatda_universal.dmg](https://github.com/barbellsoft/chatda-releases/releases/latest/download/Chatda_universal.dmg) |

On a Mac you can also install it with Homebrew:

```
brew install --cask barbellsoft/tap/chatda
```

Chatda tells you when a new version is out and updates itself.

## What it does

- **Search inside documents.** Finds text inside PDF, Word (DOCX), Excel (XLSX), PowerPoint (PPTX), Hangul (HWPX) and plain-text files, not just file names.
- **Whole-drive file name search on Windows.** Add a drive such as C:\ and Chatda reads the NTFS file table directly, so a drive with 1.2 million files is indexed in about 15 seconds. New files show up in search within seconds.
- **Network folders.** Connect a NAS or SMB share and search it in the same window.
- **Search syntax.** Filter by extension, size and date, for example `*.pdf`, `ext:docx;xlsx`, `size:>10mb`, `dm:thisweek`.
- **One table of results** you can sort, filter and group, with previews. Open Chatda from anywhere with Ctrl+Shift+Space.

## Good to know

- **Not code-signed yet.** Windows may show "Windows protected your PC" the first time; choose More info, then Run anyway. On a Mac, right-click the app and choose Open, or install with Homebrew.
- **Fast indexing service (Windows).** The installer asks once whether to install it. It lets Chatda index whole drives quickly and catch up on changes made while the app was closed. With the service, everyone who signs in to that PC can search file names on its drives. Installing and updating ask for administrator approval.
- **Privacy.** The index stays on your computer. Apart from a NAS or search server you connect yourself, the only thing Chatda sends out is the update check.

## Feedback

Report bugs and ideas in this repository's [Issues](https://github.com/barbellsoft/chatda-releases/issues).

Chatda is freeware, free for personal and business use. You may redistribute the original, unmodified installer free of charge. The source code is not public. See [LICENSE](LICENSE) for the terms.

---

## 한국어

Chatda는 내 컴퓨터와 네트워크 폴더에서 파일을 찾아 주는 무료 검색 프로그램입니다. 파일 이름만 보는 게 아니라 문서 안의 글자까지 찾고 Windows와 macOS에서 모두 돌아갑니다.

## 내려받기

| 운영체제 | 파일 |
|---|---|
| Windows 10·11 (64비트) | [Chatda_x64-setup.exe](https://github.com/barbellsoft/chatda-releases/releases/latest/download/Chatda_x64-setup.exe) |
| macOS (Apple Silicon·Intel) | [Chatda_universal.dmg](https://github.com/barbellsoft/chatda-releases/releases/latest/download/Chatda_universal.dmg) |

맥에서는 터미널에 아래 한 줄을 붙여 넣어도 됩니다. 최신판을 받아 응용 프로그램 폴더에 넣어 줍니다.

```
curl -fsSL https://github.com/barbellsoft/chatda-releases/releases/latest/download/install.sh | bash
```

설치한 뒤에는 새 버전이 나오면 앱이 알려 주고 단추 하나로 업데이트됩니다.

## 이런 걸 할 수 있습니다

- **문서 본문 검색.** PDF, Word(docx), Excel(xlsx), PowerPoint(pptx), 한글(hwpx), 텍스트 파일 안의 글자로 찾습니다. 한국어는 "결산"으로 "업무결산보고"가 걸리도록 붙여 쓴 말 안쪽까지 찾습니다.
- **드라이브 전체 파일 이름 검색.** Windows에서 C:\ 같은 드라이브를 통째로 추가하면 NTFS 파일 목록을 직접 읽어 120만 개 파일을 15초 안팎에 색인합니다. 드라이브 전체는 이름·크기·날짜만 색인하고 본문은 따로 추가한 폴더에서만 읽습니다.
- **네트워크 폴더.** 회사·집 NAS의 공유 폴더(SMB)를 연결해 같은 창에서 찾습니다.
- **검색 문법.** `*.pdf`, `ext:docx;xlsx`, `size:>10mb`, `dm:thisweek` 처럼 확장자·크기·수정일로 거를 수 있습니다.
- **바뀐 파일 자동 반영.** 파일을 만들거나 고치거나 지우면 색인에 바로 반영됩니다.

## 알아 두실 것

- **아직 코드 서명이 없습니다.** Windows에서는 처음 실행할 때 "Windows의 PC 보호" 창이 뜰 수 있습니다. "추가 정보 → 실행"을 누르면 됩니다. 맥은 위의 한 줄 설치를 쓰거나, 앱을 오른쪽 클릭한 뒤 "열기"를 누르세요.
- **드라이브 빠른 색인 서비스(Windows).** 설치할 때 한 번 물어봅니다. 서비스가 있으면 드라이브 전체를 빠르게 색인하고 새 파일을 몇 초 안에 찾으며, 앱이 꺼져 있던 동안 바뀐 파일도 따라잡습니다. 그 PC에 로그인하는 모든 사용자가 드라이브의 파일 이름을 검색할 수 있게 됩니다. 설치와 업데이트에는 관리자 승인이 필요합니다.
- **개인정보.** 색인은 내 컴퓨터 안에만 저장됩니다. 직접 연결한 NAS나 검색 서버를 빼면 Chatda가 밖으로 보내는 것은 업데이트 확인뿐이고, 검색 내용이나 파일 정보는 어디로도 보내지 않습니다.

## 문의

버그나 제안은 이 저장소의 [Issues](https://github.com/barbellsoft/chatda-releases/issues)에 남겨 주세요.

Chatda는 개인과 회사 모두 무료로 쓸 수 있는 프리웨어입니다(업무용 포함). 소스 코드는 공개하지 않습니다. 이용 조건은 [LICENSE](LICENSE)를 보세요.
