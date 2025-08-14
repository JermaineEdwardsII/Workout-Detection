This is my project "Workout-Detection". My project detects the workouts: push-up, sit-up, plank, lunge, and jumping-jack.<br>
To start the detection use the code <br><br>
imagenet.py --model=$NET/resnet18.onnx --input_blob=input_0 --output_blob=output_0 --labels=$DATASET/labels.txt $DATASET/test/(workout)/(the photo) test_workout.jpg.<br><br>
for example, if you want to test jumping jack 1 you would put <br><br>
imagenet.py --model=$NET/resnet18.onnx --input_blob=input_0 --output_blob=output_0 --labels=$DATASET/labels.txt $DATASET/test/jumping_jack/01.jpg test_workout.jpg.<br><br>
<img width="2395" height="1448" alt="image" src="https://github.com/user-attachments/assets/62302e63-da87-4b55-a13b-c52a90b93d96" />
