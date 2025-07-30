# 🐙 Advanced Formatting

## Alerts

Alerts are a Markdown extension based on the blockquote syntax that you can use to emphasize critical information. They are displayed with distinct colors and icons to indicate the importance of the content.

> [!NOTE]  
> Useful information that users should know, even when skimming content.

> [!TIP]  
> Helpful advice for doing things better or more easily.

> [!IMPORTANT]  
> Key information users need to know to achieve their goal.

> [!WARNING]  
> Urgent info that needs immediate user attention to avoid problems.

> [!CAUTION]  
> Advises about risks or negative outcomes of certain actions.

## Collapsible Section

You can temporarily hide sections of your Markdown by creating an expandable section that the reader can choose to open. For example, when you want to include technical details in an issue comment that might not be relevant or interesting to all readers, you can place those details in a collapsible section.

Any Markdown inside the `<details>` block will remain collapsed until the reader clicks to expand it.

Inside the `<details>` block, use the `<summary>` tag to give readers a preview of what's inside. The label appears next to the arrow.

<details>

<summary>Tips for collapsed sections</summary>

### You can add a header

You can add text within a collapsed section.

You can also include an image or a code block.

```ruby
   puts "Hello World"
```

</details>

## Mermaid Diagrams

**Mermaid** is a Markdown-inspired tool that transforms text into diagrams. For example, Mermaid can render flowcharts, sequence diagrams, pie charts, and much more.

To create a Mermaid diagram, add the Mermaid syntax inside a fenced code block with the language identifier `mermaid`.

Here is a simple flow chart:

```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```

## Maps

You can use GeoJSON or TopoJSON syntax to create interactive maps. To create a map, place GeoJSON or TopoJSON inside a fenced code block using the `geojson` or `topojson` syntax identifier.

```geojson
{
  "type": "FeatureCollection",
  "features": [
    {
      "type": "Feature",
      "id": 1,
      "properties": {
        "ID": 0
      },
      "geometry": {
        "type": "Polygon",
        "coordinates": [
          [
            [-90, 35],
            [-90, 30],
            [-85, 30],
            [-85, 35],
            [-90, 35]
          ]
        ]
      }
    }
  ]
}
```
