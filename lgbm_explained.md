## LightBGM Algorithm

The LGBM algorithm is a fast, distributed, high performance gradient boosted framework based on decision tree algorithms. It is a relatively new algorithm that is challenging and outperforming existing algorithms.

### Pros
1. Faster training speed and higher efficiency
2. Lower memory usage
3. Better accuracy
4. Support of GPU learning
5. Handle large-scale data

## Cons
1. Sensitive to overfitting
2. Not recommended for small data sets

## Tree Growth
Most decision tree algorithms grow by level-wise. That is, they grow horizontally. However LGBM is unique because it grows leaf-wise or vertically. It will choose the leaf with the max delta loss to grow which can reduce more loss. The follow visual explains the growth: 
