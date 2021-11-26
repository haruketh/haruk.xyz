+++
author = "Paru"
title = "ENSトークンローンチ"
date = 2021-11-03T20:10:12+09:00
description = ""
Categories = [ "crypto"]
+++

ENSがDAOになるよ！ その配布条件と使われ方をさらっと！

<!--more-->

## ENSトークン

ENS DAOのコミュニティ投票には $ENS トークンが使われるよ。

ENSドメイン（.eth）を登録している保有者には、総発行数の25％のエアドロップされる。（13.7万アカウント）

- トークン配布期間　2021.11.8〜2022.5.4
- 対象は .eth のドメイン取得者で、過去の保有者も含む
- ENS name ごとではなく、アカウントごとに算出。
- 割当数量の計算は、過去の保有日数＋有効期限までの残日数
- プライマリENS（リバースレコード）を登録している人はその2倍もらえる

これらの計算は、2021.10.30時点のスナップショットを元にするから、これから急いでENS登録してもトークンはもらえないよ。

あと、second-levelドメインを対象にしているから、サブドメイン（3rd-level）は対象外ということになりそう。


## ENS憲法と投票

ENSの投票は2種類。ENS憲法改正と、それ以外のプロポーザルに分かれていて、まるで日本国憲法と法律みたいに分けてるんだね。

- 憲法改正は、5%のQuoram、67%の賛成が必要
- プロポーザルは、最低10万トークン、1％のQuoram、過半数の賛成が必要

普通の人はこんなにトークンを持っていないし、プロポーザルや投票をするほど知識もないよね。

だから、信頼できる人に委任する「デリゲート」しよう！ Gitcoinと同じような感じだね。


## （参考）ENS憲法

※ ENS憲法の案の和訳です。原文は[こちら](https://discuss.ens.domains/t/proposed-ens-constitution/814)。


ENS憲法は、ENSコミュニティがどのようにENSを統治すべきかについてのルールとガイドラインです。

#### 1. 名前の所有権は絶対的な権利である

ENSガバナンスは、ENSユーザが所有する名前を保持する権利を侵害したり、名前の所有者が名前を更新、譲渡、またはその他の方法で使用する能力を不当に差別するような変更を制定しない。

例
- 許可されること：　ENSガバナンスは、この憲法に記される目標を追求する限りにおいて、例えば期間のような透明性のある基準について、すべての名前の登録または更新費用に影響を与える変更を制定することができる。
- 許可されないこと：　ENSガバナンスは、特定のグループに不当に利益を与えたりペナルティを与えたりすることになるような、既存のENSネームのリストの更新費用を増加または減少させる変更を制定してはならない。

#### 2. インセンティブ・メカニズムとしての登録料の存在

登録料の主な目的は、ENSの名前の登録、更新、失効を規制し、投機的な登録によってネームスペースが圧迫されるのを防ぐためのインセンティブメカニズムとして存在します。二次的な目標として、ENSの継続的な開発と改善に資金を提供するためにDAOに十分な収益を提供します。ENSのガバナンスは、これらの目的以外のいかなる料金も制定しません。

例
- 許可されること：　ENSガバナンスは、登録料が低く設定されていることで過度の投機的登録が誘発される場合、あるいは、現在の価格が継続的なENS運営の合理的なレベルの資金を調達するのに不十分である場合、名前登録の価格を引き上げることができる。
- 許可されないこと：　ENSガバナンスは、ENS内のDNSドメインを主張するための手数料を課す変更を制定してはならない。なぜなら、そのような手数料は純粋に収入を得るための手段であり、インセンティブメカニズムではないからである。

#### 3. インカムファンド ENSとその他の公共財

ENSの財務で発生したいかなる収入も、まずENSの長期的な存続を確保し、ENSシステムの継続的な開発と改善のために使用されます。この目標を達成するために合理的に必要とされない資金は、ENSのガバナンスが適切と判断した場合、Web3内の他の公共財の資金として使用することができます。

ENSガバナンスは、割り当てられた資金を使用する際には、本憲法に概説されているのと同じ原則を守ることを約束しないチームまたは個人に資金を割り当てません。

例
- 許可されること：　ENSガバナンスは、ENSの長期的な存続に影響を与えない限り、ENSやイーサリアムとは無関係の公益のために助成金を提供することができます。
- 許可されないこと：　ENSガバナンスは、ENSの目標に抵触するプロジェクトを支援するために資金を使用してはならない。

#### 4. ENSのグローバルネームスペースへの統合

最も広く使用可能なネーミングシステムの構築を促進するため、ENSはENSの分散性を犠牲にすることなく、可能な限りレガシーDNSネーミングシステムと統合することを目指しています。ENSのガバナンスは、ENSの能力を損なうような変更を行いません。

例
- 許可されること：　ENSガバナンスは、要求に応じてDNSシステムにおいてトップレベルドメインの制御権をその所有者に与えるべきである。
- 許可されないこと：　ENSのガバナンスは、DNS機関によってENSに付与されたものでない限り、新しいトップレベルドメインを作成してはならない。

#### 5. 多数決による本憲法の変更

本憲法の変更は、3分の2以上の賛成と全参加者のトークンの5％以上の賛成によってのみ行うことができます。
