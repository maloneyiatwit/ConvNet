# ConvNet

Assesment 1

  What is your MSE/MAE with linreg vs tuned network?
  
    MSE with linreg : 24.29
    
    MSE with tuned net : 9.93
    
  What happens to your train and test results if you add 5 hidden layers with 128 neurons each?
  
    The performance of the model improves greately, but the runtime drasticlly increases
    

Assesment 2
  
  What is a response layer? (Give a brief, 1-sentence description)
  
    The response layer is the filtered layers after convolution.
  
  Given the filter shape of (26, 26, 32), what does each number represent?
  
    First two being dimensions (Height and Width) third being the amount of filters
  
  Given 6x6 input and filter of (3,3): what is the response shape that we get? 
  
    4x4
  
  Given (33, 33, 1) input and filter of (2,2): what is the response shape that we get? 
 
    32x32
  
  What is the difference between ‘valid’ and ‘same’ padding? Given 6x6 input and filter of (3,3), what are the response shapes for both options? 

    Valid: padding disabled
    Same: output size will be made equal to input
    
    Valid Shape: 4x4
    Same Shape: 6x6
    
    
 Assesment 3
  
  What is max pooling? (Give a brief, 1-sentence description)
  
    Aggresive Down sampling, ie : pulls maximum within window size, reduces parameters
  
  If I apply pooling of 2 (2,2 window with a stride of 2) to a (6,6) array, what is the resulting size?
  
    3x3
