## Header

Some text

```python
import pandas as pd
data = pd.read_csv("data.csv")
data.head()
```

{/*% plot plot2 %*/}}
var trace1 = {
  x: [1, 2, 3, 4],
  y: [10, 15, 13, 17],
  type: 'scatter'
};

var trace2 = {
  x: [1, 2, 3, 4],
  y: [16, 5, 11, 9],
  type: 'scatter'
};

data = [trace1, trace2];
fig = {
  data: data
}
{{/*% /plot %*/}}


```mermaid
graph TD;
  A-->B;
  A-->C;
  B-->D;
  C-->D;
```



{{< math >}}
$$
\gamma_{n} = \frac{ \left | \left (\mathbf x_{n} - \mathbf x_{n-1} \right )^T \left [\nabla F (\mathbf x_{n}) - \nabla F (\mathbf x_{n-1}) \right ] \right |}{\left \|\nabla F(\mathbf{x}_{n}) - \nabla F(\mathbf{x}_{n-1}) \right \|^2}
$$
{{< /math >}}