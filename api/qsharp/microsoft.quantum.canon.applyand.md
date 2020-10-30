---
uid: Microsoft.Quantum.Canon.ApplyAnd
title: ApplyAnd operation
ms.date: 10/30/2020 12:00:00 AM
ms.topic: article
qsharp.kind: operation
qsharp.namespace: Microsoft.Quantum.Canon
qsharp.name: ApplyAnd
qsharp.summary: >-
  Inverts a given target qubit if and only if both control qubits are in the 1 state,
  using measurement to perform the adjoint operation.
---

# ApplyAnd operation

Namespace: [Microsoft.Quantum.Canon](xref:Microsoft.Quantum.Canon)

Package: [](https://nuget.org/packages/)


Inverts a given target qubit if and only if both control qubits are in the 1 state,

```qsharp
operation ApplyAnd (control1 : Qubit, control2 : Qubit, target : Qubit) : Unit
```


## Description

Inverts `target` if and only if both controls are 1, but assumes that

## Input

### control1 : [Qubit](xref:microsoft.quantum.lang-ref.qubit)

First control qubit


### control2 : [Qubit](xref:microsoft.quantum.lang-ref.qubit)

Second control qubit


### target : [Qubit](xref:microsoft.quantum.lang-ref.qubit)

Target auxiliary qubit; must be in state 0



## Output : [Unit](xref:microsoft.quantum.lang-ref.unit)



## References

- Cody Jones: "Novel constructions for the fault-tolerant Toffoli gate",