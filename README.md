# Ex04 Places Around Me
## Date: 14.12.2025

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google.

### STEP 3
Using ```<map>``` tag name the map.

### STEP 4
Create clickable regions in the image using ```<area>``` tag.

### STEP 5
Write HTML programs for all the regions identified.

### STEP 6
Execute the programs and publish them.

## CODE
```
urls.py
from django.contrib import admin
from django.urls import path

urlpatterns = [
    path('admin/', admin.site.urls),
]


upperlake.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>UPPERLAKE</title>
</head>
<body>
    <IMG SRC="Upper Lake View is a famous tourist attraction in….jpeg"HEIGHT="600"WIDTH="368">  <IMG SRC="Upper Lake View.jpeg"HEIGHT="600"WIDTH="368">
    <h2>UPPER LAKE</h2>
    <h3>LOCATED IN KODAIKANAL</h3>
    <p>
        Kodaikanal's Upper Lake View is a famous, free viewpoint offering stunning panoramic vistas of the star-shaped Kodai Lake, its lush surroundings, and the distant hills, ideal for photography, especially early morning, providing a tranquil escape with food stalls and crafts nearby, despite its name referring to a viewpoint overlooking the main lake, not a separate lake. 
Key Aspects:
The View: A bird's-eye perspective of the iconic star-shaped Kodaikanal Lake and dense greenery.
Best Time: Early mornings (before 8 AM) for calm, clear views and fewer crowds; daytime for bright photos.
Attractions: Photography, nature appreciation, serene atmosphere.
Amenities: Food stalls, local crafts, seating, easily accessible by transport.
Cost/Entry: Free entry, open during daytime hours (e.g., 10 AM - 5 PM, though viewpoints are often accessible longer).
Location: A short distance from Coakers Walk, often visited en route to Green Valley Viewpoint. 
In essence, it's a prime spot to capture the essence of Kodaikanal's beauty from above. 
    </p>
</body>
</html>


starlake.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>STARLAKE</title>
</head>
<body>
       <IMG SRC="A trip to Kodaikanal promises gorgeous views of….jpeg"HEIGHT="600"WIDTH="368"> <IMG SRC="Screenshot 2025-12-14 204819.png"HEIGHT="600"WIDTH="368">
    <h2>STAR LAKE</h2>
    <h3>LOCATED IN KODAIKANAL</h3>
    <p>
      Star Lake (Kodai Lake) in Kodaikanal is a famous, man-made, star-shaped lake in the heart of the hill station, built in 1863; it's a hub for activities like boating, cycling, and scenic walks, surrounded by lush greenery and offering peaceful, picturesque views, making it a key landmark for tourists and locals alike, especially popular for its tranquil mornings and stunning sunset backdrops for Bollywood films. 
Key Highlights:
Shape & Origin: A distinct, four-point star shape, formed by damming three streams.
History: Created by Sir Vere Henry Levinge, the Madurai Collector, to promote tourism.
Activities: Boating (pedal boats, rowboats), cycling around the lake, horse riding, and walking/jogging.
Scenery: Encircled by hills, flora, fauna, and charming boat houses, offering tranquil, cool weather.
Significance: A central attraction, featured in Bollywood films, known as the "heart of Kodaikanal".
Accessibility: Easily reachable from the town center, with no entry fee, open from early morning. 
    
    </p>
    
</body>
</html>

silvercascade.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SILVERCASECADE</title>
</head>
<body>
     <IMG SRC="Silver cascade Water falls, Kodaikanal.jpeg"HEIGHT="600"WIDTH="368"> <IMG SRC="Silver Cascade Waterfall__Waterfall in Tamil Nadu.jpeg"HEIGHT="600"WIDTH="368">
    <h2>SILVERCASCADE FALLS</h2>
    <h3>LOCATED IN KODAIKANAL</h3>
    <p>
        
      Silver Cascade Falls in Kodaikanal is a popular, picturesque 180-foot waterfall on the way to the hill station, formed by overflow from Kodai Lake, known for its silvery water, lush surroundings, photo opportunities, and street food stalls, offering a refreshing stop for tourists enjoying the ghat road journey
      Key Features & Details:
Height: Around 180 feet (55 meters).
Location: Along the Kodaikanal-Madurai Road, easily accessible from the main road.
Origin: The overflow from Kodaikanal Lake creates the falls.
Scenery: Features white, glistening water, rocky cliffs, and abundant greenery, often with rainbows visible.
Attractions: A designated viewing platform offers great photo spots, and visitors can find street food and local snacks nearby.
Access: Free entry; parking is available, but can be busy. 
Why Visit?
Photogenic Spot: Ideal for nature photography due to its stunning backdrop.
Quick Stop: A perfect place to pause, stretch, and enjoy the cool atmosphere during your drive.
Local Flavors: Enjoy fresh snacks and refreshments from the roadside stalls
    </p>
    
</body>
</html>

place.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>IMAGE MAP</title>
</head>
<body>
    <!-- Image Map Generated by http://www.image-map.net/ -->
<img src="Screenshot 2025-12-10 154700.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="SILVERCASCADE" title="SILVERCASCADE" href="silvercascade.html" coords="1015,426,45" shape="circle">
    <area target="" alt="STARLAKE" title="STARLAKE" href="starlake.html" coords="421,538,612,682" shape="rect">
    <area target="" alt="UPPERLAKE" title="UPPERLAKE" href="upperlake.html" coords="233,647,301,695" shape="rect">
</map>
</body>
</html>

views.py
from django.contrib import admin
from django.urls import path

urlpatterns = [
    path('admin/', admin.site.urls),
]

```

## OUTPUT
<img width="1919" height="1017" alt="image" src="https://github.com/user-attachments/assets/b7d04a41-87f9-4142-92c2-3871682f1f9b" />
<img width="1919" height="1014" alt="Screenshot 2025-12-14 205550" src="https://github.com/user-attachments/assets/bb1da90c-239e-4a11-89ef-32ba386b7caf" />
<img width="1919" height="1016" alt="Screenshot 2025-12-14 205816" src="https://github.com/user-attachments/assets/0713aa29-b1f0-426d-8378-8ce8722de048" />
<img width="1919" height="1016" alt="Screenshot 2025-12-14 210108" src="https://github.com/user-attachments/assets/54143966-6716-45cf-aa03-640ceb7f2de6" />










## RESULT
The program for implementing image maps using HTML is executed successfully.
