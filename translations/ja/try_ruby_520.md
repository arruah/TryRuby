---
lang:   JA
title:  キリンは要約（その7）を盗みません
answer: 
class:  stretcher chapmark
ok:     
error:  
load:   prev;blurb2=Blurb.new :confused, "I can not believe Mt. Hood was stolen!"
---

やっと、ここまできました。すべてを1つにしました。まだアプリを現実に近づけるつもりですが、その前にやったことを振り返りましょう。いいですか？

### クラス
Rubyのすべてはオブジェクトです。クラスはオブジェクトを説明するもので、特定のオブジェクトがどう動くかを説明します。
例えば、いくつか新しいBlurb<sup>TM</sup>オブジェクトを作成したとすると、それらのオブジェクトはクラスによって説明されたということです。
つまり、それらはBlubオブジェクトです。
クラスを（ある種）現実世界のオブジェクトのモデルとして使うことができます。

### アクセサ
アクセサは、オブジェクトの__外__から使うことのできる、オブジェクトに付けられた変数です。
（blurb2.time = Time.now）

### オブジェクトの変数
オブジェクト変数はアクセサで触れる変数と同じです。けれど、オブジェクトの__内側__にあります。
（@time = Time.now）
