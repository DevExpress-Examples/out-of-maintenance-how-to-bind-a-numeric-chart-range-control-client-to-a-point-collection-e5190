<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128568769/22.2.2%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/E5190)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
<!-- default file list -->
*Files to look at*:

* [MainWindow.xaml](./CS/BindNumericChartClientToPointCollection/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/BindNumericChartClientToPointCollection/MainWindow.xaml))
<!-- default file list end -->
# How to bind a numeric chart range control client to a point collection


<p>This example demonstrates how to bind a numeric chart range control client to a <strong>System.Windows.Media.PointCollection</strong> containing <strong>System.Windows.Point</strong> objects.</p><p>For this, declare a point collection as a static resource, bind it to the <a href="https://help.devexpress.com/#WPF/DevExpressXpfChartsRangeControlClientChartRangeControlClient_ItemsSourcetopic"><u>ChartRangeControlClient.ItemsSource</u></a> property and set the <a href="https://help.devexpress.com/#WPF/DevExpressXpfChartsRangeControlClientChartRangeControlClient_ArgumentDataMembertopic"><u>ChartRangeControlClient.ArgumentDataMember</u></a> property to "<strong>X"</strong> and the <a href="https://help.devexpress.com/#WPF/DevExpressXpfChartsRangeControlClientChartRangeControlClient_ValueDataMembertopic"><u>ChartRangeControlClient.ValueDataMember</u></a> property to "<strong>Y</strong>".</p><p>Note that the numeric chart client sorts data from the point collection by arguments in the ascending order (if the <strong>ChartRangeControlClient.ArgumentDataMember</strong> property is specified). If you wish to see data in the order in which points have been added to the collection, do not use the <strong>ChartRangeControlClient.ArgumentDataMember</strong> property. </p><p>See also:</p><p>- <a href="https://www.devexpress.com/Support/Center/CodeCentral/ViewExample.aspx?exampleId=E5110"><u>How to bind a numeric chart range control client to an array of integers</u></a>;<br />
- <a href="https://www.devexpress.com/Support/Center/CodeCentral/ViewExample.aspx?exampleId=E5193"><u>How to bind a numeric chart range control client to a list of custom objects</u></a>.</p>

<br/>


