# libhangul #

## 소개 ##
지금까지 한글 입력기 구현을 위해서 반복적으로 사용되는 코드가 많아서 낭비되고 관리하기 어려운 점이 있었습니다.
한글 입력기 구현의 핵심 알고리듬을 공유하여 쉽게 한글 입력 루틴을 구현하기 위해서 만들어진 프로젝트 입니다.

libhangul은 다음과 같은 기능을 제공합니다.

  * 한글 입력기의 기본 동작을 구현한 코드를 제공합니다. libhangul의 [HangulInputContext](http://libhangul.googlecode.com/git/doc/html/group__hangulic.html#hangulicusage)를 이용하면 한글 조합 루틴을 별도로 작성하지 않아도 한글 입력 기능을 손쉽게 구현할 수 있습니다.
  * 한자 사전 파일과 검색 루틴을 제공합니다. 한글 입력기에서 한자 변환에 필요한 데이터를 한자 사전 파일 형태로 제공하고, 그 파일에서 원하는 한자를 쉽게 찾아볼 수 있는 함수를 제공합니다.
  * 몇가지 간단한 유니코드 한글 처리 루틴을 제공합니다.

## 지원하는 자판 ##
[libhangul이 지원하는 자판 목록](http://libhangul.googlecode.com/git/doc/html/group__hangulkeyboards.html)

## 빌드 방법 ##
```
./configure --prefix=XXX
make
make install
```

## libhangul API Reference ##
[libhangul API Reference Manual](http://libhangul.googlecode.com/git/doc/html/index.html)

## libhangul을 사용하는 프로젝트 ##
  * XIM nabi : http://code.google.com/p/nabi/
  * SCIM용 한글 엔진 scim-hangul: http://sourceforge.net/projects/scim/
  * [ibus](http://code.google.com/p/ibus/)용 한글 엔진 ibus-hangul: http://github.com/choehwanjin/ibus-hangul/
  * [GTK+](http://www.gtk.org/)용 한글 입력 모듈 imhangul: http://code.google.com/p/imhangul/
  * [Qt](http://qt.nokia.com/)용 한글 입력 모듈: http://code.google.com/p/qimhangul/
  * Hangul JFBTERM: http://kldp.net/projects/hangul-jfbterm/
  * Mac OS X 용 한글입력기 바람: http://baram.or.kr/
  * Mac OS X 용 한글입력기 구름: http://gureum.org/
  * [fcitx](http://code.google.com/p/fcitx/)용 한글 엔진: https://github.com/fcitx/fcitx-hangul