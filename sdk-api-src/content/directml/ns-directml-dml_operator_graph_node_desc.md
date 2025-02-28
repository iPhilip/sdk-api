---
UID: NS:directml.DML_OPERATOR_GRAPH_NODE_DESC
title: DML_OPERATOR_GRAPH_NODE_DESC
description: Decribes a node within a graph of DirectML operators defined by [DML_GRAPH_DESC](/windows/desktop/api/directml/ns-directml-dml_graph_desc) and passed to [IDMLDevice1::CompileGraph](/windows/desktop/api/directml/nf-directml-idmldevice1-compilegraph).
helpviewer_keywords: ["DML_OPERATOR_GRAPH_NODE_DESC","DML_OPERATOR_GRAPH_NODE_DESC structure","direct3d12.dml_operator_graph_node_desc","directml/DML_OPERATOR_GRAPH_NODE_DESC"]
tech.root: directml
ms.date: 11/05/2020
req.header: directml.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: 
req.target-min-winversvr: 
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: 
req.dll: 
req.irql: 
targetos: Windows
req.typenames: 
req.redist: 
f1_keywords:
 - DML_OPERATOR_GRAPH_NODE_DESC
 - directml/DML_OPERATOR_GRAPH_NODE_DESC
dev_langs:
 - c++
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - HeaderDef
api_location:
 - DirectML.h
api_name:
 - DML_OPERATOR_GRAPH_NODE_DESC
---

## -description

Decribes a node within a graph of DirectML operators defined by [DML_GRAPH_DESC](/windows/desktop/api/directml/ns-directml-dml_graph_desc) and passed to [IDMLDevice1::CompileGraph](/windows/desktop/api/directml/nf-directml-idmldevice1-compilegraph).

The behavior of this node is defined by a DirectML operator.

## -struct-fields

### -field Operator
 
Type: <b>[IDMLOperator](/windows/win32/api/directml/nn-directml-idmloperator)*</b>

A DirectML operator defining the behavior of the node.

### -field Name

Type: \_Field\_z\_ \_Maybenull\_ **const char\***

An optional name for the graph connection. If provided, this might be used within certain error messages emitted by the DirectML debug layer.

## Availability

This API was introduced in DirectML version `1.1.0`.

## -see-also

* [IDMLDevice1::CompileGraph method](/windows/desktop/api/directml/nf-directml-idmldevice1-compilegraph)
* [DML_GRAPH_DESC structure](/windows/desktop/api/directml/ns-directml-dml_graph_desc)
* [DML_GRAPH_NODE_DESC structure](/windows/desktop/api/directml/ns-directml-dml_graph_node_desc)
