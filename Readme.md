<!-- default file list -->
*Files to look at*:

* [CustomRibbonItem.cs](./CS/CustomRibbonItem.cs) (VB: [CustomRibbonItem.vb](./VB/CustomRibbonItem.vb))
* [MainPage.xaml](./CS/MainPage.xaml) (VB: [MainPage.xaml](./VB/MainPage.xaml))
* [MainPage.xaml.cs](./CS/MainPage.xaml.cs) (VB: [MainPage.xaml.vb](./VB/MainPage.xaml.vb))
* [MainViewModel.cs](./CS/MainViewModel.cs) (VB: [MainViewModel.vb](./VB/MainViewModel.vb))
* [RichEditEx.cs](./CS/RichEditEx.cs) (VB: [RichEditEx.vb](./VB/RichEditEx.vb))
* [ThemeFriendlyNameConverter.cs](./CS/ThemeFriendlyNameConverter.cs) (VB: [ThemeFriendlyNameConverter.vb](./VB/ThemeFriendlyNameConverter.vb))
* [generic.xaml](./CS/Themes/generic.xaml) (VB: [generic.xaml](./VB/Themes/generic.xaml))
<!-- default file list end -->
# How to introduce Color Scheme support for a custom control


<p>This example illustrates how to introduce Color Scheme support for a custom control. In this implementation, the <strong>CustomRibbonItem</strong><strong> </strong>control uses colors defined in the <strong>generic.xaml</strong> resource dictionary.<br><br></p>
<p>To associate custom resources with predefined colors from default Color Schemes, use the ColorKey.Link attached property at the target resource level.<br><br>If you wish to do this in an older version, refer to the <a href="https://www.devexpress.com/Support/Center/p/T404948">[Deprecated] How to support default Color Schemes in a custom control</a> example for a solution.</p>

<br/>


