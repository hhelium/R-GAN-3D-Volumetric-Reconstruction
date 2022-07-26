# R-GAN-3D-Volumetric-Reconstruction
Getting 3D volumetric information for an object is essential in applications ranging from autonomous manufactur- ing to robotic scene perception. In order to get 3D volumetric information for an object, RGB-D sensors are widely used to capture depth information. To reconstruct 3D volumetric infor- mation of an object, this paper designed an extended generative adversary network (GAN) with a recurrent generator. The model can take a single or a sequence of depth scans of an object to reconstruct the 3D volumetric model of the object. In precise, 3D long short-term memory (LSTM) units that are employed in the generator can extract features from the sequence of depth scans in different time steps. The reconstructed results of the proposed model are evaluated by calculating intersection over union (IoU) in both 3D space and 2D projection. The model achieved 77.71% in IoU, 80.08% in hit rate, and 97.45% in accuracy, which outperformed other methods.
<img src = "./images/title_image.png">
Some 3D Reconstruction Results are shown below. 
#### Brake ####
https://user-images.githubusercontent.com/63925943/180903724-04e577f8-52ce-4fea-83b1-82fbd94270be.mp4
#### Fastener ####
https://user-images.githubusercontent.com/63925943/180903747-081fc3ea-cba0-48c3-ad8b-035bf1ea1e73.mp4
#### Handle ####
https://user-images.githubusercontent.com/63925943/180903769-ce2853a3-ec9e-42d7-9f13-18a6037c042b.mp4
#### Linear ####
https://user-images.githubusercontent.com/63925943/180903797-68288c87-eeaf-484b-b2f5-a410b386cd1b.mp4
#### Power Transmition ####
https://user-images.githubusercontent.com/63925943/180903827-c90314bc-1ab6-4e0a-84e7-7b979f2b07bd.mp4
#### Sealing ####
https://user-images.githubusercontent.com/63925943/180903846-cb103abb-8c26-42e9-9985-af67793e3ae5.mp4

Reconstructed 3D Models are availabes in ./3D Models







