## Custom export filters

JabRef allows you to define and use your own export filters, in the same way as the standard export filters are defined. An export filter is defined by one or more layout files, which with the help of a collection of built-in formatter routines specify the format of the exported files. Your layout files must be prepared in a text editor outside of JabRef.

### Adding a custom export filter

The only requirement for a valid export filter is the existence of a file with the extension .layout. To add a new custom export filter, open the dialog box Options -> Manage custom exports, and click Add new. A new dialog box will appear, allowing you to specify a name for the export filter (which will appear as one of the choices in the File type dropdown menu of the file dialog when you use the File -> Export menu choice in the JabRef window), the path to the .layout file, and the preferred file extension for the export filter (which will be the suggested extension in the file dialog when you use the export filter).