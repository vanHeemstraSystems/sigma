# 300 - Building Our Application

Based on "Sigma - Quick Start" at https://www.sigmajs.org/#quickstart

Based on "Looking-glass Viewer" at https://github.com/MercuryTechnologies/looking-glass-viewer

Based on "Looking Glass Graph Viewer" at https://mercurytechnologies.github.io/looking-glass-viewer/

Try above Looking Glass Graph Viewer with the following JSON data:

```
{
  "edges": [
    {
      "to": "someOtherNode",
      "from": "someNode",
      "amount": "2.50"
    },
    {
      "to": "yetAnotherNode",
      "from": "someOtherNode",
      "amount": "125.00"
    }
  ],
  "nodes": {
    "someNode": {
      "color": "red",
      "props": {
        "someProp": "someNode",
        "googleSearch": "sherlock holmes"
      }
    },
    "someOtherNode": {
      "color": "red",
      "props": {
        "someProp": "someOtherNode",
        "googleSearch": "sherlock holmes"
      }
    }
  },
  "title": "My visualization"
}
```
