# Connect to SharePoint document libraries from PowerApps
SharePoint Online document libraries ( https://support.office.com/en-us/article/What-is-a-document-library-3b5976dd-65cf-4c9e-bf5a-713c10ca2872 ) are now supported in Canvas apps. Document libraries show up from the data sources panel when you select a SharePoint Online list.  Your end users can view a listing of files that are in the SharePoint document library (if they have permissions to do so). Follow these steps to get started.

SharePoint Document Library supported types in the web player:
•	Images
•	Videos
•	Audio

A sample is provided (link) for this scenario, but you can also create a new app or start from an existing app.
1.	In PowerApps Studio, click or tap Open in the left pane.
2.	Click or tap Browse, then open the SPDocLib_BlogApp.msapp file that you downloaded.
3.	Click or tap Allow, so that PowerApps can use SharePoint.
4.	On the ribbon, on the View tab, click or tap Data sources.
 
5.	In the Data panel, click or tap Add Data Source.
6.	We'll show you two ways to connect to the list, depending on whether PowerApps already established a SharePoint connection for you:
•	If you see a SharePoint connection already, click or tap that connection.
 
•	If you don't see a SharePoint connection, click or tap New connection.
 
7.	Then click or tap SharePoint and click or tap Create.
 
8.	Enter the URL for the SharePoint Online site that contains a document library or select a recent site (be sure the document library contains documents), then click or tap Connect.
 
9.	Select the Documents list, then click or tap Connect.
 
10.	Click or tap the ellipsis (. . .) next to Documents, then click or tap Refresh.
 


Limitations:
•	PDF Viewer does not support viewing PDFs from SharePoint Online document libraries
•	Mobile devices and Windows 10 App limitations
o	Document Library List content will show up in a Gallery, however, to view content, you will need to use the Launch Command (https://docs.microsoft.com/en-us/powerapps/maker/canvas-apps/functions/function-param ) to display the content in a browser on the mobile device
o	The download function is not supported for mobile devices
•	Adding files from PowerApps to a SharePoint Online document library is not supported
•	SharePoint Online support only, On-Premise is not supported
