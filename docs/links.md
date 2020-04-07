# 計算化学関係のツール・リンク

## 計算プログラム
- [Quantum ESPRESSO](https://www.quantum-espresso.org/): 平面波基底を用いた第一原理計算プログラム
- [Gaussian](https://gaussian.com/): Gauss関数の局在基底を用いた量子化学計算プログラム
- [ORCA](https://orcaforum.kofo.mpg.de/app.php/portal): 局在基底を用いた量子化学計算プログラム

### Quantum ESPRESSO関係
- [Input Description](https://www.quantum-espresso.org/resources/users-manual/input-data-description): QE公式のマニュアル。頻繁に使うものは、[pw.x](https://www.quantum-espresso.org/Doc/INPUT_PW.html), [ph.x](https://www.quantum-espresso.org/Doc/INPUT_PH.html), [dynmax.x](https://www.quantum-espresso.org/Doc/INPUT_DYNMAT.html), [pp.x](https://www.quantum-espresso.org/Doc/INPUT_PP.html), [projwfc.x](https://www.quantum-espresso.org/Doc/INPUT_PROJWFC.html)
- [擬ポテンシャル](https://www.quantum-espresso.org/pseudopotentials)
- [Quantum ESPRESSO tutorial](http://www.cmpt.phys.tohoku.ac.jp/~koretsune/SATL_qe_tutorial/): QEでのSCF計算・フォノン他様々な計算の実行方法の解説。
- [Quantum ESPRESSO入力ファイル作成手順](https://qiita.com/xa_member/items/727c1a62930611babaf7): クロスアビリティ社の方による解説記事。特に[擬ポテンシャルの選択方法](https://qiita.com/xa_member/items/006d9dd44c662a17903d)など参考になります。

### Gaussian関係
- [Gaussian 16 Users Reference](https://gaussian.com/man/): リファレンス(公式)
- [List of Gaussian Keywords](https://gaussian.com/keywords/) : キーワードリスト(公式)

## 計算手法など
- [Basis Set Exchange](https://www.basissetexchange.org/): 原子局在基底関数のデータベース。そのままGaussianの入力なども作成可能。

## 可視化ツール
- [VESTA](https://jp-minerals.org/vesta/jp/): 結晶構造の可視化は大体これを使っています。
- [XCrySDen](http://www.xcrysden.org/): 描画の美しさはVESTAの方が上ですが、QEのinput/outputを直接読めるので便利。構造最適化(relax)の過程も描画可能です。
- [AFLOW](http://materials.duke.edu/awrapper.html): 1st BZ の作成に主に利用しています。
- [Materials Cloud Tools](https://www.materialscloud.org/work/tools/options): 主に[Interactive phonon visualizer](https://www.materialscloud.org/work/tools/interactivephonon)を利用しています。

## 結晶構造・データベース
- [CCDC](https://www.ccdc.cam.ac.uk/)
- [COD](http://www.crystallography.net/cod/) (Crystallography Open Database) : CCDCよりも動作がかなり軽快。
- [Springer Materials](https://materials.springer.com/)
- [Materials Project](https://materialsproject.org/) : 構造・物性の計算結果のデータベース
- [結晶構造ギャラリー](https://staff.aist.go.jp/nomura-k/japanese/itscgallary.htm): 産総研が公開している結晶構造ライブラリ。cifが入手可能。

- [CCCBDB](https://cccbdb.nist.gov/Intro.asp): 量子化学計算と実験値（スペクトル）を対応させるためのデータベース。[振動のスケールファクター](https://cccbdb.nist.gov/vibscalejust.asp)などはたまに見ます。

