## ライセンス
[LGPLv3 or later](https://spdx.org/licenses/LGPL-3.0-or-later.html) with [Independent Module Linking exception](https://spdx.org/licenses/Independent-modules-exception.html)
(SPDX-License-Identifier: LGPL-3.0-or-later WITH Independent-modules-exception)

|対象|ライセンス|ユーザーへの提供|再結合の保証・​OBJ公開|リバース​エンジニアリング|インストール​情報の提供|著作権表示|ライセンス表記|
|-|-|-|-|-|-|-|-|
|このライブラリ|LGPLv3 or later with <br>Independent Module Linking exception|必要|-|-|-|必要|必要|
|あなたのソースコード|独自の条件を設定可能 <br>(LGPLの伝播なし)|不要|-|-|-|-|-|
|実行可能ファイル|独自の条件を設定可能 <br>(LGPLの伝播なし)|不要|不要|制限可能|不要|-|-|

Independent Module Linking exception により、商用・非公開のプログラムにLGPLを伝播させることなく、このライブラリを組み込んで配布することが可能です。<br>
あなたのプログラムにこのライブラリを静的または動的にリンクしても、あなたのプログラムのソースコードや、生じた実行可能ファイルをLGPLで公開する必要はありません。<br>
リバースエンジニアリングの制限や、インストール情報を提供しないことも可能です。<br>
また、動的リンクにおいて再結合を保証する必要はなく、ライブラリの差し替えの保証やオブジェクトファイルの公開は不要です。

ただし、著作権表示やライセンス表記の義務は無効化されておらず、配布時にこのライブラリのソースコードを同梱するか、リポジトリへのURLなどの入手方法を提供する必要があります。<br>
このライブラリ自体を改変した場合は、その変更をLGPLで公開する必要もあります。

詳細は[LICENSE](LICENSE)を参照してください。
