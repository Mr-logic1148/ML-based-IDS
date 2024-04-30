How to run the live intrusion detection code:
You would require the following resources to run the code which is:
* Jupyter Notebook installed (and running using admin permissions).
* Tensorflow and Keras installed.
* Npcap installed.
* And to make sure that malicious traffic is going through the network (ONLY FOR LEARNING PURPOSES) turn off the firewall.
* Lastly, put the given model and live intrusion detection code in the same folder so that the code detects the model while loading the model.
And these are all the resources required. Now, follow the below steps to run the code:
Step 1:
Open the code in a jupyter notebook environment. Check if all the libraries are installed if not then do that first. And then run the cell for headers files.
Step 2:
And then run the next block which has the conversion of label-encoded attack types in the dictionary. This is necessary because the pop function won’t be able to give pop as the attacks were never reversed from the label encoded form.
Step 3:
Run all the functions present which will ensure to ask for user consent and the IP address of their system with their permission and run the feature extraction and model prediction function for appropriate network traffic extraction and accurate predictions.
Step 4:
Before running the last block make sure that the model is in the same folder as the code or else it will produce an error.
Step 5:
After running the last block of code, it asks for user consent first if it doesn’t ask, please do not proceed further. If it does, then follow what it says, and after a couple of steps, it will begin to extract network traffic and look for any intrusions.

And this is how you can run the live intrusion detection code.

