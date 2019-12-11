# Machine Learning Challenge
## Receipt cropping

Visma has a product where users can take a picture of a receipt in order to use it for bookkeeping. In the app we would like to automatically crop out the receipt. We think this can be done using machine learning. 

Your task is to build a proof of concept model that can find all 4 corners of the receipt in an image. 

## Things we are looking for: 
- A proof of concept implementation which does not need to cover all cases, but that could be expanded upon to handle 100x data
- Clean understandable and readable code 
- Conclusion
  - Is this viable
  - does it work
  - how well does it work
  - What should the next steps be if we want to get it in production

## Data
The data consists of a zip file containing 133 images and labels. The data can be found in this folder in the file `cropping_data.zip`

The labels are in the file ‘cropped_coords.csv’ with the following format:

| Filename | TopLeftX | TopLeftY  | TopRightX | TopRightY | BottomRightX | BottomRightY | BottomLeftX | BottomLeftY |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| String | float | float | float | float | float | float | float | float |

Each `Filename` have a corresponding image in the zipfile of either `.jpg`, `.jpeg` or `.png` format.

## Guidelines
We would like to remind you of a few important things:
- The data set is quite small and created from real world images. An acceptable model might not exist, so don't feel bad if your results are disappointing. But we believe that it is possible to get an idea weather a model is viability given the data.  
- Focus on the right stuff. Don't spend many hours on data wrangling and other stuff that does not show us your true skill-set. Instead, please make a few assumptions, and make sure to tell us about the assumptions you made.
- We do not judge you on the accuracy of your predictive model, but on your problem solving skills. So don't spend all your time tweaking parameters.
- Use what ever tech stack you feel comfortable using.

## Got stuck?
You can always email us and ask for advice or just ask questions to ensure you correctly understood the task. This will not be seen as a sign of weakness, to the contrary it shows that fully understanding the problem is important to you.
