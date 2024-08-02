To test the model, you should:
1. Install python 3.12.
2. Pip install all required libraries specified in the "requirements.txt".
3. Find the "example_captions.txt" file under "using detectron 2/data/birds", where you can input customized captions for generating bird images.
4. Type your descriptions in the file "example captions.txt" and save it.
Because the training data is limited for training efficiency, not all discriptions can always generate meaningful outputs. Hence we recommend you to use the following captions for testing.

-- example captions:
"This bird has wings that are blue and black and has a red belly"
"The bird has wings that are blue and has a red belly."
"The bird has wings that are black and has a white belly."
"The bird has wings that are grey and a yellow belly."
"This bird is black and white and has a very short beak."
"This bird has a red crown with grey wings."
"This bird is yellow with a short beak and a long tail."

5. Type the following command in the command line to run the evaluation: "cd code", and then "python main.py --cfg cfg/eval_bird.yml --gpu 0".
6. You can view the 5 groups of generated results under "using detectron 2/models", there will be a new folder named "netG_epoch_200" created to store the results.


