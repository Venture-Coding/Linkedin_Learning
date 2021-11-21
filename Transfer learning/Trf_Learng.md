## Transfer Learning ##

Transfer learning is a technique that focuses on storing knowledge gained while solving one problem and applying it to a different but related problem.   
For example, knowledge gained while learning to recognize fruits could apply when trying to recognize fruit vendors/vegetables/baskets etc.  
Effective in :  
- Image Classification,  
- Object Detection,  
- Instance segmentation,  
- NLP.  
  
One common approach is using a model pre-trained on millions of data poins and then fine-tuning it on a small subset of new problem's data points. It also used for fixed feature-extraction scenarios.  
  
Example: VGG - 16   
<img width="727" alt="Screenshot 2021-11-21 at 4 48 53 PM" src="https://user-images.githubusercontent.com/61674750/142759738-39b17d53-99aa-4e05-bf7f-0de287fc5459.png">
  
Learning Rates :  
- Adam optimiser : experimental values suggest 3e-4 being a good guesstimate for fine-tuning.
