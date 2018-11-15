<!-- default file list -->
*Files to look at*:

* [MainWindow.xaml](./CS/Wpf_MapControl_ListSourceDataAdapter/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/Wpf_MapControl_ListSourceDataAdapter/MainWindow.xaml))
<!-- default file list end -->
# How to bind a Map control to a datasource


<p>This example illustrates how to bind a map control to data, which is stored in an external XML file. The XML data source contains information about wrecked ships including ship coordinates. </p><p>In this example the map control automatically generates ship images based on data from a datasource, along with a description for each image on a tooltip. </p><br />



<h3>Description</h3>

<p>&nbsp;To provide data from a list source.<br />1. Create a <strong>ListSourceDataAdapter</strong> object and assign it to the <strong>VectorLayer.Data</strong> property.<br />2. Specify the <strong>DataSource</strong> property of the object.<br />3. Specify mappings to data source fields to assign these field values to adapter generated map items. For this, configure the <strong>ListSourceDataAdapter.Mappings</strong> property.<br />4. Specify the settings of adapter generated map items. For this, customize the <strong>ItemSettings</strong> property of the object.</p>

<br/>


