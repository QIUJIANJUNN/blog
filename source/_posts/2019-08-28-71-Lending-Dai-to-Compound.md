---
title: 071 | 用穩定幣 Dai 放貸（年化率15.81%），就在Compound借貸平台躺著賺教學
tags:
  - 所有文章
  - Dai
  - Compound
  - 躺著賺
  - 被動收入
  - 教學
  - 穩定幣
  - DiFi
date: 2019-08-28 09:42:27
---
![](https://firebasestorage.googleapis.com/v0/b/blog-1f60b.appspot.com/o/071-p0.png?alt=media&token=38c86192-aedb-435d-8eeb-1a959a8fd9ed)
本金500萬，每月被動收入6.5萬，X！嚇得我趕緊放Dai。

### 什麼是 Dai?
將抵押品（ETH）存入智能合約，借出一種Token（Dai）。借出的Token（Dai）與美元1比1錨定。
<br>

### Dai安全嗎？
1Dai抵押品最少有1.5倍的資產。
![](https://firebasestorage.googleapis.com/v0/b/blog-1f60b.appspot.com/o/JuLiZi%E2%80%94%E2%80%94zh.gif?alt=media&token=0d94eb23-99a7-415e-88d2-5455b313d65f)
當前1 ETH價格是200，由於必須保持1.5:1，因此抵押1 ETH能獲得133.33 Dai。
歸還時，除了133.33 Dai，以及調控錨定美元的費用，就能拿回1 Eth。
<br>

### 為什麼它能夠穩定在1美元?
當Dai高於1美元時，調控錨定美元的費用會下降。因此抵押ETH借Dai者會增加，使Dai流通量多，進而將價格下降到1美元。
相反
當Dai低於1美元時，調控錨定美元的費用會上升。因此抵押ETH借Dai者還Dai，使Dai流通量減少，將價格抬升到1美元。

關於更詳細的可以參考
>[MakerDAO上手PTT](https://defi-chengdu.github.io/slides-2019-07-28/)
>[MakerDAO官網](https://makerdao.com/en/dai)
<br>

### 除了抵押ETH獲得Dai，還有其他方法嗎？
可以到MakerDAO上面推薦的eth2dai，或是Coinbase pro(0.5%)。
最簡單的應該是使用手機錢包imtoken上的Tokenlon(0.3%)購買。
<br>

### 如果在手機錢包imtoken購買？
[All new Tokenlon now launched on imToken](https://youtu.be/K7pahIzE_mM)
<br>

### 什麼是Compound？
[Compound](https://compound.finance/)是一個去中心化的借貸Dapp。能夠借貸ETH、Dai、Usdc等等token。
目前總供應量為$160,915,033.44。
<br>

### 如何在Imtoken的Compound放Dai
1.點擊下方Market後，點擊DAI Lending
![Compound__000](https://firebasestorage.googleapis.com/v0/b/blog-1f60b.appspot.com/o/Compound__000.png?alt=media&token=6a65d51a-eee6-4f46-b33a-9a211aa4d908)
<br>

2.點擊Dai（Supply APR為放貸年化收益率，Borrow APR為借貸年化貸款率）。
![Compound__001](https://firebasestorage.googleapis.com/v0/b/blog-1f60b.appspot.com/o/Compound__001.png?alt=media&token=02e1aa90-6226-4bd4-a640-9fd28d7c8e1f)
<br>

3.因為是要借出Dai因此，點ENABLE DAI（注意!!這個是指對方智能合約可以控制你錢包內的Dai，因此不要亂使用來路不明的合約）。
![Compound__002](https://firebasestorage.googleapis.com/v0/b/blog-1f60b.appspot.com/o/Compound__002.png?alt=media&token=19f4114c-7550-4b21-a544-d8de132ddc46)
<br>

4.接下來會與Compound的合約做簽章動作。
![Compound__003](https://firebasestorage.googleapis.com/v0/b/blog-1f60b.appspot.com/o/Compound__003.png?alt=media&token=24b3cd9f-e202-4cfa-9666-d6b78b4560b2)
<br>

5.當合約發送打包完成，點擊SUPPLY
![Compound__004](https://firebasestorage.googleapis.com/v0/b/blog-1f60b.appspot.com/o/Compound__004.png?alt=media&token=9df2437b-259e-4774-a0ef-957b1ebdf73c)
<br>

6.輸入要借出的數量，點擊SUPPLY
![Compound__005](https://firebasestorage.googleapis.com/v0/b/blog-1f60b.appspot.com/o/Compound__005.png?alt=media&token=7dc87f87-be62-4da7-b9e4-15e8f5dd484a)
<br>

7.如果首頁是這樣就代表借出去啦。
![Compound__006](https://firebasestorage.googleapis.com/v0/b/blog-1f60b.appspot.com/o/Compound__006.png?alt=media&token=6f914aa8-4ffe-4b51-8887-eb1913bb7756)
<br>

### 查看收益
1.點擊Dai
![Compound__007](https://firebasestorage.googleapis.com/v0/b/blog-1f60b.appspot.com/o/Compound__007.png?alt=media&token=8f1dc323-36cb-4c4f-b1ab-b5ae264a17f3)
<br>

2.Interest Earned 就是你的收益，約每15秒產生一次收益，看的我晚上睡不著覺。
![Compound__008](https://firebasestorage.googleapis.com/v0/b/blog-1f60b.appspot.com/o/Compound__008.png?alt=media&token=6f9c564a-5f32-4368-ad9b-c03bbc001495)
<br>

### Dai的貸款利息怎麼算？
5% + 已借出的Dai / 存入Compound的Dai * 15% = 貸款利息
<br>

### Dai的存款利息怎麼算？
貸款利息 * 已借出的Dai / 存入Compound的Dai * 15% = 存款利息
<br>

### Vitalik聊Dai利率
最近Vitalik發起一個投票，關於為什麼出借Dai給Compound有11.5%利率，而美國10年期國債卻只有1.5%。隨後在評論說了他的觀點，DeFi的“Lending”是錯誤的比喻，有興趣的朋友可以看看。
![](https://firebasestorage.googleapis.com/v0/b/blog-1f60b.appspot.com/o/071-p1.png?alt=media&token=82e5fccf-37b9-41e9-bf4d-c9872e85f0bf)
<br>

***
![](https://firebasestorage.googleapis.com/v0/b/blog-1f60b.appspot.com/o/%E6%95%B2%E9%BB%91%E6%9D%BF.gif?alt=media&token=6c8bcefd-00be-4eed-8a5f-b7943a377dab)

好的，今天禮拜三是定投日，這周是賺還是虧？（微微笑）
### 本期購買數據
![](https://firebasestorage.googleapis.com/v0/b/blog-1f60b.appspot.com/o/%E8%B4%AD%E4%B9%B0%E6%95%B0%E6%8D%AE071.png?alt=media&token=d7283784-17b2-4a37-ba77-d8426dd582d2)

### 目前盈虧狀況為：37.49%
- BTC收益率：73.13%
- ETH收益率：(9.46%)
- EOS收益率：(25.64%)

### 全部購買數據及損益狀況
![](https://firebasestorage.googleapis.com/v0/b/blog-1f60b.appspot.com/o/%E5%85%A8%E9%83%A8%E8%B4%AD%E4%B9%B0%E6%95%B0%E6%8D%AE%E5%8F%8A%E6%8D%9F%E7%9B%8A%E7%8A%B6%E5%86%B5071.png?alt=media&token=c4c7167d-b12e-44ca-9c4f-dbbe2495ef3c)

![](https://firebasestorage.googleapis.com/v0/b/blog-1f60b.appspot.com/o/%E5%85%A8%E9%83%A8%E8%B4%AD%E4%B9%B0%E6%95%B0%E6%8D%AE%E5%8F%8A%E6%8D%9F%E7%9B%8A%E7%8A%B6%E5%86%B50031-060.png?alt=media&token=57f6125d-2f30-4ee2-a09b-50b9d3629184)

![](https://firebasestorage.googleapis.com/v0/b/blog-1f60b.appspot.com/o/%E5%85%A8%E9%83%A8%E8%B4%AD%E4%B9%B0%E6%95%B0%E6%8D%AE%E5%8F%8A%E6%8D%9F%E7%9B%8A%E7%8A%B6%E5%86%B5001-030.png?alt=media&token=ef3327f5-cbca-480b-a2f2-b1df9014f42c)