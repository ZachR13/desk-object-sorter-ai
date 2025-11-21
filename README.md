# desk-object-sorter-ai
AI Foundations Lab- Computer Vision

This project uitilizes Google Teachable Machine to idientify common objects you might find on a students desk. Unfortunately I am out of town and not at a desk so I completed most of this lab at the airport. However I did inlcude common objects you would find on my desk at home at anytime.

## Classes Identified
List the objects your model was trained to identify:
* Class 1 Vitamin Water Bottle (Hydration)
* Class 2 Dot's Pretzels(Brain Food)
* Class 3 Apple Airpods(Distraction Preventers)


## Discussion & Reflection
*(Please answer the following questions thoughtfully)*

1.  **Model Performance & Iteration:**
    * How accurate was your first trained model? Very accurate. I was impressed how quick the model was able to train with the amount of images proivided.
    * What steps did you take to iterate and improve its performance? I added more images from different angles and distances from the camera. By doing so I was able to increase the accuracy of the model. 
    * How did these changes affect the model's accuracy and confidence scores? Dramatically increased to 100% or very close to it even when the label or an obvoius idenifying factor was not visible. 

2.  **Challenges & Observations:**
    * Which objects were the easiest for your model to learn and distinguish? Why do you think that was? The Vitamin water bottle. I think its distinct shape and colors made it easier for the model to detect. 
    * Which objects were the most challenging? What made them difficult (e.g., similar shapes, variable appearances)? The apple airpods. They are smaller and only white in color. I think it was harder to identify in the images. 
    * What happened when you showed the model an object it wasn't trained on? How did the confidence scores behave, and why is this significant? The confidence scores dropped dramatically. Even like objects still dropped by 50-60 percent or more. 

3.  **Bias in AI:**
    * If you only trained your "mug" class with images of *your specific mug* (and didn't vary color, shape, etc.), how well do you think it would recognize other students' significantly different mugs? How does this illustrate the concept of bias being introduced through training data?
    * Imagine all your training images were taken in very bright, direct lighting. What might happen if you tried to use the model in a dimly lit room or with strong shadows? How does this relate to the robustness and potential biases of AI models?

4.  **Model Limitations & Usefulness:**
    * What are some key limitations of the model you created?
    * Why is it useful to be able to download your trained model files (like `model.json`, `weights.bin`) and share them (e.g., via GitHub)? What does this enable?

5.  **Real-World Applications & Ethics:**
    * Brainstorm 2-3 real-world applications where a similar image classification model could be useful.
    * Briefly discuss one ethical consideration that developers should keep in mind when building and deploying image recognition AI in the real world (e.g., related to fairness, privacy, misuse).

## (Optional) Challenges Faced / Interesting Discoveries
* Add any other specific challenges you encountered or interesting things you discovered during this lab.

## (Optional) Screenshot
* You can embed a screenshot of your Teachable Machine interface here if you like.
