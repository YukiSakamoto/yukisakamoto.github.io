
# Tiny Hartree-Fock Program

分子軌道計算に用いるHartree Fock法のプログラムを、C++で実装してみたものです。

### Repository:

Githubに置いています。 [Here](https://github.com/YukiSakamoto/HartreeFock_solver)

### Compilation and Run:

README.mdをみてください。

### Hartree Fock 法について

Hartree Fock法は、量子化学計算など多電子系のシュレーディンガー方程式を解くときに用いられる計算手法です。精度の面から、近年ではこの手法が単体で用いられることは少なくなりました。しかし、ここで用いられる１電子ハミルトニアンおよび１電子波動関数の形は、現在広く使われている密度汎関数法(DFT)の定式化であるKohn-Sham方程式も似たような形をしており、その意味では分子軌道法の基本となる手法と言えます。  
近年では様々な計算パッケージが存在しているため、スクラッチで書く機会は滅多にないものの、勉強を兼ねて自作してみたものです。  

また、これについて、Qiitaの方にも数回に分けてpythonで書いたものを説明とともにアップしました。

[量子化学計算コードを自作してみた記録　その１](https://qiita.com/YukiSakamoto@github/items/5694fdb099cb96b050e8)  
[量子化学計算コードを自作してみた記録　その２](https://qiita.com/YukiSakamoto@github/items/1ce600a233e23ee67f5f)  
[量子化学計算コードを自作してみた記録　その３ 構造最適化の実装](https://qiita.com/YukiSakamoto@github/items/a771780fd57fa4bfbebb)
