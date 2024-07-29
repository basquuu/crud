# Model

1. 모델 정의 
```python
class Post(models.Model):
  title = models.CharField(max_length=100)
  content = models.TextField()
```