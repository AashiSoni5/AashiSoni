Animal Classifier for Wildlife Enthusiasts by Aashi Soni

These are the steps by which i made the animal classifier for wildlife enthusiasts that identifies different species of animals from photos;useful for wildlife tracking which can beintegrated into a real-time wildlife monitoring system thatprovides instant species identification:-

I began by categorizing the wildlife into five major classes: reptiles, mammals, insects, birds, and marine animals. Each class was further divided into specific species to ensure a diverse dataset that captures various characteristics within each group. This step was essential to give the model a broad perspective on different types of wildlife.

I used Google Images to find high-quality photos representing each species. I aimed for a 100 images per species as was mentioned in the project, I prioritized images with varying angles, lighting, and backgrounds to ensure the dataset was diverse. I also filtered out any images that were low quality, duplicated, or contained multiple species, as these could confuse the model

Once I gathered the images, I organized them into folders based on their class (e.g., reptiles, mammals). Within each class folder, I created subfolders for each species. This systematic organization allowed me to label the data accurately when uploading it to the Teachable machine for model training. Precise labeling is crucial as it directly influences the model's ability to distinguish between different species.

Then I uploaded it to Google Teachable Machine, where I manually assigned each species to its respective class. Teachable’s user-friendly interface streamlined the process, allowing me to focus on refining the model. I configured the model to prioritize accuracy and enabled additional training cycles to improve precision in detecting subtle differences among species.

How Google’s Teachable Machine was used to create the model

To create a wildlife detection model, I started by collecting images of various species from Google, organizing them into folders based on categories like reptiles, mammals, insects, birds, and marine animals. This structured approach allowed me to efficiently manage the data and prepare it for training.

Next, I utilized Google’s Teachable Machine to develop the model. I uploaded each set of categorized images into Teachable Machine, assigning them to corresponding classes. This platform enabled me to train the AI on visual patterns unique to each category, such as the scales on reptiles or the wings of insects.

The process was streamlined and user-friendly, making it easy to transform raw data into a fully functional detection model.

Features and functionalities integrated into the model

Multi-Class Classification: The model is designed to recognize and differentiate between multiple wildlife categories, such as reptiles, mammals, insects, birds, and marine animals, based on unique visual patterns.

Real-Time Detection: Integrated real-time detection allows the model to classify images or live video feeds instantaneously, providing immediate feedback on the species present.

User-Friendly Interface: Using Google’s Teachable Machine, the model benefits from a straightforward, accessible interface. This ensures that even users with minimal technical experience can operate it and interpret results easily

Methods Used to Evaluate the Model’s Performance

Accuracy Testing: By using a test set of images, I measured the model’s accuracy in correctly classifying different species. I compared the model’s predictions with the true labels to gauge its precision.

Real-World Testing: I tested the model in a simulated real-world setting, using images outside the training set. This allowed me to evaluate its ability to generalize to new, unseen data.

Explain how the model can be applied to solve practicalproblems or enhance real-world applications.

Wildlife Conservation and Monitoring: The model can be deployed in nature reserves or wildlife sanctuaries to monitor animal populations. By analyzing images or videos from camera traps, it can automatically identify and catalog species, track their movements, and alert conservationists to any unusual activity or presence of endangered species. This enhances conservation efforts by providing accurate, real-time data on wildlife, which is crucial for making informed decisions on habitat protection and species preservation.

Agricultural Pest Control: In agricultural settings, the model can help identify pests that threaten crops by analyzing images from field cameras or drones. Early detection of specific insects or animals known to damage crops allows farmers to take targeted actions to prevent infestations. This reduces the need for widespread pesticide use, leading to more sustainable farming practices and better crop yields

Here are some screenshots of the process and the project:-

![Screenshot (2262)](https://github.com/user-attachments/assets/7399ba3f-e3d5-4075-8560-0143215fb747)

![Screenshot (2263)](https://github.com/user-attachments/assets/7dcad48b-ba59-456d-98b5-4610344cfd96)

![Screenshot (2264)](https://github.com/user-attachments/assets/ea05181f-dee9-4918-b236-37b0c7e4f3aa)

And here's the link of the model:-
https://teachablemachine.withgoogle.com/models/[...]

Dataset links:-
https://drive.google.com/drive/folders/1usqus4qXT393px-G3wiX5ZM_kjC76Eun?usp=drive_link

https://drive.google.com/drive/folders/1jLj54ITXShxVaahr2xnQ6O-6bHbBFQ26?usp=drive_link

https://drive.google.com/drive/folders/1rdVrvwRaAEKWSrro4EX5OWlrUiyvHKVq?usp=drive_link

https://drive.google.com/drive/folders/1_cMmiq__ETtNoYSyoHDoCvMZpJIVU7a0?usp=drive_link

https://drive.google.com/drive/folders/18bE-MlfTs55yMINK4ouawUVLPfopwHXe?usp=drive_link
