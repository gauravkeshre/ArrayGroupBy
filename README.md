
**Usage**

    let array = [[“company” = “apple”, “empID” : “E10”],
    [“company” = “apple”, “empID” : “E10”],
    [“company” = “apple”, “empID” : “E12”],
    [“company” = “apple”, “empID” : “E13”],
    [“company” = “apple”, “empID” : “E14”],
    [“company” = “microsoft”, “empID” : “E106”],
    [“company” = “microsoft”, “empID” : “E103”],
    [“company” = “google”, “empID” : “E17”],
    [“company” = “google”, “empID” : “E19”],
    [“company” = “google”, “empID” : “E122”]]

> let groupedByCompany = array.groupBy(“company”)

    /*
    Returns:
    [“apple”: [“E10”, “E12”, “E13”, “E14”],
    “microsoft”: [“E106”, “E103],
    “google”: [“E17”, “E19”, “E122”]]
    */



> Written with [StackEdit](https://stackedit.io/).

