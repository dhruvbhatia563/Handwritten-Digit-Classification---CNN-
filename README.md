# Handwritten-Digit-Classification---CNN-
---------------------------------------------------------
The MNIST data is a database of handwritten digits from 0 to 9. The database contains 60,000 28x28 grayscale images of the 10 digits, along with a test set of 10,000 images. Your task is to create a CNN model for identifying the digit from the handwritten images. 
---------------------------------------------------------
---------------------------------------------------------
Please perform the following tasks
---------------------------------------------------------
- Load the database to variable named digit_mnist using the Keras inbuilt datasets (digit_mnist = keras.datasets.mnist)
- Import data to create X_train_full, y_train_full, X_test and y_test variables
- Reshape the independent (X) data
- Normalize the data
- Create a validation set of 6000 images
- Create a CNN model (Model_A) with a Conv layer of filters = 32, kernel_size = (3, 3), strides=1, padding='valid', a Max pooling layer of 2 by 2 window and two dense layers with 200 and 100 neurons
- Compile and train the model for 60 epochs
- Plot the loss and accuracy against epoch
- Evaluate the model accuracy on the test dataset
- Create another model (model_B) with number of filter =64
- Compare the performance and execution time for Model_A and Model_B

![image](https://user-images.githubusercontent.com/68370376/135503852-aa364661-8518-4c8d-8c44-ab503011ad98.png)

![image](https://user-images.githubusercontent.com/68370376/135503888-110f4b69-1fdb-4480-9830-dc4f6e64c918.png)

![image](https://user-images.githubusercontent.com/68370376/135503980-1be62a18-4cf4-42dc-a51a-66edd2062677.png)

![image](https://user-images.githubusercontent.com/68370376/135504064-51b03d4b-f297-4ba9-80d8-4126cc5d34fe.png)

![image](https://user-images.githubusercontent.com/68370376/135504112-7fc5f3ab-fdbf-45e7-a4be-c7986c7e6e51.png)

The following images of sample dataset to be tested: X_test[0,1,2]
![image](https://user-images.githubusercontent.com/68370376/135504537-54b0565b-64ed-4387-8a17-22a91848737f.png)

Model A predicted
![image](https://user-images.githubusercontent.com/68370376/135504854-e971eb59-3e0a-4480-92b9-880f542e3648.png)

Model B predicted
![image](https://user-images.githubusercontent.com/68370376/135504922-09b18fd5-2055-41e0-a855-c42a7f98c4f9.png)


