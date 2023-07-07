# Test

```kroki-plantuml format="svg" classes="uml myDiagram" alt="diagram placeholder" title="Libs"
"client" -- "service"
"client" -- "common"
"service" -- "common"
```

```kroki-blockdiag no-transparency=false
blockdiag {
  blockdiag -> generates -> "block-diagrams";
  blockdiag -> is -> "very easy!";

  blockdiag [color = "greenyellow"];
  "block-diagrams" [color = "pink"];
  "very easy!" [color = "orange"];
}
```