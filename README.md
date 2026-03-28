<p align="center">
<a href="https://github.com/zxcloli666/SoundCloud-Desktop/releases/latest">
<img src="https://raw.githubusercontent.com/zxcloli666/SoundCloud-Desktop/legacy/icons/appLogo.png" width="180px" style="border-radius: 50%;" />
</a>
</p>

<h1 align="center"><a href="https://soundcloud.su/">SoundCloud Desktop 한국어</a></h1>

<p align="center">
<b>SoundCloud를 위한 네이티브 데스크톱 앱</b><br>
광고 없음 · CAPTCHA 없음 · 검열 없음 · 한국어 지원
</p>

> [!CAUTION]
> SoundCloud가 앱 차단을 시작했습니다. 우회 방법은 있지만 향후 대응 방향은 여기에서 확인해 주세요: [#264](https://github.com/zxcloli666/SoundCloud-Desktop/discussions/264)

> [!CAUTION]
> 이 레포지토리는 zxcloli666의 [SoundCloud-Desktop](https://github.com/zxcloli666/SoundCloud-Desktop)에서 포크해왔습니다. 저작권은 원작자에게 있습니다.

<p align="center">
<a href="https://github.com/zxcloli666/SoundCloud-Desktop/releases/latest">
<img src="https://img.shields.io/github/v/release/zxcloli666/SoundCloud-Desktop?style=for-the-badge&logo=github&color=FF5500&label=VERSION" alt="Version"/>
</a>
<a href="https://github.com/zxcloli666/SoundCloud-Desktop/releases">
<img src="https://img.shields.io/github/downloads/zxcloli666/SoundCloud-Desktop/total?style=for-the-badge&logo=download&color=FF5500&label=Downloads" alt="Downloads"/>
</a>
<a href="https://github.com/zxcloli666/SoundCloud-Desktop/stargazers">
<img src="https://img.shields.io/github/stars/zxcloli666/SoundCloud-Desktop?style=for-the-badge&logo=github&color=FF5500&label=Stars" alt="Stars"/>
</a>
<a href="https://github.com/zxcloli666/SoundCloud-Desktop/blob/main/LICENSE">
<img src="https://img.shields.io/badge/License-MIT-FF5500?style=for-the-badge" alt="License"/>
</a>
</p>

<p align="center">
<a href="https://github.com/zxcloli666/SoundCloud-Desktop/releases/latest">
<img src="https://img.shields.io/badge/다운로드-최신_버전-FF5500?style=for-the-badge" alt="Download"/>
</a>
<a href="https://github.com/zxcloli666/SoundCloud-Desktop-EN">
<img src="https://img.shields.io/badge/English-README-0066FF?style=for-the-badge" alt="English"/>
</a>
</p>

---

## 소개

**SoundCloud Desktop**은 SoundCloud 음악 감상을 위한 완전한 데스크톱 앱입니다. Tauri 2 + React 19로 제작되었으며, 네이티브로 동작하고 시스템 리소스를 적게 사용하며 버벅임 없이 가볍게 실행됩니다.

현재 **100,000명 이상이 사용 중**이며, Windows, Linux, macOS에서 동작합니다.

---

## 왜 SoundCloud Desktop인가

### 러시아에서도 사용 가능

SoundCloud는 차단되어 있어서 공식 웹 버전이 열리지 않을 수 있습니다. SoundCloud Desktop은 별도 우회 프로그램 없이 바로 동작하며, SoundCloud 전체 카탈로그에 온전히 접근할 수 있습니다.

### 한국어 지원

한국어가 지원됩니다. (포크해서.내가.함.ㅋ)
시간 별 메시지에 다양성이 있습니다.

### 광고 없음

배너 광고도 없고, 트랙 사이의 프로모 안내도 없고, “프리미엄을 구독하세요” 같은 팝업도 없습니다. 음악에만 집중할 수 있습니다.

### CAPTCHA 없음

끝없는 사람 확인이나 “로봇이 아닙니다” 같은 절차가 없습니다. 그냥 바로 들으면 됩니다.

### 검열 없음

지역 제한 없이 SoundCloud 전체 카탈로그에 접근할 수 있습니다. 모든 트랙, 모든 아티스트, 모든 장르를 그대로 이용할 수 있습니다.

### 네이티브, 그리고 가벼움

Electron 대신 **Tauri 2**(Rust) 위에서 동작합니다. 그 덕분에:
- 설치 파일 크기 약 **15MB** 수준
- 재생 중 메모리 사용량 약 **80~120MB**
- 빠른 실행 속도
- 낮은 사양에서도 60 FPS에 가까운 부드러운 인터페이스

### 완전한 러시아어 지원

인터페이스는 러시아어로 완전히 번역되어 있습니다. 언어는 시스템 설정을 기준으로 자동 선택되며, 따로 설정할 필요가 없습니다.

### 시스템 통합

- **시스템 제어 지원**: 키보드 미디어 키, Windows 시스템 미디어 컨트롤, Linux MPRIS 지원
- **Discord Rich Presence**: 지금 듣고 있는 음악을 Discord에 표시
- **트레이 지원**: 앱을 백그라운드에서 계속 실행 가능
- **자동 업데이트**: 새 버전을 한 번의 클릭으로 설치 가능

---

## 다운로드

### Windows

[최신 릴리스 페이지](https://github.com/zxcloli666/SoundCloud-Desktop/releases/latest)에서 다음 중 하나를 다운로드하세요:
- **`.exe`** (NSIS 설치 프로그램) - 권장
- **`.msi`** - 대체 설치 프로그램

요구 사항: Windows 10 (1809+) 또는 Windows 11

### Linux

| 형식 | 아키텍처 | 설명 |
|--------|------------|----------|
| `.deb` | amd64, arm64 | Ubuntu, Debian, Mint, Pop!_OS |
| `.rpm` | amd64, arm64 | Fedora, openSUSE, CentOS |
| `.AppImage` | amd64, arm64 | 범용 포맷, 대부분의 배포판에서 실행 가능 |
| `.flatpak` | amd64 | 샌드박스, 자동 업데이트 지원 |

[최신 릴리스 페이지](https://github.com/zxcloli666/SoundCloud-Desktop/releases/latest)에서 원하는 포맷을 다운로드하세요.

AppImage를 사용할 경우:
```bash
chmod +x soundcloud-desktop-*.AppImage
./soundcloud-desktop-*.AppImage
```

### macOS

- **Apple Silicon** (M1/M2/M3/M4): `*_arm64.dmg`
- **Intel**: `*_x64.dmg`

[최신 릴리스 페이지](https://github.com/zxcloli666/SoundCloud-Desktop/releases/latest)에서 다운로드할 수 있습니다. 첫 실행 시 macOS 보안 경고가 표시될 수 있습니다.

---

## 스크린샷

<p align="center">

![home-screen](https://github.com/user-attachments/assets/66d6abb5-7ecd-493c-a0a1-19e7b22d2da5)

![liked-tracks](https://github.com/user-attachments/assets/d590bfe7-487b-4578-90fd-2c21646e262a)

</p>

---

## 참여 방법

| | |
|---|---|
| 아이디어 제안 | [토론 #121](https://github.com/zxcloli666/SoundCloud-Desktop/discussions/121) |
| 문제가 있어요 | [토론 #144](https://github.com/zxcloli666/SoundCloud-Desktop/discussions/144) |
| 별표 남기기 | [GitHub Stars](https://github.com/zxcloli666/SoundCloud-Desktop/stargazers)로 프로젝트를 도와주세요 |

Pull request는 언제나 환영합니다. 큰 변경을 계획 중이라면 먼저 issue를 열어 주세요.

---

## 소스에서 빌드

<details>
<summary><b>개발자를 위한 안내</b></summary>

### 요구 사항

- **Node.js** 22+
- **pnpm** 10+
- **Rust** 1.77+ (stable)

### 개발 실행

```bash
git clone https://github.com/zxcloli666/SoundCloud-Desktop.git
cd SoundCloud-Desktop/desktop
pnpm install
pnpm tauri dev
```

### 프로덕션 빌드

```bash
pnpm tauri build
```

빌드 결과물은 `src-tauri/target/release/bundle/`에 생성됩니다.

### 검사

```bash
npx tsc --noEmit        # TypeScript 타입 검사
cargo check             # Rust 컴파일 검사
npx biome check src/    # 린트
```

</details>

---

## 기술 스택

| 구성 요소 | 기술 |
|-----------|-----------|
| 셸 | Tauri 2 (Rust) |
| 프런트엔드 | React 19, Vite 7, Tailwind CSS 4 |
| 상태 관리 | Zustand, TanStack Query |
| 오디오 | rodio (rust) |
| UI 컴포넌트 | Radix UI |
| 백엔드 | NestJS 11, TypeORM, PostgreSQL |
| CI/CD | GitHub Actions, 모든 플랫폼 빌드 |
| 린터 | Biome |

---

## 통계

<p align="center">
<img src="https://api.star-history.com/svg?repos=zxcloli666/SoundCloud-Desktop&type=Date" alt="Star History" />
</p>

<p align="center">
<img src="https://zxcloli666.github.io/download-history/zxcloli666_SoundCloud-Desktop.svg" alt="Download History" />
</p>

---

## 라이선스

MIT 라이선스입니다. 자세한 내용은 [LICENSE](LICENSE)를 확인하세요.

SoundCloud는 SoundCloud Ltd.의 상표입니다. 이 앱은 SoundCloud와 제휴되어 있지 않습니다.

---

<p align="center">
<code>soundcloud desktop</code> · <code>soundcloud 앱</code> · <code>soundcloud 클라이언트</code> · <code>pc용 soundcloud</code> · <code>soundcloud windows</code> · <code>soundcloud linux</code> · <code>soundcloud macos</code> · <code>광고 없는 soundcloud</code> · <code>러시아 soundcloud</code> · <code>러시아에서 soundcloud</code> · <code>soundcloud가 열리지 않음</code> · <code>soundcloud 차단</code> · <code>soundcloud blocked russia</code> · <code>soundcloud desktop app</code> · <code>soundcloud desktop client</code> · <code>soundcloud player</code> · <code>soundcloud app for pc</code> · <code>captcha 없는 soundcloud</code> · <code>pc에 soundcloud 설치</code> · <code>soundcloud desktop download</code> · <code>soundcloud alternative client</code> · <code>soundcloud no ads</code> · <code>soundcloud 음악 플레이어</code>
</p>

<p align="center">
<a href="https://github.com/zxcloli666/SoundCloud-Desktop/releases/latest">
<img src="https://img.shields.io/badge/다운로드_SoundCloud_Desktop-FF5500?style=for-the-badge&logoColor=white" alt="Download" height="50"/>
</a>
</p>
