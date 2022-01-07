# Orchest + PyCaret

Demonstration of how to use PyCaret for regression prediction in Orchest

In the `Load` step configure the dataset name:

```
{
  "dataset": "insurance"
}
```

Pick any PyCaret dataset that has Regression as the default task: https://pycaret.org/get-data/#datasets

Or replace the `Load` step with a step that loads a custom dataset.

![Orchest + PyCaret](https://pviz.orchest.io/?pipeline=https://github.com/ricklamers/orchest-pycaret/blob/master/main.orchest)
