# Hi there

컴퓨터공학을 공부하는 학생입니다. 트랜지스터부터 컴파일러까지, 컴퓨터가 실제로 어떻게 돌아가는지 아래층부터 하나씩 만들어 보며 배우고 있습니다.

지금 관심 있는 분야는 CPU 마이크로아키텍처와 메모리 계층, x86-64 어셈블리, 컴파일러(IR과 최적화), 하드웨어 보안입니다. 회로이론과 미적분도 기초부터 따로 공부하고 있습니다.

이 계정은 부계정이며, 실제 계정은 [@twopercenz](https://github.com/twopercenz)입니다.


## Research

> 여기에 있는 대부분의 프로젝트는 twopercenz 계정에 게시되어 있습니다.

**Von Neumann Bottleneck and Systolic Array Architecture: An Empirical Efficiency Comparison** (2026)
아두이노 나노 4대로 2×2 시스톨릭 배열을 구성하고, 폰 노이만식 순차 처리와 시스톨릭 배열의 두 데이터 흐름 방식(OS, WS)을 행렬 곱셈으로 비교했습니다. PE 간 통신은 비트뱅잉으로 구현했고, 처리 시간·MAC 연산 수·메모리 접근 횟수·사이클 수를 측정했습니다. 4인 팀 프로젝트입니다.

**KDAA: Korean Dubeolsik Acoustic Attack** (진행 중)
키보드 타건음으로 입력을 추정하는 음향 사이드채널 공격(ASCA)을 한글 두벌식 자판에 적용하는 연구입니다. 기존 연구는 대부분 영문 QWERTY를 대상으로 합니다. 근접 마이크, 원거리 마이크, 배경소음의 세 가지 공격 시나리오에서 CNN 기반 모델의 성능을 비교합니다.

**TRNG 엔트로피원 비교** (진행 중)
애벌랜치 노이즈, 이산소자 링 오실레이터, FPGA 링 오실레이터를 엔트로피원으로 하는 진짜 난수생성기를 만들어 비교하고 있습니다.

## Projects

**[Percentage](https://github.com/twopercenz/percentage)**
나무위키 형태의 한국어 개방형 위키입니다. 자체 위키 문법인 PerMark를 사용합니다. Next.js와 Supabase로 만들었습니다.
*쌓으면, 보입니다.*

**[Cotton](https://github.com/twopercenz/cotton)**
Rust, C 계열, Lua, Python, JavaScript의 특징을 섞은 프로그래밍 언어입니다. 언어 명세 v0.2를 완성했고, Rust로 작성한 렉서가 동작합니다. 다음 목표는 파서와 IR입니다.

**Hobby OS**
x86-64 어셈블리로 만들고 있는 운영체제입니다. 부트섹터에서 시작해 커널 로드, 32비트 보호 모드, 페이징과 64비트 롱 모드를 거쳐, freestanding C 커널에서 VGA 드라이버가 동작하는 단계까지 왔습니다. QEMU에서 테스트합니다.

**[music.player](https://github.com/twopercenz/music.player)**
개인용 뮤직 플레이어입니다. 오디오 추출 계층으로 [MUXIC.js](https://github.com/twopercenz/MUXIC.js)를 쓰는 방안을 검토하고 있습니다.

**[MUXIC.js](https://github.com/twopercenz/MUXIC.js)**
mp3 다운로더 라이브러리입니다.

**KSCA** (기획 중)
전국 단위 청소년 컴퓨터 사이언스 학회를 위한 웹 서비스입니다. 영구 식별자, APA·BibTeX 인용 형식, 버전 관리를 갖춘 Zenodo 형태의 논문 아카이브와 커뮤니티 게시판으로 구성됩니다.

## Open Source

[oven-sh/bun](https://github.com/oven-sh/bun)에 기여하려고 준비하고 있습니다. 첫 작업은 AggregateError 출력 개선(#21528)입니다.

## Stack

`x86-64 ASM` `C` `Rust` `TypeScript` `Next.js` `Supabase` `Arduino` `KiCad` `QEMU` `Docker` `Oracle Cloud`
