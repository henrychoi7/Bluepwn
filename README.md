# Project Bluepwn

Bluepwn은 대학 연합 정보보안 커뮤니티 SUA (SecurityPlus Union Academy) 소속 대학생들로 구성된 팀, Nevermind에서 진행하고 있는 프로젝트입니다. 본 프로젝트의 목적은 국내 보안 업계에 BlueBorne 취약점의 위험성을 더 자세히 알리면서 동시에 최대한 많은 사람들이 블루투스 보안에 대한 경각심을 가질 수 있게 하기 위함입니다.

## CVE-2017-0785 PoC

Armis에서 발표한 안드로이드 메모리 정보 유출 취약점에 대한 PoC 스크립트입니다.

자세한 정보: https://www.armis.com/blueborne/

PoC를 실행하려면 `pybluez`와 `pwntools`를 설치해야 합니다.

```
sudo apt-get install bluetooth libbluetooth-dev
sudo pip install pybluez
sudo pip install pwntools
```
