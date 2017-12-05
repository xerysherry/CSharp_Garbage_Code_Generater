C# Garbage Code Generater
-------------------------
	-h: Help
	-o: Output Dir, Default="garbate"
	-c: Generate Class Count, Default=400
	-mc: Method Count, Default=30
	-pc: Property Count, Default=30
	-ac: Attribute Count, Default=30
	-verbose: Print Every Generate Class Name
	-q: QuietMode, Print Nothing

ex. lua garbage_code_generater.lua -o output -c 100  
ex. lua garbage_code_generater.lua

C#垃圾代码生成器
--------------
	-h: 帮助
	-o: 输出路径, 默认值="garbate"
	-c: 生成类数量, 默认值=400
	-mc: 类方法数量, 默认值=30
	-pc: 类变量数量, 默认值=30
	-ac: 类属性数量, 默认值=30
	-verbose: 输出每一个类文件名
	-q: 安静模式, 不输出任何东西

例子. lua garbage_code_generater.lua -o output -c 100  
例子. lua garbage_code_generater.lua  

该工具用于生成大量垃圾代码。鄙人的一个Unity项目因为要向Apple提交马甲包，最终代码有不能过于相似，所以在正常代码里混入垃圾代码。  
用法为：用工具生成垃圾代码后，把输出路径直接复制到Unity项目路径中，然后导出Xcode工程
 