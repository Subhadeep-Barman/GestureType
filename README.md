# GestureType
Introducing the revolutionary new lens - a game-changer for blind people and sign language learners alike! With this lens, you can type words automatically simply by showing your sign language.

https://drive.google.com/file/d/1600Ddu_jo30aggX1zQnOB9bTY94j7H_X/view?usp=share_link 
Drive link for project.data file Please download this from drive and upload it to the same folder to run the project

Inspiration
One fine day I went for a charity run, and I met one of my dearest friend who was born disabled. She always looks at her fellow friend busy on social media but can't find herself attached, so I decided to build something that can make her feel included through social media. It has been developed by using machine learning to classify various hand motions into American Sign Language in real time. This lens not only provides accurate and precise transcriptions but also displays the text in augmented reality, enhancing the user experience. With the added convenience of being able to toggle live predictions on and off simply by tapping the screen, this lens serves as a valuable tool for bridging the communication gap between hearing and deaf individuals.

What it does
The proposed lens aims to make content creation more accessible for the deaf community by transcribing American Sign Language in real time. It will help bridge the communication gap and empower individuals with a new way to express themselves without the need for captions. Additionally, the lens can also serve as a valuable tool for those learning ASL by providing real-time feedback and improving their sign language skills. The lens is a novel solution to a long-standing challenge, and its potential to change the lives of those who use it is immense.

How we built it
This lens was built using Lens Studio and Javascript. A machine learning model was created incorporating transfer learning and image augmentation using the MobileNetV2 architecture from Tensorflow Hub and the American Sign Language dataset. The model was fine-tuned using Tensorflow and Keras API and had a final validation accuracy of 92%.

Challenges we ran into
The challenges that we ran into were: • Model performance was not up to the desired standards due to limitations of the device's processing power and memory capabilities, leading to slower inference speeds and lower accuracy. • Integration of the model into the AR lens required a lot of optimization and fine-tuning to ensure smooth performance on mobile devices. • Maintaining and updating the model to keep up with sign language changes and improve recognition accuracy was a continuous challenge. • Getting the lens to work on a wide range of devices with different processing power and memory capabilities was challenging due to compatibility issues. • Achieving higher accuracy and reducing overfitting by using advanced techniques like Transfer Learning and Fine-Tuning. • Developing a highly scalable and efficient application by utilizing cloud computing and big data technologies. • Developing a user-friendly interface and making the application accessible to non-technical users. • Integrating various APIs and integrating the model with other systems. • Receiving positive feedback from users and making a real-world impact with the model

Accomplishments that we're proud of
Building an app that helps typing-disabled people type using hand gestures is a proud accomplishment. The app, called the "Gesture-Type," allows people with disabilities to participate in social media and express themselves in new ways. Not only does it provide a solution for the disabled community, but it also serves as a tool for others to learn and understand the challenges faced by the disabled. By creating this app, you have made a positive impact on many people's lives and have helped to promote inclusivity in technology.

What we learned
Things that we learned are: • Transfer Learning and Fine-tuning • Building and Training Convolutional Neural Networks • Using Pretrained Models such as ResNet, Inception, VGG and more • Hyperparameter Tuning and Regularization Techniques • Understanding and Visualizing Convolutional Neural Network Models. • Using sign language

What's next for Gesture Type
The next version of Gesture Type will have:

Integrating this lens into much more disabilities exist
Expand this idea from the lens to other platforms so that it reaches every interested people
Creating a more extensive database so that we can test and train the model more accurately
