imgElement.src = aiGeneratedImg;

        //When the image is loaded, remove the loding class
        imgElement.onload = () => {
            imgCard.classList.remove("loading");
        }


        illustrate a cozy cabin in the snowy mountains


        updateImageCard([...data])

         if(!response.ok) throw new Error("Failed to generate images! please try again.")

          


        const updateImageCard = (imgDataArray) => {
    imgDataArray.forEach((imgObject, index) => {
        const imgCard = imageGallery.querySelectorAll(".img-card")[index];
        const imgElement = imgCard.querySelector("img");

       //Set the image source to the AI-generated image data
        const aiGeneratedImg = `data:image/jpeg;base64,${imgObject.}`;
        
    });
}