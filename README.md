# Iris ML API

## API Contract

The `/predict` Once you’ve learned the basics of machine learning, it’s important to try out some practical projects to strengthen your skills. This section includes fun and simple machine learning projects for beginners that you can quickly pick up to build a strong foundation.
# Prediction API Flow

```text
Client sends a request
        ↓
POST /predict

Input:
{
  "sepal_length": 5.1,
  "sepal_width": 3.5,
  "petal_length": 1.4,
  "petal_width": 0.2
}
        ↓
validation
{
  "sepal_length": 5.1,
  "sepal_width": 3.5,
  "petal_length": 1.4,
  "petal_width": 0.2
} 


  