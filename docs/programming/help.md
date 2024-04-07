# Help

<html>
<head>
<meta charset="UTF-8">
<title>Build a Configuration and Generate Services: RacePoint Blueprint Programming Guide</title>
<link rel="stylesheet" type="text/css" href="../css/ContextualHelpCSS.css">
</head>
<body>
<h1>Build a Configuration and Generate Services</h1>
 

<h3><b>RacePoint Blueprint&reg;</b><b> Programming Guide</b></h3>
 

<table border="0" cellpadding="5" cellspacing="0"><tbody><tr><td colspan="1" rowspan="1">Release:</td><td colspan="1" rowspan="1">daVinci 10.5.2</td></tr><tr><td colspan="1" rowspan="1">Date:</td><td colspan="1" rowspan="1">July 2015</td></tr></tbody></table>

<p> </p>

<p>Building a complete configuration involves accomplishing the following in RacePoint Blueprint.</p>

<ul><li>Changing, replacing, or renaming the Zone Master</li><li>Changing, replacing, or renaming Zones</li><li>Adding Unique Identifier (UID) codes to Components</li><li>Changing, replacing, or renaming Components</li><li>Adding, deleting, and modifying Zones</li><li>Adding, deleting, moving, or modifying Components</li><li>Configuring modules and assignable I/Os within Components</li><li>Placing Components onto the layout view</li><li>Wiring the Components</li></ul>

<ol><li>Open the RacePoint Blueprint application by clicking the icon on the HDD. If you have not yet entered a license registration key, one will be required to begin. See <b>License Key Registration Deployment Guide</b> for more information on setup.</li><li>The <b>Layout</b> window opens automatically. The <b>Layout</b> window provides a tool bar and areas where user-defined Zones, Components, and wiring connections are displayed. When the <b>Layout</b> window opens, note that the Zone Master (Savant Controller) and the first Zone (Room 1) are automatically selected. The default tool bar consists of the following:</li></ol>

<p><img height="56" src="../pix/doc000001214image001.png" width="800"></img></p>

<p ><b>Tool Palette</b>: Use tools to control what is displayed by the layout view.</p>

<p ><b>Layer Filter</b>: Show and hide the audio, video, signal, digital, and control wiring types on the <b>Layout </b>view.</p>

<p ><b>Save</b>: Save the <b>Layout</b> configuration using this or go to <b>File </b>&gt;<b> Save as</b>.</p>

<p ><b>State</b>: The circle and indicates the state of the system.</p>

<ul ><li><b>Red</b> indicates that no connections have been made.</li><li><b>Yellow</b> indicates the configuration services have been generated, but the workflows have not been generated.</li><li><b>Blue </b>indicates the configuration is valid to use in the Savant Controller, but the iPads are incomplete.</li><li><b>Green </b>indicates the configuration is valid to use in Savant Controllers and iPads.</li></ul>

<p ><b>Generate Services</b>: Generate Services for the configuration. This action must be done once all wires are connected and everything is adjusted in order to complete setting up any Savant System.</p>

<p ><b>Update All UI Screens</b>:<b> </b>Updates the iPads or Savant Controller screens. This is an integral part to completing the setup of any Savant System.</p>

<p ><b>Show Library</b>: View and select components to add to the configuration. It is also possible to look at the profile code for most items in the <b>Component Library.</b></p>

<p ><b>Show Inspector</b>: View and edit user, profile, zone, component, and connector information. The <b>Inspector</b> window will automatically float in front of other windows.</p>

<p ><b>Upload to Master</b>: This option provides a second way to upload the configuration to Master, in addition to <b>File</b> &gt; <b>Upload to Master...</b></p>

<p ><b>View Services</b>: Launch the <b>Services</b> window to view and adjust available services for the configuration.</p>

<p ><b>Review Service Paths</b>: Launch the <b>Service Ordering</b>, <b>Grouping</b>, and <b>Aliasing</b> window.</p>

<p ><b>Review Triggers</b>: Launch the <b>Triggers</b> window.</p>

<p><a id="DocumentListTable" name="DocumentListTable"></a></p>

<h2><b>RacePoint Blueprint Layout window</b></h2>

<p>The screenshot below is of a new RacePoint Blueprint configuration when it is opened for the first time with no changes. The numbered areas in this image are defined in further detail below it.</p>

<p><img height="527" src="../pix/doc000001214image002.png" width="771"></img></p>

<ol><li>
	<p><b>Zone/Component List</b>: Lists Zone master, Zones, and Components to be configured.</p>
	</li><li>
	<p><b>Layout View</b>: This is the physical area in the software where we place our Components to be wired, inspected, and customized further.</p>
	</li><li>
	<p><b>Splitter</b> <b>Bar</b>: Adjusts the size of the Zone and Component list and <b>Layout</b> view.</p>
	</li><li>
	<p><b>Slider</b>: Adjusts the scale of the <b>Layout</b> view. For larger configurations, it may help to zoom out to get a clearer picture of all the Components involved.</p>
	</li><li>
	<p><b>Plus (+)</b>/<b>minus (-)</b> buttons: Adds a new Zone or removes a Zone or Component when one is highlighted.</p>
	</li></ol>

<p> </p>

<h2><b>Renaming a Zone or Component</b></h2>

<p>The installer can change the name of the Zone Master, Zone, or Component in the Zone/Component list. To do this, click the <b>&lt;option&gt;</b> key on the Zone Master (Savant),  Zone, or Component in the list and type in the desired name.</p>

<p> </p>

<h2><b>Adding, Deleting, and Modifying Zones</b></h2>

<ol><li>To add a Zone(s) to the Zone/Component list, highlight Savant (Zone master) and click the plus (+) button. You can also right-click the Savant (Zone Master) and use the contextual menu. The <b>Enter a unique name for the zone</b> window opens.</li></ol>

<p><b>Note</b>: Each Zone name must be unique. RacePoint Blueprint enforces this requirement.</p>

<p> </p>

<ol start="2"><li>Enter the new name and select the Zone type from the <b>Type</b> menu. Click <b>Create</b>.</li></ol>

<p><img alt="" src="../pix/doc000001214image003.png"></img></p>

<p><b>Important</b>: If a Zone contains Components that are used only in that Zone, the Zone is considered a User Zone. This is the default Zone type. Shared resource Zones are known as Global Zones. Components that affect multiple User Zones (HVAC and Lighting Control Components) must be placed in Global Zones.</p>

<ol start="3"><li>To change an existing zone type, for example, from <b>User</b> to <b>Global</b>, highlight the zone in the <b>Zone/Component</b> list and click <b>Show Inspector </b>in the tool bar.</li><li>Click <b>Device</b> and the <b>Edit</b> checkbox.</li><li>Select <b>Global</b> in the <b>Type</b> pull-down menu.</li></ol>

<p><img src="../pix/doc000001214image004.png"></img></p>

<ol start="6"><li class="Normal">To delete zone from the <b>Zone/Component</b> list, highlight the desired zone<b> </b>and click on the minus (<b>-)</b> button.</li><li>If you want to modify a zone or require detailed zone information, click on <b>Show Inspector</b> to open the <b>Inspector </b>window and refer to <b><a href="./000001169.html" target="_blank">Inspector Window: RacePoint Blueprint Programming Guide</a></b> for detailed information.</li></ol>

<div class="Normal"><b>Note</b>: If a zone is deleted, it will also delete any components  added to the zone.</div>

<p><b>Note</b>: Also,<b> </b>click<b> &lt;option&gt; </b>on<b> </b> the zone name to rename the zone.</p>

<p> </p>

<p><b>Defining Zones as Video Only</b></p>

<p>In RacePoint Blueprint specify a <b>Zone</b> to implement services for only the video portion of the service definition.</p>

<ol><li>To enable this feature, select the desired <b>Zone</b> in the <b>Zone/Component</b> list in the a <b>Layout</b> window, .</li><li>Click <b>Show Inspector</b>.</li><li>Ensure the <b>Edit </b>checkbox is checked and click the <b>Device</b> button.</li><li>Select the <b>Ignore Audio Service Paths</b> checkbox. This selection allows you to realize full services (like DVD, cable, etc.) that only use video and does not require audio support in the Zone.</li></ol>

<p><br><img alt="" src="../pix/doc000001214image005.png"></img></p>

<p> </p>

<h5>Configuring Zones with a Preferred Audio Source</h5>

<p>This enhancement allows RacePoint Blueprint to speed up the configuration process by choosing the preferred service paths.</p>

<ol><li>To enable this feature, select the desired <b>Zone </b>in the <b>Zone/Component</b> list in the <b>Layout</b> view, .</li><li>Click  <b>Show Inspector</b>.</li><li>Ensure the <b>Edit </b>checkbox is checked and click the <b>Device</b> button.</li><li>At the <b>Preferred Audio Source:</b> menu, choose <b>PCM</b> (stereo), <b>SPDIF</b> or <b>HDMI</b> <b>preferred audio.</b></li><li>Click <b>Generating Services</b> in the tool bar, RacePoint Blueprint will select service paths and services that use the preferred audio type from the source device and disable paths and services that do not use this audio type.</li></ol>

<p> </p>

<h5>Setting Up Zones to Demonstrate a System or Disabling Control to Certain Zones</h5>

<p>This function allows you to demonstrate a system using an iPad (UI), by disabling control of components in a specific Zone or Zones. This function also allows you to disable control to certain zones.</p>

<p>Follow the steps below to accomplish the above functions:</p>

<ol><li>To enable this feature, select the iPad in the <b>Layout</b> view.</li><li>Click <b>Show Inspector</b>.</li><li>Select <b>Default Profile</b> and in the <b>Properties for:</b> <b>Default Profile</b> area, double-click the <b>Enabled Zones</b> property.</li></ol>

<p><img alt="" src="../pix/doc000001214image006.png"></img></p>

<ol start="4"><li>After the window opens, under the <b>Control</b> column, uncheck the <b>Zones</b> to disable the Components.</li><li class="Normal">Click <b>Done</b>.</li></ol>

<p><img alt="" src="../pix/doc000001214image007.png"></img></p>

<p> </p>

<p><a name="ComponentLibraryPalette"></a></p>

<h2><b>Adding, Deleting, Moving, and Modifying Components</b></h2>

<ol><li>At the select <b>Layout</b> window tool bar, click <b>Show Library</b> to open the <b>Components </b>window to view the Library of available components.</li></ol>

<p><br><img alt="" height="351" src="../pix/doc000001214image008.png" width="526"></img><br> </p>

<p><b>All Components (search field)</b></p>

<p>This field allows the user to search the library for all Components or by Component class. Click  the <b>Clear</b> button to return the menu to <b>All Components</b>.</p>

<p><b>All Manufacturers (search field)</b></p>

<p>This field allows the user to search the <b>Component Library</b> by manufacturer. Click the <b>Clear</b> button to return the menu to<b> All Manufacturers</b>.</p>

<p><b>Control Types (search field)</b></p>

<p>The <b>Control Type</b> menu shows details of what is selected in the menu. For example, it will show either <b>All Control Types</b>, <b># Control Types</b>, or depending on whether all (or none) of the types are checked, more than one type is checked, or a single type is checked, respectively.</p>

<p><b>Search Field</b></p>

<p>The search field only shows components, manufacturers, or models that match the text entered in the search field.</p>

<ul><li>As text is entered into the <b>Search</b> field, the set of Components shown in the list will be changed to match the entered text.</li><li>If there is text in the <b>Search</b> field, a <b>Clear</b> button will appear on the right edge of the field.</li><li>Click the <b>Clear</b> button to empty the <b>Search</b> field text.</li></ul>

<p><b>Component Product Descriptions</b></p>

<p>In the <b>Show Library</b> window, for Savant components only, right-click  the component and the menu will show the available product descriptions for that Component. Choosing the model number will show the product description for this model in the Preview application as shown below.</p>

<div class="Normal">
<p>Select the desired components from the Library and drag each component (one at a time) to the selected zone in the<b> Zone/Component</b> list or the <b>Layout</b> view.</p>
</div>

<ul><li>If there is one zone present in the<b> Layout</b> view, the component will be placed in Zone and then placed in the <b>Layout </b>view at the dropped point. </li><li>If there is more than one Zone in the<b> Layout</b> view, a dialog will appear asking you to choose the Zone in which to place the component. It will then place the component into the chosen Zone and then place it in the<b> Layout</b> view at the dropped point.</li></ul>

<p>The <b>Enter a unique name for the component</b> window opens. Enter the new name and click <b>Create</b>.</p>

<p><img alt="" src="../pix/doc000001214image009.png"></img><br> </p>

<p><b>Note</b>: Each component name must be unique. RacePoint Blueprint enforces this requirement. A default name is always created. You can make a default name if you have setup the component and/or wire preferences in the <b>Prefix Preferences</b> panel. Refer to <b><a href="./000001301.html" target="_blank">Preferences: RacePoint Blueprint Programming Guide</a></b> for detailed information.</p>

<p>To move a component from one Zone to another Zone, hold down the <b>command</b> key and drag the component to the desired Zone.</p>

<p>To delete a component(s) from the <b>Zone/Component</b> list, highlight the desired component<b> </b>and click  the minus (<b>-) </b>button or use the <b>&lt;command&gt; &lt;delete&gt;</b> keys.</p>

<p>If you want to modify a component or require detailed component information, highlight the component in the<b> Zone/Component</b> list or <b>layout </b>view and do either of the following:</p>

<ul><li>Click  <b>Show Inspector</b> in the <b>Layout </b>window tool bar to open the <b>Inspector </b>window. Remember,  enable the<b> Edit</b> checkbox in the <b>Inspector </b>window when using this method.</li><li>Right-click the component in the <b>Zone/Component</b> list or <b>Layout </b>view and select <b>Edit in Inspector</b> to open the<b> Inspector </b>window. Using this method automatically enables the <b>Edit</b> checkbox in the <b>Inspector </b>window.</li></ul>

<p> </p>

<p>Refer to <b><a href="./000001169.html" target="_blank">Inspector Window: RacePoint Blueprint Programming Guide</a></b> for detailed information.</p>

<p> </p>

<h2><b>Choose Zone From List</b></h2>

<p>To choose a Zone from a list, do the following:</p>

<ol><li>Drag a component from the Library window into the <b>Layout</b> window when there is more than one Zone present.</li><li>The dialog below will display:</li></ol>

<p><img alt="" src="../pix/doc000001214image010.png"></img></p>

<ol start="3"><li>Select the Zone you want the component placed into and enter the name for the Component.</li><li>Click <b>Choose</b>.</li></ol>

<ul><li> </li></ul>

<p> </p>

<p><b>To replace the System Master (Host), do the following:</b></p>

<ol><li>Open the <b>Component Library</b> and drag the desired Host on top of the original Host (System Master).</li><li>Select the Host you would like to replace the default Host with, and drag it from the component window on top of the default configuration Host as indicated in the picture below:</li></ol>

<p><img alt="" src="../pix/doc000001214image011.png" width="800"></img></p>

<ol start="3"><li>A popup will appear asking if you want to replace the existing master.</li><li>Click <b>Replace</b> to do so. (Depending on your version of RacePoint Blueprint, you may be given the option to move the original host down to one of the zones.)</li></ol>

<p><img alt="" src="../pix/doc000001214image012.png"></img></p>

<ol start="5"><li>Enter the new UID in the <b>Device</b> tab of the host within Inspector window.</li></ol>

<p><b>Note:</b> The UID is on a sticker located on the unit.</p>

<p><img alt="" src="../pix/doc000001214image013.png"></img><br> </p>

<p><b>Configuring Modules and Assignable I/Os</b></p>

<p>After placing the components into the selected Zones, modify <b>Assigned I/Os</b> and any <b>Slot</b> populations. Not all components are configurable. You only change a component configuration, if you want to change the default configuration from the factory.</p>

<div class="Normal">
<p>Refer to <b><a href="./000001169.html" target="_blank">Inspector Window: RacePoint Blueprint Programming Guide</a></b> for detailed information.</p>
</div>

<p><b>Placing Components onto the Layout View</b></p>

<p>Drag a component from the <b>Zone/Component</b> list or <b>Component Library</b> one at a time and place it where you would like on the <b>Layout </b>view. You must place at least two components in the Layout area.</p>

<p><b>Note</b>: Include a <b>Generic Signal Source</b> component in each zone with other radio/cable/satellite components that require antenna or signal connections.</p>

<p><b>Note</b>: Use the <b>Generic StereoSpeakers</b> and <b>Generic SurroundSpeakers </b>components to represent any passive stereo speaker or surround sound speaker systems.</p>

<p><b>Note</b>: Include an Apple iPad component (any UI) in the configuration.</p>

<ul><li>You can select a placed component by clicking on the component icon.</li><li>By moving components to positions outside of the white background, the <b>Layout</b> view extends by the number of pages required to enclose that component.</li><li>The <b>Layout</b> view expands only to the right and down. If you try to place or drag a component near the top or left of the <b>Layout</b> view, it will be placed as close as possible to the right and down while still keeping the component visible.</li><li>A small green dot on each component allows you to show (maximize) or hide (minimize) unconnected connectors, so you don&#39;t have such a large component when you place it. The <b>View &gt; Minimize all Components</b> and <b>Maximize all Components</b> menu items from the RacePoint Blueprint menu allow you to minimize or maximize all the components.</li><li>Delete a component by highlighting it and using the &lt;<b>command&gt; &lt;delete&gt;</b> keys.</li><li>You can select multiple components to move or delete by clicking and dragging in the <b>Layout</b> view. All components and/or wires are selected that intersect the rectangle that is drawn as you drag into the <b>Layout</b> view. You can also select all components and wires with the <b>Edit &gt; Select All</b> menu item and then drag the group to make room to the left at the top of the <b>Layout</b> view.</li><li>If a component has been placed on the <b>Layout</b> view, but is not visible, use the <b>Edit &gt; Select All</b> menu item from the RacePoint Blueprint menu (or by using the &lt;<b>command&gt; &lt;a&gt;</b> keys) to select all the components. Drag the component group down until the component appears.</li><li>Once a component has been placed in the <b>Zone/Component </b>list, change the name of the component by clicking it to select and then click it again to open it for editing.</li><li>Once a component has been placed in the <b>Zone/Component </b>list, change the component with one from the same device class. Drag the component from the <b>Show Library</b> and drop it onto the component in the <b>Zone/Component </b>list. A screen will display asking whether you want to change components. The name of the replaced component will be retained by the new component but all connections will be lost if it has been wired.</li></ul>

<p><b>Wiring the Components</b></p>

<p>The <b>Select Styles</b> panel in the <b>Preference</b>s window of the RacePoint Blueprint menu allows the user to select the colors used for highlighting connectors while wiring and to select the color, width, and line style of the various kinds of wires.</p>

<p>Refer to <b><a href="./000001301.html" target="_blank">Preferences: RacePoint Blueprint Programming Guide</a></b> for detailed information.</p>

<p>The media connectors, in the <b>Layout</b> window, are sorted as either an <b>input</b> or <b>output</b> on each component and sorted into the following groups: </p>

<ul><li>Video, Audio, and Signal connector types </li><li>Data and Control connector types</li><li>Logical I/O (Video and Audio) connector types</li></ul>

<ol><li>Click a connector inside one of the components. All of the compatible connectors on other components will highlight (the text will become bold and change color to what you have set in the <b>Select Styles</b> panel in the <b>Preference</b>s window).</li><li>Drag the connector you originally selected and drop it on the associated connector on the other component.</li></ol>

<p >A wire will be drawn (in a color and width as specified in the<b> Select Styles</b> panel) and the connector highlight will change to indicate that the connector has now been wired.</p>

<p ><b>Note</b>: Make sure to draw radio, satellite, and cable signal connections from the <b>Generic SignalSource</b> component. Also, draw the control (RS-232, IR) connections from the Savant Controller in addition to any audio/video connections among components.</p>

<ol start="3"><li>After the components are wired, you are now ready to <b>Generate Services</b> for the configuration.</li></ol>

<ul ><li>You can also make connections by holding the <b>&lt;control&gt;</b> key down and clicking  a connector or right-clicking a connector if you have a multi-button mouse. A popup menu will appear with all of the legal connections listed, grouped by component. Simply select the desired connection in this menu and the connection will be made.</li><li>The wires are run point-to-point. The wire can run underneath another component, if necessary. It only makes a connection at an end-point as shown by the connection dot.</li><li>The <b>Layer Filter</b> button group <b>A V S D C</b> (Audio/Video/Signal/Data/Control) allows the user to highlight the buttons representing the various types of wire connections.</li><li>If a button is highlighted, that wire type connection will be shown.</li><li>If a button is not highlighted, that wire type connection will be hidden.</li></ul>

<p><b>Note</b>: The <b>View</b> menu from the RacePoint Blueprint menu also provides menu items to access a list of Zones that can be selected or deselected to show or hide the components and wires within any zone or zones.</p>

<ul><li>You can erase a wire by clicking the connector at either end or somewhere along the wire itself and using the<b> Edit &gt; Delete</b> menu item from the RacePoint Blueprint menu (or by using the <b>&lt;command&gt; &lt;delete&gt;</b> keys).</li><li>You can wire to a minimized component only by using the contextual (<b>control-click</b>) menu. To wire by using drag and drop, you need to first maximize both components (if one or both are minimized).</li><li>If you want to modify certain connection property values or require detailed component information, click <b>Inspector</b> to open the <b>Inspector </b>window and refer to <b>Error! Reference source not found.</b>, <b>Connection Inspector Window</b> for detailed information.</li></ul>

<p><br><b>Connectivity Validation and Changes</b></p>

<p>After the components are wired, check the color of a component header in order to validate connectivity.</p>

<p>Refer to <b><a href="./000001522.html" target="_blank">Component Highlighting: RacePoint Blueprint Programming Guide</a></b> for detailed information.</p>

<p>If you want to modify certain connection property values or require detailed component information, refer to <b><a href="./000001169.html" target="_blank">Inspector Window: RacePoint Blueprint Programming Guide</a></b> for detailed information.</p>

<p><b>Update Component Profiles in a Configuration with the System Version</b></p>

<p>After opening a RacePoint Blueprint configuration, and the <b>Update Component </b>window appears stating there is a difference between the configuration version and the system version of a component profile or component profiles, refer to<i> </i><b><a href="./000001589.html" target="_blank">Profile Update Alerts when Opening a Configuration: RacePoint Blueprint Programming Guide</a></b></p>

<p> </p>

<div class="Heading1">
<p><b>Generate Services for the Configuration</b></p>
</div>

<p>After wiring the components, <b>Generate Services</b> for the configuration.</p>

<div class="Normal">
<ol><li>At the <b>layout</b> window toolbar, click on <b>Generate Services</b> or use the <b>Tools&gt;</b><b> </b><b>Generate Services</b> menu item.</li></ol>
</div>

<p ><b>Note</b>: If the <b>Automator</b> application is open, see an alert reminding you to close it so that changes in the workflows will be shown when a workflow is opened.</p>

<p><img class="li1" alt="" src="../pix/doc000001214image014.png"></img><br> </p>

<ol start="2"><li class="Normal">When generating services is complete, the <b>Services Selection</b> window opens. Refer to <b><a href="./000001160.html" target="_blank">Service Selection: RacePoint Blueprint Programming Guide</a></b> for detailed information.</li><li class="Normal">From this window you can see the realized services list (and if you choose the <b>View </b>&gt;<b> Unrealized</b> menu item, you will see the unrealized services list). The right panel of the window shows the components, resources, and wiring connections that are used to implement the services that are selected in the left panel.</li></ol>

<p ><b>Note</b>: The Realized Services list provides a list of available AV services based on the components and wiring specified. The set of enabled, realized services determines the set of menu screens that will be available on the touch panels.</p>

<p ><b>Note</b>: The Unrealized Services list provides a list of possible services that might be realized from the set of components but the existing component wiring or configuration does not allow these services to be realized. This list also provides a way to help you to troubleshoot when you are not seeing Realized Sservices that should be available. This situation can occur due to wiring and configuration errors.</p>

<div class="Normal">
<ol start="4"><li>From the Realized Services list you can choose the services you want to implement.</li></ol>
</div>

<ul ><li>If a particular service has more than one implementation, those implementations will be shown as subheadings of a service.</li><li>If a service has multiple implementations, each implementation will have a radio button next to it. Only one can be enabled at a time.</li><li>If a service has only one implementation, it will have a checkbox next to it. A service (and any subheadings) will be disabled if the box is not checked.</li><li>You can enable or disable a service or an entire zone of services.</li><li>You can disable some of the subheadings of a service but not all of them. In this case, the service checkbox will have a minus (-) in it to indicate that not all of the subheadings are enabled.</li></ul>

<p> </p>

<p> </p>
</body>
</html>
