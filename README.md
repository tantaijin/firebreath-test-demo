# firebreath-test-demo
firebreath里面的测试demo,仅仅用做dll和html备份。

如果测试非IE内核NPAPI的话 配置下注册表
比如
HKEY_LOCAL_MACHINE\SOFTWARE\WOW6432Node\MozillaPlugins\@haitaichina.com/Assistant

Path D:\code\github\firebreath\build\bin\Assistant\Release\npAssistant.dll

测试IE内核的话 regsvr32 D:\code\github\firebreath\build\bin\Assistant\Release\npAssistant.dll
