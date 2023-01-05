README

Make sure to add aloi_red4_col/png/* to this directory


1) Run in preprocess FirstFilter.ipynb| Create Folder called Filtered and Original_labels.csv
- Filtered contains images that are either plastic, metal or "wood,paper"
- Original_labels.csv is the matching csv file
2) Run in preprocess TrainTestValFilter.ipynb
- Splits the Filtered images into train|Test|Val (creates trainvaltest folder). Where we ensure that items are seperated.
- Augment the data to be balanced
- Add after balancing an additional 2000 images to each class
3) Now you can run in convnet the convnet.ipynb
- Use the trainvaltest folder and creates neural net with training

Note some poth directories may not match if you see these errors make sure the files match with your directory