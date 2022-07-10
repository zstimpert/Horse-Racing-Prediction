# Yuri Updates

Unfortunately, including the `Season Stakes` introduces look ahead bias. The `Season Stakes` is an accumulated number over the course of the season, instead of accumulated earnings up to the date of that specific race. Because of that, a horse with a high `Season Stakes` is implied to have placed well during the season, while a horse with a low `Season Stakes` is implied to have placed poorly. If you exclude `Season Stakes` from your dataset, you'll see that the model reverts back to being nearly random.

# Horse-Racing-Prediction
This work focuses on the prediction of Hong Kong Jockey Club (HKJC) horse racing results using Deep Learning Neural Networks. We decide to collect a large dataset from the ofﬁcial HKJC website and provide a tool to directly download the most current data. Furthermore, we tackle the problem of using various deep learning architectures, including a simple MLP regression method, a CNN to account for spatial relationships, as well as an RNN to model temporal dependencies along with sequential historical data. The results of ”win” and ”place” accuracy are shown for all the different architectures that have been tested and implemented.
