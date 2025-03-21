## Results of 1-NN Classification using DTW and ED  

The following table presents the classification error rates for 1-Nearest Neighbor (1NN) classification using **Euclidean Distance (ED)** and **Dynamic Time Warping (DTW)** on selected datasets from the UCR Time Series Archive. The results demonstrate that DTW often outperforms ED in capturing temporal variations in time series data.  

### Classification Error Rates  

| Dataset                   | ED     | DTW    |
|---------------------------|--------|--------|
| Adiac                     | 0.3887 | 0.3964 |
| Beef                      | 0.3333 | 0.3667 |
| CBF                       | 0.1478 | 0.0033 |
| Coffee                    | 0.0000 | 0.0000 |
| Cricket_X                 | 0.4231 | 0.2462 |
| Cricket_Y                 | 0.4333 | 0.2564 |
| Cricket_Z                 | 0.4128 | 0.2462 |
| ECG200                    | 0.1200 | 0.2300 |
| FaceAll                   | 0.2864 | 0.1923 |
| FaceFour                  | 0.2159 | 0.1705 |
| Fish                      | 0.2171 | 0.1771 |
| Gun_Point                 | 0.0867 | 0.0933 |
| LargeKitchenAppliances    | 0.5067 | 0.2053 |
| Lighting2                 | 0.2459 | 0.1311 |
| OliveOil                  | 0.1333 | 0.1667 |
| OSULeaf                   | 0.4793 | 0.4091 |
| ShapeletSim               | 0.4611 | 0.3500 |
| SmallKitchenAppliances    | 0.6587 | 0.3573 |
| Symbols                   | 0.1005 | 0.0503 |
| SyntheticControl          | 0.1200 | 0.0067 |
| Trace                     | 0.2400 | 0.0000 |
| TwoLeadECG                | 0.2529 | 0.0957 |

These results highlight the effectiveness of **DTW** over **ED** in many cases, reinforcing its suitability for time series classification tasks.  
