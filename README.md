# netset
A big and human-curated dataset over all topics, including separation of difficulty levels. English.

## IMPORTANT
A concept I have in mind is that besides on making a good output example, you also would like to make a output that explains why the prior output is like that.
For example, if the model is teached to explain how a bootloader works, then you might want to make the model to respond this question:
"Explain what you had in mind while making this explanation"
this way, the model will KNOW what is a good output and WHY, capturing details. 
So the model can respond:
"First of all, I assumed you knew the basics of a computer, such as what is a CPU, since no one who knows nothing about computers would make that level of question.
So assuming what you probably already knows, I started to explain the concept from the beginning; that's why I stated that "the BIOS -- which is the first
code that the CPUs execute -- ..." [...]

So, if you want to contribute with this dataset on the teaching part of it (it is, when the model must explain something to the user like a teacher), please try to do that after
the explanation.

## THE STYLE OF THE DATASET

I use the following to divide the dataset:
<!input!> and </!input!> -- opens and closes an input.
<!output!> and </!output!> -- opens and closes an output (model's expected output for training).
<comment> -- used in the top of all .txt files to tell something important about that specific file.
for datasets that does not have input-output (so they are based on text completion), it's used the flag <TEXT_COMPLETION> at the beginning of the text file.
