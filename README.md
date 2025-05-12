# SWD4CS
SWD4CS is an abbreviation for Simple WinForms Designer for CSharp (VSCode)
VisualStudio is resource-intensive, so I often use VSCode. However, it lacks a designer.
I had no idea how to create a designer, so I just tried to build one based on my ideas as they came.
This approach isn't suitable for complex projects. Maybe it can be used for small tools?
Development Environment
Windows11 Home
VisualStudio2022 C# → VSCode .net6.0
Screenshots
![alt text](https://user-images.githubusercontent.com/86605611/152679486-e8f7bbed-69b4-4186-b402-35d7bd2fec8f.png)

![alt text](https://user-images.githubusercontent.com/86605611/152784518-c135ec3a-e156-4163-8f8d-90cc023d8448.png)

*Note: The ControlTree is for display only.
Videos
https://youtu.be/BJAhuU2W3uM
https://youtu.be/3LyjAvXLpYg
https://youtu.be/82qa0vOP_qk
https://youtu.be/FkDaMW4hGyk
Blog
https://danpapa-hry.hateblo.jp/entry/2022/02/23/210416
Implemented Features
・Drag and drop (Potopeta - colloquial term for drag and drop)
・Modification of some properties
・Button
・CheckBox
・CheckedListBox
・ComboBox
・DataGridView
・DateTimePicker
・DomainUpDown
・FlowLayoutPanel
・GroupBox
・HScrollBar
・Label
・LinkLabel
・ListBox
・ListView
・MaskedTextBox
・MonthCalender
・Panel
・PictureBox
・ProgressBar
・PropertyGrid
・RadioButton
・RichTextBox
・SplitContainer
・Splitter
・StatusStrip
・TabControl
・TableLayoutPanel
・TabPage
・TextBox
・TrackBar
・TreeView
・VScrollBar
・ColorDialog
・FolderBrowserDialog
・FontDialog
・imageList
・OpenFiledialog
・SaveFiledialog
・Timer
・Read/Write of Designer.cs files ~~ (However, files edited with tools other than SWD4CS cannot be opened)~~
・Other controls, etc., will be added as needed.
Supported Properties (Type)
・System.Drawing.Point
・System.Drawing.Size
・System.String
・System.Boolean
・System.Int32
・System.Windows.Forms.AnchorStyles
・System.Windows.Forms.DockStyle
・System.Drawing.ContentAlignment
・System.Windows.Forms.ScrollBars
・System.Windows.Forms.HorizontalAlignment
・System.Drawing.Color
・System.Windows.Forms.FormStartPosition
・System.Windows.Forms.FormWindowState
・System.Windows.Forms.FixedPanel
・System.Windows.Forms.PictureBoxSizeMode
・System.Windows.Forms.View
・System.Windows.Forms.Orientation
・System.Windows.Forms.FormBorderStyle
・System.Windows.Forms.AutoScaleMode
・System.Drawing.Font
・System.Windows.Forms.TableLayoutPanelCellBorderStyle
How to Add Controls
Add to the section marked "// Edit the following when adding controls"
・cls_control.cs
