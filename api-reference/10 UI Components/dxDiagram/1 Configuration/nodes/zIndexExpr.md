---
id: dxDiagram.Options.nodes.zIndexExpr
type: String | function(data, value)
default: undefined
---
---
##### shortDescription
Specifies the name of a data source field or an expression that provides a node's z-index.

##### param(data): any
The current node's data object.

##### return: any
A node's z-index.

##### param(value): any
<!-- Description goes here -->

---
The z-index specifies the node stack order. A node with greater stack order is in front of a node with a lower stack order.