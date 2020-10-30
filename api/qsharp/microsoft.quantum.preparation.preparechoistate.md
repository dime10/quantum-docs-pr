---
uid: Microsoft.Quantum.Preparation.PrepareChoiState
title: PrepareChoiState operation
ms.date: 10/30/2020 12:00:00 AM
ms.topic: article
qsharp.kind: operation
qsharp.namespace: Microsoft.Quantum.Preparation
qsharp.name: PrepareChoiState
qsharp.summary: >-
  Prepares the Choi–Jamiłkowski state for a given operation onto given reference
  and target registers.
---

# PrepareChoiState operation

Namespace: [Microsoft.Quantum.Preparation](xref:Microsoft.Quantum.Preparation)

Package: [](https://nuget.org/packages/)


Prepares the Choi–Jamiłkowski state for a given operation onto given reference

```qsharp
operation PrepareChoiState (op : (Qubit[] => Unit), reference : Qubit[], target : Qubit[]) : Unit
```


## Input

### op : [Qubit](xref:microsoft.quantum.lang-ref.qubit)[] => [Unit](xref:microsoft.quantum.lang-ref.unit) 

Operation $\Lambda$ whose Choi–Jamiłkowski state $J(\Lambda) / 2^N$


### reference : [Qubit](xref:microsoft.quantum.lang-ref.qubit)[]

A register of qubits starting in the $\ket{00\cdots 0}$ state


### target : [Qubit](xref:microsoft.quantum.lang-ref.qubit)[]

A register of qubits initially in the $\ket{00\cdots 0}$ state



## Output : [Unit](xref:microsoft.quantum.lang-ref.unit)



## Remarks

The Choi–Jamiłkowski state $J(\Lambda)$ of a quantum process is

## See Also

- [Microsoft.Quantum.Preparation.PrepareChoiStateA](xref:Microsoft.Quantum.Preparation.PrepareChoiStateA)
- [Microsoft.Quantum.Preparation.PrepareChoiStateC](xref:Microsoft.Quantum.Preparation.PrepareChoiStateC)
- [Microsoft.Quantum.Preparation.PrepareChoiStateCA](xref:Microsoft.Quantum.Preparation.PrepareChoiStateCA)