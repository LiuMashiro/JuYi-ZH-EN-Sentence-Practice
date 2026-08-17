# Changelog
All notable changes to this project will be documented in this file.

## [1.0.2]
### Added
- 查词源标记、版本号和WiKi词典词条链接

## [1.0.1]
### Added
- 逐句保存，若需要保存错误版初稿，不需要一直保存错误直到全文翻译完毕再整篇保存，即可逐句保存、即时校对修正
- 当中文查词结果为英文单词时，通过Free Dictionary API为它补充词性
- 为中文查词结果添加Free Dictionary API进一步查询跳转入口
- 缺词标记，在此处应有一词而缺词的位置添加标记
- 英文查词和英译中
- 新增"取消编辑"按钮，还原进入编辑前的原文并返回练习视图（实际上不修改文本点击确认效果相同，但可能引起用户对自己已写数据是否受损的担忧）

### Changed
- 标红不再固定显示在文本框下，而是选中文本后浮动按钮
- Free Dictionary API接口失败时先重试，不行则显示具体接口名与错误码
- 保存机制改为初稿、二稿、终稿最多各一篇

### Fixed
- ESC弹窗层级错误
- 有道无法使用，移除
