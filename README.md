Uses a dataset of movies attached here.

Chosen features are keywords, cast, genres & director.These are combined to create a single column aclled 'cobined_features' and CountVectorizer is used to tokenize the data.
Little bit of data preprocessing is done toreplace any rows having NaN values with a space/empty string.
Cosine similarity is used to generate similiar movies to the one mentioned here as the one user 'likes'.
