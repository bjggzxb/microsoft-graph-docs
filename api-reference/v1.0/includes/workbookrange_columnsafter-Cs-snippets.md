
```Cs

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

await graphClient.Me.Drive.Root.Workbook.Worksheets["{id}"]
	.Range()
	.ColumnsAfter(count)
	.Request()
	.PostAsync()

```