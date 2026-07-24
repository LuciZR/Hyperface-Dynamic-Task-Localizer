# Hyperface-Dynamic-Task-Localizer

This repository contains analyses of the Hyperface data, specifically the dynamic localizer task. The data were obtained from the open-access database OpenNeuro and include 21 participants. 
https://openneuro.org/datasets/ds007384/versions/1.0.0

During the task, participants viewed naturalistic 4-second videos from five conditions: faces, bodies, scenes, objects, and scrambled objects.

The main analysis focused on representational similarity analysis (RSA) within the fusiform face area (FFA), a brain region associated with face processing. ROI-RSA analyses were conducted in Python using Nilearn and beta maps estimated with a first-level general linear model (GLM). We mainly explored three representational models: (1) animacy, contrasting faces and bodies with objects, scenes, and scrambled objects; (2) objects versus scenes; and (3) intact versus scrambled objects. We also briefly explored the available metadata. The project includes exploratory whole-brain searchlight classification analyses as well.

The repository includes the code used to organize the data, run the fMRI analyses, generate representational dissimilarity matrices, and visualize the results.

Contributors: [Lucia Z-Rivera](https://github.com/LuciZR), [Jillian O'Malley](https://github.com/jomalle), [Bailey Harris](https://github.com/baileyb-harris),[Natalia Pallis-Hassani](https://github.com/nataliakph), [Heather Laurel Jensen](https://github.com/heatherlaureljensen)& [Emily Fitzgerald](https://github.com/e2fitzgerald)
