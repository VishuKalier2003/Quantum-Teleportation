
# ${Snippets}$

This folder contains the important snippets used in the Code and notebooks. The Snippets can be used for having a glance of the pseudocode of the Project explaining the
specific details of the Project with the generated Code.


## ${Snippets}$

### ${Snippet \space I}$

```java
Circuit.h(1)
Circuit.cx(1, 2)   // Entangling Qbits q1 and q2 using Hadamard and Control Negation Gate...
Circuit.barrier()    // Setting up barriers for better visualizations...
Circuit.draw()
```

### ${Snippet \space II}$

```java
Circuit.barrier()
Circuit.measure([0, 1], [0, 1])            // Measuring Qbits 0 and 1, Storing it in Cbits 0 and 1...
Circuit.draw()
```

### ${Snippet \space III}$

```java
Circuit.barrier()
Circuit.cx(1, 2)             // Applying Control Negation Gate between Qbits 1 and 2...
Circuit.cz(0, 2)             // Applying Pauli Z Gate or Phase Shift Gate between Qbits 0 and 2...
Circuit.draw(output="mpl")
```

## ${Created \space By}$
***Vishu Kalier***




