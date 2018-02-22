# DeepTesla End-to-End Steering Model

This project showcases some of the Convolutional Neural Networks (CNNs) that can be used to model End-to-End steering from a dash-mounted camera.  The models run on MIT's [DeepTesla site](https://selfdrivingcars.mit.edu/deeptesla/), which allows for fast iteration and good visualization of the model during training


### Prerequisites

All training is done in the web browser so all that is required is a modern browser (Chrome, Firefox, etc.).  These examples were tested on both Firefox and Chrome


### Use

To experiment with one of the included networks, copy the text from the respective file in the 'Models' directory onto MIT's [DeepTesla site](https://selfdrivingcars.mit.edu/deeptesla/) and select 'Restart Training'

### Analysis

While the DeepTesla site enables one to dive straight into developing and visualizing a model, the predicted results can use improvement.  The biggest challenge appears to be that my model is not sufficiently turning the wheel, even in a turn.  This may be a reflection of the training dataset, where (like most normal driving), the wheel is usually centered.

To overcome this issue and explore greater functionality, I am building another model in Keras/TF

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* README template courtesy of Bille Thompson - [PurpleBooth](https://github.com/PurpleBooth)

