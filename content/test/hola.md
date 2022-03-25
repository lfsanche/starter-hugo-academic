## Header

Some text

```python
import pandas as pd
data = pd.read_csv("data.csv")
data.head()
```


{{< chart  data= "first_figure.json" >}}

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