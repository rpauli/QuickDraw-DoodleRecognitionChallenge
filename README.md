# QuickDraw-DoodleRecognitionChallenge

The challenge provided a dataset of doodles from Quick Draw! with their respective labels.
My approach was to use a standard deep learning architecture as the resnet18 and initially use just grayscale images.
I later ssitched to the color coding used in this kernel. I encoding the stroke velocity in yello and used Red and green channels to encode the succession of paintbrush strokes, i.e. first stroke is red last ons is green and rest inbetween.

This kernel still uses fastai 0.7.0 so alot of adjustments of the pytorch code and the dataset format I had to do are now absolete because most of it comes wit hthe newest version. 

I currently get 0.87 score, which is not high but I think it should be easy to improve my approach.
For now the runtime of 9hrs on kernels is the main bottleneck, I can currently train 12 cycles with 5k images per category.
