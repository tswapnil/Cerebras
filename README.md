README - 

I chose to abstract The network creation by introducing Layer Class. 
In addition, I also separated the Script Executor() (script to run the code and evaluate the results)
and the class for UnitTesting the helper methods of OilSpill().

Layer() class to randomly initialize the weights .
OilSpill() class has the methods required for training the MLP .
Executor() has the script to read MNIST csv file , preprocess the inputs (Normalize) and then call the training procedure of OilSpill
TestOilSpill() has the unit tests for the helper methods of the OilSpill object. 

When trained on a dataset of 20,000 data points and validated on 500 elements , maximum 95.6 % accuracy is achieved. 
Following shows the accuracy on validation set after every 10 epochs . 

accuracy is 0.91 - hits 455

accuracy is 0.936 - hits 468

accuracy is 0.946 - hits 473

accuracy is 0.952 - hits 476

accuracy is 0.956 - hits 478

accuracy is 0.954 - hits 477

accuracy is 0.954 - hits 477

accuracy is 0.954 - hits 477

accuracy is 0.954 - hits 477

accuracy is 0.956 - hits 478

accuracy is 0.958 - hits 479

accuracy is 0.958 - hits 479 

Following are the results on test Data Set - 

accuracy is 0.9481
hits 9481

accuracy is 0.9556
hits 9556

accuracy is 0.9595
hits 9595

accuracy is 0.9608
hits 9608

accuracy is 0.9624
hits 9624

accuracy is 0.9636
hits 9636

accuracy is 0.9643
hits 9643

accuracy is 0.9648
hits 9648

accuracy is 0.9647
hits 9647

accuracy is 0.9652
hits 9652

accuracy is 0.9658
hits 9658

accuracy is 0.9655
hits 9655

