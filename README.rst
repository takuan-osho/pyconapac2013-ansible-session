このリポジトリは何か？
======================

このリポジトリは、`PyCon APAC 2013 in Japan`_ のセッションの一つである「入門Ansible_」の説明の補足として用意されたものです。

.. _PyCon APAC 2013: http://apac-2013.pycon.jp/ja/
.. _PyCon APAC 2013 in Japan: http://apac-2013.pycon.jp/ja/
.. _入門Ansible: http://apac-2013.pycon.jp/ja/program/sessions.html#session-15-1110-rooma0765-ja2-ja

このリポジトリの使い方
======================

「入門Ansible_」の説明の補足となるように作ってあるので、「入門Ansible_」で説明したことの復習に使えます。

具体的な利用の仕方は、次に書く注意事項以降に書いてあります。


注意事項
--------

実際にこのリポジトリを利用してAnsibleの学習を行う際には以下の点に注意してください。

- 最低でも10GBの空き容量があるPCで学習してください。
   - このリポジトリではVagrantとVirtualBoxを利用します。その際Ubuntuの仮想マシンを最低1つ、最高3つ使いますが、仮想マシン1つに付き3GB弱の空き容量を必要とするので、十分な空き容量を用意してください。
- 複数人で同じネットワークを共用している場合、ネットワークの帯域が細いと問題が起きる可能性があります。
   - デフォルトのVagrantfileは'precise64'という名前でUbuntu 12.04 LTSのbox(300〜400MB)をVagrant公式のサイトからダウンロードするようになっているため、共用しているネットワークが貧弱だと仮想マシンを立ち上げるところから失敗するかも知れません。

動作環境
--------

動作確認しているのは以下の環境だけです。

:OS:
   OS X Mountain Lion 10.8.4
:Python:
   2.7.2
:VirtualBox:
   4.2.18 r88780
:Vagrant:
   1.3.0
:Ansible:
   1.2.3

Unix/Linux環境ならほぼ問題なく動くと思います。

Windows環境で試したことは全くないので分かりませんが、`Cygwin上でAnsibleが動いた <http://blog.s-uni.net/2013/08/27/ansible-running-on-cygwin/>`_ という事例があるそうなので、工夫すれば動くかも知れません。
