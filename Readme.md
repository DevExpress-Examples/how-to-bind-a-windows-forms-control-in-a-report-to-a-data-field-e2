# How to bind a Windows Forms control in a report to a data field


<p>The following example demonstrates how to bind a Windows Forms control, which is embedded into a report via the <strong>WinControlContainter</strong> control, to a data field. To accomplish this task, it is necessary to handle the <strong>WinControlContainer</strong>'s <strong>BeforePrint</strong> event, manually obtain the required value from a report's data source via the <strong>GetCurrentColumnValue</strong> method and assign the resulting value to a Windows Forms control (e.g. to a <strong>Label</strong>'s <strong>Text</strong> property).</p>

<br/>


