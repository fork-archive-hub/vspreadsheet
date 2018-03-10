# FAQs about spreadsheet

## 产品架构与功能设计

- 工作簿workbook vs 工作表worksheet
    - A workbook in Microsoft Excel 2010 is the entire Excel file (typically identified with a file type of .xls or .xlsx). If you see an Excel file in your My Documents folder, then that file is a workbook.
    - The worksheet in a Microsoft Excel 2010 file is a single spreadsheet consisting of rows and columns. 
- Apache POI功能
    - POIFS (较差混淆技术实现文件系统) : 此组件是所有其他POI元件的基本因素。它被用来明确地读取不同的文件。
    - HSSF (可怕的电子表格格式) : 它被用来读取和写入MS-Excel文件的`xls`格式。
    - XSSF (XML格式) : 它是用于MS-Excel中`XLSX`文件格式。
    - HPSF (可怕的属性设置格式) : 它用来提取MS-Office文件属性设置。
    - HWPF (可怕的字处理器格式) : 它是用来读取和写入MS-Word的`doc`扩展名的文件。
    - XWPF (XML字处理器格式) : 它是用来读取和写入MS-Word的`docx`扩展名的文件。
    - HSLF (可怕的幻灯片版式格式) : 它是用于读取，创建和编辑PowerPoint演示文稿。
    - HDGF (可怕的图表格式) : 它包含类和方法为MS-Visio的二进制文件。
    - HPBF (可怕的出版商格式) : 它被用来读取和写入MS-Publisher文件。

## code

- gwt client包
