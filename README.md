# WPF GridControl clipboard operations

This repository contains the samples which demonstrates various clipboard operation customization in [WPF GridControl](https://help.syncfusion.com/wpf/gridcontrol/overview).

`GridControl` provides support for clipboard operations. You can cut or copy and paste data to or from grid to other external sources, like notepad, excel, etc.

You can change the copy paste operations in `GridControl` by setting the flaggable enum [CopyPasteOption](https://help.syncfusion.com/cr/wpf/Syncfusion.Windows.Controls.Grid.GridModelOptions.html#Syncfusion_Windows_Controls_Grid_GridModelOptions_CopyPasteOption) property. You can enable copy and paste by setting `CopyPasteOption` property to [CopyText](https://help.syncfusion.com/cr/wpf/Syncfusion.Windows.Controls.Grid.CopyPaste.html) and [PasteText](https://help.syncfusion.com/cr/wpf/Syncfusion.Windows.Controls.Grid.CopyPaste.html).

``` csharp
gridControl.Model.Options.ActivateCurrentCellBehavior = GridCellActivateAction.DblClickOnCell;
grid.Model.Options.CopyPasteOption = CopyPaste.CopyText | CopyPaste.PasteText;
```

![WPF GridControl clipboard operations](https://www.syncfusion.com/uploads/user/kb/wpf/wpf-51280/wpf-51280_img1.png)