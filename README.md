# mhgu
怪物猎人GU的资料库

## 说明
在贴吧上看到**剑似轻狂**的贴子[链接](https://tieba.baidu.com/p/5610999048)，感谢他做的APP。可惜太监了。

看得日文很不爽，然后就自己做。因为手头上有项目的原因，只能在闲时断断续续的搞。期间解析HTML很蛋疼，写代码时想法又太多，花费了不少时间

现在休假中，对需求重新整理，然后按需求表一步步来做。

其中最重要的翻译，实在是太烦琐了，只能寻找有志之士帮忙了处理了。

已经提取文本，放在[在线文本](https://docs.google.com/spreadsheets/d/1hw0ZgkxVsN_2pb9WyNlavaQhKN5yJU51tX52fC4ep5Q/edit?usp=sharing)上，所有人都可以编辑

当某页文本都翻译完了，我会进行处理，然后发布新版本

### 项目结构
 * app 主项目  基本结构已经确立，后期主要更新数据库及assets里的html

 * convert Java库，用与HTML的数据提取。主要使用Junit工作

 * dbwrapper 数据库制作APP，根据提取的数据制作数据库，帮助主项目分离数据库初始化的过程。主项目初始化时只需要Copy最新的数据库就可直接使用

 * db 数据库基础库，定义数据库相关的类，提供给app,dbwrapper使用

 * temp 用与存放提取的数据，以Json格式保存
    * summary 提取的各汇总数据
    * translation 待翻译数据
    * translated 已经翻译好的数据

### 需求列表

* 搜索及导航 （已完成）

    导航后期根据需求不定时更新，比如各种数据的汇总，网上优秀的文章链接等。

* 翻译（待协作，不定时更新）
    * 武器
        *  太刀  进度：已完成
        *  片手  进度：待翻译
        *  双刀  进度：待翻译
        *  大锤  进度：待翻译
        *  盾斧  进度：待翻译
        *  斩斧  进度：待翻译
        *  长枪  进度：待翻译
        *  铳枪  进度：待翻译
        *  笛  进度：待翻译
        *  笛旋律  进度：待翻译
        *  弓  进度：待翻译
        *  轻弩  进度：待翻译
        *  重弩  进度：待翻译
     * 猎猫
       * 猫武器 进度：待翻译
       * 猫防具 进度：待翻译
       * 猫技能  进度：待翻译
     * 猫饭
       * 食材 进度：待翻译
       * 料理及说明 进度：待翻译
     * 其它
       * 通用模板的文字 进度：待提取
       * 个别未翻译的文字 进度：待翻译
       * 繁体中文 进度：待翻译

* 界面优化 （待美工妹子中）

* 其它需求 （待定）

### 版本发布
[Fir](https://fir.im/v4hr)

有问题或建议请发[Email](jestar719@gmail.com)
