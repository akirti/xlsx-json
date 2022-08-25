# xlsx-json

This Notebook File can be help for createing the JSON Schema from xls file which follows the patter as per given sample file.

Input Josn 
```
inps = {
        "filePath" : "/Users/anand/Documents/sayansi/workspaces/condaws/xlsx-json/samplefile",
        "fileName" : "kfk.xlsx",
        "columnNames" : ["Source Topic",
            "Schema",
            "Attribute Name",
            "Data Type",
            "Length",
            "Decimal",
            "Source To Target Mapping/Transformation Logic",
            "Topc",
            "Schema",
            "Field",
            "Data Type",
            "Length",
            "Decimal",
            "Comment",
            "CustomType"],
        "columnNameRowIndex" : 0,
        "schemaCols" : [
             "Schema_8",
             "Field",
             "Data_Type_10",
             "Length",
             "Decimal",
             "Comment","CustomType"],
        "sheetNames":["Sheet1","Sheet2"],
        "rename":True,
        "rowno":0, 
        "startColNo":0,
        "endColNo":15,
        "schemaNmsCol":"Schema_8",
        "sheetName":"Sheet1"
    }
    ```