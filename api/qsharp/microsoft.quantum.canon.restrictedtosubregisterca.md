---
uid: Microsoft.Quantum.Canon.RestrictedToSubregisterCA
title: RestrictedToSubregisterCA function
ms.date: 10/26/2020 12:00:00 AM
ms.topic: article
qsharp.kind: function
qsharp.namespace: Microsoft.Quantum.Canon
qsharp.name: RestrictedToSubregisterCA
qsharp.summary: >-
  Restricts an operation to an array of indices of a register, i.e., a subregister.
  The modifier `CA` indicates that the operation is controllable and adjointable.
---

# RestrictedToSubregisterCA function

Namespace: [Microsoft.Quantum.Canon](xref:Microsoft.Quantum.Canon)

Package: [](https://nuget.org/packages/)


Restricts an operation to an array of indices of a register, i.e., a subregister.The modifier `CA` indicates that the operation is controllable and adjointable.

```qsharp
function RestrictedToSubregisterCA (op : (Qubit[] => Unit is Adj + Ctl), idxs : Int[]) : (Qubit[] => Unit is Adj + Ctl)
```


## Input

### op : [Qubit](xref:microsoft.quantum.lang-ref.qubit)[] => [Unit](xref:microsoft.quantum.lang-ref.unit) Adj + Ctl

Operation to be restricted to a subregister.


### idxs : [Int](xref:microsoft.quantum.lang-ref.int)[]

Array of indices, indicating to which qubits the operation will be restricted.



## Output : [Qubit](xref:microsoft.quantum.lang-ref.qubit)[] => [Unit](xref:microsoft.quantum.lang-ref.unit) Adj + Ctl



## See Also

- [Microsoft.Quantum.Canon.RestrictedToSubregister](xref:Microsoft.Quantum.Canon.RestrictedToSubregister)