[//]: # (Image reference)
[image1]: https://img.youtube.com/vi/hLIXTkSNILs/0.jpg
[image2]: https://img.youtube.com/vi/hLIXTkSNILs/0.jpg
[image3]: https://img.youtube.com/vi/hLIXTkSNILs/0.jpg
[image4]: documentation/pr.png

# Test Project

This is a project for churn prediction.

**This project is created for Data science academy**
---




| Video1      | Video2     | Video3 |
| ------- | ------- |--|
|[![alt Coding competition][image1]](https://www.youtube.com/watch?v=hLIXTkSNILs) | [![alt Coding competition][image1]](https://www.youtube.com/watch?v=hLIXTkSNILs) | [![alt Coding competition][image1]](https://www.youtube.com/watch?v=hLIXTkSNILs)|

*Neural network classifier for Dog breed classification*

> A neural network is a network or circuit of neurons, or in a modern sense, an artificial neural network, composed of artificial neurons or nodes.[1] Thus a neural network is either a biological neural network, made up of biological neurons or an artificial neural network, for solving artificial intelligence (AI)

## Team structure
**Team members:**
1. Violeta    
1.1  Katerina  
1.2 Martin
2. Marija

## Project Introduction
**Our project is built using the following ML techniques:**
- Deep Learning
- Clustering (unsupervised Learning)
- PCA


## Implemenmtation 

This is the code snippet that contributed to the greatest model accuracy

```

# Python program for implementation of Bubble Sort
  
def bubbleSort(arr):
    n = len(arr)
  
    # Traverse through all array elements
    for i in range(n-1):
    # range(n) also works but the outer loop will repeat one time more than needed.
  
        # Last i elements are already in place
        for j in range(0, n-i-1):
  
            # traverse the array from 0 to n-i-1
            # Swap if the element found is greater
            # than the next element
            if arr[j] > arr[j + 1] :
                arr[j], arr[j + 1] = arr[j + 1], arr[j]
  
# Driver code to test above
arr = [64, 34, 25, 12, 22, 11, 90]
  
bubbleSort(arr)
  
print ("Sorted array is:")
for i in range(len(arr)):
    print ("% d" % arr[i]), 
```


## Dataset Info

Link to dataset : Click [here](http://www.google.com)
![alt Coding competition](https://media.geeksforgeeks.org/wp-content/cdn-uploads/20210127175547/Must-Do-Coding-Questions-for-Product-Based-Companies.png)
<p align="center">
<img src="https://media.geeksforgeeks.org/wp-content/cdn-uploads/20210127175547/Must-Do-Coding-Questions-for-Product-Based-Companies.png" width="25%" height="25%"/>
</p>

## Evaluation results

| Test      | Training     | Validation |
| ------- | ------- |--|
| 93% | 47% | 99%|

![Precision recall][image4]

We tried the following ML models : 

- [x] Resnet 50
- [ ] Inception
- [ ] Densnet

## Future work
To do :

- [x] ~~Heavy light decomposition~~
- [ ] PCA 
- [ ] KMeans




