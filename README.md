# Capstone-Project
The following steps were done to generate python code for the given statement
    Dataset has around 4600 python programs with statement
    Every program statement begins with # symbol, then follows code
    Apply preprocessing for the special characters like :, indentation, function beginning and end
    split the data using # symbol
    move statement to Title and remaining to target code
    created customized embedding vector for special characters using Word2Vec model
    set max_length in encoder as 100 and 400 in decoder
