# XelScript 使用说明
XelScript(可发音为CellScript)，用于快捷处理一组Excel单元格。
通常情况下，Excel中要对多行进行处理，我们就必须创建公式，并拖动填充公式到所有行，当需处理的行数较大时，操作起来就比较麻烦，修改起来也比较麻烦。
本工具就是无需在表格内创建公式，而是在工具内创建计算代码，设定好来源单元格和目标单元格后，即可批量进行计算，将结果置于目标单元格中。
计算代码基于JavaScript和ActivexObject（通过ActiveX对象控制Excel或WPS），和VBA操作EXCEL是完全类似的，只是从Visual Basic语言换成了JavaScript。

## 特点：
1. 代码储存在表格文件外，而VBA代码是绑定文件的，如果要在别的文件使用，就必须复制到别的文件中去。
2. 可以使用JavaScript的所有功能，包括正则表达式。
3. 可以使用ActiveX对象，通过ActiveX对象可以操作Excel或WPS。
4. 可以使用Excel的所有功能，包括公式、函数等等。
5. 可以使用Excel的所有对象，包括Workbook、Worksheet、Range等等。


