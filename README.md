# InstagramClone
In this app , i tried to develop a clone of Instagram. Let's see together !

Firstly, I started learn Google Firebase and created a new project. I configured a connection between my app and firebase. Firebase gave me a .json file and i implemented it to my project.
When the settings are done , I was gonna see the members and posts in Firebase Dashboard.
(For security i deleted .json file in the project.)


![members](https://user-images.githubusercontent.com/54797582/177054995-3dec5334-1b54-4fad-9a3f-9e19a0dbe7ab.png) 
![posts_folder](https://user-images.githubusercontent.com/54797582/177054999-b94c0184-e29e-42b7-98d4-4485010f4d3d.png)

Then I started to design user interface. 

![giris](https://user-images.githubusercontent.com/54797582/177054804-2b5765b3-6a12-4beb-a713-e635c1919baf.png)

I used RecyclerView in my feed page. Bottom of the feed page, There are two buttons. New photo and quit buttons. If you press the new photo button, the upload page is opened. And when the user sign in again, the app downloads the photos with picasso library.

![feed](https://user-images.githubusercontent.com/54797582/177055124-f374ea19-43a2-45b4-b2c2-1fbf51f70771.png)

In the Upload Page, i used uses permissions. In the first time you upload a new photo , app ask you for permission.

![permission](https://user-images.githubusercontent.com/54797582/177055186-d77a5a68-46a6-426b-af80-0f85f61c58b1.png)![upload](https://user-images.githubusercontent.com/54797582/177055226-6c750eab-b5f6-4ccf-b478-c507d8ee4db0.png)

Moreover, I used a date filter in firestore. (orderBy("date", Query.Direction.DESCENDING)) When the users upload a photo, the app shows the latest photo at the top.

Thanks for reading :)




