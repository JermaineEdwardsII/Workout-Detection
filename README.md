This is my project "Workout-Detection". My project detects the workouts: push-up, sit-up, plank, lunge, and jumping-jack.
To start the detection use the code 
imagenet.py --model=$NET/resnet18.onnx --input_blob=input_0 --output_blob=output_0 --labels=$DATASET/labels.txt $DATASET/test/(workout)/(the photo) test_workout.jpg.
for example, if you want to test jumping jack 1 you would put 
imagenet.py --model=$NET/resnet18.onnx --input_blob=input_0 --output_blob=output_0 --labels=$DATASET/labels.txt $DATASET/test/jumping_jack/01.jpg test_workout.jpg.
