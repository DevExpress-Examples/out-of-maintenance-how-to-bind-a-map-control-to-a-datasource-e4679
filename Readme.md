<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128571175/21.1.5%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/E4679)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
<!-- default file list -->
*Files to look at*:

* [MainWindow.xaml](./CS/Wpf_MapControl_ListSourceDataAdapter/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/Wpf_MapControl_ListSourceDataAdapter/MainWindow.xaml))
<!-- default file list end -->
# How to bind a Map control to a datasource


<p>This example illustrates how to bind a map control to data, which is stored in an external XML file. The XML data source contains information about wrecked ships including ship coordinates. </p><p>In this example the map control automatically generates ship images based on data from a datasource, along with a description for each image on a tooltip. </p><br />



<h3>Description</h3>

<p>&nbsp;To provide data from a list source.<br />1. Create a <strong>ListSourceDataAdapter</strong> object and assign it to the <strong>VectorLayer.Data</strong> property.<br />2. Specify the <strong>DataSource</strong> property of the object.<br />3. Specify mappings to data source fields to assign these field values to adapter generated map items. For this, configure the <strong>ListSourceDataAdapter.Mappings</strong> property.<br />4. Specify the settings of adapter generated map items. For this, customize the <strong>ItemSettings</strong> property of the object.</p>

<br/>


