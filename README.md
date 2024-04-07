# Neural_Style_Transfer_Image_Processing_Project
Abstract

 Neural image style transfer is an optimization technique that takes two images- a content image and a
 style reference image (such as an artwork by a famous painter) and blends them so the output image
 looks like the content image, but “painted” in the style of the style reference image. Neural style
 transfer is a growing topic of research. It is currently being used in diversified domains like gaming,
 virtual reality, photo and video editors, and art. We aim to implement 2 approaches: Gatys style
 transfer [1] and Fast style transfer [2] for neural image style transfer leveraging advanced image
 processing and machine learning techniques. With these implementations, we plan to thoroughly
 analyse and compare the efficiency and effectiveness of both approaches.
 
 #Project Specification
 
 Neural Image Style transfer : Given two images namely, content image and style reference
 image,create a visually appealing image as output that retains the recognizable content of the original
 but incorporates the stylistic elements of a reference image. More formally,given a content image C
 and a style image S, the objective is to generate an image G that retains the content of C while
 adopting the visual style of S. It involves finding the optimal pixel values for G, using techniques like
 gradient descent, in such a way that a predefined loss function, which combines content and style
 losses, is minimised .The final output is an optimised image that preserves the content of the content
 image while adopting the style characteristics of the style image.
 Mathematically, it involves finding the generated image G that minimises the loss function:
 LTotal(G)=αLcontent(C,G)+βLstyle(S,G) [5]
 LContent(C,G) measures the content difference between C and the generated image G.
 LStyle(S,G) measures the style difference between S and the generated image G.
 α and β are hyperparameters that control the relative importance of content and style in the generated
 image.
 We explore 2 approaches : Gatys style transfer and fast style transfer. We also aim to provide insights
 into the strengths and limitations of each approach, enabling informed decision-making for selecting
 the most suitable method based on specific requirements and constraints.
