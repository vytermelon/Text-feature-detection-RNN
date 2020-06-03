# Text-feature-detection-RNN
This notebook extracts messages from a whatsapp chat and isolates messages of the person whose textual behaviour is to be predicted.

After it isolates the messages, the transforms it into a form which can be inputted to the character level rnn model, which feeds its previous hidden state into each next step. After Training the model (say 50 epochs), you start to evaluate the model with an input string(say 'hello'). The model predicts the next sequence of character given the previous character and identifies the person's textual behavious. In my example there were accurate displays of emojis and sudden capitalization of letters as done by the person.

