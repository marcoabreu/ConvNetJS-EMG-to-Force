# ConvNetJS-EMG-to-Force
Implementation of [Stanfords ConvNetJS](1) to calculate relations between EMG signals and the applied force

## Input
This network allows to import data as a csv-seperated file.

## Output
The trained network may be exported as JSON using the "Save Network" button.

## Results
In this example, the applied force gets calculated based on the measured EMG-signals. 

![Result example][result-img]

For debugging purposes, the actual force output, the force output calculated by the neural network as well as the training accuracy of the current iteration are displayed. To gain an overview over the networks performance, the amount of total iterations and the accuracy during the last X iterations are displayed.


## Statistics
To visualize the development of the neural network, additional statistics are available as graphs.

![Statistics example][statistics-example]

**Loss-graph**: Respresents the loss between every batch of iterations.

**Accuracy-graph**: Represents the development of the accuracy with increasing number of iterations. This allows to determine whether the performance is converging or further training may improve the accuracy of the neural network.


[1]: https://cs.stanford.edu/people/karpathy/convnetjs/
[result-img]: https://github.com/marcoabreu/ConvNetJS-EMG-to-Force/blob/master/github-img/results.PNG?raw=true
[statistics-example]: https://github.com/marcoabreu/ConvNetJS-EMG-to-Force/blob/master/github-img/statistics.PNG?raw=true
