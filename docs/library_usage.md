Example

```
clientset := pomo.New(baseURL)
pomos, err := clientset.V1().Pomos().List()
if err != nil {
  panic(err.Error())
}
fmt.Printf("There are %d pomos\n", len(pomos.Items))
```
