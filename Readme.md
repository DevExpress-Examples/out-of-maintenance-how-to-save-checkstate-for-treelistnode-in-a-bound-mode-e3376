<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128638077/11.1.4%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/E3376)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
<!-- default file list -->
*Files to look at*:

* [frmMain.cs](./CS/SaveCheckStateTreeListNode/frmMain.cs) (VB: [frmMain.vb](./VB/SaveCheckStateTreeListNode/frmMain.vb))
* [Program.cs](./CS/SaveCheckStateTreeListNode/Program.cs) (VB: [Program.vb](./VB/SaveCheckStateTreeListNode/Program.vb))
* [SaveCheckHelper.cs](./CS/SaveCheckStateTreeListNode/SaveCheckHelper.cs) (VB: [SaveCheckHelper.vb](./VB/SaveCheckStateTreeListNode/SaveCheckHelper.vb))
<!-- default file list end -->
# How to save CheckState for TreeListNode in a bound mode


<p>This example demonstrates how to save TreeListNode.CheckState in a bound mode. It is necessary to create an instance of the SaveCheckHelper class and pass TreeList and a field, containing CheckState, to a datasource bound to TreeList.<br><br>In recent versions of our components, use the <a href="https://documentation.devexpress.com/WindowsForms/DevExpress.XtraTreeList.TreeList.CheckBoxFieldName.property">TreeList.CheckBoxFieldName</a> property to bind built-in checkboxes to a field in the data source.</p>

<br/>


