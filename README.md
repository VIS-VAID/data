# KB4VA Data

The repository hosts all figures of the visualizations and VA systems in KB4VA.
The metadata of visualizations and VA systems are provided in `json` format.

Metadata of the visualizations:
```{javascript}
  {
      "viewId": string (the unique id of the view),
      "viewFile": string (the file name of the view),
      "dataType": string (data representation),
      "structuralData": string (formatted sturctural data representation),
      "nonStructuralData": string (formatted non-sturctural data representation),
      "taskType":[string] (tuple of task types),
      "figFile": string (file name of the system),
      "figId": string (unique id of the system),
      "figCaption": string,
      "figBox":[], ## Bounding box of the view
      "figVis":[string] (tuple of visualization types),
      "taskNote": string (quoted description of the selected tasks),
      "Datanote": string (explanation of the visual encoding)
  }
```
Metadata of the VA systems:
```{javascript}
{
        "figId": string (unique id of the system),
        "figFile": string (file name of the system),
        "title": string (paper title of the system),
        "caption": string (caption of the system)
        "viewIds": [string] (view ids of the system)
    }
```
