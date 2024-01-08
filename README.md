This is a fork of RVC that allows models to be trained on Paperspace.

Usage:

1. Clone this repository into the Paperspace machine
2. Navigate into the cloned folder and run 'make install' in the terminal. This step will need to be run every time the machine is restarted.
3. Run 'make basev1'
4. Run 'make basev2'
5. Run 'pip install protobuf==3.20' -- i'll fix this issue eventually
6. Run 'make run-ui' and use the gradio URL as normal
6a. If you want to use Tensorboard, in a separate terminal run 'make tensorboard' 