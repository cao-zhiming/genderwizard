# GenderWizard!

要知道，在当今世界，有时候性别这种简单的问题都会难以得出答案。~~因为你总不能去随随便便扒别人衣服或者裤子吧。~~
而，由于互联网的普遍应用，每日只能看见互相的文字的朋友愈来愈多。TA到底是男、是女、还是……？

[做这方面的程序](https://github.com/topics/gender-recognition)很多，许多使用[Python](https://python.org)。它们运用AI技术，识别人的面部或者声音。

难道真的需要这么复杂吗？

事实上，我们不仅可以从一个人的性征等方面得出其性别，其它方面也会表现出其真实性别。AI固然能更好地理解人类，但是~~我不会写AI和机器学习代码~~其它代码也可以判别。
本程序的代码既然没有使用AI，因此准确率应该会大大下降。预估大约为**70%-80%**。因此仅作参考/娱乐使用。

## 如何实现的

你知道，如果你看到这样的一个名字，```杨国森```（虚构姓名，如确有其人，非有意冒犯，请谅解），你一定不会认为是个女性吧？
没错，从姓名上，我们就能十拿九稳了。可问题是……

**迟子建**（虽知确有其人，但非有意冒犯）

这个名字怎么听、怎么看都像男性的，连她自己都这么认为。但是，她是[一位*女*作家](https://baike.baidu.com/item/%E8%BF%9F%E5%AD%90%E5%BB%BA/4835084)。

于是，我们就需要应用到－－心理学。尽管可能许多人的生理性别和心理性别不完全一致，但这毕竟也是一种方法。

## 亮点&特征
<details><summary>最主要特征</summary>
本站非fork、非翻译、非部署已有程序、非搬运。是我的第一个自主研发算法与脚本的程序。
如有怀疑，欢迎进行代码比对，或者审阅每次commit。</details>

主程序特征：
- 在姓名中查找关键词判断性别
- [ ] 开发中：从心理上判断性别
- [ ] 开发中：寻找与你性别相同、性格类似的Harry Potter角色
- [ ] 开发中：PWA可离线访问

速度等特征：
- 小图直接存储在/static/文件夹下，不必进行额外DNS请求
- 大图使用jsDelivr加速，并使用懒加载提高整体速度

显示特征：
- 任何设备皆可流畅访问
- Webslides类PPT显示
- [ ] 开发中：添加```canvas-ribbon.js```等样式

