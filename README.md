# Dream House Project
## CS 4331-002 - Mayur Bhakta
Project to design and create our dream house, we are allowed to use 3D models or create our own models for the house and include decorations.

## Libraries Used
- aframe.min.js
- sky.js
- sunSetter.js
- aframe-extras.min.js

## Description
- The application is written in HTML, JavaScript, and A-Frame.
- A plane with a texture of grass was implemented to make a base for the floor and the house, on top of that an entity with the geometry of a box and given a texture of a floor was implemented to create the base of the house.
![pic1](https://user-images.githubusercontent.com/32318210/36348669-adf03706-143a-11e8-979e-a61f43004f6c.PNG)
- To create walls, a-box tag was used and also it was given specific attributes to sorround the floor, and it was also given a texture.
![pic2](https://user-images.githubusercontent.com/32318210/36348679-e8068788-143a-11e8-82ef-51b3e0d81d6a.PNG)
- The ceiling of the house was created by using the a-entity tag with a geometry of a box and given specific attributes and texture.
![pic3](https://user-images.githubusercontent.com/32318210/36348685-0ccf63b4-143b-11e8-9e2f-ecde9596a5e1.PNG)
- An animated sky was added using the libraries sky.js and sunSetter.js, the animation of the sky was given using the a-animation tag and providing the initial and final sun position, duration of the animation, and repetition.
![pic4](https://user-images.githubusercontent.com/32318210/36348695-299c53e4-143b-11e8-92c8-336750981ea8.PNG)
![pic5](https://user-images.githubusercontent.com/32318210/36348702-5d8a9cb0-143b-11e8-9583-fc7e930bd200.PNG)
- To decorate the house, gLTF models were used to fill the house, and they were loaded using a-gltf-model tag with appropiate attributes such as, position, rotation, scale, etc. Also each model is not larger than 500kb for mobile run efficiency.
- Below are the links for each of the models used in this project.
### Bedroom
- Bed: https://sketchfab.com/models/715fd6855bf7437e8e239ee541a7c2e8
- TV Stand: https://sketchfab.com/models/65b67b81ee194c5b961fdeb892f5c07e
- TV: https://sketchfab.com/models/014e75456b4e465b9cecd1b136a0312b
- Shelf: https://sketchfab.com/models/9fc806334b614607be1b93d5f3bf2238
### Living Room
- TV: https://sketchfab.com/models/cc1d40351d294f6d99ee12dbd852c17c
- TV Stand: https://sketchfab.com/models/717f80d4995c42df920f03438504dce5
- Sofa: https://sketchfab.com/models/fd5ac2451ba84893a44740d3399d7629
- Coffee Table: https://sketchfab.com/models/6e30dab18dc84a1e9a198dae52bf7592
- Dinner Table: https://sketchfab.com/models/5430ef6f11f54c4a937cad8d8092e56d
- Door: https://sketchfab.com/models/392010964cb74d54a068be4dead348ac
### Office Room
- Bookshelf: https://sketchfab.com/models/b8f46cf7daca419a87ac8d131bad056f
- Desktop: https://sketchfab.com/models/4643d59bf4dc4ffb8e000167d257d589
- Poster: https://sketchfab.com/models/cf6fe6a27d5f4413a0479a200884b08a
- Desktop Chair: https://sketchfab.com/models/3177fdf2630c4922a43fecb876d96e1d
- Extra Table: https://sketchfab.com/models/b782be2e0040478da98d24910cb078a6

## Interactable objects
- Added action to the house door so when the user click the lock then it will open or close. Used a gltf model for the door, and wrapped the lock section with a box, then created a fuction which when called changes the position and rotatior of the door.
![pic6](https://user-images.githubusercontent.com/32318210/36348727-f86d781a-143b-11e8-861f-89b693172016.PNG)
![pic7](https://user-images.githubusercontent.com/32318210/36348726-f85ca706-143b-11e8-8d15-4a226803b3c6.PNG) 
- Added sound to the CPU in the gltf model located in the office room, also wrapped the model in a box so when it is clicked it will trigger Windows XP Startup sound.
- Added a switch for the light using boxes so the user has control over it, when the switch is clicked a function for the light will be called each time it is clicked the intensity of the light will change, in this case the function only has four levels of intensity, which allows the user to have control over the light in the environment.
![pic8](https://user-images.githubusercontent.com/32318210/36348760-7eb4605a-143c-11e8-9b08-70185b338950.PNG)
![pic9](https://user-images.githubusercontent.com/32318210/36348761-7ec3a312-143c-11e8-8f2b-f4e195fa4b25.PNG)
![pic10](https://user-images.githubusercontent.com/32318210/36348758-7e94382a-143c-11e8-9416-a3848edc5b0f.PNG)
![pic11](https://user-images.githubusercontent.com/32318210/36348759-7ea4d342-143c-11e8-8f5f-9f7fc8ba023e.PNG)
- Added text to each of the interactable objects in the application so the user knows which objects can be clicked.


