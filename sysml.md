This is SysML


$$\Gamma(z) = \int_0^\infty t^{z-1}e^{-t}dt\,.$$   (for display)
\\[\Gamma(z) = \int_0^\infty t^{z-1}e^{-t}dt\,.\\] (also for display)
\\(\Gamma(z) = \int_0^\infty t^{z-1}e^{-t}dt\,.\\) (for inline)






![](assets/sysml-d1f2d.png)

Term 1
Term 2
:   Definition Akkk
:   Definition B

$\Gamma(n) = (n-1)!\quad\forall n\in\mathbb N$


```puml
a->b
```

```mermaid
classDiagram
Class01 <|-- AveryLongClass : Cool
<<interface>> Class01
Class09 --> C2 : Where am i?
Class09 --* C3
Class09 --|> Class07
Class07 : equals()
Class07 : Object[] elementData
Class01 : size()
Class01 : int chimp
Class01 : int gorilla
class Class10 {
  <<service>>
  int id
  size()
}
```

```mermaid
stateDiagram-v2
[*] --> Still
Still --> [*]
Still --> Moving
Moving --> Still
Moving --> Crash
Crash --> [*]
```

```sequence {theme="hand"}
a -> b: test
```
