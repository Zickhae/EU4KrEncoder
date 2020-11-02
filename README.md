# EU4TranslateTools

필요 환경
=========
* Python 3.x (https://www.python.org/downloads/ 에서 다운로드 가능)

사용 방법
=========

* original 폴더 아래에 bmfc, yml, txt 폴더가 필요. 아래는 각 폴더의 역할
  * bmfc: 자동으로 생성될 비트맵 폰트의 설정이 들어가 있음.
    * 확장자 .bmfc는 일반 폰트, ._bmfc는 월드맵용 폰트.
  * yml: 번역 원문들을 넣을 폴더
  * txt: 일부 txt 형식의 번역 원문이 들어갈 폴더
* 기타 설정 파일
  * default_source.txt: 텍스트 중에 없더라도 폰트 생성에 반드시 포함할 글자들

동작
===
1. original/yml 폴더에 있는 텍스트를 바탕으로 이스케이프된 텍스트를 생성하여 result/yml 폴더에 넣는다.
2. original/yml에 존재했던 글자들과 default_source.txt의 글자를 더해 ingame_source.txt, worldmap_source.txt를 생성한다
  * worldmap_source.txt 에는 original/yml에 존재하는 모든 글자를 포함하는 것이 아니라, 다음과 같은 파일에 있는 글자만이 포함됨
    * countries_l_english
    * prov_names_l_english
    * area_regions_l_english
    * cultures_phase4_l_english
    * prov_names_adj_l_english
    * regions_phase4_l_english
    * tags_phase4_l_english

관련 프로젝트
=======
* EU4SpecialEscape (https://github.com/matanki-saito/EU4SpecialEscape)
* EU4fontcreate (https://github.com/matanki-saito/EU4fontcreate)

저작권
===
* EU4Tools.py는 MIT 라이센스. bmfont64.exe는 bmfont의 소스 라이센스에 준거.

------

必要な環境
=====
* Python 3.x (https://www.python.org/downloads/ でダウンロードできる)

使い方
===

* original フォルダの下に bmfc, yml, txt フォルダが必要。下はそれぞれの役目
  * bmfc: ビットマップフォントの設定を置く
    * .bmfcは一般のフォントで、._bmfcはワールドマップに使うフォント
  * yml: 翻訳の結果を置くフォルダ
  * txt: 一部txtタイプの翻訳原文を置くフォルダ
* 他の設定ファイル
  * default_source.txt: ymlの中にいなくても、フォントの作りに必ず含める文字たち

動き
===

1. original/ymlフォルダに有るテキストを元でエスケープされたテキストを作って、result/ymlフォルダに置く
2. original/ymlにあった文字にdefault_source.txtの文字を加えてingame_source.txt, worldmap_source.txtを作る
  * worldmap_source.txtにはoriginal_ymlにある全ての文字を持つのではなく、以下のファイルにある文字だけを含める
    * countries_l_english
    * prov_names_l_english
    * area_regions_l_english
    * cultures_phase4_l_english
    * prov_names_adj_l_english
    * regions_phase4_l_english
    * tags_phase4_l_english

関連プロジェクト
=======
* EU4SpecialEscape (https://github.com/matanki-saito/EU4SpecialEscape)
* EU4fontcreate (https://github.com/matanki-saito/EU4fontcreate)

ライセンス
=====
* EU4Tools.pyはMITライセンス。bmfont64.exeはbmfontのソースライセンスに準拠