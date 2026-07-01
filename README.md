# Double-Sided Tea Kettle
## CAD model of a double-sided kettle, allowing it to cook tea through steam (convection) rather than utilizing a hot surface (conduction). Model is tailored towards an additive manufacturing process. FreeCAD was the choice of software for this project.


### Motivation
This project is dedicated to my grandfather, an inventor with many patents, one of which is this kettle. He believed that a cooking method that uses convection infuses a richer taste in tea compared to the standard conduction method. My goal here was to design a 3D CAD model of a kettle that would allow steam to pass from a body of water to a body of tea, cooking it in the process.

### Initial CAD Model
<img width="527" height="517" alt="Screenshot 2026-07-02 000538" src="https://github.com/user-attachments/assets/59c49e9f-5e53-47d9-b460-16cd94543251" />

This was my first version of the kettle. When I was first creating this model, I didn't give much thought to optimising my design for additive manufacturing like 3D printing. I later learned the hard way the importance of respecting the manufacturing process during design. The problem with this model was that it was broken down into four parts: water body + spout, tea body + spout, lid and handle. Treating the body and spout as one unit made manufacturing difficult. I also didn't design this model to use supports.

### Final/Improved CAD Model
<img width="364" height="395" alt="image" src="https://github.com/user-attachments/assets/be332fc9-00b6-4e0e-839c-bf9f54c28999" />

This was my final version. I split the model into 6 parts: water body, water spout, tea body, tea spout, lid and handle (note: this version has a handle attached to the side of the water body, unlike that of the initial design which has a handle over the lid). By splitting the water/tea body and spout into 2 separate parts, manufacturing became easier as the printing path became realistic. (Note that, in the model, the handle is displaced slightly in order to show the two holes in the water body for the handle)

Another change to this design was the addition of supports, an incredibly useful feature for an additive manufacturing process like 3D printing. Examples of supports are below (orange is the main print, green is the support):

<img width="895" height="626" alt="Screenshot 2026-07-01 150159" src="https://github.com/user-attachments/assets/8d9c8470-61ed-4072-8cef-16e4c073d767" />
<img width="843" height="425" alt="Screenshot 2026-07-01 102334" src="https://github.com/user-attachments/assets/7b79f3ff-2b23-4073-8643-57f3d5940065" />
<img width="892" height="629" alt="Screenshot 2026-07-01 102041" src="https://github.com/user-attachments/assets/a8e2d7e8-a890-4bd7-b480-bcee79b93186" />
<img width="786" height="456" alt="Screenshot 2026-06-30 195510" src="https://github.com/user-attachments/assets/91602b0f-c6b6-4752-8ed8-dbf51f81c98d" />

I also 3D printed a couple of these parts for proof of concept:

<img width="4032" height="3024" alt="IMG_3832" src="https://github.com/user-attachments/assets/d81e2559-714c-41b3-b4a2-fbaa3c755043" />
<img width="3520" height="1980" alt="IMG_3807" src="https://github.com/user-attachments/assets/f60de4a1-b897-41db-9910-9a59ba2a2b37" />


### Limitations
Although my design was sufficient enough to support additive manufacturing, creating a stainless steel tea kettle fundamentally requires a subtractive manufacturing process like CNC machining. In the future, I plan on creating a similar version of this kettle that would allow for a subtractive process using stainless steel, making the kettle a usable product.
